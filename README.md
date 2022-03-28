# Bluetooth restart after system sleep wake up
Restart bluetooth service and reload mod btusb

- sudo curl -fsSLo /lib/systemd/system-sleep/bt https://raw.githubusercontent.com/AlessandroPerazzetta/bt-restart/main/bt
- sudo chmod +x /lib/systemd/system-sleep/bt
