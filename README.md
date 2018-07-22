# Set Visual Studio Code as the default text editor
```bash
$ xdg-mime default code.desktop text/plain
```

# Install a theme for GNOME Terminal
List of themes: https://github.com/Mayccoll/Gogh/blob/master/content/themes.md

```bash
# installs the theme called "elementary"
$ wget -O xt  http://git.io/v3D8R && chmod +x xt && ./xt && rm xt
```

*Upon completion, go to Edit / Preferences, select the newly created profile, click Set as default, and then restart the terminal. (There is no built-in command line interface for changing the default profile of GNOME Terminal.)*