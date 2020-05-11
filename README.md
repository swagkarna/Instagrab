Instagrab
=========

> Grab images and videos and more from Instagram

## Features

- No need to sign in Instagram account
- No need to register Instagram API
- Download images and videos from Instagram directly
- Download json data in additional, including profile data, image/video data...
- Choose to skip image download, or/and video download, or/and json data download

## Dependency

- [curl](https://curl.haxx.se/download.html)
- [jq](https://stedolan.github.io/jq/download/)

## Usage

```
Usage:
  ./instagrab.sh -u <username> [-d] [-i] [-v]

Options:
  -u               required, Instagram username
  -d               optional, skip json data
  -i               optional, skip image
  -v               optional, skip video
```

### How to run tests

```bash
~$ bats test/instagrab.bats
```

## Disclaimer

The purpose of this script is to download media contents from Instagram in order to backup and archive them. Please do NOT copy or distribute downloaded contents to any third party. Please do remember that the copyright of contents always belongs to the owner of Instagram account. Please use this script at your own responsibility.
