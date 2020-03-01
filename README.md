

* Build
````
brew install nasm pkg-config
brew install nasm wxmac
brew cask install osxfuse
````

````
git clone https://github.com/zouguangxian/TrueCrypt
cd TrueCrypt
mkdir Pkcs11
cd Pkcs11
wget https://raw.githubusercontent.com/Pkcs11Interop/PKCS11-SPECS/master/v2.20/headers/pkcs11.h
wget https://raw.githubusercontent.com/Pkcs11Interop/PKCS11-SPECS/master/v2.20/headers/pkcs11f.h
wget https://raw.githubusercontent.com/Pkcs11Interop/PKCS11-SPECS/master/v2.20/headers/pkcs11t.h

make clean && make -j 4
````

* Thanks
http://www.nerdenmeister.org/2013/08/16/build-truecrypt-on-os-x-64-bit-with-hardware-acceleration/



