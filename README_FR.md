# AI TRADER FACTORY 1.0 — Kraken + paper trading

Importer/remplacer à la racine du dépôt GitHub Pages : `index.html`, `manifest.webmanifest`, `sw.js` et le dossier `icons/` (PNG 192x192 et 512x512). Ne téléversez pas le ZIP lui-même.

## Déploiement Android
1. Dépôt GitHub > Ajouter un fichier > Importer des fichiers.
2. Importer les trois fichiers et le dossier icons, remplacer les anciens, puis valider les modifications.
3. Attendre le déploiement Pages, ouvrir l'URL HTTPS et actualiser.
4. Si l'ancien raccourci affiche encore l'ancienne version, supprimer ce raccourci puis le recréer depuis Chrome après actualisation.

## Fonctionnalités
- API publique Kraken Ticker, sans clé privée ; BTC, ETH, SOL, XRP, LTC contre USD.
- Paper trading local, positions et P/L indicatif ; actualisation toutes les 30 secondes.
- Aucun ordre réel envoyé, aucune clé privée demandée.

## Limites
L'appel direct navigateur vers Kraken peut échouer selon CORS ou le réseau. En cas d'indisponibilité, l'interface le signale et n'invente pas de prix. Un backend HTTPS sera alors nécessaire. Les simulations n'intègrent pas encore correctement tous les frais, le spread, le slippage ou le financement. Elles ne prouvent pas la rentabilité.
