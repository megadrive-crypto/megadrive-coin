<h1 align="center">

  <img src="https://avatars.githubusercontent.com/u/124246008?s=100&u=a5bd256981854b0f0dbbbb3e9c23b301b97a7281&v=4"/>
 
 MegaDrive Coin source code

</h1>


<span style="width:100%; text-align:center; margin:0px auto;">
</span>

### A working in progress

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/5611a4ac8b194ede8ede620aa9011394)](https://www.codacy.com/gh/megadrive-crypto/megadrive-coin/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=megadrive-crypto/megadrive-coin&amp;utm_campaign=Badge_Grade)
![Build Status](https://github.com/megadrive-crypto/megadrive-coin/actions/workflows/build.yml/badge.svg)
![Build Status](https://github.com/megadrive-crypto/megadrive-coin/actions/workflows/makefile.yml/badge.svg)


## Build on

![CircleCI](https://img.shields.io/badge/circle%20ci-%23161616.svg?style=for-the-badge&logo=circleci&logoColor=white)
![Octopus Deploy](https://img.shields.io/badge/octopus%20deploy-0D80D8?style=for-the-badge&logo=octopusdeploy&logoColor=white)
![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white)
![Electron.js](https://img.shields.io/badge/Electron-191970?style=for-the-badge&logo=Electron&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101)
![Yarn](https://img.shields.io/badge/yarn-%232C8EBB.svg?style=for-the-badge&logo=yarn&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-%230167ff.svg?style=for-the-badge&logo=digitalOcean&logoColor=white)
![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white)
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-007ACC?style=for-the-badge&logo=Xcode&logoColor=white)

## Made with 
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Solidity](https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white)
![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

---

## MEGADRIVE COIN
#### An Anonymous, Decentralized and Mineable Cryptocurrency for Sega Mega Drive Enthusiasts
### Introduction
The Sega Mega Drive was one of the most popular game consoles of the 1990s. It was a revolutionary system that took gaming to a whole new level. Now Sega Mega Drive enthusiasts have a new way to show their love for the console: Megadrive Coin.

Megadrive Coin is an anonymous, mineable and decentralized cryptocurrency based on the MONERO blockchain (cryptonode) that will have a DeFi token backed by the AVALANCHE network (AVAX). designed to bring together the Sega Mega Drive community, a memecoin/fantoken that will be used to reward users for their contributions to the community, purchase exclusive merchandise, access special events, invest in our DeFi platform, and much more.

Megadrive Coin is designed to reward users for their contributions to the community. The token will be distributed via airdrops, giveaways and other promotional activities. You can mine MegaDriveCoin with your computer and cell phone.

### PRE-SALE - ICO
*MegaDrive Coin Tokenomics and ICO Pricing is not yet available for public purchase. 
## MegaDex EcoSistem
### MegaDex DeFi
is a blockchain-based platform that provides a set of tools and services for users to earn, spend and manage their digital assets. The platform includes a betting system, farming opportunities, games, a metaverse, and non-fungible tokens (NFTs).

### Stake
Allows users to earn rewards by locking their coins in a smart contract. This is a great way to earn passive income and increase the value of your coins.

### Farming / Mint
Allow users to earn rewards by providing liquidity to the platform.

### Games
Several 16bit games based on the console's original games will be available on the platform, allowing users to earn rewards by playing. This is a great way to have fun and increase the value of your coins.

### Play2Mine Roms
You can mine megadrive coins while playing megadrive roms (run on pc, mac, raspberry pi, smartv).

### MegaMetaverse
it is a virtual world where users can explore, create and interact with other people, adding value and knowledge to the MegaDex ecosystem.

### FanArt NFT Market
Non-fungible Tokens (NFTs) Marketplace with FanArts and exclusive collections. They are unique digital assets and cannot be replicated.

### Roadmap - Roadmap

Comming soon... Stay Tuned!

------

## How to build Megadrive coin 

### On *nix

Dependencies: GCC 4.7.3 or later, CMake 2.8.6 or later, and Boost 1.55.

You may download them from:

* http://gcc.gnu.org/
* http://www.cmake.org/
* http://www.boost.org/
* Alternatively, it may be possible to install them using a package manager.

To build, change to a directory where this file is located, and run `make`. The resulting executables can be found in `build/release/src`.

**Advanced options:**

* Parallel build: run `make -j<number of threads>` instead of `make`.
* Debug build: run `make build-debug`.
* Test suite: run `make test-release` to run tests in addition to building. Running `make test-debug` will do the same to the debug version.
* Building with Clang: it may be possible to use Clang instead of GCC, but this may not work everywhere. To build, run `export CC=clang CXX=clang++` before running `make`.

### On Windows
Dependencies: MSVC 2013 or later, CMake 2.8.6 or later, and Boost 1.55. You may download them from:

* http://www.microsoft.com/
* http://www.cmake.org/
* http://www.boost.org/

To build, change to a directory where this file is located, and run theas commands: 
```
mkdir build
cd build
cmake -G "Visual Studio 12 Win64" ..
```

### Actions - Artifact files (work in progress)
- [makefile.yml](https://github.com/megadrive-crypto/megadrive-coin/actions/makefile.yml)
- [build.yml](https://github.com/megadrive-crypto/megadrive-coin/actions/build.yml)



And then do Build.
Good luck!
