# Alpha Trench for Safari

<p align="center">
  <strong>The Alpha Tek trench client, packed for Safari on Mac.</strong><br />
  <sub>Unsigned developer preview · Safari 18+ · Paper first · Same product as Chrome</sub>
</p>

<p align="center">
  <a href="https://www.AlphaTek.App"><img src="https://img.shields.io/badge/Website-AlphaTek.App-00D4FF?style=for-the-badge&labelColor=0A0A0A" alt="AlphaTek.App" /></a>
  <a href="https://discord.gg/epicalpha"><img src="https://img.shields.io/badge/Discord-Epic%20Alpha-5865F2?style=for-the-badge&labelColor=0A0A0A&logo=discord&logoColor=white" alt="Epic Alpha" /></a>
  <a href="https://www.AlphaTek.App/alpha-trench/safari"><img src="https://img.shields.io/badge/Download-AlphaTek.App-4285F4?style=for-the-badge&labelColor=0A0A0A" alt="Download from AlphaTek.App" /></a>
</p>

---

## Why a separate repo?

**Alpha Trench is one product.** Chrome and Safari are two **install paths**.

| Repo | Who it is for |
|---|---|
| [AlphaTek.App/alpha-trench](https://www.AlphaTek.App/alpha-trench) | Windows / Chromium product and download page |
| **This repo** | Safari documentation, changelog, screenshots, and support |

Development source remains private. Safari packages are delivered through an authenticated AlphaTek.App account download.

---

## What this is (honest)

- **Not** the Mac App Store listing yet  
- **Not** a different trading engine  
- Historical preview 0.9.239 was packed from the Chromium client  
- Paper Instant Trade, Alpha Guard, Mint Intel, journal, **Trade Replay** (platform history when wallet linked)  
- **Trench Cast / Market Replay / Wallet Replay** on [AlphaTek.App](https://www.alphatek.app) — web Theater  
- **Music Lite is Chrome-only** (Safari has no `offscreen` documents)  
- Mainnet Instant Trade stays **locked**

Historical versions through 0.9.239 retain MIT. Future releases are proprietary Alpha Tek packages.

Product updates and downloads live on [AlphaTek.App](https://www.AlphaTek.App/alpha-trench/safari).

---

## Download Alpha Trench for Safari

- **Official Safari Download:** [AlphaTek.App/alpha-trench/safari](https://www.AlphaTek.App/alpha-trench/safari)
- Sign in with your Alpha Tek account to receive the current package.
- **What Changed:** [CHANGELOG.md](CHANGELOG.md)

## Install (unsigned / temporary)

1. Sign in and download the Safari zip from [AlphaTek.App](https://www.AlphaTek.App/alpha-trench/safari), then unzip it.
2. Safari → Settings → **Advanced** → Show features for web developers.
3. Safari → Settings → **Developer** → **Allow unsigned extensions** (Safari may turn this off after quit).
4. **Develop** menu → **Add Temporary Extension…** → select the folder that contains `manifest.json` (`unpacked`).
5. Settings → Extensions → enable **Alpha Trench for Safari**.
6. Open Axiom / Padre / Photon → toolbar icon → **Always Allow on This Website** → reload.

That last step is Safari’s permission model. The overlay will not inject until you allow the venue.

---

## Trust

- Historical versions through 0.9.239 retain MIT; future versions are proprietary  
- No closed helper app for this preview  
- Paper ledger is local fake SOL until you opt into DevNet  
- Never paste a seed phrase into the extension  

Chrome Web Store / Safari App Store come **after** this preview is boringly stable.

---

## Support

[AlphaTek.App](https://www.AlphaTek.App) · [discord.gg/epicalpha](https://discord.gg/epicalpha)
