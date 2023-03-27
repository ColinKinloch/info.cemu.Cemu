# Flatpak for Cemu

Cemu is a Nintendo Wii U emulator. For more information, please [visit the project website](https://cemu.info/) or [view the source code](https://github.com/cemu-project/Cemu/).

## Filesystem read/write permissions

To get read/write filesystem permissions for converting files to wua I suggest running Cemu from the terminal via:

```
flathub run --filesystem=host info.cemu.Cemu
```

This can be done more permanently with the flatseal GUI or with:
```
flatpak override --user --filesystem=host info.cemu.Cemu
```
