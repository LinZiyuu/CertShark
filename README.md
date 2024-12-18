# CertShark
A Python tool to crawl subdomains from [crt.sh](https://crt.sh/).

## Getting Started
Please, follow the instructions below for installing and run CertShark.

### Pre-requisites
Make sure you have installed the following tools:
```
Python 3.8 or later.
pip3 (sudo apt-get install python3-pip).
```

### Installing
```bash
$ git clone https://github.com/LinZiyuu/CertShark.git
$ cd CertShark
$ pip3 install -r requirements.txt
```

## Usage
Parameters and examples of use.

### Parameters
```
-i --input_sld_file [target_sld_file] (required)
-o --output [output_floder] (required)
```

### Examples
```bash
$ python3 ctfr.py -i sld.txt -o sld
```

### Reference
[ctfr](https://github.com/UnaPibaGeek/ctfr)