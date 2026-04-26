# Informations de pré-installation

## Fonctionnalités IA (Optionnel)

Suivi Ruches propose des fonctionnalités IA :
- **Dr. Abeille** : Assistant apicole IA pour des conseils
- **Flore & Faune** : Identification de plantes et insectes par description ou photo

Ces fonctionnalités nécessitent une **clé API Anthropic**. Vous pouvez :

1. **Obtenir une clé API** sur [console.anthropic.com](https://console.anthropic.com/)
2. **Désactiver l'IA** en laissant le champ vide lors de l'installation

La clé API sera stockée de manière sécurisée dans le fichier `.env` de l'app (lisible uniquement par l'utilisateur de l'app).

## Stockage

L'app utilise le **localStorage du navigateur** pour persister les données :
- Les données des ruches, interventions et photos sont stockées localement dans votre navigateur
- Les données sont **par appareil** : changer de navigateur ou d'appareil nécessitera de re-saisir les données
- C'est un choix volontaire pour maximiser la confidentialité (aucune donnée stockée côté serveur)

Si vous avez besoin de synchroniser entre appareils, utilisez la fonctionnalité de synchronisation de votre navigateur ou exportez/importez vos données.

## Compatibilité Navigateur

Pour la meilleure expérience (surtout la dictée vocale) :
- ✅ Chrome / Chromium (recommandé)
- ✅ Microsoft Edge
- ✅ Safari 14.1+
- ⚠️ Firefox (support limité du speech-to-text)

## Permission Microphone

La dictée vocale nécessite l'accès au microphone. Votre navigateur demandera la permission lors du premier clic sur le bouton de dictée (🎤).
