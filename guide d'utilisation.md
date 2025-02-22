---
title: "Guide d'utilisation"
order: 1
in_menu: true
---
Voici un guide d'utilisation.

## Les prérequis
### Un BIOS UEFI
Cette étape est essentielle, le BIOS, c’est le coeur même de votre ordinateur : il guide le démarrage vers Windows. S’il n’y est pas, c’est foutu, vous ne pouvez pas utilisez votre ordinateur ! Sur les nouveaux ordinateurs (moi j’ai un ordi qui date de 10 ans et c’est bon), le BIOS est programmé avec la toute nouvelle puce UEFI ( en anglais : Unified Extensible Firmware Interface). Mais cetains vieux ordinateurs sont toujours en BIOS EFI, ce qui pose un problème car pour ce tuto, votre ordinateur soit avoir obligatoirement un BIOS UEFI ! Mais alors, comment le vérifier ? C’est tout simple :

1) Cliquez sur le menu Démarrer
2) Tapez dans la barre de recherche « Système » et cliquez sur « Informations système »
3) Si besoin, cliquez sur « Résumé système » tout en haut et cherchez dans cette section « Mode BIOS ». Il doit contenir la mention « UEFI »

### Un SecureBoot désactivé

Ce prérequis est très facile à faire ! Il s’agit du SecureBoot, un composant que les fabriquants mettent souvent dans leurs ordinateurs : en fait, c’est un programme qui, quand on démarre Windows, va lancer des analyses et des imaes officielles de Windows ! Sauf que nous, on va remplacer ces images officielles par des images non-officielles ! Il faut donc désactiver le SecureBoot dans les paramètres BIOS-UEFI !
C’est très simple à faire !
1) Allez dans vos paramètres
2) Cliquez sur "Système"
3) Descendez jusqu'en bas, puis cliquez sur "Récupération"
4) Cliquez sur "Démarrage avancé"
5) Cliquez sur "Réparation"
6) Cliquez sur "Options Avancées"
7) Cliquez sur "Changer les paramètres du micro-programme UEFI
8) Cherchez "Secureboot" et mettez-le en "Désactivé"
## Première partie : installer HackBGRT

HackBGRT est un petit programme qui va modifier votre BIOS pour afficher une image personnelle. 