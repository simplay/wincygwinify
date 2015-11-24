# wincygwinify

1 . Download [cygwin](http://cygwin.com/install.html) for your windows operating system.
 + E.g. Install the [64bit Windows](http://cygwin.com/setup-x86_64.exe) version.
2 . Install and start cygwin.

3 . Enter into cygwin's shell:

```
lynx -source rawgit.com/transcode-open/apt-cyg/master/apt-cyg > apt-cyg
install apt-cyg /bin
```

4 . Execute `installer.sh` within cygwin's shell via `./installer.sh`

5 . Install rvm via: 

```
curl -L https://get.rvm.io | bash -s stable
source ~/.profile
```

6 . Install latest ruby stable version available on rvm: `rvm install ruby`

7 . Install `jruby 9.0.4.0` (requires jdk >= 1.7): `rvm install jruby-9.0.4.0`
