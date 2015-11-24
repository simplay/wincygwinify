# wincygwinify

1. Download [cygwin](http://cygwin.com/install.html) for your windows operating system.
2. Install and start cygwin.
3. Enter into cygwin's shell:

```
lynx -source rawgit.com/transcode-open/apt-cyg/master/apt-cyg > apt-cyg
install apt-cyg /bin
```

4. Execute installer.sh within cygwin's shell via `./installer.sh`
5. install rvm: 

```
curl -L https://get.rvm.io | bash -s stable
source ~/.profile
```

6. install latest ruby stable ruby version available on rvm:
`rvm install ruby`

7. Install `jruby 9.0.4.0` (requires jdk >= 1.7): 'rvm install jruby-9.0.4.0'
