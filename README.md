# Neon-icons
### Standard version
<img src="https://github.com/Akr4ta/neon-icon-theme/blob/main/image_neon.png" alt="e.g image">

### Anarchy version
<img src="https://github.com/Akr4ta/neon-icon-theme/blob/main/image_neon-anarchy.png" alt="e.g image">

### Second Anarchy version
<img src="https://github.com/Akr4ta/neon-icon-theme/blob/main/image_neon-anarchy-op2.png" alt="e.g image">

Icon theme that combines BeautyLine, Sweet, Tela and Candy, harmonized with the Catppuccin Mocha color palette.
* BeautyLine for the majority of the icons,
* Tela for symbolic icons,
* Candy to replace some app icons,
* Sweet for the cursor and folder themes,
* Catppuccin Mocha as the color reference.

There are three versions: neon (the standard), neon-anarchy, and neon-anarchy-op2. The only differences are: in the neon-anarchy version, the menu/app grid icon is replaced by the anarchist "A" symbol, and in neon-anarchy-op2, the cosmic launcher icon is replaced by the anarchist "A" symbol.

# Install
The icon theme is available in the AUR, so you can run the command below if you are using Arch Linux or an Arch-based system:

`yay -S neon-icon-theme`

If you are using a different system, follow the instructions below.

Download the .zip file.

Extract the archive and move either the neon, neon-anarchy or neon-anarchy-op2 folder to icons directory ~/.local/share/icons/ (Create this directory if it doesn't exist).

# Usage
Change via distribution specific tweak-tool.

# Don’t like the folder colors? Try this:
Note: This method only works if you install the theme manually by placing the theme file in ~/.local/share/icons/; it does not work when installing via AUR.

Extract the zip file in your Downloads folder.

When prompted for new_color, enter the HEX color code (e.g., #123456).

Run the following commands in the terminal:

`new_color=`

In other words, the terminal command should look like this: `new_color=#123456`

Finally, run:

`find $HOME/Downloads/neon-icon-theme-main -type f -exec sed -i "s/#7287fd/"$new_color"/Ig" {} +`

Move either the neon-icons or neon-icons-anarchy folder to icons directory ~/.local/share/icons/

# Warning
This icon theme has only been tested on GNOME and COSMIC desktop environments. Other environments may display colors inconsistently.

This theme was designed to be used in dark themes.

This theme is still a work in progress, as we're currently adjusting the icon colors.
