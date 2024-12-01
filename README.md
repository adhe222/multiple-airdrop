MULTIPLE NETWORK AIRDROP


Automate multiple network airdrop installation
## MULTIPLE NETWORK NODE SETUP

An automated installation script for Multiple Node Client with user-friendly interface and step-by-step configuration.

## Requirements

- Ubuntu/Debian-based system
- Root access or sudo privileges
- Minimum 2GB RAM
- Minimum 200GB storage space
- Stable internet connection

## Quick Installation

You can quickly install Multiple Node using either `wget` or `curl`:

Using wget:

```bash
wget https://raw.githubusercontent.com/adhe222/multiple-network/refs/heads/main/setup.sh && chmod +x setup.sh && sudo ./setup.sh
```

Using curl:

```bash
curl -fsSL https://raw.githubusercontent.com/adhe222/multiple-network/refs/heads/main/setup.sh -o setup.sh && chmod +x setup.sh && sudo ./setup.sh
```

## Features

- 🚀 Automated installation process
- 📋 Step-by-step configuration
- ✅ Input validation
- 🔍 Error handling
- 📊 Progress tracking
- 🎨 Colorful and intuitive interface

## Prerequisites

The script will automatically install the following packages:

- curl
- tar
- wget
- aria2
- clang
- pkg-config
- libssl-dev
- jq
- build-essential

## Installation Steps

1. First, register for Multiple at [Multiple Registration](https://www.app.multiple.cc/#/signup?inviteCode=Pph17lgI)
2. After registration, get your identification code from [Setup Page](https://www.app.multiple.cc/#/setup)
3. Run the installation script
4. Follow the interactive prompts to configure your node:
- Enter your identification code
- Set a PIN (minimum 6 digits)
- Configure bandwidth settings
- Set storage allocation

## Post-Installation

After successful installation, you can use these commands:

1. Check node status:
   ```bash
   multiple-cli status
   ```

2. View all available commands:
   ```bash
   multiple-cli --help
   ```

## Logs

The node service logs are stored in `output.log` in the same directory as the script.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

This is an unofficial installation script. Please make sure you understand the terms and conditions of running a Multiple Node before proceeding with the installation.

## Important Note

Make sure to keep your identification code and PIN secure. Never share these credentials with anyone.

---
