# Custom looks for ubuntu

install GNOME tweaks from apt 

```bash
sudo apt-get install gnome-tweaks
```

## Themes

### Overal theme

Ant Dracula Blue theme

https://github.com/Michedev/Ant-Dracula-Blue

#### Icons theme

Flat remix dark blue icons theme

https://www.gnome-look.org/p/1012430/


#### Shell theme

```
sudo apt install gnome-shell-extensions
```

restart, go to tweaks, extensions and enable user themes

Arc-Dark shell theme

https://www.gnome-look.org/p/1181106/

## Gnome Extensions

* Applications menu
* Desktop icons

## Terminal color scheme

https://github.com/Mayccoll/Gogh

option 53 - flat remix

+ two pixels transparent


in .basrrc uncomment line 46

#force_color_prompt=yes

has to be uncommented, to have colors in tmux

font bitstream vera sans mono, 10 pts

## Dock

```
sudo apt-get install plank
```

disable ubuntu dock in extensions app

## Disable acitivities hot corner in Gnome tweaks - Top Bar

## but background on login screen

```bash
wget -qO - https://github.com/PRATAP-KUMAR/focalgdm3/archive/TrailRun.tar.gz | tar zx --strip-components=1 focalgdm3-TrailRun/focalgdm3
```

```bash
sudo apt install libglib2.0-dev
```

```bash
image:

sudo ./focalgdm3 /absolute/path/to/image

color:

sudo ./focalgdm3 \#aAbBcC

reset back:

sudo ./focalgdm3 --reset
```

