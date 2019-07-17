# gnome-random-wallpaper
random wallpaper switcher for gnome-driven OS, such as Ubuntu18.04LTS

*gnome-random-wallpaper is an absolutely free script and comes with* **absolutely no warranty**.

# Environment
This script is developed, tested, being used, and hopefully works at least in:
- OS: Ubuntu 18.04.2 LTS
- bash: 4.4.19(1)-release (x86_64-pc-linux-gnu)

# Usage
- put 'manage-wallpaper' and 'change-wallpaper' in the same directory.
- put wallpaper images ('.jpe?g' files) at '$HOME/Pictures/wallpapers',
  or modify change-wallpaper:L16.
- run and pray.
  ```
  % manage-wallpaper &
  ```

## Optional Usage

- modify manage-wallpaper:L2 to change the interval; default is set 3 minutes.
- run 'change-wallpaper' directly to switch the wallpaper just once.

# Author
https://github.com/AriyaISIHARA
