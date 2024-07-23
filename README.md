# IP-Info

## Overview

IP-Info is a versatile Python-based tool designed to provide comprehensive information about IP addresses. Whether you need to retrieve details about your own IP address or look up information about any other IP address or website, IP-Info delivers detailed insights. This tool is suitable for various Linux-based environments, including Termux on Android devices.

## Installation

To get started with IP-Info, follow these detailed installation steps:

### 1. Update and Upgrade Your System

Before installing new software, it’s good practice to update your system packages. Open your terminal and run:

```bash
apt update -y
apt upgrade -y
```

### 2. Install Python 3

IP-Info requires Python 3 to run. Install it using:

```bash
apt-get install python3 -y
```

### 3. Install Git

Git is needed to clone the IP-Info repository. Install it with:

```bash
apt install git -y
```

### 4. Clone the IP-Info Repository

Download the IP-Info source code from GitHub:

```bash
git clone https://github.com/ySixxNz/IP-Info
```

### 5. Navigate to the IP-Info Directory

Change your directory to the IP-Info folder:

```bash
cd IP-Info
```

### 6. Run the IP-Info Script

Execute the script to start using IP-Info:

```bash
python3 ipinfo.py
```

## One-Line Installation

For convenience, you can execute the following single command to perform all installation steps at once:

```bash
apt update -y && apt upgrade -y && apt-get install python3 -y && apt install git -y && git clone https://github.com/ySixxNz/IP-Info && cd IP-Info && python3 ipinfo.py
```

## Features

- **Retrieve Your IP Address Information**: Quickly obtain detailed information about your own IP address, including location, ISP, and more.
- **Lookup Any IP Address**: Enter any IP address or domain name to retrieve its associated details.
- **Open IP Location in Browser**: Get the geographical location of an IP address and view it directly on Google Maps or your browser.
- **Integration with Webhooks**: Automatically send IP address information to a specified Discord webhook for real-time updates.

## Tested On

- **Termux**: Successfully tested on Termux running on Android devices.
- **Ubuntu**: Compatible with Ubuntu-based systems.
- **Parrot OS**: Works on Parrot Security OS.

## Tip for Termux Users

In Termux, you can directly open IP address locations in your browser or Google Maps app. This provides a seamless experience for viewing IP information.

## Disclaimer

IP-Info is intended for educational and informational purposes only. Unauthorized access or use of IP information for malicious purposes is illegal and unethical. Always ensure you have proper authorization before accessing or using IP information.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Credits

- **Author**: ySixx
