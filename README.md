# GPWA-V1.0.0 (A Wifi Jammer)

### GPWA Command For Kali Linux

### 🔧 Command For Monitor Mode:
- sudo ip link set wlan0 down
- sudo iw dev wlan0 set type monitor
- sudo ip link set wlan0 up

## shortcut Command:
- sudo airmon-ng start wlan0

## Nearby Wifi Nerwork Scan Command
- sudo airodump-ng wlan0mon
