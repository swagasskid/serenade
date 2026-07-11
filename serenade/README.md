# Serenade â€” GitHub client payload

Upload **this folder** into your repo at [swagasskid/serenade](https://github.com/swagasskid/serenade/tree/main/serenade) (branch `main`).

## What goes on GitHub (this folder only)

```text
serenade/
  bin/
    Serenade.dll
    BlazeSDK.dll
    winmm.dll
  Serenade/
    QHash.key          optional
  README.md
```

The **SerenadeLoader.exe** app is **not** uploaded here. Users get the loader separately. The loader downloads the three DLLs from GitHub when they click Launch.

Download URLs used by the loader:

- `https://raw.githubusercontent.com/swagasskid/serenade/main/serenade/bin/Serenade.dll`
- `https://raw.githubusercontent.com/swagasskid/serenade/main/serenade/bin/BlazeSDK.dll`
- `https://raw.githubusercontent.com/swagasskid/serenade/main/serenade/bin/winmm.dll`

Or attach the same three files to a GitHub Release (loader checks releases first).

## Upload steps

1. Push this folder to `serenade/` in the repo
2. Distribute `SerenadeLoader.exe` + `Assets/SerenadeLogo.png` to users separately
3. User runs loader â†’ DLLs download from GitHub â†’ VRChat starts
