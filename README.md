# Luxe
Projet Seminaire de Math Applique pour les Jeux Video

Participants : 
- Darrigol Marie
- Leonard Anthony
- Pelloux-Prayer Ophelie
- Rodrigues Hugo

Initialisation du projet :
==============
- Clonez le projet : via le bash de git : git clone https://github.com/OpheliePELLOUXPRAYER/Luxe.git
- Ouvrir Epic Game
- Lancez Unreal
- Selectionnez un nouveau projet Blueprint
- Selectionnez le dossier contenant le dossier du git (Luxe) 
- Nommez le projet : Luxe
- Ouvrir les settings du projet
- Onglet maps & modes 
  - Selectionnez la maps level1 par defaut
  - Selectionner LuxeGameMode comme mode de jeu
- Onglet Input : 
  - Importez les Inputs 
  - Verifiez la partie action mapping et axes mapping
- Play -> normalemment le projet fonctionne

DefaultEngine.ini
=================
```
[OnlineSubsystem]
DefaultPlatformService=Null
```

DefaultGame.ini
===============
```
ProjectID=758DA2B846D2AFC20D1DA292EDEAD42D
```

Settings : 
---------
Changer game instance pour LuxeGameInstance
