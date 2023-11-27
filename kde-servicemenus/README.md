# Create context menu items (KDE Plasma)

- __libreofficeActions.desktop__: Convert office files like *.odt, *.xlsx and so forth to pdf or print those files directly.
  
- __pdfPrint.desktop__: Print pdf files.

##  How to

- Copy the *.desktop files to ``/usr/share/kservices5/ServiceMenus`` for a system-wide usage or to ``$HOME/.local/share/kservices5/ServiceMenus`` for the current user. 
Instead of copying the files you can also create them by using ``sudo nano`` or another text editor.  

- Rebuild the configuration cache of KService desktop file system by typing ``kbuildsycoca5``.

That's it! Work carefully on your system and check out the extended manual for creating those kind of context menu entries on [gnulinux.ch](https://gnulinux.ch/kontextmen%C3%BC-fuer-dolphin-erstellen) in the form of similar examples.
