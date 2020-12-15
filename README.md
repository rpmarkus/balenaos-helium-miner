# balenaos-helium-miner

helium miner

if you want to try you need to:
1) fork my repo to your own github account : https://github.com/rpmarkus/balenaos-helium-miner
2) inside the readme change the `repoUrl=https://github.com/rpmarkus/balenaos-helium-miner` by `repoUrl=https://github.com/YourUsername/balenaos-helium-gtw`
3) modify the docker-compose file to configure helium-miner service based on your needs:
```bash
    environment:
      - 'REGION_OVERRIDE=EU868'
```
4) click on deploy from your own repo page
5) create the app from CloudBalena, download the image, flash the image and insert the SD card into your device
6) boot the device

[![](https://www.balena.io/deploy.png)](https://dashboard.balena-cloud.com/deploy?repoUrl=https://github.com/rpmarkus/balenaos-helium-miner)
