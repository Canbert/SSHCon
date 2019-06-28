# SSHCon

Shellscript with a config file to add hosts, with or without users to allow quick remoting via SSH.

## Installing
To install SSHCon, run the install script as root.
```
sudo ./install
```
## Uninstalling

To uninstall SSHCon, run the uninstall script as root.
```
sudo ./uninstall
```

## Setting a Host
In order to set a host go to the hosts file located at:
```
~/.config/sshcon/hosts
```
Then add your host using the formatting shown below.

### Host without user
```
test=127.0.0.1
```
### Host with user
```
test=user@127.0.0.1
```

