# Suivi Ruches pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/suivi_ruches.svg)](https://dash.yunohost.org/appci/app/suivi_ruches)
![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/suivi_ruches.status.svg)
![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/suivi_ruches.maintain.svg)

[![Installer Suivi Ruches avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=suivi_ruches)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d'installer Suivi Ruches rapidement et simplement sur un serveur YunoHost.*
> *Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/install) pour apprendre comment l'installer.*

## Vue d'ensemble

Suivi Ruches est une application de suivi apicole conçue pour les apiculteurs amateurs et professionnels pratiquant l'apiculture douce.

### Fonctionnalités

- 🐝 **Gestion des ruches** : Suivi de plusieurs ruches avec leur état, reine, cadres et comptage des varroas
- 📋 **Visualisation des cadres** : Représentation visuelle de chaque cadre
- 📝 **Journal d'interventions** : Enregistrement détaillé de toutes les opérations
- 👁️ **Template d'observation guidée** : Checklist structurée pour ne rien oublier
- 🎤 **Dictée vocale** : Enregistrement mains libres avec reconnaissance vocale (français)
- 📸 **Photos** : Plusieurs photos par intervention avec vue plein écran
- 📦 **Inventaire** : Suivi des cadres, équipements, nourriture, et fournitures
- 🧠 **Dr. Abeille IA** : Assistant apicole IA (optionnel - nécessite une clé API Anthropic)
- 🌿 **Analyse Flore & Faune** : Identification des plantes mellifères et insectes
- 📅 **Calendrier mensuel** : Tâches et risques saisonniers
- ⚠️ **Alertes automatiques** : Risque d'essaimage, reine absente, surcharge de varroas

**Version incluse :** 1.4.0~ynh1

## Captures d'écran

<!-- Captures d'écran à ajouter -->

## Documentation et ressources

- Dépôt de code officiel de l'app : <https://github.com/TngBlt/suivi-ruches>
- YunoHost Store : <https://apps.yunohost.org/app/suivi_ruches>
- Signaler un bug : <https://github.com/TngBlt/suivi_ruches_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull requests sur la [branche `testing`](https://github.com/TngBlt/suivi_ruches_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/TngBlt/suivi_ruches_ynh/tree/testing --debug
ou
sudo yunohost app upgrade suivi_ruches -u https://github.com/TngBlt/suivi_ruches_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** <https://yunohost.org/packaging_apps>
