# ra1nsn0w
A little release of ra1nsn0w doed by me :)

install dependencies like futurerestore

to install autoconf automake libtool use brew

to build libipatcher run : git clone https://github.com/tihmstar/libipatcher.git 

cd libipatcher 

git submodule add https://github.com/tihmstar/jssy.git 

add xpwn/includes file in libipatcher/include and add libcommon.a and libxpwn.a to usr/local/lib 

git submodule update --init --recursive 

run ./autogen.sh 

make

make install

if wikiproxy can't be reaced you can try to save the bundle of you IPSW using inferius

and add them to localhost using docker
