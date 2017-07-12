= ComarchCryptoProvider.deb =

DEB packaging of Comarch Crypto Provider from ePUAP

Run:
```
mkdir -p /tmp/ccp-deb
cd /tmp/ccp-deb
git clone https://git.jacekk.net/r/projects/comarchcryptoprovider-deb
cd comarchcryptoprovider-deb
debuild -us -uc
sudo dpkg -i ../comarchcryptoprovider_*_amd64.deb
```
