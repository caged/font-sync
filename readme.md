MyFonts Orders Sync

MyFonts requires you to download existing orders one by one, which can be tedious. I'm also lazy, and this hack goes through your orders, downloads the associated zip files for each order and then goes through each font and downloads the preview images which I find helpful for inspiration.

### Usage

1. Create a `.env` file and add the following below. Make sure the directories exists.

```
MYFONTS_USERNAME=YOUR_MF_USERNAME
MYFONTS_PASSWORD=YOUR_MF_PW
ARCHIVE_DIR="downloads/archives"
PREVIEW_IMAGES_DIR="downloads/previews"
```

2. Run

```
script/download-orders
```

All order zips should now be in your archive folder.
