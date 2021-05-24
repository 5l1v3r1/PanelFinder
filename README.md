# PanelFinder
Website's Admin Panel Finder.
PanelFinder is a PHP brute-force tool to find the admin panel of a target website. To be used in Linux recommended.
<br><br>**Note: I am not responsile for anything, if the tool isn't working properly that maybe because the target isn't responding. I am also not responsible for any misuse of this tool.**

##  Installation

Clone.
```sh
$ git clone https://github.com/5HR3D/PanelFinder
```

Open directory.
```sh
$ cd PanelFinder
```
## Usage
default:
```sh
php PanelFinder --url=<target>
```
To keep searching even after target page is found:
```sh
php PanelFinder --url=<target> --c
```
For a bigger bruteforce wordlist:
```sh
php PanelFinder --url=<target> --dS
```
**recommended**
```sh
php PanelFinder --url=<target> --c --dS
```

## Prerequisites

- PHP
- cURL

### Contact
visit https://linktr.ee/5HR3D
