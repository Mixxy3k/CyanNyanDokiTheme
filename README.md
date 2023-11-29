## Doki Theme with Cyan in the background
![Screenshot](./Screenshots/CyanBeeg.png)
![Screenshot](./Screenshots/CyanSmool.png)

## Configuring Doki Theme with Cyan Theme

1. **Install the Doki Theme Extension for Visual Studio Code:**
   - [Doki Theme Extension](https://marketplace.visualstudio.com/items?itemName=unthrottled.doki-theme)

2. **Additional Details:**
   - For more detailed instructions, visit [Doki Theme Documentation](https://marketplace.visualstudio.com/items?itemName=unthrottled.doki-theme#custom-assets)

3. **Save Images:**
   - Save the theme images in any preferred folder (remember the location).

4. **Open Command Palette:**
   - Use the shortcut (Ctrl + Shift + P).

### Option 1 (UI way):

   - Select: Preferences: Open User Settings.
   - Press Enter.
   - In the search bar, type "Doki"
   - All options are well documented, you can do it!

### Option 2 (JSON way):

   - Select: Preferences: Open User Settings (JSON).
   - Press Enter.
   - Paste the following at the bottom:
   - Remember to change paths to the one you use!
     ```json
     "doki.statusbar.name": "Cyan Nyan",
     "doki.sticker.path": "D:\\DokiExt\\CyanSTCode.png",
     "doki.wallpaper.path": "D:\\DokiExt\\CyanBGCode.png",
     "doki.background.path": "D:\\DokiExt\\CyanBGCode.png",
     ```

     - For the sticker, you can either disable it:
       ```json
       "doki.wallpaper.enabled": false
       ```
     - Or adjust its position (code below moves it higher):
       ```json
       "doki.sticker.css": "z-index:100;background-position:100% 63%"
       ```

### Special Thanks
   - [Doki Theme developers](https://github.com/doki-theme/doki-theme-vscode)
   - [Hacker Neko Waifu Cyan](https://cyan.yt/) 
   - Sticker made by [@yuyuzu11]()
