# nekoget
A simple tool for getting images from NekosAPI and yande.re. **(Linux ONLY)**

### Disclaimer
Do **NOT** rely on the maturity ratings too much, as the API does sometimes accidentally include NSFW material as "safe" or "suggestive". This is not something I can control, and I do not blame the team behind NekosAPI either.

### Another Disclaimer
Do not expect that many updates, since this project is quite small and simple.

## Installation
Well, this isn't hard. You can clone the source code, and run `makepkg -si` in the folder. This only works for Arch-based distributions, which are the only officially supported distribution type for now.

## Before you Ask..
### Why is the code written badly?
Because I am not an expert, and merely had a simple cool idea that I wanted to make happen. Like said in `--version`, ChatGPT made requesting, and then I built upon the simple request feature, to make it a full fledged cli tool.

## Blob use and reasoning

### `iv-cli` bykenshaw on github. (https://github.com/kenshaw/iv/)
This package is used for viewing images in the terminal, for terminal mode.
Modifications:
- Renamed binary from "iv", to "iv-cli"

**Why?**
I have decided to include this package, as per trying to install it from the **AUR** gave me an error, that an executable called `iv` already existed, and therefore was not possible for me to obtain from the **AUR**, meaning I needed to get it manually. **ALL** of the credits for that tool, go to "bykenshaw" on Github. The **LICENSE** (MIT) for the tool is included as `LICENSE.iv`.
