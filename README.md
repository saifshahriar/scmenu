# Scmenu - A dmenu/rofi screenshot utility.

A simple rofi/dmenu menu for taking quick screenshots.

## Screenshots
<div align="center">
  <img src="https://github.com/user-attachments/assets/9c75fd2b-ec4b-4e2d-b48d-8fc09745f874" alt="a" style="width: 100%;">
  <img src="https://github.com/user-attachments/assets/00ebcce7-2bec-4a55-a1ef-6e6fea5ef66f" alt="b" style="width: 33%;">
  <img src="https://github.com/user-attachments/assets/a78574b0-7dfa-4da4-8dc3-73783311fa86" alt="c" style="width: 33%;">
  <img src="https://github.com/user-attachments/assets/d56011ad-0b23-48df-9313-d5667eadda5f" alt="d" style="width: 33%;">
</div>

## Dependencies
- maim
- curl
- rofi/dmenu

## Installation/Usage

To get a copy of the utility on your local machine:

```fish
git clone https://github.com/saifshahriar/scmenu.git
cd scmenu
```
Make sure the scmenu is executable. If not, you could do this so by
```fish
chmod +x scmenu
```
and run with ``./scmenu``

You could also add it to your system path in order to call it from anywhere

```fish
cp ./scmenu ~/.local/bin
```

and/or assign a specific keybinding to it for quick access.

```fish
# sxhkd
shift + Print
    scmenu
Print
    maim | xclip -selection -t image/png
```


