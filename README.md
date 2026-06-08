<div align="center">
  </h1>SpotNeoTify</h1>

  TUI-inspired theme with dynamic pywal integration, and many preconfigured colorschemes!
</div>

![Main Preview](md-assets/spicetify-PurpPink.png)

## Colorschemes

First, some I've generated with Pywal: (You can do the same!)

### Warm (w/ Transparency)
![Warm](md-assets/spicetify-warm.png)

### Warm (Opaque)
![Warm](md-assets/spicetify-warm-opaque.png)

### Blue (w/ Transparency)
![Blue](md-assets/spicetify-blue.png)

### Blue (Opaque)
![Blue](md-assets/spicetify-blue-opaque.png)

### PurpPink (w/ Transparency)
![PurpPink](md-assets/spicetify-PurpPink.png)

### PurpPink (Opaque)
![PurpPink](md-assets/spicetify-PurpPink-opaque.png)

Want to generate your own colorschemes in real time from pywal?

Download the `pywal-to-spicetify.sh`` script from my bash-scripts repo:
```
$ curl -sLO https://raw.githubusercontent.com/0lswitcher/bash-scripts/refs/heads/main/scripts/pywal-to-spicetify.sh
```

Then, make the script executable:
```
$ chmod +x ./pywal-to-spicetify.sh
```

Finally, run it!
```
$ bash ./pywal-to-spicetify.sh
```

> [!NOTE]
> To use this script without the flatpak version of spotify,  
> edit the final block to reference the non-flatpak version.

Next, there are 21+ different colorschemes designed for specific use with this theme, \
rather than assumedly binding a color generated color pallete.

> I do not take credit for the following colorschemes, they are all part of the original \
[text](https://github.com/spicetify/spicetify-themes/tree/master/text) theme that SpotNeoTify is built off of.

### CatppuccinMocha

![CatppuccinMocha](md-assets/og/CatppuccinMocha.png)

### CatppuccinMacchiato

![CatppuccinMacchiato](md-assets/og/CatppuccinMacchiato.png)

### CatppuccinLatte

![CatppuccinLatte](md-assets/og/CatppuccinLatte.png)

### Dracula

![Dracula](md-assets/og/Dracula.png)

### Gruvbox

![Gruvbox](md-assets/og/Gruvbox.png)

### GruvboxHard

![GruvboxHard](md-assets/og/GruvboxHard.png)

### Kanagawa

![Kanagawa](md-assets/og/Kanagawa.png)

### Nord

![Nord](md-assets/og/Nord.png)

### Rigel

![CatppuccinMaRigelcchiato](md-assets/og/Rigel.png)

### RosePine

![RosePine](md-assets/og/RosePine.png)

### RosePineMoon

![RosePineMoon](md-assets/og/RosePineMoon.png)

### RosePineDawn

![RosePineDawn](md-assets/og/RosePineDawn.png)

### Solarized

![Solarized](md-assets/og/Solarized.png)

### TokyoNight

![TokyoNight](md-assets/og/TokyoNight.png)

### TokyoNightStorm

![TokyoNightStorm](md-assets/og/TokyoNightStorm.png)

### ForestGreen

![ForestGreen](md-assets/og/ForestGreen.png)

### EverforestDarkHard

![EverforestDarkHard](md-assets/og/EverforestDarkHard.png)

### EverforestDarkMedium

![EverforestDarkMedium](md-assets/og/EverforestDarkMedium.png)

### EverforestDarkSoft

![EverforestDarkSoft](md-assets/og/EverforestDarkSoft.png)

## Troubleshooting

### "I updated spotify/spicetify, and now the theme is broken!"

Unfortunately, new updates regularly break formatting. Your best bet is to run:
```
spicetify restore backup
spicetify backup apply
```
And simply hope the formatting fixes. If not, either manual fixing is required, or you'll \
have to wait until I push the newest update with the corrected formatting. 


## Credits
Based on [text](https://github.com/spicetify/spicetify-themes/tree/master/text) by [darkthemer](https://github.com/darkthemer/)

## License
This repository is licensed under the [Unlicense License](LICENSE) (do whatever u want idc)

---

<p align="center">
  <sub>built with ❤️ by 0lswitcher</sub>
</p>