# Dotfiles

## Necessary stuff:
1. termite
2. polybar
3. i3wm
4. fish & omf
5. fonts-hack-ttf
6. fonts-font-awesome
7. rofi
8. xorg
9. sublime text
10. nitrogen

## Configure fish

In .config/fish/config.fish add:

```if status --is-interactive
    eval sh $HOME/.config/base16-dark.sh
end
```

## Pictures

![alt-text](https://raw.githubusercontent.com/kristoy0/dotfiles/master/Desktop.jpg "Screenshot")