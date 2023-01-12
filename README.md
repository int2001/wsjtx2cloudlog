# wsjtx2cloudlog
Bridge for WSJT-X UDP Log-Messages to Cloudlog.
Adds a UDP-Listener to Cloudlog, so that one can automaticly log WSJT-X QSOs into Cloudlog

## Prerequisites:
* Cloudlog
* WSJT-X
* Linux/Mac with python3

## Howto:
* Go to your Linuxmachine, or to your Shell
* `git clone https://github.com/int2001/wsjtx2cloudlog`
* `cd wsjtx2cloudlog`
* edit config_uni
 ** adjust the URL to your cloudlog-instance
 ** Enter the Key from your cloudlog-Account (retrieve via top-right Menu -> API-Keys)
* start script with: `python3 ./server_uni.py *` then `disown`
* Go to WSJT-X // Preferences // Reporting and Enable `secondary UDP-Server`
* Enter IP of the Machine where the Script is runnung and Port 2333 
* Enjoy
