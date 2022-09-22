# ubuntu-terminal - my custom setup

This is just my custom dconf to keep it for future use and updates

## Installation
Dconf Editor is needed, so Install it, if not already

```bash
sudo apt update
sudo apt install dconf-editor
```
Then reset and import profile

```bash
dconf reset -f /org/gnome/terminal/legacy/profiles:/
dconf load /org/gnome/terminal/legacy/profiles:/:b1dcc9dd-5262-4d8d-a863-c897e6d979b9/ < aca-terminal.dconf 