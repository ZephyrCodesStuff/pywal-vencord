# pywal-vencord

### What is pywal-vencord?

pywal-vencord is a Pywal template file for Discord's modified Vencord client. It allows you to generate Vencord themes that match your Pywal color scheme.

### How to use pywal-vencord

1. Install Pywal if you don't already have it.
2. Clone this repository to your computer and copy the `colors-discord.css` file in your `$HOME/.config/wal/templates` directory.
3. Run `wal -i <image>`. This will generate a Vencord theme in your `$HOME/.cache/wal` directory.
4. Create a symbolic link as follows: `ln -s $HOME/.cache/wal/colors-discord.css $HOME/.config/VencordDesktop/VencordDesktop/themes/pywal-vencord.theme.css`
5. Go on Vencord's Themes tab and click on "Load missing themes". Finally, enable the theme.

Note that you will have to reload the theme manually every time your color scheme changes.

### Troubleshooting
If you're having trouble getting pywal-vencord to work, please check the following:

- Make sure that you have Pywal installed and that it's working properly.
- Make sure that you're running the pywal command with a valid image file.
- Make sure that you're linking the generated theme file to the correct location.
- Make sure that you're enabling the correct theme in the Vencord settings.

If you're still having trouble, please open an issue on this repository.

### Contributing
If you would like to contribute to pywal-vencord, please feel free to submit a pull request. All contributions are welcome!

I hope this will be helpful!
