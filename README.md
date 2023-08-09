
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

# How to Use
Take a look inside [Wiki Site](https://github.com/danimahardhika/candybar-library/wiki)

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

# Translation
Help translating CandyBar to supports more languages [here](http://danimahardhika.oneskyapp.com/collaboration/project?id=245866)

# Need a Help?
Join [CandyBar community](https://plus.google.com/communities/113391514858983102172) on Google+

# Icon Pack Using CandyBar
Want your icon pack listed here? Mention me at [Google Plus](https://plus.google.com/u/1/+DaniMahardhika).
* [Delta](https://play.google.com/store/apps/details?id=website.leifs.delta)
* [Simpax](https://play.google.com/store/apps/details?id=com.sikebo.simpax.icons)
* [Tabloid](https://play.google.com/store/apps/details?id=com.indigomadina.tabloid)
* [Pixel](https://play.google.com/store/apps/details?id=com.themezilla.pixelui)
* [Silhoutte](https://play.google.com/store/apps/details?id=com.xonyxltd.icon.silhouettedonate)
* [Apollo](https://play.google.com/store/apps/details?id=com.solarium.apollo)
* [Minimale](https://play.google.com/store/apps/details?id=com.mowmo.minimale)
* [Origin](https://play.google.com/store/apps/details?id=com.mojojojodevlabs.origin)
* [Dimitrix](https://play.google.com/store/apps/details?id=com.darin.dimitrix)
* [Cikukua](https://play.google.com/store/apps/details?id=com.setio.budi.cikukua.icons)
* [Monoic White](https://play.google.com/store/apps/details?id=com.kdpixels.iconpacks.monoic)
* [Lens Icon Pack](https://play.google.com/store/apps/details?id=ru.xorrisont.lens)

# License
```
Copyright (c) 2014-2016 Dani Mahardhika

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
