# wine-2

This is an experimental snap of the wine-2 tree (trying to follow the latest 2.x release)

## Building

First create an i386 lxc container:

`snap install lxd`

`lxd init`

`lxc launch ubuntu:16.04/i386 local:snapcraft-i386`

`lxc exec local:snapcraft-i386 -- script /dev/null -c bash`

inside the container install snapcraft and git, clone this branch and run snapcraft ... 

`git clone https://github.com/ogra1/wine-2.git`

`cd wine-2`

`snapcraft`
