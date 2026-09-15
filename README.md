<p align="center">
  <img src="assets/branding/ncore-logo.jpg" alt="Logo officiel NCore Framework pour nanos world" width="300" height="150">
</p>

<h1 align="center">NCore Framework &amp; NCore Control</h1>

<p align="center"><strong>Un écosystème modulaire pour installer, gérer et développer des serveurs RP sur NANOS / nanos world.</strong></p>

<p align="center">
  <a href="https://github.com/boubeur/ncore-framework/releases">Releases officielles</a> ·
  <a href="https://discord.gg/Ey4dn4Cbqj">Discord officiel</a> ·
  <a href="LICENSE.md">Mentions de droits</a>
</p>

## NCore Control 1.0.0

**NCore Control** est l'application Windows officielle NCore destinée à installer et gérer des serveurs NANOS / nanos world.

La version **1.0.0** constitue la première version publique de NCore Control. Les binaires officiels sont distribués exclusivement via les **Releases officielles** de ce dépôt.

### Installation

Dans la release `control-v1.0.0`, téléchargez :

`NCore-Control-Setup-1.0.0.exe`

Puis double-cliquez sur l'installateur. Aucune extraction manuelle du package de mise à jour n'est nécessaire.

NCore Control s'installe dans le profil Windows de l'utilisateur, crée un raccourci `NCore Control` sur le Bureau et s'enregistre dans **Applications installées** de Windows.

### Fonctions disponibles dans la V1.0.0

- installation d'un serveur NANOS / nanos world standard ;
- gestion de plusieurs serveurs indépendants ;
- démarrage et arrêt des serveurs ;
- création d'un raccourci Bureau propre à chaque serveur ;
- suppression ciblée d'un serveur et de son raccourci ;
- gestion de la mise à jour de NCore Control ;
- désinstallation de NCore Control depuis Windows ;
- conservation des serveurs NANOS existants lors de la désinstallation de NCore Control.

L'installation automatique de **NCore Framework** depuis NCore Control n'est pas activée dans cette première version publique.

### Désinstallation

Utilisez :

`Paramètres Windows > Applications installées > NCore Control > Désinstaller`

La désinstallation retire NCore Control et son raccourci global. Elle ne supprime pas automatiquement les serveurs NANOS existants ni leurs données. Une réinstallation ultérieure peut retrouver les instances enregistrées conservées.

### Licence NCore Control

NCore Control et ses fichiers runtime propriétaires sont distribués sous la licence spécifique :

[`LICENSE-NCORE-CONTROL.txt`](LICENSE-NCORE-CONTROL.txt)

Les restrictions de cette licence s'appliquent de la même manière aux actions réalisées manuellement ou au moyen d'IA/AI, assistants de code, agents, générateurs de code ou outils automatisés.

Les composants tiers restent soumis à leurs propres licences. Voir [`THIRD-PARTY-NOTICES.txt`](THIRD-PARTY-NOTICES.txt) et les notices intégrées au runtime distribué.

## NCore Framework

**NCore Framework** est un framework RP modulaire conçu pour NANOS / nanos world. Il vise une architecture cohérente, performante, maintenable et extensible pour les systèmes de personnages, économie, métiers, véhicules, administration, interfaces et autres systèmes RP officiels NCore.

NCore Framework est développé séparément de NCore Control. La distribution NCore Control V1.0.0 ne donne pas accès au code source privé de NCore Framework et n'active pas encore son installation automatique.

## Versions et communauté

Les versions officielles de NCore Control et, lorsqu'elles sont publiées, les distributions officielles NCore sont disponibles dans les **[Releases officielles](https://github.com/boubeur/ncore-framework/releases)**.

Rejoignez le **[Discord officiel NCore Framework](https://discord.gg/Ey4dn4Cbqj)** pour les annonces, changelogs publics et support communautaire.

---

Copyright © 2026 Gosse Nicolas (Boubeur). Voir [LICENSE.md](LICENSE.md). Les logiciels et ressources tiers restent soumis aux droits de leurs auteurs respectifs.
