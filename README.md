![image](https://github.com/HerculesNode/Galadriel-deploy/assets/101635385/6745e666-1807-4348-af32-187eddb3db46)


### Linkler
 * [Hercules Telegram](https://t.me/HerculesNode)
 * [Hercules Twitter](https://twitter.com/Herculesnode)
 * [Galadriel Discord](https://discord.gg/galadriel)
 * [HerculesNode](https://herculesnode.xyz)

### Resmi Döküman : https://docs.galadriel.com/quickstart

### ilk işlem

- Öncelikle Discord sunucusuna katılın ve faucet üzerinden token alın. Faucet tepki vermiyor ama gönderiyor devam edin. Bakmak isterseniz  https://explorer.galadriel.com/
- !faucet cüzdan adresiniz

![image](https://github.com/HerculesNode/Galadriel-deploy/assets/101635385/f21999c0-f7b1-4f71-8b02-a6b5b3a78f0a)


### Npm ve Nodejs kuralım

```shell
sudo apt update
```

```shell
sudo apt upgrade
```

```shell
sudo apt install nodejs
```

- Sorun yaşarsanız buradan bakın kuruluma
https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-20-04

```shell
sudo apt install npm
```

### Repo Çekelim.

```shell
git clone https://github.com/galadriel-ai/contracts
```

```shell
cd contracts/contracts
```

- `.env` dosyamızı oluşturalım

```shell
cp template.env .env
```

### Env dosyası düzenleyelim.

```shell
nano .env
```
- 3 yer değişecek . Oracle adress sabit aşağıdaki gibi olacak Private key Galadriel ve Localhost cüzdanınızın Private keyi 0x sonrasına ekleyin ctrl +x + y ile kaydedin

- ORACLE_ADDRESS="0x4168668812C94a3167FCd41D12014c5498D74d7e"
- PRIVATE_KEY_GALADRIEL="0xCÜZDAN-PRİVATE-KEYİ"
- PRIVATE_KEY_LOCALHOST="0xCÜZDAN-PRİVATE-KEYİ"

  ![image](https://github.com/HerculesNode/Galadriel-deploy/assets/101635385/5ea16bf1-fdd0-4795-abac-b0f0f7109a3d)


### npm bileşenlerini kuralım

```shell
npm install
```

### Çalıştıralım

```shell
npm run callQuickstart
```

- Bu şekilde çıktı almalısınız 

![image](https://github.com/HerculesNode/Galadriel-deploy/assets/101635385/d1bccc2f-c871-436c-8391-98a643f754ee)


- Node.js versiyon yükseltmek için
- https://nodejs.org/en/download/package-manager


- Daha sonra Explorer üzerinden bakın :
https://explorer.galadriel.com/


