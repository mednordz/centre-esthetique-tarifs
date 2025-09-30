# Plan d'implémentation - Édition Frontend uniquement

## Solutions possibles pour GitHub Pages :

### 1. **localStorage + JSON** (Recommandé)
- ✅ Modifications persistantes localement
- ✅ Interface d'édition intuitive
- ✅ Sauvegarde/restauration via fichier JSON
- ❌ Limité à un navigateur/appareil

### 2. **localStorage + GitHub API** (Avancé)
- ✅ Synchronisation possible via GitHub API
- ✅ Modifications committées automatiquement
- ✅ Historique des versions
- ❌ Nécessite token GitHub

### 3. **Édition temporaire** (Simple)
- ✅ Très rapide à implémenter
- ✅ Mode "preview" des modifications
- ❌ Modifications perdues au refresh

## Architecture choisie : localStorage + Export/Import JSON