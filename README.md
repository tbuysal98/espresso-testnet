# espresso-testnet

sudo snap install docker
```

# Docker compose dosyamızı indiriyoruz (tek tek giriyoruz):
```
curl https://www.espressosys.com/cape/docker-compose.yaml --output docker-compose.yaml
docker-compose pull
apt-get install screen
screen -S Espresso
docker-compose up
```
# Ardından kişisel bilgisayarımızda komut istemine sağ tıklayarak yönetici olarak başlatıyoruz ve aşşağıdaki 2 komutu giriyoruz (tek tek giriyoruz)

Sunucu IP yazan yere sunucumuzun IP adresini girerlim.
```
netsh interface portproxy add v4tov4 listenaddress=127.0.0.1 listenport=80 connectaddress=sunucuip connectport=80
netsh interface portproxy add v4tov4 listenaddress=127.0.0.1 listenport=80 connectaddress=sunucuip connectport=80
```
![image](https://user-images.githubusercontent.com/101149671/174170473-11fc7972-e24c-4c59-ba61-166ab3588cdc.png)


#  Ardından kişisel bilgisayarımızda tarayıcımıza girerek localhost diyoruz. Set up a new CAPE Wallet kısmına giriyoruz: 

![image](https://user-images.githubusercontent.com/101149671/174170393-4f4b85bd-066b-4719-a8c4-3cb08e143fce.png)

#  Reveal keys diyerek yeni bir cüzdan oluşturuyoruz. Oluşan cüzdan bilgilerini saklayalım.

![image](https://user-images.githubusercontent.com/101149671/174170527-5b23a248-3f79-48b3-a14e-456d21f2b71b.png)

# Create keystore kısmına tıklıyoruz: 

![image](https://user-images.githubusercontent.com/101149671/174170549-8ebb198d-23d0-44fa-877f-0430ed65e2b4.png)

# Ardından Accounts kısmına gelerek Generate new address diyerek cüzdan adresi oluşturuyoruz:

![image](https://user-images.githubusercontent.com/101149671/174170575-dab78df3-9685-4d98-b5c1-b933342823f8.png)

# Ardından altta ki twitte aşşağıdaki gibi cüzdan adresimizi yolluyoruz.

Twit linki: https://twitter.com/EspressoSys/status/1537447721916698625?s=20&t=YvCHet3bK0KM5goCr-9YGg
