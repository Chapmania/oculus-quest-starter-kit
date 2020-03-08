# Oculus Quest Starter

This is a Unity starter project for the Oculus Quest platform.

## Software

* Unity 2019.3.1f1

## Unity Packacges

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