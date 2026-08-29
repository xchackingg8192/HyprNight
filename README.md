# 🌙 HyprNight

![HyprNight Showcase](https://github.com/xchackingg8192/HyprNight/blob/main/.github/showcase.png)

## 🇬🇧 English

Hi! This project is a shell designed for **Hyprland**, entirely coded in **Python**!

### Features:

* Lightweight
* Customizable
* Fast
* Fun!

---

## How to use it

To use HyprNight, you first need to install these Python/Linux dependencies on your Linux/Unix-based distribution:

* `psutil`
* `upower`
* `playerctl`
* And Python, LOL

---

## How to install it

To install HyprNight, simply go to the **Releases** section of this repository, download the `.zip` file and extract it to:

```text
~/.config/hypr/
```

Then, edit your `hyprland.lua` file (or `.conf` if you are using an older version of Hyprland) to launch HyprNight at startup by adding:

```lua
-- HyprNight autostart
hl.exec_cmd("python3 ~/.config/hypr/hyprnight.py &")
```

Once this is done, rename your Linux distribution logo to:

```text
distro.png
```

I already provide `debian.png`, `arch.png` and `opensuse.png`. Simply rename the one corresponding to your distribution!

Then, put your profile picture (`.jpg`, `.jpeg` or `.png`) in the same directory and rename it to:

```text
imgp.png
```

(`imgp.jpg`, etc. also works.)

Finally, restart your Hyprland session and you're done! 🎉

---

## How to add wallpapers

Adding wallpapers is simple!

Just put them in:

```text
~/Images/Wallpapers/
```

Then select the wallpaper you want from the dropdown menu at the top!

By default, the loaded wallpaper is called `miku`, but you can easily change it.

---

## How does it work and what is NOT included?

Using HyprNight is simple!

If you move your cursor to the **right edge of your screen**, a menu will appear showing your **GPU, RAM and CPU usage percentages**.

If you move your cursor to the **bottom of your screen**, a small dashboard will appear with your username, volume controls, a battery level indicator and some additional information.

If you move your cursor to the **top of your screen**, the wallpaper selection menu will open. You can control it using the **arrow keys** and **Enter**.

### What is NOT included:

* **An application launcher**
  You will need to use one such as `wofi` or `rofi`.

* **A configuration application**
  You still have to configure your `hyprland.conf` file yourself!

* **A Waybar-style bar**
  You are free to choose your own style. Therefore, you will need to install and configure your bar yourself.

* **Wi-Fi/Bluetooth connection management**
  You cannot connect to a network with just two clicks. You will need to use **NetworkManager**, `iwd`, or another suitable tool.

---

## Who created it?

I created HyprNight because I wanted a more lively Hyprland desktop, with nice effects and a more enjoyable interface.

That's what gave me the idea to create **HyprNight**! 🌙

---

## Contact

You can contact me by email:

**[xdatabenji@gmail.com](mailto:xdatabenji@gmail.com)**

Or on Discord (friend request):

**benjitechx_23314**

---

Thank you for reading! ❤️

And if you use what I created, thank you very much!

---

# 🇫🇷 Français

Salut ! Ce projet est un shell conçu pour **Hyprland**, entièrement codé en **Python** !

### Ses avantages :

* Léger
* Customisable
* Rapide
* Fun !

---

## Pour l'utiliser

Pour utiliser HyprNight, il suffit d'installer ces dépendances Python/Linux sur votre distribution Linux/Unix-based :

* `psutil`
* `upower`
* `playerctl`
* Et Python, LOL

---

## Comment l'installer ?

Pour installer HyprNight, il vous suffit d'aller dans la section **Releases** de ce repo, de télécharger le fichier `.zip` et de l'extraire dans :

```text
~/.config/hypr/
```

Ensuite, éditez votre fichier `hyprland.lua` (ou `.conf` si vous utilisez une ancienne version de Hyprland) afin de lancer HyprNight au démarrage en ajoutant :

```lua
-- HyprNight autostart
hl.exec_cmd("python3 ~/.config/hypr/hyprnight.py &")
```

Une fois cela fait, renommez le logo de votre distribution Linux en :

```text
distro.png
```

Je fournis déjà `debian.png`, `arch.png` et `opensuse.png`. Il suffit de renommer celui qui correspond à votre distribution !

Ensuite, mettez votre photo de profil (`.jpg`, `.jpeg` ou `.png`) dans le même répertoire et renommez-la :

```text
imgp.png
```

(`imgp.jpg`, etc. fonctionne également.)

Enfin, relancez votre session Hyprland et tout est bon ! 🎉

---

## Comment mettre des fonds d'écran ?

Pour ajouter des fonds d'écran, c'est simple !

Il vous suffit de les mettre dans :

```text
~/Images/Wallpapers/
```

Puis de sélectionner celui que vous souhaitez dans le menu déroulant en haut !

Par défaut, le fond d'écran chargé s'appelle `miku`, mais vous pouvez facilement modifier cela.

---

## Comment ça s'utilise et qu'est-ce qui n'est pas inclus ?

Pour utiliser HyprNight, c'est simple !

Si vous placez votre curseur sur le **bord droit de votre écran**, un menu apparaîtra avec le pourcentage d'utilisation du **GPU**, de la **RAM** et du **CPU**.

Si vous placez votre curseur en **bas de votre écran**, un petit dashboard apparaîtra avec votre nom d'utilisateur, un contrôle du volume, un indicateur du niveau de batterie et quelques informations supplémentaires.

Si vous placez votre curseur en **haut de votre écran**, le menu permettant de choisir votre fond d'écran s'ouvrira. Il est contrôlable avec les **flèches du clavier** et la touche **Entrée**.

### Ce qui n'est PAS inclus :

* **Un lanceur d'applications**
  Vous devrez en utiliser un comme `wofi` ou `rofi`.

* **Une application de configuration**
  Vous devez toujours configurer votre fichier `hyprland.conf` vous-même !

* **Une barre de style Waybar**
  Vous êtes libre de choisir votre propre style. Vous devrez donc installer et configurer votre barre vous-même.

* **Un gestionnaire de connexion Wi-Fi/Bluetooth**
  Vous ne pouvez pas vous connecter à un réseau en seulement deux clics. Vous devrez utiliser **NetworkManager**, `iwd` ou un autre outil adapté.

---

## Qui l'a créé ?

J'ai créé HyprNight parce que je voulais avoir un bureau Hyprland plus vivant, avec de beaux effets et une interface plus agréable.

C'est ce qui m'a donné l'idée de créer **HyprNight** ! 🌙

---

## Me contacter

Vous pouvez me contacter par e-mail :

**[xdatabenji@gmail.com](mailto:xdatabenji@gmail.com)**

Ou via Discord (demande d'ami) :

**benjitechx_23314**

---

Merci d'avoir lu ! ❤️

Et si vous utilisez ce que j'ai créé, merci beaucoup !
