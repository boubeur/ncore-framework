<p align="center">
  <img src="assets/branding/ncore-logo.jpg" alt="NCore Framework official logo for NANOS / nanos world" width="300" height="150">
</p>

<h1 align="center">NCore Framework &amp; NCore Control</h1>

<p align="center"><strong>Modular tools and framework components for NANOS / nanos world servers.</strong></p>

<p align="center">
  <a href="#english">English</a> ·
  <a href="#français">Français</a>
</p>

<p align="center">
  <a href="https://github.com/boubeur/ncore-framework/releases">Official releases</a> ·
  <a href="https://discord.gg/Ey4dn4Cbqj">Official Discord</a> ·
  <a href="LICENSE.md">Rights notice</a>
</p>

---

## English

### NCore Control 1.0.0

**NCore Control** is the official NCore Windows application for installing and managing NANOS / nanos world servers.

Version **1.0.0** is the first public release of NCore Control. Official binaries are distributed through this repository's **Official releases**.

#### Installation

From release `control-v1.0.0`, download:

`NCore-Control-Setup-1.0.0.exe`

Then double-click the installer. No manual extraction of the update ZIP is required.

NCore Control installs for the current Windows user, creates the `NCore Control` desktop shortcut, and registers itself in Windows Installed apps.

#### Features available in 1.0.0

- install a standard NANOS / nanos world server;
- manage multiple independent server instances;
- start and stop servers;
- create a dedicated desktop shortcut for each managed server;
- remove a managed server and its shortcut in a targeted way;
- manage NCore Control updates;
- use a visible Windows installation and uninstallation experience;
- preserve existing NANOS servers and their data when NCore Control is uninstalled.

Automatic installation of **NCore Framework** from NCore Control is **not enabled in this first public release**.

#### Uninstallation

Use:

`Windows Settings > Apps > Installed apps > NCore Control > Uninstall`

Uninstalling NCore Control removes the application and its global desktop shortcut. It does **not** remove existing NANOS servers, their files, configuration, databases, packages, or server data. A later reinstallation can recover the preserved managed-instance registry.

#### NCore Control license

The historical `control-v1.0.0` release remains governed by the license actually bundled with that release. A repository copy is archived at [`licenses/NCore-Control-1.0.0-LICENSE.txt`](licenses/NCore-Control-1.0.0-LICENSE.txt).

Future NCore Control releases that expressly include **NCore Proprietary Product License 1.0** are governed by:

[`LICENSE-NCORE-CONTROL.txt`](LICENSE-NCORE-CONTROL.txt)

The product license permits installation and use of NCore Control while preserving separately licensed rights of NCore packages installed or managed by Control.

French and English license sections are intended to express the same rights and restrictions. Neither is merely an informative translation.

The same restrictions apply whether an action is performed manually or through AI/IA systems, code assistants, coding agents, code generators, automated transformation tools, or similar technologies.

Third-party components remain subject to their own licenses. See [`THIRD-PARTY-NOTICES.txt`](THIRD-PARTY-NOTICES.txt) and the third-party license files included in the runtime.

### NCore Framework

**NCore Framework** is a modular RP framework designed for NANOS / nanos world. It is intended to provide a coherent, performant, maintainable, and extensible architecture for characters, economy, jobs, vehicles, administration, UI, and other official NCore RP systems.

NCore Framework is developed separately from NCore Control. The NCore Control 1.0.0 distribution does not provide access to private NCore Framework source code and does not yet enable automatic Framework installation.

### Versions and community

