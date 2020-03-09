# Oculus Quest Unity Starter

This is a Unity starter project for the Oculus Quest platform.

## Installation instructions

Make this repo your own by doing the following steps:

1. Clone the repo
2. Rename the Unity project folder
3. Remove the .git file inside the root folder (the .git file is normally a hidden file)
4. (Optional) Open the ProjectSettings.asset file (ProjectSettings/ProjectSettings.asset) in a text editor and change the productName variable, ideally to the same name as your project folder (you could also do this via Player Settings in the editor)
5. (Optional) Reinitialize git
6. Install the Unity packages and configure the settings if they are not yet set up (the repo should already contain these changes)

## Software

* Unity 2019.3.1f1

## Unity packages

Window > Package Manager

* XR Management (latest)
* XR Interaction Toolkit (latest; select 'show preview packages')
* Oculus XR Plugin (latest)

## Settings

* Build Settings
  * Platform: Android
* Project Settings
  * Player
    * Other Settings
      * Graphics APIs
        * OpenGLES3
  * XR Plugin Management
    * Plugin Providers
      * Oculus Loader
    * Installable XR Plugin Providers
      * Oculus XR Plugin
  * XR Plugin Management > Oculus
    * Stereo Rendering Mode: Multi Pass
    * V2 Signing (Quest): Checked