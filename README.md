<div align="center">

<a href="https://alt-tab.app/"><img src="docs/readme/main.svg" alt="AltTab Pro — 7.4M downloads — 15K GitHub stars — Get AltTab"/></a>

<a href="https://jb.gg/OpenSource"><img src="docs/readme/sponsor.svg" alt="Sponsored by JetBrains" width="900"/></a>

</div>

This fork adds a GitHub Action workflow that builds an unsigned version of Alt-Tab with Pro features enabled for free.

Since the app is self-signed you'll need tell your mac it's fine:

```sh
xattr -dr com.apple.quarantine "$HOME/Downloads/AltTab.app"
```

