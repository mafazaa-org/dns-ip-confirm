# Mafazaa dns ip confirm

A repo containing the logic to confirm ip for opendns by getting the opendns email, extracting the confirmation url from it, then automaticly confirm using a web scraper

## Usage

after cloning the repo run the install command to install chromium-browser, nodejs, npm and python3 on your server

```shell
./install.sh
```

then simply run the script

```shell
./run.sh
```

finally: if you want to clean the installed resources, run the following command for removing nodejs, npm and the chromium-browser. but it will leave python since the dns server use it

```shell
./clean.sh
```
