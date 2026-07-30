# Borrito / srjahh APT repo (Sileo)

Packages: **Borrito Ni Johannes**, **CraneDeck**

## Add in Sileo

Tap on device: [Add to Sileo](sileo://source/https://jhayramirez.github.io/borrito-repo/)

Or add source manually:

```text
https://jhayramirez.github.io/borrito-repo/
```

Landing page: https://jhayramirez.github.io/borrito-repo/

## Publish

```bash
# Borrito
cd ~/Documents/DoritoPad && make package FINALPACKAGE=1

# Then publish both (latest Borrito + latest CraneDeck debs)
./scripts/publish-sileo-repo.sh
```

## Privacy note

GitHub Pages on a free public repo is **world-readable** if someone has the URL (or finds it).
True private hosting needs paid GitHub private Pages or your own server with auth.
