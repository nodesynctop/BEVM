# BEVM - BTClayer2 

## Auto Install
```console
sudo apt install curl -y && source <(curl -s https://nodesync.top/bevm_install)
```
## Check logs
```console
sudo journalctl -u bevmd  -f -o cat
```
## Services Management
```sudo systemctl daemon-reload```
```sudo systemctl enable bevmd```
```sudo systemctl restart bevmd```
```sudo systemctl status bevmd```
```sudo systemctl stop bevmd```
