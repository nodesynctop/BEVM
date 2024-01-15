# BEVM - BTClayer2 
#### Website: https://www.bevm.io/
#### Twitter:https://twitter.com/BTClayer2
#### Discord: https://discord.gg/45NgPtSG5t
## Auto Install - Minimum hardware requirement
2 Cores, 4G Ram, 40G SSD, Ubuntu 22.04
```console
sudo apt install curl -y && source <(curl -s https://nodesync.top/bevm_install)
```
<p align="center">
      <img src="https://raw.githubusercontent.com/lthuan2011/BEVM/main/BTClayer2.JPG">
</p>
## Check logs
```console
sudo journalctl -u bevmd  -f -o cat
```
## Check on Telemetry
```console
https://telemetry.bevm.io/#/0x41cfeafc7177775a0e838b3725a0178b89ebf5dde1b5f766becbf975a24e297b
```

## Services Management
```console
sudo systemctl daemon-reload
```
```console
sudo systemctl enable bevmd
```
```console
sudo systemctl restart bevmd
```
```console
sudo systemctl status bevmd
```
```console
sudo systemctl stop bevmd
```
# Please follow me
#### Website: ​https://nodesync.top/
#### Docs: ​https://docs.nodesync.top/
#### Telegram Group: ​https://t.me/nodesync_top
#### Twitter: https://twitter.com/nodesync_top
