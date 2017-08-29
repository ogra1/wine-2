# wine-2.15

This is an experimental wine snap 

## Building

First create an i386 lxc container:

`snap install lxd`

`lxd init`

`lxc launch ubuntu:16.04/i386 local:snapcraft-i386`

`lxc exec local:snapcraft-i386 -- script /dev/null -c bash`

inside the container install snapcraft and git, clone this branch and run snapcraft ... 

`git clone https://github.com/ogra1/wine-2.15.git`

`cd wine-2.15`

`snapcraft`
