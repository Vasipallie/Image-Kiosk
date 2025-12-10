# Image Kiosk (via GitHub)

The Image Kiosk application is an auto reloading image kiosk, which automatically fetches images from a specified github repository folder and starts a looping carousel of images in the folder.

## Setup

Setting up the image kiosk is a very simple and easy process, ensure that the repository you are using is public.

1. Open the index.html file
2. Fill in the following fields

```
const OWNER = '';
const REPO = '';
const FOLDER_PATH = 'images'; 
```

Note that the default folder path will be "images" in your repository, to change this simply edit the path to your liking
