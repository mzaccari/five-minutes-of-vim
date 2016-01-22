## Install vim

Use your system's package manager where possible.

You should have a version that is at least 7.3.  Once installed, you can
verify the version with:

```
vim --version
```

## Ubuntu

GUI:

```
sudo apt-get install -y vim-gnome
```

CLI-only (no X-Windows):

```
sudo apt-get install -y vim-nox
```

## MacOS

```
brew install vim
```

## Red Hat

Note: RHEL and CentOS 6 only have vim 7.2 in their repos.  You may want
to install from source or find a more recent rpm from another repo.

```
sudo yum install -y vim-enhanced
```

## Windows

I recommend the [Windows installers] released by the Cream project,
but without Cream itself.

Follow the links under the heading *Vim installers without Cream*.

[Windows installers]: http://cream.sourceforge.net/download.html
