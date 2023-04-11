# SigmaToSecuronix
A simple tool for converting Sigma detection rules to Securonix Snypr Spotter queries.

## Prerequisites

* [Python](https://www.python.org/downloads/) version 3.x or later

## Installation

```bash
pip install securonix-cli
```

## Usage

```
git clone https://github.com/Securonix/SigmaToSecuronix
cd SigmaToSecuronix
poetry install && poetry shell
securonix-cli convert --mapping config/mapping.yml input_file.yml
```

## Options

* `--help` : Show help message and exit
* `--mapping`, `-m`: Sigma mapping file (required)


## Output

<img src="../main/docs/images/1.png?raw=true"  height="120">
<img src="../main/docs/images/2.png?raw=true"  height="120">
<img src="../main/docs/images/3.png?raw=true"  height="120">



## Supported Functionality

* Microsoft Windows
* Endpoint Management Systems
* Web Server
* Web Proxy
* Microsoft Windows Powershell
* Next Generation Firewall

## Contributions

This project welcomes contributions from the community. If you would like to contribute, please fork the repository and make your changes. Then, submit a pull request for review.

