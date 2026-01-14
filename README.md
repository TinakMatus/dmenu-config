## dmenu - Dynamic Menu

This is my personal build of dmenu. I use it as a fast lightweight launcher for everything on my system from opening apps to running custom scripts for screenshots or WiFi.

# How it works

I didnt want a heavy "Start Menu" or search bar. Instead I use dmenu because it is just a simple and it stays out of the way until I need it.

* The Code: I patched the C source to keep it as lightweight as possible while adding support for modern features like fuzzy searching.

* The Logic: While it reads my $PATHs to launch standard apps its real power is that I can pipe any custom text or scripts into it.

* The Result: A launcher that uses almost zero resources and allows me to trigger any script or app on my PC.

# My Applied Patches

I added these specific patches to make it more usable:

* [**center**](https://dmenu.suckless.org/patches/center/) - Moves the menu to the middle of the screen instead of a tiny bar at the top.
* [**fuzzymatch**](https://dmenu.suckless.org/patches/fuzzymatch/) - I dont have to type the exact name of an app.
* [**xresources**](https://dmenu.suckless.org/patches/xresources/) - Automatically syncs the menu colors with my wallpaper theme.

"Simple, fast, and stays out of the way."
