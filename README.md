# Gnome Shell Font Changer

## Usage

```bash
$ git clone https://github.com/sinyadal/gnome-shell-font-changer.git
$ cd gnome-shell-font-changer
$ ./script.sh 
```

## Customization

CTRL + F, find this line and change your fonts 

```bash
perl -i -p -e 's/font-family:.*;/font-family: "SF Pro Text", Cantarell, Sans-Serif;/' gnome-shell.css
```
