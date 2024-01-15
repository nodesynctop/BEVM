# BEVM - BTClayer2 
#### Website: https://www.bevm.io/
#### Twitter:https://twitter.com/BTClayer2
#### Discord: https://discord.gg/45NgPtSG5t
## Auto Install
```console
sudo apt install curl -y && source <(curl -s https://nodesync.top/bevm_install)
```

## Check logs
```console
sudo journalctl -u bevmd  -f -o cat
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
