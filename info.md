# Vaporwave Pink Pheme
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/custom-components/hacs)

This is a theme for [Home Assistant](https://www.home-assistant.io/). You can install it [manually](#installation) or via [HACS](https://hacs.xyz/).

## Installation
1. Copy the folder `themes` into your home-assistant folder
2. Create the folder `lovelave-ui` in your `www` folder. Download the [background image](https://github.com/linsvensson/vaporwave-pink-theme/raw/master/www/lovelace-ui/pink-with-mountains.jpg) and place it in the new folder.
3. Add this under the section `frontend` in your `config.yaml`:
    ```
    frontend:
      themes: !include_dir_merge_named themes
    ```
4. Restart Home Assistant
5. Enable the theme in your user profile (bottom left in Home Assistant)
 
## Screenshots
![image](https://user-images.githubusercontent.com/5594088/72549551-3511e500-3891-11ea-8806-1248dd50f523.PNG)
![image](https://user-images.githubusercontent.com/5594088/72549495-17dd1680-3891-11ea-8919-5fd18ff36a64.PNG)

## Optional disable background
Remove or comment out the 3rd line in the file `themes/vaporwave-pink.yaml`

## Attributions
- Background Image from [a0a0a0 @ wallhaven](https://whvn.cc/5wdj69)
- Home layout heavily inspired by [Isabella Gross Alström](https://isabellaalstrom.github.io/)