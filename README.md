# scanssh
simple shell script to detect local IPs (using nmap) and connect via ssh

## Download
`wget https://raw.githubusercontent.com/abi19911/scanssh/main/scanssh` <br />
you can use it as is, or copy it to your $PATH <br />
<br />
One liners: <br />
```
Linux:
wget https://raw.githubusercontent.com/abi19911/scanssh/main/scanssh && chmod +x scanssh && sudo mv scanssh /usr/local/bin

Termux:
wget https://raw.githubusercontent.com/abi19911/scanssh/main/scanssh && chmod +x scanssh && mv scanssh /data/data/com.termux/files/usr/bin
```

## Description
```
Running scanssh without any arguments; it will look for cached local IPs in tmp file and
run the script using that data. If tmp file doesn't exist, the script will scan for local IPs and create one.

Usage: scanssh <no arguments> 
         \____ [-r] refresh IP list
          \___ [-d] delete IP list
           \__ [-h] help menu
```
