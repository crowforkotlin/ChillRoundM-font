```shell
sudo pacman -S fontforge
fontforge -script make-semibold.pe ChillRoundM.otf ChillRoundM-SemiBold.otf
fc-cache -fv
fc-list | grep -i "ChillRound"
```
