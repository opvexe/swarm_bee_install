# Swarm Bee

## system info 

```
CentOS Linux release 7.6.1810 (Core)
```

## How to get Swarm Endpoint 
- 官方地址 (https://www.ethswarm.org/)
- 获取Swap Endpoint (https://infura.io/)
- 获取测试币 (https://discord.com/channels/799027393297514537/841664915218628619)
- 钱包小狐狸 (https://metamask.io/download.html)
- 代币token地址 (https://goerli.etherscan.io/address/0x07Bb27F8f4c724A3D203b3caf3b8c646812c418F#tokentxns)

## install bee-clef

```
wget https://github.com/ethersphere/bee-clef/releases/download/v0.4.12/bee-clef_0.4.12_amd64.rpm
sudo rpm -i bee-clef_0.4.12_amd64.rpm
systemctl status bee-clef
```

## install bee

```
wget https://github.com/ethersphere/bee/releases/download/v0.6.2/bee_0.6.2_amd64.rpm
sudo rpm -i bee_0.6.2_amd64.rpm
```

## Start bee 

```shell script
$ touch ~/.bee.yaml
$ sudo bee start 
```

## Config

```shell script
data-dir: /data
swap-endpoint: https://mainnet.infura.io/v3/33cd8b49cf54486281a7a38eff29fe71
verbosity: trace
clef-signer-enable: true
clef-signer-endpoint: /var/lib/bee-clef/clef.ipc
# nat-addr: 公网ip地址:1634
```

## 导出私钥

```
/var/lib/bee-clef/keystore
/var/lib/bee-clef/password
执行到处命令:
bee-clef-keys
生成: bee-clef-key-1623422820.json  bee-clef-password-1623422820.txt 
```


## 钱包

```
1.创建钱包：chrome-extension://nkbihfbeogaeaoehlefnkodbefgpgknn/home.html#
2.记住钱包生成的随即顺序字符文件: vDugceGgL.txt

```

## discord客户端

```
https://discord.com/channels/482467812179181568/483798869717680129
sudo dpkg -i discord-0.0.15.deb
```
