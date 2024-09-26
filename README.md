# nekoget
![AUR](https://img.shields.io/aur/version/nekoget?style=for-the-badge&logo=archlinux&logoColor=ffffff&label=AUR)

A simple tool for getting images from NekosAPI and yande.re. **(Linux ONLY)**

## Note
I apologize in advance for possible issues that I may accidentally cause on the project. I have not used **Github**, and I have never maintained a package on the **AUR**. There can be some simple complications that may happen, but there shouldn't be anything major.

### Maturity ratings
For NekosAPI, do **NOT** rely on the maturity ratings too much, as the API does sometimes accidentally include NSFW material as "safe" or "suggestive". This is not something I can control, and I do not blame the team behind NekosAPI either. All the things listed below, are under the impression that it may be very unreliable.
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

