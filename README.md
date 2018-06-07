# Gnome Shell Font Changer

## Backup

```bash
cp /usr/share/gnome-shell/gnome-shell-theme.gresource /usr/share/gnome-shell/gnome-shell-theme.gresource.bak
```

## Usage

```bash
$ git clone https://github.com/sinyadal/gnome-shell-font-changer.git
$ cd gnome-shell-font-changer
```

## Customization

Open the `script` file, find this line and change your fonts 

```bash
perl -i -p -e 's/font-family:.*;/font-family: "SF Pro Text", Cantarell, Sans-Serif;/' gnome-shell.css
```

Run the script and reboot. Enjoy :D

```bash
$ ./script.sh 
```
