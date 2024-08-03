# ![logo](https://www.falafelmaker.com/images/tutorial/logo/solofavicon.png) SoloCore

## Build Status

[![nopch-build](https://github.com/azerothcore/azerothcore-wotlk/actions/workflows/core-build-nopch.yml/badge.svg?branch=master)](https://github.com/azerothcore/azerothcore-wotlk/actions/workflows/core-build-nopch.yml)
[![core-modules-build](https://github.com/azerothcore/azerothcore-wotlk/workflows/core-modules-build/badge.svg?branch=master&event=push)](https://github.com/azerothcore/azerothcore-wotlk/actions?query=workflow%3Acore-modules-build+branch%3Amaster+event%3Apush)
[![windows-build](https://github.com/azerothcore/azerothcore-wotlk/workflows/windows-build/badge.svg?branch=master&event=push)](https://github.com/azerothcore/azerothcore-wotlk/actions?query=workflow%3Awindows-build+branch%3Amaster+event%3Apush)
[![macos-build](https://github.com/azerothcore/azerothcore-wotlk/workflows/macos-build/badge.svg?branch=master&event=push)](https://github.com/azerothcore/azerothcore-wotlk/actions?query=workflow%3Amacos-build+branch%3Amaster+event%3Apush)
[![docker-build](https://github.com/azerothcore/azerothcore-wotlk/workflows/docker-build/badge.svg?branch=master&event=push)](https://github.com/azerothcore/azerothcore-wotlk/actions?query=workflow%3Adocker-build+branch%3Amaster+event%3Apush)

## Introduction

SoloCore is an open-source game server application and framework designed for hosting massively multiplayer online role-playing games (MMORPGs). It is based on the popular MMORPG World of Warcraft (WoW) and seeks to recreate the gameplay experience of the original game from patch 3.3.5a.

The original code is based on Azerothcore, MaNGOS and TrinityCore and has since then had extensive development to improve stability, in-game mechanics, and modularity to the game. SC has also grown into a community-driven project with a significant number of contributors and developers. It is written in C++ and provides a solid foundation for creating private servers that mimic the mechanics and behavior of the official WoW servers.

## Philosophy

Our main goal is to create a playable game server, offering a fully working in-game experience.

Here are the main points we focus on:

* Stability
  * We make sure all changes pass the CIs before being merged into the master branch.

* Blizzlike content
  * We strive to make all in-game content to be blizzlike. Therefore we have a high standard for fixes being made.

* Customization
  * It is easy to customize your experience using [modules](#modules).

* Community driven
  * SoloCore has an active community of developers, contributors, and users who collaborate, share knowledge, and provide support through forums, Discord channels, and other communication platforms. 

### Modules

AzerothCore is designed to be highly modular, allowing developers to extend and customize the game to suit their preferences or create unique gameplay experiences. This flexibility enables the addition of custom features, content, and modifications.

We have a lot of modules already made by the community, many of which can be found in the [Module Catalogue](https://www.azerothcore.org/catalogue.html#/).

## Contributing

SoloCore can also serve as a learning resource for aspiring developers who want to understand how WoW servers work, how MMORPGs are structured, how game server emulators are created, or to improve their C++ and SQL knowledge.

Click on the "⭐ Star" button to help us gain more visibility on Github!


