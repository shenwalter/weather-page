# weather-page
Static website with Weatherwidget.io widget

Using [2.4inch RPi Display](https://www.lcdwiki.com/2.4inch_RPi_Display).
1. Use Configured images (see https://www.lcdwiki.com/2.4inch_RPi_Display, Download Resources section)
2. .sh script to: A) open Midori browser B) open [weather page](https://shenwalter.github.io/weather-page/) C) Fullscreen and Zoom In
3. sudo chmod +x run_kiosk.sh
4. add to /etc/xdg/lxsession/LXDE-pi/autostart to autorun .sh script when retstart

See https://maker-tutorials.com/en/auto-start-midori-browser-in-fullscreen-kiosk-modus-raspberry-pi-linux/
and https://www.reddit.com/r/raspberry_pi/comments/xtxost/how_to_start_a_full_screen_midori_browser_tab/mi4sw2s/

weather html page is partially ChatGPT-tweaked (formatting and div-bar alignment...); widget is from Weatherwidget.io.
