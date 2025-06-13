# SpecialEditionKDE Gold Theme

A customized KDE desktop environment theme with elegant gold accents.

## Features

- Gold-themed KDE color scheme
- Gold-accented Kvantum theme for application styling
- Gold-accented Aurorae window decoration theme
- Gold-accented Plasma desktop theme
- Custom wallpaper (SE.png)

## Installation Instructions

1. **Copy all files to your home directory:**

   ```bash
   cp -r * ~/
   ```

2. **Apply the color scheme:**
   - System Settings > Appearance > Colors > Select "SpecialEditionKDE"

3. **Apply the Kvantum theme:**
   - Open Kvantum Manager
   - Select "SpecialEditionKDE" theme
   - Click "Use this theme"

4. **Apply the window decoration:**
   - System Settings > Appearance > Window Decorations > Select "SpecialEditionKDE"

5. **Apply the Plasma theme:**
   - System Settings > Appearance > Plasma Style > Select "SpecialEditionKDE"

6. **Set wallpaper:**
   - Run the included script:
   ```bash
   chmod +x set-wallpaper.sh
   ./set-wallpaper.sh
   ```
   
   Or manually set wallpaper to SE.png

## Structure

- `.config/Kvantum/SpecialEditionKDE/`: Kvantum theme files
- `.local/share/color-schemes/SpecialEditionKDE.colors`: Color scheme
- `.local/share/aurorae/themes/SpecialEditionKDE/`: Window decoration
- `.local/share/plasma/desktoptheme/SpecialEditionKDE/`: Plasma desktop theme
- `SE.png`: Wallpaper

## Credits

Special thanks to the original theme creators whose work was modified to create this gold theme.

Enjoy your SpecialEditionKDE Gold Theme!
