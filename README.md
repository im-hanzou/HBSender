
# HBSender
[![License](https://img.shields.io/badge/license-MIT-red.svg)](https://github.com/KeepWannabe/HBSender/blob/main/LICENSE.md)   [![Version](https://img.shields.io/badge/Release-1.0-red.svg?maxAge=259200)]()  [![Build](https://img.shields.io/badge/Supported_OS-Linux-yellow.svg)]()  [![Build](https://img.shields.io/badge/Supported_WSL-Windows-blue.svg)]() [![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/KeepWannabe/HBSender/issues) [
### Plivo and Nexmo Bulk Sending SMS Tools
<img width="935" alt="hbsender" src="https://raw.githubusercontent.com/KeepWannabe/HBSender/main/top-header.jpg">


### But it's shit! And your implementation sucks!
- Yes, you're probably correct. Feel free to "Not use it" and there is a pull button to "Make it better". 

## Installation
*Sudomy* is currently extended with the following tools. Instructions on how to install & use the application are linked below.

### To Download HBSender From Github
```bash
# Clone this repository
git clone --recursive https://github.com/KeepWannabe/HBSender.git
```

## Dependencies
*Sudomy* requires [jq](https://stedolan.github.io/jq/download/) to run and parse. Information on how to download and install jq can be accessed [here](https://stedolan.github.io/jq/download/)

```bash
# Linux
apt-get update
apt-get install jq curl
sed -i 's/\r$//' HBSender module/nexmo.send module/plivo.send

```


## Usage
```text
➜  HypeBrotherSender ➜ bash HBSender
      __  ______ _____                __
     / / / / __ ) ___/___  ____  ____/ /__  _____
    / /_/ / __  \__ \/ _ \/ __ \/ __  / _ \/ ___/
   / __  / /_/ /__/ /  __/ / / / /_/ /  __/ /    
  /_/ /_/_____/____/\___/_/ /_/\__,_/\___/_/     

  [HYPEBROTHER SENDER 2K21 - LICENSE : FREE]

  ▸ [1] NEXMO SENDER
  ▸ [2] PLIVO SENDER
  ▸ [3] TWILLIO SENDER (SOON)

  ▸ OPTIONS : 
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
