<div align="center">

# 🏠 Akoonet – Home Assistant

**Intégrations personnalisées pour Home Assistant, installables via HACS**

[![HACS](https://img.shields.io/badge/HACS-Custom-orange.svg)](https://hacs.xyz)
[![Home Assistant](https://img.shields.io/badge/Home%20Assistant-compatible-41BDF5.svg)](https://www.home-assistant.io)
[![Site web](https://img.shields.io/badge/site-akoonet.com-blue.svg)](https://www.akoonet.com)
[![Licence](https://img.shields.io/badge/licence-open%20source-green.svg)](#-licence)

🇫🇷 Français · [🇬🇧 English](#-english)

🌐 **Site web : [www.akoonet.com](https://www.akoonet.com)**

</div>

---

## 👋 Présentation

Bienvenue sur la page **Akoonet – Home Assistant**.

Je développe des intégrations pour **Home Assistant** avec une approche rigoureuse : des composants propres, documentés, configurables depuis l'interface graphique, et faciles à installer grâce à **HACS**.

Ma philosophie :

- 🎯 **Fiabilité d'abord** : des comportements prévisibles, testés et documentés.
- 🖥️ **Tout dans l'interface** : configuration via l'UI, sans édition manuelle de YAML quand c'est possible.
- 📖 **Documentation claire** : README en français, version anglaise, captures d'écran et liste des entités.
- 🔬 **Honnêteté technique** : pas de formules inventées, je distingue ce qui est validé de ce qui ne l'est pas.

Plus d'informations sur mes activités : **[www.akoonet.com](https://www.akoonet.com)**

---

## 📦 Mes projets

| Projet | Description | Installation |
|--------|-------------|--------------|
| [**Calypshome-ha**](https://github.com/akoonet-homeassistant/Calypshome-ha) | Intégration des volets **Calyps'HOME / Avidsen** dans Home Assistant | HACS |
| [**volets_intelligents**](https://github.com/akoonet-homeassistant/volets_intelligents) | Gestion intelligente des volets (automatisations, panneau de configuration dédié) | HACS |
| [**Lights Simulator**](https://github.com/akoonet-homeassistant/lights_simulator) | Simulateur de présence par les lumières, pour rendre la maison « vivante » en votre absence | HACS |

> ℹ️ Adaptez les noms et liens ci-dessus aux dépôts réellement publiés.

---

## 🚀 Installation via HACS

1. Ouvrir **HACS** dans Home Assistant.
2. Menu **⋮** (en haut à droite) → **Dépôts personnalisés**.
3. Coller l'URL du dépôt souhaité, choisir le type **Intégration**, puis **Ajouter**.
4. Rechercher l'intégration dans HACS, cliquer sur **Télécharger**.
5. **Redémarrer** Home Assistant.
6. Aller dans **Paramètres → Appareils et services → Ajouter une intégration** et sélectionner l'intégration.

---

## 🧰 Prérequis

- Une installation **Home Assistant** récente (Core, OS, Container ou Supervised).
- **HACS** installé et configuré.
- Selon l'intégration : le matériel correspondant (volets, lumières, passerelle, etc.).

Chaque dépôt précise sa version minimale de Home Assistant dans son README.

---

## 🐞 Support et contributions

- **Un bug ?** Ouvrez une [issue](https://github.com/akoonet-homeassistant) dans le dépôt concerné en précisant :
  - la version de Home Assistant et de l'intégration,
  - les logs pertinents (niveau `debug` si possible),
  - les étapes pour reproduire le problème.
- **Une idée ?** Proposez-la via une issue ou une *discussion*.
- **Une contribution ?** Les *pull requests* sont les bienvenues : forkez le dépôt, créez une branche dédiée, décrivez clairement la modification.

Je gère ces projets seul sur mon temps libre : merci de votre patience pour les réponses.

> 🔒 Avant de partager des logs ou des captures d'écran, pensez à retirer toute information personnelle (noms d'entités, adresses, identifiants, jetons).

---

## 🗂️ Conventions des dépôts

- Versions au format **`année.mois.numéro`** (exemple : `2026.10.1`).
- Chaque version est accompagnée d'un **descriptif de release**.
- Toute nouvelle entité est documentée dans le README et visible dans le panneau de l'intégration.
- Les captures d'écran sont regroupées dans `docs/screenshots` et n'utilisent que des entités fictives.

---

## 📄 Licence

Sauf mention contraire dans le dépôt concerné, mes projets sont publiés sous licence open source. Consultez le fichier `LICENSE` de chaque dépôt.

---

<a id="-english"></a>

## 🇬🇧 English

🌐 **Website: [www.akoonet.com](https://www.akoonet.com)**

### About

Welcome to the **Akoonet – Home Assistant** page.

I build **custom integrations for Home Assistant**, installable through **HACS**, with a focus on reliability, UI-based configuration and clear documentation.

### Projects

| Project | Description |
|---------|-------------|
| [**Calypshome-ha**](https://github.com/akoonet-homeassistant/Calypshome-ha) | Integration for **Calyps'HOME / Avidsen** shutters |
| [**volets_intelligents**](https://github.com/akoonet-homeassistant/volets_intelligents) | Smart shutter management with a dedicated configuration panel |
| [**Lights Simulator**](https://github.com/akoonet-homeassistant/lights_simulator) | Presence simulator using your lights while you are away |

### Install with HACS

1. Open **HACS** in Home Assistant.
2. **⋮** menu → **Custom repositories**.
3. Paste the repository URL, choose the **Integration** category, then **Add**.
4. Search for the integration in HACS and click **Download**.
5. **Restart** Home Assistant.
6. Go to **Settings → Devices & services → Add integration** and select it.

### Support & contributions

Please open an issue in the relevant repository with your Home Assistant version, the integration version, relevant debug logs and reproduction steps. Pull requests are welcome. I maintain these projects alone in my spare time, so thanks for your patience.

> 🔒 Remove any personal information (entity names, addresses, tokens) before sharing logs or screenshots.

### License

Unless stated otherwise in a repository, my projects are released under an open source license. See each repository's `LICENSE` file.
