# vSIX Public Keys


## How to use

1. clone
```
cd 
git clone https://github.com/wide-vsix/public_keys
```

2. ln 
```
mkdir /home/vsix/.ssh
ln -s /home/vsix/public_kes/authorized_keys /home/vsix/.ssh/authorized_keys
```

3. set crontab

```
*/10 * * * * /home/vsix/public_keys/pull.sh
```
