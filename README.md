1. To run the kidWifi.py script, your network interface needs to be in monitoring mode to allow the script to create a capture file using airodump-ng -i IF( interface ).

2. Run the script in a full-screen terminal and ensure the correct ESSID.



Usage: python3 kidWifi.py -e ( ESSID ) -i ( interface )

Eg: python3 kidWifi.py -e "John_wifi" -i wlan0mon



The program will work by sending DeAuth frames to the target client device for 20 seconds and then take a nap for 1 minute. It will loop indefinitely and will stop only when you manually terminate the process using 'Control + C' or 'Control + Z'.



Allow your neighbors to enjoy uninterrupted connectivity :3
