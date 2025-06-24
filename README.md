# seeker-ng
A Python-based GUI tool for passively scanning and displaying nearby Wi-Fi access points using airodump-ng. Built with PyQt5, designed for simplicity, portability, and touch-screen usability. This project is built to provide mobility and ease of use with portable touch screen devices that are operating within a Linux Environment.

---

## Development
Currently paused and it's a work in progress. This project will be updated at the earilest moment. 

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
