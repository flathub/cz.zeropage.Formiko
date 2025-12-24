# Formiko

___reStructuredText and MarkDown editor___

Formiko is reStructuredText and MarkDown editor and live previewer. It is written in Python with Gtk3, GtkSourceView and Webkit2. Use Docutils and recommonmark Common Mark parser.

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```
flatpak install flathub cz.zeropage.Formiko
flatpak run cz.zeropage.Formiko
```

## Building

```
git clone git@github.com:flathub/cz.zeropage.Formiko.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install cz.zeropage.Formiko.json
```

---

**Technologies**: GNOME, GTK3, GtkSource, Webkit2, Python
