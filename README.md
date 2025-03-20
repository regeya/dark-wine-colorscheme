# Dark WINE Colorscheme

A dark colorscheme for vanilla Wine, inspired by Adwaita Dark.

![Screenshot of OpenMPT running in GNOME](/images/screeeshot.png)

A simple .reg file to change the colorscheme of Wine.  

## How to use

Let's say you have a Windows app installed in a subdirectory in your home directory.  My example here is OpenMPT, a Windows music tracker, installed in "$HOME/.openmpt".  So all you need to do is download the reg file, let's sayin in "$HOME/Downloads". So then all you need to do is:

    WINEPREFIX="$HOME/.openmpt" regedit $HOME/Downloads/dark-wine-colorscheme.reg

And then reload the app to see the changes take effect.

If you want to set your app font, open winecfg:

    WINEPREFIX="$HOME/.openmpt" winecfg
