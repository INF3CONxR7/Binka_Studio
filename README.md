<p align="center">
  <img src="https://zupimages.net/up/26/43/5zui.png" alt="Logo de Binka Studio" width="128">
</p>

<h1 align="center">Binka Studio</h1>

<p align="center">
  Convertissez les sons <b>BinkA</b> de Minecraft PS3 en <b>WAV</b>, et vos WAV en BinkA,<br>
  par lots, avec un outil rapide, fiable et moderne.
</p>

<p align="center">
  <a href="https://github.com/INF3CONxR7/Binka_Studio/releases/latest"><img src="https://img.shields.io/github/v/release/INF3CONxR7/Binka_Studio?label=t%C3%A9l%C3%A9charger&color=FF841A" alt="Télécharger"></a>
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?logo=windows&logoColor=white" alt="Windows 10 et 11">
  <a href="https://discord.gg/TbFYvqsh5z"><img src="https://img.shields.io/badge/Discord-rejoindre-5865F2?logo=discord&logoColor=white" alt="Serveur Discord"></a>
</p>

---

## Fonctionnalités

- **BinkA → WAV** : les sons du jeu (`.binka`) deviennent des WAV PCM 16 bits, lisibles et modifiables partout.
- 
- **WAV → BinkA** : vos sons repassent en BinkA, avec une **qualité** réglable de 1 (meilleur son) à 9 (fichier le plus
  petit). Tous les WAV sont acceptés : 8, 16, 24 ou 32 bits, flottants, mono, stéréo ou multicanal, jusqu’à 192 kHz
  (le son est ramené au PCM 16 bits stéréo, 48 kHz au plus, que demande l’encodeur).

- **MP3 → WAV** : vos musiques MP3 deviennent des WAV prêts à passer en BinkA, avec les décodeurs de Windows (rien à
  installer).

- **File d’attente** : glissez des fichiers ou des dossiers entiers (sous-dossiers compris), recherchez, triez, suivez
  la progression de chaque fichier ; plusieurs conversions tournent en même temps.

- **Dossier de sortie** : à côté de chaque fichier source, ou dans le dossier de votre choix ; les fichiers déjà
  présents sont remplacés, gardés (« nom (2) ») ou ignorés, au choix.

- **Taille estimée** avant de lancer la conversion.

- **Lecteur BinkA** : double-clic sur un `.binka` pour l’écouter sans le convertir (forme d’onde, lecture en boucle),
  ou « Écouter » dans la file, pour comparer un son avant et après sa conversion.

- **Quatre langues** : français, anglais, espagnol et italien, au choix dans les paramètres (la langue de Windows au
  premier lancement).

- **Mises à jour automatiques** (versions signées) et **présence Discord**.

## Installation

1. Ouvrez la [dernière version](https://github.com/INF3CONxR7/Binka_Studio/releases/latest) et téléchargez
   **`BinkaStudio-win-x64.zip`** (le fichier `.zip.sig` sert au programme de mise à jour).

2. Extrayez l’archive à l’endroit de votre choix : vous obtenez le dossier **`BinkaStudio-win-x64`**. Gardez ensemble
   tout ce qu’il contient : l’application a besoin du dossier `Encoder` pour convertir et du dossier `Updater` pour se
   mettre à jour.

   ```text
   Binka Studio.exe
   Encoder/Binka Studio Encoder.exe
   Encoder/binka_encode.exe
   Encoder/binkawin.asi
   Encoder/mss32.dll
   Updater/Binka Studio Update.exe
   ```

3. Lancez **`Binka Studio.exe`**.

Il faut un PC sous **Windows 10 ou 11 (64 bits)**. Rien d’autre à installer : le runtime .NET est inclus dans
l’exécutable, et le moteur BinkA utilise le .NET Framework 4.8 déjà présent dans Windows.

> **Windows SmartScreen** : l’exécutable n’est pas signé Authenticode, Windows peut donc afficher « Windows a protégé
> votre ordinateur ». Cliquez sur **Informations complémentaires**, puis sur **Exécuter quand même**.

## Utilisation

1. **Ajoutez vos fichiers** : *Ajouter des fichiers*, ou glissez des `.binka`, des `.wav`, des `.mp3` ou des dossiers
   sur la fenêtre.

2. **Format de sortie** : *BinkA → WAV*, *WAV → BinkA* ou *MP3 → WAV* (choisi tout seul quand vous ajoutez des fichiers
   d’un seul type). Les fichiers de l’autre type restent dans la file avec le statut « Autre format ».

3. **Dossier de sortie** : *Comme les fichiers source*, ou un dossier de votre choix.

4. **Démarrer la conversion**. *Annuler tout* l’arrête à tout moment : un fichier n’est jamais laissé à moitié écrit.

Le menu **« … »** de chaque fichier l’écoute (lui ou le fichier converti), l’affiche dans l’Explorateur, montre son
erreur, le remet en attente ou le retire de la file ; un double-clic l’écoute. **Paramètres** règle la langue de
l’interface, la qualité BinkA, la conduite à tenir avec les fichiers déjà présents, l’ouverture du dossier à la fin et
l’activité Discord.

## Crédits

Développé par **INF3C7ONxR7**. Les outils BinkA (`binka_encode.exe`, Miles Sound System `mss32.dll` et
`binkawin.asi`) sont de **RAD Game Tools** (Epic Games).

## Support

Une question, un bug : rejoignez le [serveur Discord](https://discord.gg/TbFYvqsh5z).
