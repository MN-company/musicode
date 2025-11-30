![MusiCode Banner](banner-placeholder.png)
[![Apple Intelligence](https://img.shields.io/badge/Apple%20Intelligence-required-lightgrey.svg)]()
[![Shortcuts](https://img.shields.io/badge/Shortcut-ready-green.svg)]()

MusiCode is a project inspired by _Spotify Codes_, but without their limitations. It allows you to use any image, symbol, logo, or object as a visual code that opens a link. Choose your own visual, upload it to the repo, and MusiCode takes care of the rest.

## How it works

MusiCode uses Apple Intelligence multimodal recognition.

1. The shortcut downloads the reference image named img.jpeg from your GitHub repo.
2. When you launch it, the camera opens and asks you to frame your visual code.
3. The shortcut sends both the reference image and the newly taken photo to Apple’s cloud model.
4. If the model detects a match, it opens the URL stored in url.txt.
5. If not, it displays an error notification.

## [Supported Devices](https://www.apple.com/apple-intelligence/)

| Device | Supported |
|--------|-----------|
| iPhone 15 Pro | ✔️ |
| iPhone 15 Pro Max | ✔️ |
| iPhone 16 | ✔️ |
| iPhone 16e | ✔️ |
| iPhone 16 Plus | ✔️ |
| iPhone 16 Pro | ✔️ |
| iPhone 16 Pro Max | ✔️ |
| iPhone 17 | ✔️ |
| iPhone Air | ✔️ |
| iPhone 17 Pro | ✔️ |
| iPhone 17 Pro Max | ✔️ |
| iPad Air M1+ | ✔️ |
| iPad Pro M1+ | ✔️ |
| iPad Mini | ✔️ |

## Can I change the model

Yes.

- Apple local model: works, but with lower accuracy.  
- ChatGPT Vision: works, but has higher latency and depends on your subscription.  
- Apple cloud model (recommended): best speed and accuracy.

## How to use

1. Fork this repo.  
2. Replace img.jpeg with your own visual code. Do not rename the file. Get the RAW link.  
3. Edit url.txt with the link you want to open. Get its RAW link as well.  
4. Import the shortcut on your iPhone or iPad.  
5. On first launch, enter the RAW URLs when prompted.  
6. Your system is ready. Print or display your visual code anywhere.

## Shortcut Link
[DOWNLOAD THE SHORTCUT](https://www.icloud.com/shortcuts/5de9e2422b684d009879a23c52ff7a20)

## What you can use it for

- Opening playlists or music content  
- Creating digital business cards  
- Linking physical objects to online content  
- Interactive experiences, puzzles, treasure hunts  
- Branding, merchandising and creative installations  

## License

You may not copy this project and claim authorship unless you have substantially modified it.  
Credits to the original author are always required.
