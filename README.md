# - HyprNight -

Salut ! Ce projet est un shell conçu pour Hyprland, entièrement codé en Python !

### Ses avantages :

* Léger
* Customisable
* Rapide
* Fun !

---

## Pour l'utiliser

Pour l'utiliser, il suffit de télécharger ces dépendances Python/Linux sur votre distribution Linux/Unix-based :

* `psutil`
* `upower`
* `playerctl`
* Et Python, LOL

---

## Comment l'installer ?

Pour l'installer, il vous suffit d'aller dans les **Releases** de ce repo, de télécharger le `.zip` et de l'extraire dans :

```text
~/.config/hypr/
```

Ensuite, il faut éditer le fichier `hyprland.lua` (ou `.conf` si votre version de Hyprland est antérieure) afin de lancer HyprNight au démarrage en ajoutant :

```lua
-- HyprNight autostart
hl.exec_cmd("python3 ~/.config/hypr/hyprnight.py &")
```

Une fois cela fait, il faudra renommer votre logo de distribution en `distro.png`.

Je fournis déjà `debian.png`, `arch.png` et `opensuse.png` : renommez simplement celui qui correspond à votre distribution !

Ensuite, il vous suffira de mettre le logo `.jpg`, `.jpeg` ou `.png` de votre photo de profil dans le même répertoire, en le renommant :

```text
imgp.png
```

(`imgp.jpg`, etc. fonctionne également.)

Puis, relancez votre session Hyprland et tout est bon ! 🎉

---

## Comment mettre des fonds d'écran ?

Pour ajouter des fonds d'écran, c'est simple !

Il vous suffit de les mettre dans :

```text
~/Images/Wallpapers/
```

Puis de sélectionner celui que vous souhaitez dans le menu déroulant en haut !

Par défaut, l'image chargée s'appelle `miku`, mais vous pouvez facilement modifier cela.

---

## Comment ça s'utilise et qu'est-ce qu'il n'y a pas ?

Pour l'utiliser, c'est simple !

Si vous placez votre curseur à droite, au bord de votre écran, un menu se déroulera avec le pourcentage d'utilisation du **GPU**, de la **RAM** et du **CPU**.

Si vous placez votre curseur en bas, un petit dashboard apparaîtra avec votre nom d'utilisateur, un contrôle du volume, un indicateur du niveau de batterie et quelques informations supplémentaires.

Si vous placez votre curseur en haut, cela ouvrira le menu permettant de choisir votre fond d'écran. Il est contrôlable avec les **flèches du clavier** et la touche **Entrée**.

### Et voici ce qui n'est pas inclus :

* **Un lanceur d'applications**
  Vous devrez en avoir un comme `wofi` ou `rofi`.

* **Une application de configuration**
  Vous devez toujours configurer votre fichier `hyprland.conf` vous-même !

* **Une barre de style Waybar**
  C'est à vous de choisir votre style. Par conséquent, vous devrez installer et configurer votre barre vous-même.

* **Un gestionnaire de connexion Wi-Fi/Bluetooth**
  On ne peut pas simplement se connecter à un réseau en deux clics. Vous devrez utiliser **NetworkManager**, `iwd` ou un autre outil adapté.

---

## Qui l'a créé ?

Je l'ai créé parce que je voulais avoir un bureau Hyprland plus vivant, avec de beaux effets et une interface plus agréable.

C'est ce qui m'a donné l'idée de créer **HyprNight** ! 🌙

---

## Me contacter

Vous pouvez me contacter à cette adresse e-mail :

**[xdatabenji@gmail.com](mailto:xdatabenji@gmail.com)**

Ou via Discord (demande d'ami) :

**benjitechx_23314**

---

Merci d'avoir lu ! ❤️

Et si vous utilisez ce que j'ai créé, merci beaucoup !
