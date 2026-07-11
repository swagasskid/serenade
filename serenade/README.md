# Serenade â€” GitHub client payload

Upload **this folder** to your GitHub repo (`AtiLion/AtiRoNya`, branch `master`).

## What goes on GitHub (this folder only)

```text
bin/
  Serenade.dll
  BlazeSDK.dll
  winmm.dll
Serenade/
  QHash.key          optional
README.md
```

The **SerenadeLoader.exe** app is **not** uploaded here. Users get the loader separately (zip/portable release). The loader downloads these three DLLs from GitHub when they click Launch.

Download URLs used by the loader:

- `https://raw.githubusercontent.com/AtiLion/AtiRoNya/master/bin/Serenade.dll`
- `https://raw.githubusercontent.com/AtiLion/AtiRoNya/master/bin/BlazeSDK.dll`
- `https://raw.githubusercontent.com/AtiLion/AtiRoNya/master/bin/winmm.dll`

Or attach the same three files to a GitHub Release (loader checks releases first).

## Upload steps

1. Push this folder to GitHub (keep `bin/` at repo root)
2. Distribute `SerenadeLoader.exe` + `Assets/SerenadeLogo.png` to users separately
3. User runs loader â†’ DLLs download from GitHub â†’ VRChat starts
