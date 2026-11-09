<div align="center">

# 🏠 Projets Home Assistant

**Intégrations et cartes Lovelace par Akoonet — toutes sur HACS / Marketplace**

[![HACS / Marketplace](https://img.shields.io/badge/HACS%20%2F%20Marketplace-Default-41BDF5.svg)](https://hacs.xyz)
[![Intégrations](https://img.shields.io/badge/int%C3%A9grations-5-41BDF5.svg)](#-mes-projets)
[![Cartes Lovelace](https://img.shields.io/badge/cartes%20Lovelace-4-41BDF5.svg)](#-mes-projets)
[![Documentation](https://img.shields.io/badge/documentation-FR%20%C2%B7%20EN-41BDF5.svg)](#-english)
[![Site web](https://img.shields.io/badge/site-akoonet.com-blue.svg)](https://www.akoonet.com)

🇫🇷 Français · [🇬🇧 English](#-english)

</div>

Des intégrations configurables depuis l'interface, documentées en français et en anglais, testées avant chaque version. Volets, éclairage, chauffage… et une créature-maison à faire vivre.

🌐 **Site web : [www.akoonet.com](https://www.akoonet.com)**

---

## 📦 Mes projets

### 🪟 Volets

<table>
<tr>
<td width="50%" valign="top">
<img src="https://raw.githubusercontent.com/akoonet-homeassistant/volets_intelligents/main/custom_components/volets_intelligents/brand/icon.png" width="48" height="48" align="left" alt="">
<b><a href="https://github.com/akoonet-homeassistant/volets_intelligents">Volets Intelligents</a></b><br>
<sub>Intégration + carte · HA 2026.3.0+</sub>
<br clear="left">
<p align="center"><img src="https://raw.githubusercontent.com/akoonet-homeassistant/volets_intelligents/main/docs/screenshots/carte-facades.png" alt="Carte Volets Intelligents" height="240"></p>
<p>Protège la maison de la chaleur en pilotant les volets selon le soleil, les températures et l'activité des habitants, avec un panneau de gestion graphique. Aucun YAML à écrire.</p>
<p><a href="https://my.home-assistant.io/redirect/hacs_repository/?owner=akoonet-homeassistant&amp;repository=volets_intelligents&amp;category=integration"><img src="https://my.home-assistant.io/badges/hacs_repository.svg" alt="Ouvrir dans HACS / Marketplace"></a> <img src="https://img.shields.io/github/v/release/akoonet-homeassistant/volets_intelligents?label=version&amp;color=41BDF5" alt="Version"></p>
</td>
<td width="50%" valign="top">
<img src="https://raw.githubusercontent.com/akoonet-homeassistant/Calypshome-ha/main/custom_components/calypshome/brand/icon.png" width="48" height="48" align="left" alt="">
<b><a href="https://github.com/akoonet-homeassistant/Calypshome-ha">Calyps'HOME (Avidsen Cloud)</a></b><br>
<sub>Intégration · HA 2024.11.0+</sub>
<br clear="left">
<p align="center"><img src="https://raw.githubusercontent.com/akoonet-homeassistant/Calypshome-ha/main/images/device-detail.png" alt="Appareil Calyps'HOME" height="240"></p>
<p>Pilote les volets roulants <b>Profalux Neosol 868</b> via le cloud Calyps'HOME / Avidsen, avec les identifiants de l'application mobile. La position est estimée par minuterie. Fonctionne avec Volets Intelligents.</p>
<p><a href="https://my.home-assistant.io/redirect/hacs_repository/?owner=akoonet-homeassistant&amp;repository=Calypshome-ha&amp;category=integration"><img src="https://my.home-assistant.io/badges/hacs_repository.svg" alt="Ouvrir dans HACS / Marketplace"></a> <img src="https://img.shields.io/github/v/release/akoonet-homeassistant/Calypshome-ha?label=version&amp;color=41BDF5" alt="Version"></p>
</td>
</tr>
</table>

### 💡 Éclairage et présence · 🔥 Chauffage

<table>
<tr>
<td width="50%" valign="top">
<img src="https://raw.githubusercontent.com/akoonet-homeassistant/lights_simulator/main/custom_components/lights_simulator/brand/icon.png" width="48" height="48" align="left" alt="">
<b><a href="https://github.com/akoonet-homeassistant/lights_simulator">Lights Simulator</a></b><br>
<sub>Intégration + carte · HA 2024.12.0+</sub>
<br clear="left">
<p align="center"><img src="https://raw.githubusercontent.com/akoonet-homeassistant/lights_simulator/main/docs/screenshots/carte.png" alt="Carte Lights Simulator" height="240"></p>
<p>Simulation de présence : quand la maison est vide, allume et éteint vos lampes au hasard le soir et le matin. Déclenchement par l'alarme ou par l'absence des personnes.</p>
<p><a href="https://my.home-assistant.io/redirect/hacs_repository/?owner=akoonet-homeassistant&amp;repository=lights_simulator&amp;category=integration"><img src="https://my.home-assistant.io/badges/hacs_repository.svg" alt="Ouvrir dans HACS / Marketplace"></a> <img src="https://img.shields.io/github/v/release/akoonet-homeassistant/lights_simulator?label=version&amp;color=41BDF5" alt="Version"></p>
</td>
<td width="50%" valign="top">
<img src="https://raw.githubusercontent.com/akoonet-homeassistant/edilkamin_control/main/custom_components/edilkamin_control/brand/icon.png" width="48" height="48" align="left" alt="">
<b><a href="https://github.com/akoonet-homeassistant/edilkamin_control">Edilkamin Control</a></b><br>
<sub>Intégration + carte · HA 2024.11.0+</sub>
<br clear="left">
<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/akoonet-homeassistant/edilkamin_control/main/docs/screenshots/carte_sombre.png"><img src="https://raw.githubusercontent.com/akoonet-homeassistant/edilkamin_control/main/docs/screenshots/carte.png" alt="Carte Edilkamin Control" height="240"></picture></p>
<p>Programmation et pilotage d'un poêle à granulés <b>Edilkamin</b> commandé par un ESP32 en Bluetooth / MQTT, avec planning de secours si Home Assistant s'arrête. <a href="https://akoonet-homeassistant.github.io/edilkamin_control/webflash/">Firmware ESP32 en un clic</a>.</p>
<p><a href="https://my.home-assistant.io/redirect/hacs_repository/?owner=akoonet-homeassistant&amp;repository=edilkamin_control&amp;category=integration"><img src="https://my.home-assistant.io/badges/hacs_repository.svg" alt="Ouvrir dans HACS / Marketplace"></a> <img src="https://img.shields.io/github/v/release/akoonet-homeassistant/edilkamin_control?label=version&amp;color=41BDF5" alt="Version"></p>
</td>
</tr>
</table>

### 🎮 Loisirs

<table>
<tr>
<td width="50%" valign="top">
<img src="https://raw.githubusercontent.com/akoonet-homeassistant/domogotchi/main/custom_components/domogotchi/brand/icon.png" width="48" height="48" align="left" alt="">
<b><a href="https://github.com/akoonet-homeassistant/domogotchi">Domogotchi</a></b><br>
<sub>Intégration + carte · HA 2025.1.0+</sub>
<br clear="left">
<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/akoonet-homeassistant/domogotchi/main/docs/screenshots/carte-sombre.png"><img src="https://raw.githubusercontent.com/akoonet-homeassistant/domogotchi/main/docs/screenshots/carte.png" alt="Carte Domogotchi" height="240"></picture></p>
<p>Une créature-maison façon <b>Tamagotchi</b> sur écran LCD rétro : elle a faim, joue, grandit et réagit à la vraie maison (lumières, température, présence, consommation, météo).</p>
<p><a href="https://my.home-assistant.io/redirect/hacs_repository/?owner=akoonet-homeassistant&amp;repository=domogotchi&amp;category=integration"><img src="https://my.home-assistant.io/badges/hacs_repository.svg" alt="Ouvrir dans HACS / Marketplace"></a> <img src="https://img.shields.io/github/v/release/akoonet-homeassistant/domogotchi?label=version&amp;color=41BDF5" alt="Version"></p>
</td>
<td width="50%" valign="middle" align="center">
<b>Une idée de projet ?</b><br>
Proposez-la dans une <i>issue</i> sur l'un des dépôts.
</td>
</tr>
</table>

---

## 🚀 Installation via HACS / Marketplace

Toutes mes intégrations font partie des dépôts **HACS / Marketplace par défaut** : aucun dépôt personnalisé à ajouter.

1. Cliquez sur le bouton **Ouvrir dans HACS / Marketplace** du projet, ou recherchez-le par son nom dans **HACS / Marketplace**.
2. Cliquez sur **Télécharger**, puis **redémarrez** Home Assistant.
3. Allez dans **Paramètres → Appareils et services → Ajouter une intégration** et sélectionnez l'intégration.

Pour **Edilkamin Control**, l'ESP32 qui dialogue avec le poêle s'installe en un clic depuis la [page du firmware](https://akoonet-homeassistant.github.io/edilkamin_control/webflash/).

---

## 🧭 Derrière les projets

<table>
<tr>
<td width="50%" valign="top">
<b>Fait en France</b>
<ul>
<li>Développé et testé sur une vraie installation Home Assistant.</li>
<li>Documentation en français d'abord, puis en anglais.</li>
<li>Projets gratuits et open source, maintenus sur mon temps libre.</li>
</ul>
</td>
<td width="50%" valign="top">
<b>Ma philosophie</b>
<ul>
<li>🎯 <b>Fiabilité d'abord</b> : des comportements prévisibles, testés et documentés.</li>
<li>🖥️ <b>Tout dans l'interface</b>, sans YAML à écrire quand c'est possible.</li>
<li>🔬 <b>Honnêteté technique</b> : ce qui est validé est distingué de ce qui ne l'est pas.</li>
</ul>
</td>
</tr>
</table>

---

## 🤝 Envie d'aider ?

| 🐞 Signaler un bug | 💡 Proposer une idée | 🔧 Contribuer |
|---|---|---|
| Ouvrez une *issue* dans le dépôt concerné, avec la version de Home Assistant et de l'intégration, les logs (niveau `debug` si possible) et les étapes pour reproduire. | Une fonction qui manque ? Décrivez-la dans une *issue* ou une *discussion* du projet. | Les *pull requests* sont les bienvenues : forkez le dépôt, créez une branche dédiée, décrivez clairement la modification. |

> 🔒 Avant de partager des logs ou des captures d'écran, pensez à retirer toute information personnelle (noms d'entités, adresses, identifiants, jetons).

---

## 🗂️ Conventions des dépôts

- Versions au format **`année.mois.numéro`** (exemple : `2026.10.1`).
- Chaque version est accompagnée d'un **descriptif de release**.
- Toute nouvelle entité est documentée dans le README et visible dans le panneau de l'intégration.
- Les captures d'écran sont regroupées dans `docs/screenshots` et n'utilisent que des entités fictives.

## 📄 Licence

Sauf mention contraire dans le dépôt concerné, mes projets sont publiés sous licence open source. Consultez le fichier `LICENSE` de chaque dépôt.

---

<a id="-english"></a>

## 🇬🇧 English

**Integrations and Lovelace cards by Akoonet — all on HACS / Marketplace.** Configured from the UI, documented in French and English, tested before every release. 🌐 **Website: [www.akoonet.com](https://www.akoonet.com)**

### Projects

| | Project | Description | Install |
|---|---|---|---|
| <img src="https://raw.githubusercontent.com/akoonet-homeassistant/volets_intelligents/main/custom_components/volets_intelligents/brand/icon.png" width="32" alt=""> | [**Volets Intelligents**](https://github.com/akoonet-homeassistant/volets_intelligents)<br><sub>Integration + card · HA 2026.3.0+</sub> | Smart shutter management from the sun, temperatures and occupants' activity, with a graphical management panel. No YAML to write. | [Open in HACS / Marketplace](https://my.home-assistant.io/redirect/hacs_repository/?owner=akoonet-homeassistant&repository=volets_intelligents&category=integration) |
| <img src="https://raw.githubusercontent.com/akoonet-homeassistant/Calypshome-ha/main/custom_components/calypshome/brand/icon.png" width="32" alt=""> | [**Calyps'HOME (Avidsen Cloud)**](https://github.com/akoonet-homeassistant/Calypshome-ha)<br><sub>Integration · HA 2024.11.0+</sub> | Controls **Profalux Neosol 868** roller shutters through the Calyps'HOME / Avidsen cloud. Works with Volets Intelligents. | [Open in HACS / Marketplace](https://my.home-assistant.io/redirect/hacs_repository/?owner=akoonet-homeassistant&repository=Calypshome-ha&category=integration) |
| <img src="https://raw.githubusercontent.com/akoonet-homeassistant/lights_simulator/main/custom_components/lights_simulator/brand/icon.png" width="32" alt=""> | [**Lights Simulator**](https://github.com/akoonet-homeassistant/lights_simulator)<br><sub>Integration + card · HA 2024.12.0+</sub> | Presence simulation: randomly switches your lamps on and off while the house is empty. | [Open in HACS / Marketplace](https://my.home-assistant.io/redirect/hacs_repository/?owner=akoonet-homeassistant&repository=lights_simulator&category=integration) |
| <img src="https://raw.githubusercontent.com/akoonet-homeassistant/edilkamin_control/main/custom_components/edilkamin_control/brand/icon.png" width="32" alt=""> | [**Edilkamin Control**](https://github.com/akoonet-homeassistant/edilkamin_control)<br><sub>Integration + card · HA 2024.11.0+</sub> | Scheduling and control of an **Edilkamin** pellet stove through an ESP32 (Bluetooth / MQTT) — [one-click ESP32 firmware](https://akoonet-homeassistant.github.io/edilkamin_control/webflash/). | [Open in HACS / Marketplace](https://my.home-assistant.io/redirect/hacs_repository/?owner=akoonet-homeassistant&repository=edilkamin_control&category=integration) |
| <img src="https://raw.githubusercontent.com/akoonet-homeassistant/domogotchi/main/custom_components/domogotchi/brand/icon.png" width="32" alt=""> | [**Domogotchi**](https://github.com/akoonet-homeassistant/domogotchi)<br><sub>Integration + card · HA 2025.1.0+</sub> | **Tamagotchi**-style house creature on a retro LCD screen that reacts to your real home. | [Open in HACS / Marketplace](https://my.home-assistant.io/redirect/hacs_repository/?owner=akoonet-homeassistant&repository=domogotchi&category=integration) |

### Install with HACS / Marketplace

All my integrations are part of the **HACS / Marketplace default** repositories: no custom repository needed. Click **Open in HACS / Marketplace** (or search the name in **HACS / Marketplace**), click **Download**, **restart** Home Assistant, then go to **Settings → Devices & services → Add integration**.

### Support & contributions

Please open an issue in the relevant repository with your Home Assistant version, the integration version, relevant debug logs and reproduction steps. Pull requests are welcome. I maintain these projects alone in my spare time, so thanks for your patience.

> 🔒 Remove any personal information (entity names, addresses, tokens) before sharing logs or screenshots.

### License

Unless stated otherwise in a repository, my projects are released under an open source license. See each repository's `LICENSE` file.

<div align="center"><sub>Non affilié à Home Assistant ni aux marques citées · Not affiliated with Home Assistant or the brands mentioned.</sub></div>
