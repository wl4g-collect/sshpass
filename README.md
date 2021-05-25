# sshpass
SSHpass offers you the ability to automatically offer a password via SSH when
you are prompted for it.

Mirror of http://sourceforge.net/projects/sshpass/

## Installing

```bash
git clone git://github.com/wl4g-collect/sshpass.git
#git clone git://gitee.com/wl4g-collect/sshpass.git
cd sshpass
mkdir build
./configure --prefix=$(pwd)/build
make && make install
```

## FAQ
- Errors of `sshpass/missing: line 81: aclocal-1.15: command not found` &nbsp;,&nbsp;Resolving exec:&nbsp; `autoreconf -ivf`

## Notes

This repository is a mirror of http://sourceforge.net/projects/sshpass/develop

Pull requests will not be accepted
