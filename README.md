# DotOne — Add to Wallet

A static page for events: scan the QR, pick your wallet, and DotOne Smart Chain gets added to it (same values as the "Add DotOne Smart Chain" button on [dotscan.one](https://dotscan.one)).

| | |
|---|---|
| Network name | DotOne Smart Chain |
| Chain ID | 505 (`0x1f9`) |
| Currency | DOTO (18 decimals) |
| RPC | https://rpc.dotone.online/ |
| Explorer | https://dotscan.one |

## Files

- `index.html`: the page the QR opens. It lists the wallets (MetaMask, Trust Wallet, Coinbase, OKX, Bitget, TokenPocket, imToken). On mobile it opens the selected wallet's in-app browser, then sends `wallet_addEthereumChain`.
- `qr.html`: an A5 poster with the QR, plus PNG/SVG downloads of the QR.

## Running it

The repo root is the site root. Turn on GitHub Pages (Settings → Pages → Deploy from branch → `main` / root), then open `https://<user>.github.io/dotone-add-to-wallet/qr.html` to print the QR.
