# LMaster
Application can remotly control Panasonic Lumix Cameras from Windows 10 devices (PC, Mobile, ... Xbox, Hololens!?)

Former name **GMaster**.

Application can do no more than original app from Panasonic for Android/iOS. 
While for now app does not support all remote features, supported features work in a better and faster way. 
And if something is wrong or not enough I can fix it much much faster than Panasonic in their app.

App is free and has no ad. You can install it from [MS Store](https://www.microsoft.com/store/apps/9NC2W8KC526F) or from [Project Release page](https://github.com/Rambalac/GMaster/releases/latest)

[Connection Manual](/ConnectionManual.md) (incomplete)

## Features
* Fullscreen camera liveview. Split screen and new windows for multiple cameras.
* LUT preview. Per camera setting.
* Photo capture and video recording start/stop.
* Change basic parameters like ISO, Aperture, and Shutter. Changes on camera get reflected on the screen in real time.
* Move/resize Autofocus point by mouse or gesture. Real AF area is displayed in real time for Point and Following AF.
* Power Zoom lens zoom and change focus in Manual Focus mode.
* Anamorphic desqueezing (1.33x, 1.5x, 1.75x, 2x). Per camera setting with option for Anamorphinc Video mode only.
* WiFi manager to autoconnect to camera WiFi access point.
* Multiple cameras can be controlled. You can connect cameras to common access point.

## Cameras
### Fully supported
GH4, GH3
### Confirmed
GX85, GX80, GX7, G7, G85
### Other
App may work with other Panasonic Lumix cameras, but I have no way to test it.

![Screenshot](/images/screenshots/PC-4.jpg)

## News
※ It can take from 12 hours to several days from pushing to MS Store til update appears for all users.
### 2017-05-08
Pushed version 1.8.5 to MS Store

* Renamed app to LMaster as GMaster is lens trademark.
* Added button to reset focus area to center
* Minor UI change moving camera settings to flyout menu item and adding menu item to open camera in new windows directly.

### 2017-05-04
Pushed version 1.8.4 to MS Store

* Fixed app restart issues
* Minor UI fixes

### 2017-05-01
Pushed version 1.8.3 to MS Store

Added indicators:
* Focus and autofocus modes
* Memory card left with access and error indication
* Battery
* Fix for camera mode reading during video recording.

### 2017-04-26
Pushed version 1.8.1 to MS Store

* Fixed minor bugs
* Fixed one focus area resize on GH4
* Added full support for manual focus with assist moving, switching and resizing

### 2017-04-21
Pushed version 1.8.0 to MS Store

* Improved stability and fixed instant values glitch
* Added synchronised operations. Can start/stop recording or captrue multiple cameras at once. Separate option for parameters and focus.
* Improved focus areas display and fixed their rendering glitches
* Fix for TS5/FS5

#### 2017-04-14
Pushed version 1.7.5 to MS Store

* Fixes for Lumix G80.
* Connection fixes for reconnect on network problems.
* Better logging.
#### 2017-04-12
Pushed version 1.7.3 to MS Store

* Added workaround for wrong XML returned by at least GH5. XML response contains duplicated ids.
#### 2017-04-10
Pushed version 1.7.0 to MS Store

* More fixes and workarounds for other cameras connectivity.
* Added split screen modes and new window.
* Added WiFi management to remember and autoconnect to access points.
* Minor fixes.
#### 2017-04-07
Pushed version 1.6.0 to MS Store

* Hopefully fixed issue with modern camera models like GX85. Thanks to Lufthummel from DPreview
* Added Cube LUT support. Don't have grading experience so could be wrong.
* Added Anamorphic desqueezing support (1.33x, 1.5x, 1.75x, 2x).
* Added hardware acceleration as for LUT as for general performance improvement.
#### 2017-04-04
Pushed version 1.5.0 to MS Store

* Added Power Zoom
* Added Manual Focus
* Fixed Focus point rendering for different aspects
* Fixes for reconnect problems in specific networks
* Added better Enum conversion from int
* Moved Tools to separate project
* Added test for IntToEnum
* Fixed focus point pinch resize
* Fixed initial ISO, Sh and Ap selection

