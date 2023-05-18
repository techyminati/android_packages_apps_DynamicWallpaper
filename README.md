# DynamicWallpaper
----------------------------------------------------------------------------------
* This app aims to generate beautiful gradient wallpapers and allows user to set it with this app itself.

-------------------------------------------------------------------------------------------------------
* Description
- This is an Android application that generates gradient wallpapers. The main functionality of the app is to create a gradient using random colors and then set it as a wallpaper for the device. Here is a brief overview of the code:

Importing required libraries:
The required libraries for this app are imported in the beginning, including the standard Android libraries as well as some third-party libraries like the "androidx.appcompat.app" library.

Initializing the views and variables:
The views used in the app, such as the toolbar, imageView, and imageButton, are initialized in the onCreate() method. The width and height of the screen are also calculated in this method.

Creating gradient:
The createGradient() method takes an array of color values as input and returns a LinearGradient object that can be used to draw the gradient. This method uses the width and height of the screen to determine the start and end points of the gradient.

Refreshing the wallpaper:
The refreshWallpaper() method generates random color values, creates a gradient using those colors, and then creates a bitmap using that gradient. The bitmap is then set as the image in the imageView.

Button animations:
The buttonAnimation() method is called when a button is clicked to create an animation effect on the button. The animation scales up the button and rotates it by 180 degrees for a duration of 250ms.

Setting the wallpaper:
The setWallpaper() method is called when the user chooses to set the generated gradient as their wallpaper. This method uses the WallpaperManager class to set the generated bitmap as the device's wallpaper.

Handling menu items:
The toolbar is used to create a menu with a single item, "Set Wallpaper". When this item is clicked, a dialog box is displayed that allows the user to choose where they want to set the wallpaper (home screen, lock screen, or both). The setWallpaper() method is called with the appropriate value based on the user's selection.

Overall, this code generates a random gradient and allows the user to set it as their wallpaper in a few clicks.
