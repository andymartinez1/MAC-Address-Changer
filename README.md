# MAC Address Changer

This is a simple MAC address changer program for Linux.

## Prerequisites

- Python 3.x
- `subprocess` module (usually included with Python)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/MAC-Address-Changer.git
   ```
2. Navigate to the project directory:
   ```bash
   cd MAC-Address-Changer
   ```

## Usage

1. Run the script with root privileges:
   ```bash
   sudo python3 MACAddressChanger.py -i [interface] -m [new_mac_address]
   ```
   - Replace `[interface]` with the network interface you want to change the MAC address for (e.g., `eth0`, `wlan0`).
   - Replace `[new_mac_address]` with the new MAC address you want to assign.
     > **!! Important:** The first octet in the MAC addresses must be even

## Example

```bash
sudo python3 MACAddressChanger.py -i eth0 -m 00:11:22:33:44:55
```

## Disclaimer

This tool is for educational purposes only. Use it responsibly and only on networks you own or have permission to test.
