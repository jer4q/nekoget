# nekoget
A simple tool for getting images from NekosAPI and yande.re. **(Linux ONLY)**

### Maturity ratings
Do **NOT** rely on the maturity ratings too much, as the API does sometimes accidentally include NSFW material as "safe" or "suggestive". This is not something I can control, and I do not blame the team behind NekosAPI either. All the things listed below, are under the impression that it may be very unreliable.
- safe : mostly safe content
- suggestive : mostly suggestive content
- borderline : nudity allowed, but most often not straight hentai
- explicit : no limits

However on yande.re, the maturity ratings are A LOT more reliable. But, it does raise quickly.
- safe : safe to slightly suggestive content
- questionable : nudity is allowed, even more if censored
- explicit : no limits

### Disclaimer
Do not expect that many updates in the future, since this project is quite small and simple.

## Installation
You have two options.

**1. AUR**

You can officially install `nekoget` from the **AUR**. You can use your favorite **AUR Helper** for this.
```bash
$ paru -S nekoget
```

**2. Manual**

You can also install it manually.
```bash
$ git clone https://github.com/jer4q/nekoget
$ cd nekoget
$ makepkg -si
```

## Before you Ask..
### Why is the code written badly?
Because I am not an expert, and merely had a simple cool idea that I wanted to make happen. Like said in `--version`, ChatGPT made requesting, and then I built upon the simple request feature, to make it a full fledged cli tool.

## Blob use and reasoning

### `iv-cli` kenshaw on github. (https://github.com/kenshaw/iv/)
This package is used for viewing images in the terminal, for terminal mode.

**Modifications:**
- Renamed binary from "iv", to "iv-cli"

**Why?**

I have decided to include this package, as per trying to install it from the **AUR** gave me an error, that an executable called `iv` already existed, and therefore was not possible for me to obtain from the **AUR**, meaning I needed to get it manually. **ALL** of the credits for that tool, go to "kenshaw" on Github. The **LICENSE** (MIT) for the tool is included as [`LICENSE.iv`](https://github.com/jer4q/nekoget/blob/main/LICENSE.iv).
