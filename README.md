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

8 . Close the cygwin shell and restart it.

9 . Exectue `gem update --system`
+ Keep in mind doing so for every installed rubyversion.

10 . Go to rvm's global gemset and install the bundler gem: 
+ 1. `rvm gemset use global`
+ 2. `gem install bundler`
