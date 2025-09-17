# Termux Style++

<p align="left">
  <img src="https://img.shields.io/badge/Maintained%3F-YES-green?style=for-the-badge">
  <img src="https://img.shields.io/github/license/indra87g/termux-stylepp?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/indra87g/termux-stylepp?style=for-the-badge">
  <img src="https://img.shields.io/github/forks/indra87g/termux-stylepp?color=teal&style=for-the-badge">
  <img src="https://img.shields.io/github/issues/indra87g/termux-stylepp?color=violet&style=for-the-badge">
</p>

A fork of original [termux-style](https://github.com/adi1090x/termux-style)

![gif](images/main.gif) <br />

> **`termux-stylepp` provides more color-schemes and fonts, rather than the original version which is no longer maintained .**

### How to install

Follow the steps below - 

```bash
# Go to home dir - 
cd $HOME

# Clone this repository (use `gh repo clone adi1090x/termux-style` if you want to use the GitHub CLI)- 
git clone https://github.com/indra87/termux-stylepp

# Change to termux-style dir -
cd termux-stylepp

# To install it, run -
chmod +x install
./install

# And follow the steps, it'll be installed on your system.
```

### Run

Run `termux-style` & select the right option -

```bash
termux-style # it will changed to 'txs' soon
```

### Features

+ 96 color-schemes.
+ 20 powerline patched fonts.
+ Randomly change color-schemes.
+ Import color-schemes from *local file* or *file URL*.
+ Set colors and fonts in place.

### Use Import
```bash
    [Select Option]: 4

    [1] Local File (Enter path to file)
    [2] Internet File (Enter File URL)

    [Select Option]: 2

    [Enter Color-scheme URL]: https://raw.githubusercontent.com/adi1090x/termux-style/master/colors/gruvbox-dark.properties

    [*] Reloading Settings...
    [*] Applied Successfully.
```

+ To import *local file*, enter the full path (e.g. - `/data/data/com.termux/files/home/spiderman.properties`) of the color-scheme.
+ To import *web file*, enter the file url (e.g. - `https://raw.githubusercontent.com/adi1090x/termux-style/master/colors/gruvbox-dark.properties`) of the color-scheme.
<br />
