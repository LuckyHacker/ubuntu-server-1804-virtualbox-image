# Instructions how to get `ova` file

### Linux

Run:
```
./join-files.sh
```

Outputs file: `Ubuntu Server 18.04 template.ova`

### Windows

Methods to run `join-files.bat`:

1. Run `join-files.bat` by double clicking or right-click --> Open
2. Run `.\join-files.bat` in Command Prompt or PowerShell

Outputs file: `Ubuntu Server 18.04 template.ova`

### Output file

* name: `Ubuntu Server 18.04 template.ova`
* sha256: `c0d9bc537244acc3411ce4cdff0d7c1d35acaa49992ac53c0911af7175d01b97`

### Note

If you are going to clone this virtual machine to be used on the same network, new machine id needs to be generated to prevent cloned machine getting same IP as the original machine. Run this command to fix it:

```
sudo rm /etc/machine-id && sudo systemd-machine-id-setup && reboot
```
