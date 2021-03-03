Backgammony Flatpak

```bash
# Building
flatpak-builder build-bundle uk.jnthn.backgammony.json backgammony --force-clean

# Running
flatpak-builder --run build-bundle uk.jnthn.backgammony.json backgammony

# Installing
flatpak-builder --user --install build-bundle org.jnthn.backgammony.json
```

