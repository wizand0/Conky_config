Conky-elementaryos-info

===== INSTALLATION =====
- Extract/copy `Conky-elementaryos-info` folder to `/home/$USER/.conky/`
- Install all the fonts in the `fonts` folder
- Read the section below and make any necessary changes accordingly based on your system hardware/OS 
- Apply this conky by selecting it in conky manager
or
- just replace default config


- Network adapters (Wired)
--- Search and replace all "enp3s0f1" instances with your ethernet adapter (as shown in ifconfig)

- Network adapters (Wifi)
--- Search and replace all "wlp1s0" instances with your wireless adapter (as shown in ifconfig)

- Battery
--- Search and replace "BATT" instances
(as shown in ls /sys/class/power_supply/ | grep "BAT")


