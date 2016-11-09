# Configuration

## Electron plugin - v1.0 - by Armaldio

Description : Run your game with the best performances inside Electron

Category : General

Cordova-plugins : undefined

Flags : No

Help : 

Id : armaldio_electron

Rotatable : No

Type : object

<br>
# Actions

There are 10 actions available

**Exit** : Close electron windows *#App*

<br>
**Restart** : Restart electron windows *#App*

<br>
**Focus** : focuses on the application’s first window *#App*

<br>
**Hide** : Hide app window *#App*

<br>
**Show** : Show app window *#App*

<br>
**Maximize** : Maximize window *#App*

<br>
**Set Fullscreen** : Toggle fullscreen *#App*

There is 1 parameters : 

* **State** : Fullscreen state (default value : Set fullscreen)

  * Fullscreen

  * Not fullscreen

<br>
**Show open dialog** : Open a dialog to chose a file *#Dialog*

There are 5 parameters : 

* **Title** : The title of the window

* **Fefault path** : The preselected path

* **Confirmation text (optional)** : The text of the Confirm button

* **Filters (TODO)** : You can filter by filetype

* **Properties** : openFile, openDirectory, multiSelections, createDirectory and showHiddenFiles (comma separated)

<br>
**Write data to file** : Write data to a specific file asynchronously *#Write*

There are 3 parameters : 

* **Tag** : A unique tag to keep track of the result

* **Path** : The path of the file to write

* **Data** : The data to write

<br>
**Read file** : Read a file asynchronously *#Read*

There are 2 parameters : 

* **Tag** : A unique tag to keep track of the result

* **Path** : The file to read

<br>
# Conditions

There are 5 conditions available

**On save success** : Trigger when a specific save action succeed *#Save*

There is 1 parameters : 

* **Tag** : The unique tag

<br>
**On save fail** : Trigger when a specific save action fail to save *#Save*

There is 1 parameters : 

* **Tag** : The unique tag

<br>
**On read success** : Trigger when a specific read action succeed *#Read*

There is 1 parameters : 

* **Tag** : The unique tag

<br>
**On read fail** : Trigger when a specific read action fail to read *#Read*

There is 1 parameters : 

* **Tag** : The unique tag

<br>
**Is Electron** : Test if the game is running on electron *#Test*

<br>
# Expressions

There are 17 expressions available

**GetAppPath** : Returns the current application directory. *#App*

<br>
**GetLocale** : Get locale based on the system *#App*

<br>
**GetOSArch** : Returns a string identifying the operating system CPU architecture *#OS*

<br>
**GetOSHomedir** : Returns the home directory of the current user *#OS*

<br>
**GetOSHostname** : Returns the hostname of the operating system *#OS*

<br>
**GetOSPlatform** : Returns the operating system platform *#OS*

<br>
**GetHomePath** : User’s home directory *#Path*

<br>
**GetAppDataPath** : %APPDATA% (Win), $XDG_CONFIG_HOME or ~/.config (linux), ~/Library/Application (Mac) *#Path*

<br>
**GetUserDataPath** : By default it is the appData directory appended with your app’s name *#Path*

<br>
**GetExePath** : The current executable file *#Path*

<br>
**GetDesktopPath** : The current user’s Desktop directory *#Path*

<br>
**GetDocumentsPath** : User’s document directory *#Path*

<br>
**GetDownloadsPath** : User’s download directory *#Path*

<br>
**GetMusicPath** : User’s music directory *#Path*

<br>
**GetPicturesPath** : User’s picture directory *#Path*

<br>
**GetVideoPath** : User’s video directory *#Path*

<br>
**GetTempPath** : Temporary folder path *#Path*