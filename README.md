# xps
To run any of these scripts on startup (highly recommend for backlight) add "sh /path/to/script/backlight.sh || exit 1"

1. The script backlight.sh turns off the backlight of the XPS keyboard. Every time the computer restarts the back light will be on at full brightness. You can adjust the level of brightness (0 is off, 3 is max).

2. The script bluetooth.sh blocks the bluetooth device using rfkill. Again recommending running at startup

3. The script wifi.sh resets the wifi connection buy removing and then adding the wifi drivers, In this cause iwlwifi. In my experience with the XPS there are some issues with connect to public wifi locations or connection cutting out. This is extremely convenient and helpful.

4. The script audio.sh kills the pulseaudio (restart automatically) and also resets the Advanced Linux Sound Architecture (ASLA). I have experiences where my headphones would not be detected at all and this script really helps.  

note: to run the script use chmod to give yourself permission for execute I like to use 764. Hope this help guys. 
