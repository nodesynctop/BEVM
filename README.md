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
