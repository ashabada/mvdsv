MVDSV: a QuakeWorld server
===
Just a fork for private use

to compile mvdsv as 32bit on 64bit target platform use next:  
for gcc its like: make mvdsv FORCE32BITFLAGS=-m32  
configure script add FORCE32BITFLAGS=-m32  


```
apt-get install libc6:i386 libncurses5:i386 libstdc++6:i386 libc6-dev:i386 gcc:i386
git clone https://github.com/ashabada/mvdsv
cd mvdsv/build/make
./configure && make
```
