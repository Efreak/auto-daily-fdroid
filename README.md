## note
This repo is a clone of [xarantolus/fdroid](https://github.com/xarantolus/fdroid), filtered (via git-filter-repo's clean-ignore filter) to remove all app-specific commits. A modification has been made to the metascoop go program to only fetch 5 releases from each repo. You can get a clean copy of this repo (without apks or metadata) at [efreak/fdroid-action](https://github.com/efreak/fdroid-action), however it's not guaranteed to be up to date with xaranolus' code.

# fdroid
This repository hosts an [F-Droid](https://f-droid.org/) repo for the following apps. This allows you to install and update apps very easily.

### Apps

<!-- This table is auto-generated. Do not edit -->
| Icon | Name | Description | Version |
| --- | --- | --- | --- |
| <a href="https://github.com/ArizArmeidi/AnimSearch"><img src="fdroid/repo/icons/com.example.anim_search.2001.png" alt="AnimSearch icon" width="36px" height="36px"></a> | [**AnimSearch**](https://github.com/ArizArmeidi/AnimSearch) | Anime and Manga search app. created using Flutter and Jikan API | 1.0.0 (2001) |
| <a href="https://github.com/iamtheblackunicorn/Buwa"><img src="fdroid/repo/icons/com.blackunicorn.buwa.4.png" alt="Black Unicorn Wallpapers icon" width="36px" height="36px"></a> | [**Black Unicorn Wallpapers**](https://github.com/iamtheblackunicorn/Buwa) | Sexy and beautiful wallpapers for your Android-powered device! :black_heart: | 1.3.0 (4) |
| <a href="https://github.com/k0shk0sh/FastHub"><img src="fdroid/repo/icons/com.fastaccess.github.461.png" alt="FastHub (official) icon" width="36px" height="36px"></a> | [**FastHub (official)**](https://github.com/k0shk0sh/FastHub) | FastHub the ultimate GitHub client for Android. | 4.6.1 (461) |
| <a href="https://github.com/LightDestory/FastHub-RE"><img src="fdroid/repo/icons/" alt="FastHub Re(vival) icon" width="36px" height="36px"></a> | [**FastHub Re(vival)**](https://github.com/LightDestory/FastHub-RE) | Revival Attempt for FastHub the ultimate GitHub client for Android. | 4.7.7 (477) |
| <a href="https://github.com/amangautam1/flutter-musicplayer"><img src="fdroid/repo/icons/com.onedreamers.musicplayer.2006.png" alt="Flutter Music Player icon" width="36px" height="36px"></a> | [**Flutter Music Player**](https://github.com/amangautam1/flutter-musicplayer) | A complete music player in flutter with cool UI and design. | 1.0 beta (2006) |
| <a href="https://github.com/amangautam1/flutter-musicplayer"><img src="fdroid/repo/icons/com.yourcompany.musicplayer.5.png" alt="Flutter Music Player icon" width="36px" height="36px"></a> | [**Flutter Music Player**](https://github.com/amangautam1/flutter-musicplayer) | A complete music player in flutter with cool UI and design. | 0.8 (5) |
| <a href="https://github.com/VarunS2002/Flutter-Sudoku"><img src="fdroid/repo/icons/com.varuns2002.sudoku.2040.png" alt="Flutter-Sudoku icon" width="36px" height="36px"></a> | [**Flutter-Sudoku**](https://github.com/VarunS2002/Flutter-Sudoku) | This is a fully fledged Sudoku game written in Dart using Flutter. | 2.4.0 (2040) |
| <a href="https://github.com/Livinglist/Hacki"><img src="fdroid/repo/icons/" alt="Hacki icon" width="36px" height="36px"></a> | [**Hacki**](https://github.com/Livinglist/Hacki) | A Hacker News client made with Flutter that is just enough. | 0.2.27 (69) |
| <a href="https://github.com/kawaiiDango/pScrobbler"><img src="fdroid/repo/icons/" alt="Pano Scrobbler icon" width="36px" height="36px"></a> | [**Pano Scrobbler**](https://github.com/kawaiiDango/pScrobbler) | A last.fm scrobbler and viewer for Android | 2.64 - 2022, Jun 01 (264) |
| <a href="https://github.com/vellt/GetX-Stream-Music-Player-Flutter"><img src="fdroid/repo/icons/com.example.music_player_fluttter.1.png" alt="Stream Music Player with GetX icon" width="36px" height="36px"></a> | [**Stream Music Player with GetX**](https://github.com/vellt/GetX-Stream-Music-Player-Flutter) | Listen to music online with a clean GetX MVC architecture | 1.0.0 (1) |
| <a href="https://github.com/Suwayomi/Tachidesk-Sorayomi"><img src="fdroid/repo/icons/" alt="Tachiyomi-Sorayami icon" width="36px" height="36px"></a> | [**Tachiyomi-Sorayami**](https://github.com/Suwayomi/Tachidesk-Sorayomi) | A free and open source manga reader based on Flutter to read manga from a Tac... | 0.2.3 (1) |
<!-- end apps table -->

### How to use
1. At first, you should [install the F-Droid app](https://f-droid.org/), it's an alternative app store for Android.
2. Now you can copy the following [link](https://raw.githubusercontent.com/efreak/auto-daily-fdroid/main/fdroid/repo), then add this repository to your F-Droid client:

    ```
    https://raw.githubusercontent.com/efreak/auto-daily-fdroid/main/fdroid/repo
    ```

    Alternatively, you can also scan this QR code:

    <p align="center">
      <img src=".github/qrcode.png?raw=true" alt="F-Droid repo QR code"/>
    </p>

3. Open the link in F-Droid. It will ask you to add the repository. Everything should already be filled in correctly, so just press "OK".
4. You can now install my apps, e.g. start by searching for "Notality" in the F-Droid client.

### Apps

<!-- This table is auto-generated. Do not edit -->
<!-- end apps table -->
Please note that some apps published here might contain [Anti-Features](https://f-droid.org/en/docs/Anti-Features/). If you can't find an app by searching for it, you can go to settings and enable "Include anti-feature apps".

### For developers
If you are a developer and want to publish your own apps right from GitHub Actions as an F-Droid repo, you can fork/copy this repo and see  [the documentation](setup.md) for more information on how to set it up.

### [License](LICENSE)
The license is for the files in this repository, *except* those in the `fdroid` directory. These files *might* be licensed differently; you can use an F-Droid client to get the details for each app.
