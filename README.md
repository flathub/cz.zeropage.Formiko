# Formiko

___reStructuredText and MarkDown editor___

Formiko is a reStructuredText and MarkDown editor and live previewer. It is written in Python with GTK 4, GtkSourceView 5 and WebKit. It uses Docutils for reStructuredText and M2R2 as a Markdown-to-reStructuredText converter.

Upstream project: https://github.com/ondratu/formiko

---

## Install from Flathub

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```
flatpak install flathub cz.zeropage.Formiko
flatpak run cz.zeropage.Formiko
```

## Building

```
git clone https://github.com/flathub/cz.zeropage.Formiko.git
cd cz.zeropage.Formiko
flatpak-builder --user --ccache --force-clean --install build cz.zeropage.Formiko.yaml
```
