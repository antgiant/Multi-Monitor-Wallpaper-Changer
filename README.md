Multi Monitor Wallpaper Changer
==============

A simple scriptable commandline wallpaper changer (Modified from [**xupefei**](https://github.com/xupefei)'s [Bing Wallpaper](https://github.com/xupefei/Bing-Wallpaper) changer.)

Usage
------
\>Wallpaper.exe [options]

Options
------
* \# = Enter the number of the monitor you want to change the Wallpaper on.
  * If omitted changes all monitors to same wallpaper
* image = Supports the following image options (If omitted uses today's Bing Wallpaper.)
  * Fully qualified path (i.e. "C:\My Wallpapers\awesome.jpg")
  * URL (http and https only)
    * Note: URL must end with an extension of a supported wallpaper format (i.e. bmp, gif, jpg, png, tiff)
  * Folder (Will randomly select one image from folder)
* (optional) crop = x,y,w,h (Information to crop the image)
  * x = x coordinate of starting point
  * y = y coordinate of starting point
  * w = width of cropped image
  * h = height of cropped image
* (optional) download_is_temporary allows for deleting image after download. Option is "download_is_temporary" without the quotes.

Download
------
[Latest Version](https://github.com/antgiant/Multi-Monitor-Wallpaper-Changer/releases/latest)

**Only for Windows 8 and above**
