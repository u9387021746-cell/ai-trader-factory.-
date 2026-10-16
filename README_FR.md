# AI TRADER FACTORY 3.0 FINAL

## Publication GitHub Pages
1. Décompresser l’archive.
2. Téléverser le contenu de ce dossier à la racine du dépôt GitHub Pages, en conservant `icons/`.
3. Remplacer les fichiers existants et valider avec Commit changes.
4. Ouvrir le site et actualiser complètement la page.

## Fonctions
- Cours publics Kraken et bougies OHLC pour BTC, ETH, SOL, XRP et LTC contre USD.
- Indicateurs EMA 9/21, RSI 14 et MACD, avec signal heuristique LONG/SHORT/NEUTRE.
- Simulation uniquement : capital fictif, positions, stop-loss, take-profit, frais estimés, historique local et export CSV.
- Gestion comptable paper : le notionnel est réservé à l’ouverture et rendu à la clôture, avec P/L et frais estimés.
- Paramètres et historique stockés dans le navigateur local de l’appareil.

## Limites importantes
- Aucun ordre réel, aucune clé privée et aucun backend.
- Le signal n’est pas un modèle d’IA entraîné et le score n’est pas une probabilité de gain.
- L’API publique peut être indisponible selon le réseau ou le navigateur. Les stops sont simulés uniquement lorsque l’application est ouverte et qu’une actualisation reçoit les cours.
- Données stockées localement : elles ne se synchronisent pas entre appareils et peuvent être effacées par la suppression des données du site.
- Frais, slippage, liquidité et exécution réelle ne sont pas reproduits intégralement. Tester avant toute utilisation décisionnelle.
