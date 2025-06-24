# seeker-ng
A Python-based GUI tool for passively scanning and displaying nearby Wi-Fi access points using airodump-ng. Built with PyQt5, designed for simplicity, portability, and touch-screen usability. The device I used was a touch screen HyperPixel display which was attached to a raspberry pi to make a portable device for scanning devices on the move.

# Seeker-ng

🛰️ **Seeker-ng** is a lightweight, PyQt5-based GUI tool for scanning nearby Wi-Fi access points using `airodump-ng`. Built with a focus on simplicity and touchscreen compatibility, it's ideal for Raspberry Pi-based cyber tools or field-ready interfaces.

---

## Features

- Enables monitor mode on selected Wi-Fi interfaces
- Displays nearby access points (SSID, BSSID, Channel, Signal Strength, Encryption)
- Clean dark-mode GUI with column sorting
- Parses real-time CSV output from `airodump-ng`
- Docker-compatible and easy to run on lightweight Linux systems

---

## Screenshots

I will add screenshots shortly.

---

## Requirements

- Python 3.7+
- PyQt5
- airodump-ng
- Linux based
- Antenna which supports monitoring mode 

---

## Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/seeker-ng.git
cd seeker-ng

# Create a virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
