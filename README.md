# DLogin – Dmenu Login

DLogin is a simple program to manage login via Dmenu.
The usage is very simple:
* `$ dlogin` – run the program

## Dependencies
1. dmenu
1. elogind

## (Un)Installation
### Universal
#### Installation
##### Latest Git Master (Bleeding Edge)
1. Git clone the repository.
* `$ git clone https://github.com/Amarakon55/dlogin`
2. Change working directory to *dlogin*.
* `$ cd dlogin`
3. Install DLogin using the Makefile
* `# make install`
#### Uninstallation
##### Latest Git Master (Bleeding Edge)
1. Change working directory to *dlogin*.
* `$ cd dlogin`
2. Uninstall DLogin using the Makefile
* `# make uninstall`

### Gentoo
#### Installation
##### Latest Git Master (Bleeding Edge)
1. Add my personal [Gentoo overlay](https://github.com/Amarakon55/amarlay) using [eselect-repository](https://packages.gentoo.org/packages/app-eselect/eselect-repository)
* `# eselect repository add amarlay git https://github.com/Amarakon55/amarlay`
2. Sync my personal [Gentoo overlay](https://github.com/Amarakon55/amarlay) using `emerge`
* `# emerge --sync amarlay`
3. Emerge the DLogin package
* `# emerge x11-misc/dlogin` or `# emerge dlogin`
#### Uninstallation
##### Latest Git Master (Bleeding Edge)
1. Unmerge the DLogin package
* `# emerge -c x11-misc/dlogin` or `# emerge -c dlogin`
2. (Optional) Remove my overlay
* `# eselect-repository remove -f amarlay`
3. (Optional) Sync using `emerge`
* `# emerge --sync`
