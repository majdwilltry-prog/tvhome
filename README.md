# TV Home — an Apple TV–style home screen for Android TV

## 1. Build the APK (no software to install)
1. Make a free account at github.com and create a new repository.
2. Click "uploading an existing file" and drag in everything from this folder
   (including the hidden `.github` folder), then click Commit.
3. Open the **Actions** tab, then wait about 5 minutes for "Build APK" to finish.
4. Click the finished run and download **TVHome-apk** (a zip with `app-debug.apk`).

(Or open the folder in Android Studio and choose Build > Build APK.)

## 2. Install it on the TV
1. On the TV, install **Downloader** (by AFTVnews) from the Play Store, or copy the APK to a USB stick.
2. Settings > Device Preferences > Security & restrictions > allow **Unknown sources** for Downloader / File manager.
3. Open the APK and press Install.

## 3. Make it your home screen
Press **Home** on the remote. If the TV asks which app to use, pick **TV Home > Always**.
If it never asks, see the section on stubborn TVs in the chat instructions.

## Remote controls
- Arrows: move between apps
- OK: open the app
- Hold OK: app info (uninstall, clear data)
- Back: jump to the first app

## Customizing
Edit the "Easy settings" block at the top of `MainActivity.kt`:
number of columns, banner colors, and tile colors.
