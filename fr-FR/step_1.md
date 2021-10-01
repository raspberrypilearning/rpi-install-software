Ton Raspberry Pi devra être connecté pour installer des paquets. Avant d'installer un paquet, mets à jour et mets à niveau Raspbery Pi OS, le système d'exploitation de ton Raspberry Pi.

+ Ouvre une fenêtre de terminal et entre les commandes suivantes pour faire ceci :

![Ouvrir le terminal](images/terminal.png)

```bash
sudo apt-get update
sudo apt-get upgrade
```

+ Tu peux maintenant installer les paquets dont tu auras besoin en tapant les commandes `install` dans la fenêtre du terminal. Par exemple, voici comment installer le logiciel Sense HAT :

```bash
sudo apt-get install sense-hat
```
