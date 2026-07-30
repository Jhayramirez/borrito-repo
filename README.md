# Borrito repo (Sileo)

APT source for **Borrito Ni Johannes** (`com.srjahh.doritopad`) by srjahh.

## Add in Sileo

1. Sileo → Sources → **+**
2. Paste:

```text
https://srjahh.github.io/borrito-repo/
```

3. Refresh sources → install / update **Borrito Ni Johannes**

## Maintainers

From the DoritoPad tree after `make package`:

```bash
./scripts/publish-sileo-repo.sh
```

That copies the newest `.deb`, rebuilds `Packages` / `Release`, and pushes this repo (GitHub Pages).
