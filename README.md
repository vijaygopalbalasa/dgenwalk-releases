# dGENwalk releases

Signed Android builds of **dGENwalk**, a walking game for the [dGEN1](https://shop.freedomfactory.io/) on ethOS. This repository holds the release files only. The source code is not here.

## Latest: 2.2.4

**[Download dgenwalk-2.2.4.apk](https://github.com/vijaygopalbalasa/dgenwalk-releases/releases/download/v2.2.4/dgenwalk-2.2.4.apk)** (78.3 MB)

| | |
|---|---|
| Package | `io.dgenwalk.app` |
| Version | 2.2.4 (versionCode 9) |
| SHA-256 of the APK | `f2834b9989aea586926ede6a5f6ccc9196eff21f2bb7c2201235a9a71d297ee5` |
| Signing certificate SHA-256 | `8E:4D:3F:55:BB:92:71:85:03:12:39:78:B0:C9:EB:F8:76:C4:57:E5:4B:59:C1:83:BC:F9:72:07:BC:02:EE:47` |
| Tested on | A physical dGEN1 on ethOS 4.5 (`V04.20261005`) |

Check your download:

```bash
shasum -a 256 dgenwalk-2.2.4.apk
apksigner verify --print-certs dgenwalk-2.2.4.apk
```

The same certificate is published at <https://api.dgenwalk.xyz/.well-known/assetlinks.json>.

## What it does

dGENwalk makes your daily walk a game on the dGEN1: steps count in the background, and your charge bar fills on the screen and the Terminal strip. Walk 5,000 steps to unlock a free daily call on whether ETH ends the day higher or lower; right calls build a streak and climb the weekly board. Step pools let walkers put USDC from their own dGEN1 wallet on keeping a daily goal (an allow-listed beta while legal checks are completed).

The app signs and sends through the ethOS WalletSDK.

## Links

- Website: <https://api.dgenwalk.xyz/>
- Privacy: <https://api.dgenwalk.xyz/privacy>
- Terms: <https://api.dgenwalk.xyz/terms>
- Support: <https://api.dgenwalk.xyz/support> or support@dgenwalk.xyz
- Delete your account: <https://api.dgenwalk.xyz/delete-account>
- X: [@dgenwalk](https://x.com/dgenwalk)
