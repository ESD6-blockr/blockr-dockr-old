<div align="center">

# blockr-dockr-old

<img src="https://media.giphy.com/media/nXxOjZrbnbRxS/giphy.gif">
<br>
<i>After some painfull hours we did it blockrs!</i>

<div align="left">
  
## What is this repository
  
This repository is a reconfiguration of the old blockchain with added `docker`🐳 support. 
Each module within the blockchain has its own `dockerfile` which will be build with `docker-compose` when creating the full stack.
The stack exists of the following applications:
- main validator (using leveldb)
- backup validator (using mongodb)
- p2p API 
- mongodb

## How to run this piece of beautiful software on your machine

⚠️ __first make sure your local machine has `docker`🐳 installed__ ⚠️
1. clone this repository
2. start the stack by running `docker-compose up --build` in the `/`

## Installing docker 🐳

| step | `Windows`     | `Linux`       |`MacOs`        |
|:---- |:------------- |:------------- |:------------- |
| 1. | [download](https://download.docker.com/win/stable/Docker%20for%20Windows%20Installer.exe) | [go here](https://docs.docker.com/install/linux/docker-ce/ubuntu) | [download](https://download.docker.com/mac/stable/Docker.dmg) |
| 2. | install | let us be lazy and follow the guide 😴 | install |
| 3. | you're done | NullPointerException | you're done |

</div>
<br><br>

## Special thanks:
<a href="https://github.com/roelvdboom"><img src="https://avatars2.githubusercontent.com/u/25582889?s=128"></a>
<a href="https://github.com/timof97"><img src="https://avatars1.githubusercontent.com/u/31408460?s=128"></a>
<a href="https://github.com/quintaartsen"><img src="https://avatars2.githubusercontent.com/u/25610414?s=128"></a>
<a href="https://github.com/saltz"><img src="https://avatars3.githubusercontent.com/u/7994007?s=128"></a>

</div>
