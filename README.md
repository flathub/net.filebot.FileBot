# FileBot Flatpak

## Building

```
flatpak-builder build-dir --user --ccache --force-clean --install net.filebot.FileBot.yml
```

Then you can run it via the command line:

```
flatpak run net.filebot.FileBot
```

or just search for the installed app on your system

## Translations

If you change anything in the appdata.xml file, you need to run the following command:

```
itstool -o translations/net.filebot.FileBot.pot -i translations/appstream.its net.filebot.FileBot.appdata.xml
```
