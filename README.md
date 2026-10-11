# Mod Initialize Scoreboard — Wiki officiel

Un petit outil pour résoudre certains conflits de données de scoreboard lors du chargement d'un monde Minecraft.

## 🆕 Version présentée

**Plugin serveur Bukkit / compatible** · **modudilitaire-1.0.0.jar**.

**[Page CurseForge](https://www.curseforge.com/minecraft/bukkit-plugins/mod-initialize-scoreboard)** · [Guide pratique](docs/Fonctionnement.md) · [Installation](docs/Installation.md) · [FAQ](docs/FAQ.md) · [Sources et vérification](docs/Sources-et-verification.md)

---

## Ce que ce projet apporte

- Plugin annoncé pour réinitialiser le scoreboard
- Installation sur un serveur compatible Bukkit, et non dans le dossier Fabric `mods`
- Intervention susceptible d'affecter objectifs et scores existants
- Sauvegarde et test recommandés avant tout usage sur un serveur réel

## 🚀 Premiers pas

1. Sauvegarde intégralement le serveur et ses objectifs scoreboard.
2. Télécharge `modudilitaire-1.0.0.jar` depuis CurseForge.
3. Place-le dans `plugins/` d'un serveur Bukkit compatible **de test**, puis redémarre.
4. Vérifie les journaux, l'état du monde et les scores avant de considérer le problème résolu.

## 1. Sauvegarder les données avant toute chose

Un scoreboard peut contenir des objectifs de datapacks, des scores de joueurs et des réglages du serveur. Une réinitialisation peut les faire disparaître : protège une copie complète de ton monde et de ses données.

## 2. Choisir le bon serveur

CurseForge distribue ce projet comme **plugin Bukkit**. Il se place dans le dossier `plugins/` d'un serveur compatible, et non dans `mods/` d'un client Fabric.

## 3. Effectuer un essai contrôlé

Utilise une copie du serveur, reproduis le problème de chargement et active le plugin uniquement dans cet environnement. Examine les journaux de démarrage et vérifie ce qui a réellement été modifié dans les objectifs de scoreboard.

## 4. Décider de le garder ou de le retirer

Quand l'erreur est résolue, vérifie les dépendances éventuelles d'autres plugins et datapacks avant de déployer la même procédure en production. Le contenu exact du JAR n'a pas encore été inspecté.

## 📚 Toutes les rubriques

| Rubrique | Ce que tu trouveras |
|---|---|
| [🚀 Guide pratique](docs/Fonctionnement.md) | Étapes pour utiliser le projet sans risque |
| [⚙️ Installation](docs/Installation.md) | Fichiers et dossier de destination |
| [🧩 Fonctionnalités](docs/Accueil.md) | Vue d'ensemble des ajouts |
| [❓ Questions fréquentes](docs/FAQ.md) | Limites et problèmes courants |
| [🔎 Sources et limites](docs/Sources-et-verification.md) | Informations annoncées et vérifiées |
| [🇬🇧 English overview](docs/English-Overview.md) | Guide court en anglais |

## Vérification et précautions

Le JAR exact n'a pas été retrouvé dans les dossiers inspectés. Cette documentation s'appuie sur le classement et la description CurseForge ; les commandes, permissions et effets réels doivent être confirmés dans le plugin.

Ce dépôt ne redistribue ni archives complètes ni ressources privées du projet. Les illustrations de nouvelles créatures sont volontairement réservées aux éventuelles photos officielles choisies par l'auteur sur CurseForge.

[**Télécharger / consulter le projet sur CurseForge**](https://www.curseforge.com/minecraft/bukkit-plugins/mod-initialize-scoreboard).
