# Borrito repo (Sileo)

APT source for **Borrito Ni Johannes** (`com.srjahh.doritopad`) by srjahh.

## Add in Sileo

1. Sileo → Sources → **+**
2. Paste:

```text
https://jhayramirez.github.io/borrito-repo/
```

3. Refresh sources → install / update **Borrito Ni Johannes**

## Publish a new build

From DoritoPad after packaging:

```bash
make package FINALPACKAGE=1
./scripts/publish-sileo-repo.sh
```