Official NCore Control releases and future authorized NCore distributions are available in the **[Official releases](https://github.com/boubeur/ncore-framework/releases)**.

Join the **[NCore Framework official Discord](https://discord.gg/Ey4dn4Cbqj)** for public announcements, changelogs, and community support.

---

## Français

### NCore Control 1.0.0

**NCore Control** est l’application Windows officielle NCore destinée à installer et gérer des serveurs NANOS / nanos world.

La version **1.0.0** constitue la première version publique de NCore Control. Les binaires officiels sont distribués via les **Releases officielles** de ce dépôt.

#### Installation

Dans la release `control-v1.0.0`, téléchargez :

`NCore-Control-Setup-1.0.0.exe`

Puis double-cliquez sur l’installateur. Aucune extraction manuelle du ZIP de mise à jour n’est nécessaire.

NCore Control s’installe pour l’utilisateur Windows courant, crée le raccourci Bureau `NCore Control` et s’enregistre dans les Applications installées de Windows.

#### Fonctions disponibles dans la version 1.0.0

- installer un serveur NANOS / nanos world standard ;
- gérer plusieurs instances serveur indépendantes ;
- démarrer et arrêter les serveurs ;
- créer un raccourci Bureau dédié pour chaque serveur géré ;
- supprimer de manière ciblée un serveur géré et son raccourci ;
- gérer les mises à jour de NCore Control ;
- utiliser une installation et une désinstallation Windows avec interface visible ;
- conserver les serveurs NANOS existants et leurs données lors de la désinstallation de NCore Control.

L’installation automatique de **NCore Framework** depuis NCore Control **n’est pas activée dans cette première version publique**.

#### Désinstallation

Utilisez :

`Paramètres Windows > Applications > Applications installées > NCore Control > Désinstaller`

La désinstallation de NCore Control retire l’application et son raccourci Bureau global. Elle ne supprime **pas** les serveurs NANOS existants, leurs fichiers, configurations, bases de données, packages ou données serveur. Une réinstallation ultérieure peut récupérer le registre conservé des instances gérées.

#### Licence NCore Control

La release historique `control-v1.0.0` reste régie par la licence réellement embarquée avec cette release. Une copie de référence est archivée dans [`licenses/NCore-Control-1.0.0-LICENSE.txt`](licenses/NCore-Control-1.0.0-LICENSE.txt).

Les futures releases NCore Control qui embarquent expressément **NCore Proprietary Product License 1.0** sont régies par :

[`LICENSE-NCORE-CONTROL.txt`](LICENSE-NCORE-CONTROL.txt)

La licence produit autorise l’installation et l’utilisation de NCore Control tout en préservant les droits accordés séparément par les licences des packages NCore installés ou gérés par Control.

Les sections française et anglaise de la licence sont destinées à exprimer les mêmes droits et restrictions. Aucune des deux n’est une simple traduction informative.

Les mêmes restrictions s’appliquent qu’une action soit réalisée manuellement ou au moyen de systèmes IA/AI, assistants de code, agents de codage, générateurs de code, outils de transformation automatisée ou technologies similaires.

Les composants tiers restent soumis à leurs propres licences. Voir [`THIRD-PARTY-NOTICES.txt`](THIRD-PARTY-NOTICES.txt) et les fichiers de licence tiers inclus dans le runtime.

### NCore Framework

**NCore Framework** est un framework RP modulaire conçu pour NANOS / nanos world. Il vise une architecture cohérente, performante, maintenable et extensible pour les personnages, l’économie, les métiers, les véhicules, l’administration, les interfaces et les autres systèmes RP officiels NCore.

NCore Framework est développé séparément de NCore Control. La distribution NCore Control 1.0.0 ne donne pas accès au code source privé de NCore Framework et n’active pas encore son installation automatique.

### Versions et communauté

Les versions officielles de NCore Control et les futures distributions NCore autorisées sont disponibles dans les **[Releases officielles](https://github.com/boubeur/ncore-framework/releases)**.

Rejoignez le **[Discord officiel NCore Framework](https://discord.gg/Ey4dn4Cbqj)** pour les annonces publiques, changelogs et support communautaire.

---

Copyright © 2026 Gosse Nicolas (Boubeur). See / Voir [LICENSE.md](LICENSE.md). Third-party software and resources remain subject to their respective rights and licenses.


---

## Public licensing map / Carte des licences publiques

| Scope / Périmètre | License / Licence |
|---|---|
| Public repository documentation and presentation / Documentation et présentation du dépôt public | [`LICENSE.md`](LICENSE.md) |
| NCore Control future releases expressly adopting the current product license / Futures releases Control adoptant expressément la licence produit actuelle | [`LICENSE-NCORE-CONTROL.txt`](LICENSE-NCORE-CONTROL.txt) |
| Historical NCore Control 1.0.0 / NCore Control 1.0.0 historique | [`licenses/NCore-Control-1.0.0-LICENSE.txt`](licenses/NCore-Control-1.0.0-LICENSE.txt) |
| NCore scripts/packages / Scripts/packages NCore | License included with each package / Licence incluse avec chaque package |
| Third-party components / Composants tiers | [`THIRD-PARTY-NOTICES.txt`](THIRD-PARTY-NOTICES.txt) and bundled third-party terms / et conditions tierces embarquées |

See / Voir [`NOTICE.md`](NOTICE.md) and / et [`COPYRIGHT.md`](COPYRIGHT.md).


### In practice / En pratique

**NCore Control (product / produit)**

- authorized / autorisé: install, run, use documented settings / installer, exécuter, utiliser les réglages documentés;
- not granted / non accordé: redistribution, resale, mirrors, publication of private source, modification of proprietary Control binaries / redistribution, revente, mirrors, publication du source privé, modification des binaires propriétaires Control;
- mandatory legal rights remain preserved / les droits impératifs prévus par la loi restent préservés;
- future releases adopting the current license will require explicit license acceptance before installation / les futures releases adoptant la licence actuelle demanderont une acceptation explicite avant installation.

**NCore scripts/packages**

When a package includes **NCore Proprietary Package License 1.0**, an authorized user may install, run, configure and privately modify that package for their own server, but may not redistribute, resell, mirror or republish it without written authorization.

Lorsqu'un package inclut **NCore Proprietary Package License 1.0**, l'utilisateur autorisé peut installer, exécuter, configurer et modifier ce package en privé pour son propre serveur, mais ne peut pas le redistribuer, le revendre, le mirrorer ou le republier sans autorisation écrite.

A product license never removes rights separately granted by a package license.  
Une licence produit ne retire jamais les droits accordés séparément par une licence de package.
