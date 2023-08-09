
# Gradle Dependency
The minimum API level supported by this library is API 15

Add JitPack repository to root ```build.gradle```
```Gradle
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
```
Add the dependency
```Gradle
dependencies {
    implementation 'com.github.danimahardhika.candybar-library:core:3.5.0-b4'
}
```
Or use a snapshot
```Gradle
dependencies {
    implementation('com.github.danimahardhika.candybar-library:core:-SNAPSHOT') {
        changing = true
    }
}
```


# Previews
<img src="https://raw.githubusercontent.com/danimahardhika/candybar-library/master/screenshots/home.jpg" width="215"/> <img src="https://raw.githubusercontent.com/danimahardhika/candybar-library/master/screenshots/navigation_drawer.jpg" width="215"/> <img src="https://raw.githubusercontent.com/danimahardhika/candybar-library/master/screenshots/changelog.jpg" width="215"/> <img src="https://raw.githubusercontent.com/danimahardhika/candybar-library/master/screenshots/icon_request.jpg" width="215"/>
<img src="https://raw.githubusercontent.com/danimahardhika/candybar-library/master/screenshots/cloud_wallpapers.jpg" width="215"/> <img src="https://raw.githubusercontent.com/danimahardhika/candybar-library/master/screenshots/wallpaper_preview.jpg" width="215"/> <img src="https://raw.githubusercontent.com/danimahardhika/candybar-library/master/screenshots/icons.jpg" width="215"/> <img src="https://raw.githubusercontent.com/danimahardhika/candybar-library/master/screenshots/settings.jpg" width="215"/>

# Features
* License Checker
* Apply: 23 launchers
  * [List of Supported Launchers](https://github.com/danimahardhika/candybar-library/wiki/List-of-Supported-Launcher)
* Icon Picker: see all icons included with sections and search
* Icon Request
  * Regular Request: free to request
  * Premium Request: pay to request
* Cloud Based Wallpaper
  * Preview wallpaper
  * Apply wallpaper: inbuilt wallpaper crop
  * Download wallpaper
* Settings
  * Clear Cache
  * Swith to Dark Theme
  * Restore Purchases: restore premium request after reinstalling
* Frequently Asked Questions: with search
* About
* Donation
* Changelog: show changelog every update
* Muzei Live Wallpaper: smart art source loader
* Localization: supports more than 10 languages

**NOTE:** This is just Icon Pack Dashboard, not Icon Pack template or Icon Pack tutorial. You need to add required XML for Icon Pack by yourself.

# Support Development
Support development by making donation through demo app at Google Play

