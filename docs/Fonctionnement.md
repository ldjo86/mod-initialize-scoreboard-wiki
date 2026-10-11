# Mod Initialize Scoreboard — Guide pratique

Un petit outil pour résoudre certains conflits de données de scoreboard lors du chargement d'un monde Minecraft.

**Version concernée :** modudilitaire-1.0.0.jar.

## 1. Sauvegarder les données avant toute chose

Un scoreboard peut contenir des objectifs de datapacks, des scores de joueurs et des réglages du serveur. Une réinitialisation peut les faire disparaître : protège une copie complète de ton monde et de ses données.

## 2. Choisir le bon serveur

CurseForge distribue ce projet comme **plugin Bukkit**. Il se place dans le dossier `plugins/` d'un serveur compatible, et non dans `mods/` d'un client Fabric.

## 3. Effectuer un essai contrôlé

Utilise une copie du serveur, reproduis le problème de chargement et active le plugin uniquement dans cet environnement. Examine les journaux de démarrage et vérifie ce qui a réellement été modifié dans les objectifs de scoreboard.

## 4. Décider de le garder ou de le retirer

Quand l'erreur est résolue, vérifie les dépendances éventuelles d'autres plugins et datapacks avant de déployer la même procédure en production. Le contenu exact du JAR n'a pas encore été inspecté.

## Checklist avant de commencer

- [ ] Sauvegarde intégralement le serveur et ses objectifs scoreboard.
- [ ] Télécharge `modudilitaire-1.0.0.jar` depuis CurseForge.
- [ ] Place-le dans `plugins/` d'un serveur Bukkit compatible **de test**, puis redémarre.
- [ ] Vérifie les journaux, l'état du monde et les scores avant de considérer le problème résolu.

## Fiabilité des informations

Le JAR exact n'a pas été retrouvé dans les dossiers inspectés. Cette documentation s'appuie sur le classement et la description CurseForge ; les commandes, permissions et effets réels doivent être confirmés dans le plugin.

[Retour au wiki](../README.md) · [CurseForge](https://www.curseforge.com/minecraft/bukkit-plugins/mod-initialize-scoreboard)
