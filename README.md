# 4chan /wg/ scrapper using dmenu and feh

## Requirements

`dmenu` & `feh`

## Usage

`chmod +x wg`

`./wg [download/review] [thread cap]`

## Patches

### image-name.diff

After selecting "Save" another dmenu asks how the image should be called.

### How to patch

`patch < patches/image-name.diff`
