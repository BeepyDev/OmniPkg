# OmniPkg
### ⚠️ Alpha stage

Search multiple Linux package managers for a package, for the times when you don't know where to find it.

> Currently only officially supported on Debian-based machines, such as Ubuntu.  
> Experimental DNF support for other distros, if you try it please report bugs in Issues.

## Setup
```
sudo mv /PATH/TO/THE/SCRIPT/main.py /usr/local/bin/omnipkg
chmod +x /usr/local/bin/omnipkg
```

## Usage
After setup, run:
```
omnipkg
```
then type in the package name.

## More info
- It searches APT, Snap, and (experimentally) DNF.

## Roadmap
- Soon: add fancy colored text
- Soon: finish DNF support
- Soonish: add AppImageHub support
- Later: add Flatpak support
- Later: test on more distros
