# ICECAT ($ICECAT) — HyperEVM meme site

Static landing for the HYPE × ICE collab narrative on **HyperEVM**.

## Preview
Serve the folder (already on `http://127.0.0.1:8780/` in the agent box):

```bash
python3 -m http.server 8780 --bind 127.0.0.1
```

## Go live
Edit `config.js`:

```js
window.ICECAT = {
  name: "ICECAT",
  ticker: "ICECAT",
  ca: "0xYOUR_CONTRACT",          // replace COMING_SOON
  dexscreenerPair: "0xPAIR",      // HyperEVM pair — unlocks chart + stats
  buyUrl: "https://…",            // DEX buy link
  chartUrl: "https://…",          // optional; defaults to DexScreener
  twitter: "https://x.com/thedevrrrrrrr/status/2116574324710633923",
};
```

- CA stays `COMING_SOON` until you paste the real address. Never invent one.
- Chart / Dex tiles stay hidden until `dexscreenerPair` is set (no empty iframe).

## Contents
- Enter gate (“ENTER THE ICE”)
- Sticky nav · hero with CA copy pill · lore · HyperEVM how-to-buy · conditional chart · X embed · meme vault · FAQ
- Assets: `logo.png`, `hero.jpg`, `banner-1500x500.png`, vault + OG art

## Narrative (do not invent beyond)
Tweet: https://x.com/thedevrrrrrrr/status/2116574324710633923 — ice cat for the HYPE × ICE collab; pair to both. Hyperliquid welcomed ICE Markets.
