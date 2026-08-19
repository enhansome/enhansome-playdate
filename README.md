<!--lint disable awesome-github-->

<!--lint disable double-link-->

<!--lint disable awesome-list-item-->

<!--lint disable awesome-toc-->

<!-- todo: address these 👆 and reenable lint rules -->

# Awesome Playdate with stars

A list of awesome resources for game development on Panic's Playdate console.

> ⚠️   Links may include spoilers

## Contents

* [Game Development](#game-development)
  * [Programming Frameworks & Languages](#programming-frameworks--languages)
  * [Development Concepts](#development-concepts)
  * [Graphics](#graphics)
  * [Fonts](#fonts)
* [Open Source Playdate Games & Example Code](#open-source-playdate-games--example-code)
* [Playdate Games & Dev Blogs](#playdate-games--dev-blogs)
* [Social](#social)
  * [Discussion groups](#discussion-groups)
  * [Accounts to follow](#accounts-to-follow)

## Game Development

### Programming Frameworks & Languages

#### Pulp + Pulpscript

A "no-code alternative to the full SDK", Pulp provides a "click-and-place" game editor right in your browser.

* [Pulp](https://play.date/pulp/)
* [The Official Pulp Forum](https://devforum.play.date/c/pulp/46)

##### Articles on Pulp + Pulpscript

* [Panic unveils Pulp - Gamasutra](https://www.gamasutra.com/view/news/382905/Panic_unveils_Pulp_a_free_nocode_tool_for_creating_Playdate_games.php)
* [Playdate Pulp - playdate.wiki](https://playdate.wiki/development/playdate-plup)
* [Playdate Pulp - Gamedeveloper.com](https://www.gamedeveloper.com/console/playdate-pulp-zero-to-video-game-in-60-seconds)

#### Lua

* [Learn X in Y minutes, Where X=Lua](https://learnxinyminutes.com/docs/lua/) - A succinct Lua cheatsheet for developers with experience in other languages like Python.

##### Playdate SDK

Panic publishes two versions of their SDK: a high-level API for Lua, similar to LÖVE, and a lower-level C library for applications with higher performance needs.

###### Official

* [Playdate SDK Lua Documentation](https://sdk.play.date/inside-playdate)
* [Playdate SDK C Documentation](https://sdk.play.date/inside-playdate-with-c)
* [Develop for Playdate](https://play.date/dev/)

###### Unofficial

* [Playdate API and build tools in Rust](https://github.com/boozook/playdate) ⭐ 195 | 🐛 112 | 🌐 Rust | 📅 2026-08-17
* [Playdate SDK Docker Image](https://github.com/hjhart/playdate-docker) ⭐ 11 | 🐛 0 | 🌐 Lua | 📅 2022-09-08
* [Install Playdate SDK with Package Managers](https://gist.github.com/idleberg/e246f7a582ac173d156c60ec23ce2af0)

###### Playdate SDK Previews

* [Playdate Programming LIVE](https://www.youtube.com/watch?v=MZRtfiD_308\&t=2629s) - 50 minute long programming demo that shows some of the SDK and simulator.
* [Playdate Unboxing + Project Setup](https://www.youtube.com/watch?v=LiCJF4TfWno)
* [Early Playdate SDK release notes](https://twitter.com/playdate/status/1143268123098796033)
* [Code sample in /r/PlaydateConsole](https://www.reddit.com/r/PlaydateConsole/comments/nw6is4/i_started_to_prototype_a_small_game_while_waiting/h18ilkg/)

##### Lua Libraries

The following libraries are expected to work well-enough on the Playdate:

* [rxi/json.lua](https://github.com/rxi/json.lua) ⭐ 2,183 | 🐛 28 | 🌐 Lua | 📅 2023-11-28 - A lightweight JSON library for Lua.
* [middleclass](https://github.com/kikito/middleclass) ⭐ 1,918 | 🐛 1 | 🌐 Lua | 📅 2025-11-03 - A simple OOP library for Lua that introduces inheritance, operator overloads, static variables, and mixin support.
* [rxi/lume](https://github.com/rxi/lume) ⭐ 1,238 | 🐛 22 | 🌐 Lua | 📅 2023-11-19 - A collection of functions for Lua, geared towards game development.
* [bump.lua](https://github.com/kikito/bump.lua) ⭐ 1,098 | 🐛 13 | 🌐 Lua | 📅 2023-09-29 - A 2D colission detection library.
* [rxi/classic](https://github.com/rxi/classic) ⭐ 1,073 | 🐛 19 | 🌐 Lua | 📅 2021-12-31 - A tiny class module for Lua. Attempts to stay simple and provide decent performance by avoiding unnecessary over-abstraction.
* [tiny-ecs](https://github.com/bakpakin/tiny-ecs) ⭐ 785 | 🐛 0 | 🌐 Lua | 📅 2023-03-15 - An entity component system in pure Lua.
* [Jumper](https://github.com/Yonaba/Jumper) ⭐ 650 | 🐛 39 | 🌐 Lua | 📅 2022-10-21 - A pure Lua pathfinding library for grid-based games.
* [Knife](https://github.com/airstruck/knife) ⭐ 519 | 🐛 2 | 🌐 Lua | 📅 2018-09-17 - A collection of useful micro-modules for Lua.
* [Noble Engine](https://github.com/NobleRobot/NobleEngine) ⭐ 508 | 🐛 21 | 🌐 Lua | 📅 2024-07-07 - Noble Engine is a Lua-based game engine library built on top of the Playdate SDK that offers a variety of helpful features.
  * [Documentation](https://noblerobot.github.io/NobleEngine/)
  * [Presentation from the creator](https://www.youtube.com/watch?v=fL46v-QmnNk)
* [rxi/tick](https://github.com/rxi/tick) ⭐ 206 | 🐛 0 | 🌐 Lua | 📅 2015-03-11 - A small Lua module that simplifies the calling of functions at a set interval or after a delay.
* [philanc/plc](https://github.com/philanc/plc) ⭐ 195 | 🐛 0 | 🌐 Lua | 📅 2025-07-20 - Pure Lua Crypto. Crpytographic functions and utilities implemented in pure Lua.
* [AnimatedSprite](https://github.com/Whitebrim/AnimatedSprite) ⭐ 168 | 🐛 1 | 🌐 Lua | 📅 2026-02-05 - A lua-based library for animating sprites. Containing finite state machine, json configuration and plugNplay behaviour.
* [deep](https://github.com/Nikaoto/deep) ⭐ 108 | 🐛 1 | 🌐 Lua | 📅 2026-02-17 - An "action-queue" library; helpful for things like z-indexing (although the Playdate already has z-index support in its draw ordering).
* [profile.lua](https://github.com/2dengine/profile.lua) ⭐ 97 | 🐛 0 | 🌐 Lua | 📅 2026-08-11 - Performance profiling for Lua applications.
* [lua-star](https://github.com/wesleywerner/lua-star) ⭐ 79 | 🐛 0 | 🌐 Lua | 📅 2021-07-25 - A\* pathfinding in pure Lua.
* [rxi/shash](https://github.com/rxi/shash) ⭐ 79 | 🐛 0 | 🌐 Lua | 📅 2022-06-22 - A simple, lightweight spatial hash for Lua.
* [GFXP](https://github.com/ivansergeev/gfxp) ⭐ 72 | 🐛 0 | 🌐 Lua | 📅 2024-07-05 - A library with a collection of dithering patterns for the Playdate. An online version of the editor can be seen [here](https://ivansergeev.com/gfxp/).
* [vector.lua](https://github.com/themousery/vector.lua) ⭐ 63 | 🐛 3 | 🌐 Lua | 📅 2024-12-03 - An alternative 2D vector library for Lua.
* [Keyboard Based Menu](https://github.com/AavaGames/playdate-keyboard-based-menu-ui) ⭐ 4 | 🐛 0 | 🌐 Lua | 📅 2024-03-26 - A menu that uses the playdate's keyboard to navigate and select.

##### LOVE

The Lua-based [LÖVE](https://love2d.org/) framework offers a similar API to the Playdate Lua SDK, useful for prototyping before the public release of the Playdate SDK.

See [love2d-community/awesome-love2d](https://github.com/love2d-community/awesome-love2d) ⭐ 4,469 | 🐛 2 | 🌐 PowerShell | 📅 2026-06-18 for additional resources.

* [Sheepolution's "How to LÖVE" tutorial](https://sheepolution.com/learn/book/contents) - An oft-recommended intro to game development in Lua. Most concepts should be transferable to Playdate
* [love-playdate-emulation](https://github.com/cadin/love-playdate-emulation) ⚠️ Archived - A basic template for previewing games built with LÖVE in a Playdate-like environment.

#### C

* [Taxman Engine](https://github.com/McDevon/taxman-engine) ⭐ 134 | 🐛 0 | 🌐 C | 📅 2024-10-15 - A 2D, platform-independent game engine designed for the Playdate. Online demo [here](https://mcdevon.github.io/taxman-wasm/).
* [Prismatic Engine](https://github.com/Sheep42/prismatic-engine) ⭐ 18 | 🐛 7 | 🌐 C | 📅 2026-05-02 - A 2D game engine designed for faster prototyping and simplified development with the Playdate C API.
* [Playdate Game Development in C](https://rua.ua.es/dspace/bitstream/10045/117000/1/Playdate_game_development_in_C_Benavent_Ramon_Alberto.pdf) - Alberto Benavent Ramón's Bachelor's Thesis in Multimedia Engineering, explores the hardware and software of the Playdate

##### Low-level Hardware Documentation & Datasheets

This information was gleaned from a developer preview unit and screenshots.

* [Playdate Reverse Engineering](https://github.com/jaames/playdate-reverse-engineering) ⭐ 307 | 🐛 1 | 🌐 Python | 📅 2026-08-07 - Unofficial documentation covering the Playdate's file formats, USB serial commands, and server API.
* [CPU: ST STM32F746](https://www.st.com/resource/en/datasheet/stm32f745ie.pdf)
  * [MCU Reference Manual](https://www.st.com/resource/en/reference_manual/dm00124865-stm32f75xxx-and-stm32f74xxx-advanced-arm-based-32-bit-mcus-stmicroelectronics.pdf)
  * [CPU Programming Manual](https://www.st.com/resource/en/programming_manual/dm00237416-stm32f7-series-and-stm32h7-series-cortexm7-processor-programming-manual-stmicroelectronics.pdf)
  * [SPI Documentation](https://www.st.com/content/ccc/resource/training/technical/product_training/group0/3e/ee/cd/b7/84/4b/45/ee/STM32F7_Peripheral_SPI/files/STM32F7_Peripheral_SPI.pdf/_jcr_content/translations/en.STM32F7_Peripheral_SPI.pdf)
  * [DMA Documentation](https://www.st.com/resource/en/application_note/dm00046011-using-the-stm32f2-stm32f4-and-stm32f7-series-dma-controller-stmicroelectronics.pdf)
* [Audio: Cirrus 42L52CNZ](https://www.alldatasheet.com/datasheet-pdf/pdf/255532/CIRRUS/CS42L52-CNZ.html)
* [eMMC: Kioxia THGBMDG5D1LBAIT 4GB](https://www.mouser.com/datasheet/2/1034/Toshiba_FAB_eMMC-1669846.pdf)
* [SPI Flash: Winbond W25Q32JVS 4MB](https://www.mouser.com/datasheet/2/949/w25q32jv_revg_03272018_plus-1489806.pdf)
* [DRAM: Winbond W967D6HBGX7I 16MB](https://www.mouser.com/datasheet/2/949/w967d6hb_datasheet_pkg_a01-003_20130529-1489841.pdf)
* [LCD Module: Sharp LS027B7DH01A](https://www.sharpsde.com/fileadmin/products/Displays/Specs/LS027B7DH01A_06Aug12_Spec_LCP-1112041.pdf)
  * [LCD Screen Programming Guide](https://www.sharpsde.com/fileadmin/products/Displays/2016_SDE_App_Note_for_Memory_LCD_programming_V1.3.pdf)

#### Experimental & Other

These projects represent experiments with the Playdate. Use at your own risk.

* [Crankstart](https://github.com/rtsuk/crankstart) ⭐ 261 | 🐛 15 | 🌐 Rust | 📅 2025-04-05 - An experimental Rust crate to write games for the Playdate in Rust.
* [VSCode-PlaydateTemplate](https://github.com/Whitebrim/VSCode-PlaydateTemplate) ⭐ 220 | 🐛 2 | 🌐 Shell | 📅 2024-11-27 - VSCode autocompletion with the Playdate simulator. For Windows & Linux.
* [playbit](https://github.com/GamesRightMeow/playbit) ⭐ 113 | 🐛 60 | 🌐 Lua | 📅 2026-07-29: Build cross-platform Playdate games, create build scripts, and utilize preprocessor macros!
* [mini3d-plus](https://github.com/nstbayless/mini3d-plus) ⭐ 86 | 🐛 2 | 🌐 C | 📅 2023-02-08 - 3D engine based on the mini3d library provided in the SDK examples.
* [playdate-nim](https://github.com/samdze/playdate-nim) ⭐ 81 | 🐛 5 | 🌐 Nim | 📅 2026-07-31 - Nim bindings with extra features for the Playdate SDK.
* [pd-usb](https://github.com/jaames/pd-usb) ⭐ 61 | 🐛 0 | 🌐 TypeScript | 📅 2024-12-08 - JavaScript librarty for interacting with a Playdate connected over USB.
* [playdate-rs](https://github.com/igaryhe/playdate-rs) ⭐ 22 | 🐛 0 | 🌐 Rust | 📅 2021-06-19 - Unofficial Rust binding for Playdate C API.
* [playdate4j](https://github.com/am1goo/playdate4j) ⭐ 9 | 🐛 0 | 🌐 Java | 📅 2024-09-07 - Unofficial Java binding for Playdate C API.
* [pd.sh](https://github.com/dknight/pd.sh/) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2025-11-02: A shell script to create a new project from a template, run/stop simulator directly from the terminal.
* [playdate-vscode-build-macos](https://github.com/milkbottlelough/playdate-vscode-build-macos) ⭐ 5 | 🐛 0 | 🌐 Lua | 📅 2023-03-14 - VSCode one click build and simple starter template. macOS only.
* [VSCode-PlaydateTemplateForLinux](https://github.com/imrmnabil/VSCode-PlaydateTemplateForLinux) ⭐ 1 | 🐛 0 | 🌐 Lua | 📅 2022-10-28 - VSCode autocompletion with the Playdate simulator. Linux based system only.
* [GitHub Action: get-playdate-sdk](https://github.com/marketplace/actions/get-playdate-sdk) Installs the Playdate SDK in your GitHub Actions Workflows

### Development & Graphics tools

* [Tiled](https://www.mapeditor.org/) - 2D map editor
* [Thrshold](https://www.figma.com/community/plugin/776033210163988440/Thrshold) - Figma plugin to apply a threshold effect filter
* [LDtk](https://ldtk.io) - A modern 2D level editor with a strong focus on user-friendliness
* [PlaydateLDtkImporter](https://github.com/NicMagnier/PlaydateLDtkImporter) ⭐ 130 | 🐛 4 | 🌐 Lua | 📅 2024-03-29 - Load tilemaps created with LDtk in playdate games

### Development Concepts

#### Game Programming Patterns

* [Game Programming Patterns (book)](https://gameprogrammingpatterns.com/) - The Web version is free.

#### Graphics & Art

* [Ditherpunk](https://surma.dev/things/ditherpunk/) - An article about monochrome image dithering.
* [Stabilized dithering using sphere mapping](https://forums.tigsource.com/index.php?topic=40832.msg1363742#msg1363742) - A dithering implementation used in *Return of the Obra Dinn*.
* [Playdate Art: Scale](https://donaldhays.com/2019/12/30/playdate-art-scale/) - Important notes on designing sprites, fonts, and tiles for the Playdate.

#### Physics

* [Video Game Physics Part I: An Introduction to Rigid Body Dynamics](https://www.toptal.com/game/video-game-physics-part-i-an-introduction-to-rigid-body-dynamics) - Core physics material for game developers.

#### Procedural Generation

* [Making Martian Faces](https://dukope.itch.io/mars-after-midnight/devlog/263965/making-martian-faces) - Notes about generating characters for *Mars after Midnight*.
* [Procedural Content Generation Wiki](http://pcg.wikidot.com/)

### Graphics

* [Memory Icons](https://github.com/Pictogrammers/Memory) ⭐ 201 | 🐛 12 | 🌐 TypeScript | 📅 2023-12-31 - Open Source 1bit icon set
* [DrawDate](https://neil.today/drawdate/) - 1-bit, browser-based sprite editor. [GitHub Source](https://github.com/neil-morrison44/drawdate) ⭐ 22 | 🐛 22 | 🌐 C | 📅 2023-01-06.
* [Pixen](https://pixenapp.com) - Pixel art editor for Mac and iPad, with recent optimizations for [Playdate graphics creation](https://furnacecreek.org/blog/2024-01-28-pixen-and-playdate).

### Fonts

* [Playdate Arcade Fonts](https://idleberg.github.io/playdate-arcade-fonts/) - Collection of classic arcade fonts for the Playdate.
* [PDFontTool](https://github.com/abenokobo/PDFontTool) ⭐ 85 | 🐛 5 | 🌐 C++ | 📅 2022-05-18 - Converts TrueType Font, OpenType Font to Playdate Font.

## Open Source Playdate Games & Example Code

* [Panels](https://github.com/cadin/panels) ⭐ 196 | 🐛 2 | 🌐 Lua | 📅 2026-07-15 – Build interactive comics for the Playdate console.
* [Panels](https://github.com/cadin/panels) ⭐ 196 | 🐛 2 | 🌐 Lua | 📅 2026-07-15 – Build interactive comics for the Playdate console.
* [Playnote Studio](https://github.com/jaames/playnote-studio) ⭐ 103 | 🐛 5 | 🌐 Lua | 📅 2026-02-12 - An unofficial Flipnote Studio animation player for the Playdate.
* [Factory Farming](https://github.com/timboe/FactoryFarming) ⭐ 102 | 🐛 0 | 🌐 C | 📅 2026-04-27
* [Mini3D+](https://github.com/nstbayless/mini3d-plus) ⭐ 86 | 🐛 2 | 🌐 C | 📅 2023-02-08 – Enhanced 3D engine for the Panic Playdate.
* [Mini3D+](https://github.com/nstbayless/mini3d-plus) ⭐ 86 | 🐛 2 | 🌐 C | 📅 2023-02-08 – Enhanced 3D engine for the Panic Playdate.
* [Playlate](https://github.com/downie/playlate) ⭐ 69 | 🐛 2 | 🌐 Lua | 📅 2022-03-22 – A template for Playdate to explore Playdate SDK and build your games faster.
* [Klondike Solitaire for Playdate (GitHub Repo)](https://github.com/rtsuk/crankstart-klondike) ⭐ 67 | 🐛 0 | 🌐 Rust | 📅 2022-11-05
* [PickPackPup](https://github.com/NicMagnier/PickPackPup/) ⭐ 62 | 🐛 0 | 🌐 Lua | 📅 2023-05-16
* [BrickCrusher 2000](https://github.com/aliasaria/BrickCrusher2020) ⭐ 27 | 🐛 0 | 🌐 Lua | 📅 2023-09-18 - Brickbreaker Clone for Playdate
* [Gimme Friction Baby](https://github.com/notpeter/playdate-friction) ⭐ 23 | 🐛 1 | 🌐 Lua | 📅 2026-02-13 - Lua/Playdate port of a classic casual Flash game.
* [Artsy Gallery](https://github.com/artsy/hack-playdate-gallery) ⭐ 12 | 🐛 0 | 🌐 Lua | 📅 2022-04-01
* [Game of Life](https://github.com/Whitebrim/Game-of-life-love2d-playdate) ⚠️ Archived - An implementation of Conway's Game of Life meant to provide a template for games to be built in Love2d and ported to Playdate.
* [Six Card Golf](https://github.com/CGagnier/six-card-golf) ⭐ 4 | 🐛 0 | 🌐 Lua | 📅 2021-01-01 - A love2d card game meant to be ported to Playdate.
* [Oops You Started An Intergalactic War](https://monkeymad2.itch.io/oops-you-started-an-intergalactic-war)
  * [GitHub Repo](https://github.com/neil-morrison44/playdate_jam_etiquette) ⭐ 7 | 🐛 0 | 🌐 Lua | 📅 2020-11-15
* [Playdate Anticipation Jam Submissions (Unofficial. - Nov. 2020)](https://itch.io/jam/unofficial-playdate-jam/entries) - A first "pre-Playdate" 1-bit game jam with Playdate-inspired submissions.
* [Sketch, Share, Solve](https://github.com/veu/sketch-share-solve) – Sketch, Share, Solve is a nonogram game for the Playdate.

## Tutorials & How-Tos

### Playdate SDK

* [How to Make a Simple Playdate Game](https://www.youtube.com/watch?v=BG-pbLrY3ro\&list=PLlMPQvEA0GZPOuKJyhSr3Ra0vrpCiBTnb\&index=7) - How to make a simple Space Invaders-inspired game (Lua)
* [Unlicensed Paddle Game](https://github.com/mostlybits/playdate-unlicensed-paddle-game-tutorial) ⭐ 28 | 🐛 0 | 🌐 Lua | 📅 2023-06-03 - How to build a Pong clone (Lua)

### Pulp

* [Pulp Pong](https://devforum.play.date/t/pulp-pong-dev-tutorial/2315) - How to recreate the all-time classic Pong

## Playdate Games & Dev Blogs

* [Crankin's Time Travel Adventure (Official site)](https://uvula.jp/crankin)
  * [Demo Video](https://www.youtube.com/watch?v=rwxrfgCIZ-c)
  * [Demo Video 2](https://www.youtube.com/watch?v=C8rv8HeSAs8)
* [Daily Driver (Dev Blog)](https://blog.gingerbeardman.com/tag/dailydriver/)
  * [Patreon](https://www.patreon.com/dailydriver)
* [HYPER METEOR (Official site)](http://www.vertexpop.com/hypermeteor/)
  * [Twitter](https://twitter.com/vertexpop)
  * [Vertex Pop Blog](http://www.vertexpop.com/blog/)
* [Mars after Midnight (Devlog)](https://dukope.itch.io/mars-after-midnight)
* [Poly's Roly Rumble (Patreon)](https://www.patreon.com/rngparty)
  * [Discord](http://discord.gg/BWW9YNF)
  * [YouTube Channel](https://www.youtube.com/channel/UC15JbSpnLmarkIVL3rQSxNg)
* [Pullfrog 2-Bits (Devlog)](https://amano.games/devlog)
* [Silverball Tactics (Official site)](https://silverballtactics.com/)
  * [YouTube Channel](https://www.youtube.com/channel/UC7TGO4RB663chmDe7VlZL6Q)
  * [Instagram](https://www.instagram.com/silverballtactics/)
* [Widget Satchel II: Return of Sprocket (Official site)](https://noblerobot.com/widgetsatchel-ii)

## Social

### Discussion groups

* [Unofficial Playdate Discord](https://discord.com/invite/zFKagQ2)
* [/r/PlaydateConsole/](https://www.reddit.com/r/PlaydateConsole/) - A Playdate subreddit. Panic employees comment here occasionally.

### Accounts to follow

#### Official Playdate accounts

* [@panic](https://twitter.com/panic) - Official Panic Twitter.
* [@playdate](https://twitter.com/playdate/) - Official Playdate Twitter.
* [@playdateAlerts](https://twitter.com/playdateAlerts) - Official Playdate news.
* [@panic@panic.social](https://social.panic.com/@panic) - Official Panic Mastodon.
* [@playdate@panic.social](https://social.panic.com/@playdate) - Official Playdate Mastodon.

#### Game Dev Accounts

##### Playdate & Panic

* [@gregmaletic](https://twitter.com/gregmaletic) - Project lead on Playdate at Panic.
* [@mrgan](https://twitter.com/mrgan) - Designer at Panic. Contributes to Discord server.
* [@shauninman](https://twitter.com/shauninman) - Playdate Developer & Designer at Panic. Developing [*The Ratcheteer*](https://twitter.com/shauninman/status/1402298970848772099?lang=en).
* [/u/dave\_\_h](https://www.reddit.com/user/dave__h) - Playdate Developer, contributes to /r/PlaydateConsole and the unofficial Discord.
* [/u/gregmaletic](https://www.reddit.com/user/gregmaletic) - Project lead on Playdate at Panic, contributes to /r/PlaydateConsole.
* [/u/sardinebrunch](https://www.reddit.com/user/sardinebrunch) - Playdate Developer at Panic, contributes to /r/PlaydateConsole.
* [@cabel@social.panic.com](https://social.panic.com/@cabel) - Playdate Developer at Panic.

##### Third-party Devs

* [@amanogames](https://twitter.com/amanogames_) - Developing *Pullfrog 2-Bits*.
* [@andreintg](https://twitter.com/andreintg) - Developing *Date of Life*.
* [@aronegal](https://twitter.com/aronegal) - Developing *Omaze*.
* [@bfod](https://twitter.com/bfod) - Developing *Zipper*.
* [@castpixel](https://twitter.com/castpixel) + [@Nelsormensch](https://twitter.com/Nelsormensch) - Developing *Forrest Byrnes: Up In Smoke*.
* [@ChuhaiLabs](https://twitter.com/ChuhaiLabs) - Developing *Whitewater Wipeout*.
* [@cmakcmak](https://twitter.com/cmakcmak) - Developing *Saturday Edition*.
* [@dadakogames](https://twitter.com/dadakogames) - Developing [*Questy Chess*](https://questychess.com).
* [@davemakes](https://twitter.com/DaveMakes) - Developing *Executive Golf DX* and other Playdate games.
* [@davemakes](https://twitter.com/davemakes) - Developing *Robot Fishing*.
* [@dmierau](https://twitter.com/dmierau) - Developing *Playmaker*.
* [@Dovuro](https://twitter.com/Dovuro) - Misc. Jam games, including a version of Chess, and a port of Bubble Factory.
* [@dukope](https://twitter.com/dukope) - Developing [*Mars after Midnight*](https://dukope.itch.io/mars-after-midnight).
* [@DuncanFyfe](https://twitter.com/DuncanFyfe) - Developing *Demon Quest 85*.
* [@frankjonen](https://twitter.com/frankjonen) - Developing *Silverball Tactics*.
* [@GerudoGibbs](https://twitter.com/GerudoGibbs) - Developing *Spellcorked*.
* [@gingerbeardman](https://twitter.com/gingerbeardman) - Developing *Daily Driver*.
* [@helvetica](https://twitter.com/helvetica) - Developing *Snak*.
* [@kataStatik](https://twitter.com/kataStatik) - Developing *Direct Drive*.
* [@matthew\_ej](https://twitter.com/matthew_ej) - Developing [*Oxy Con Brio*](https://www.loveofdrawing.com/oxy-con-brio.html).
* [@mayli](https://twitter.com/mayli) - Developing *Boogie Loops*.
* [@michaelfrei10](https://twitter.com/michaelfrei10) - Developing *Getting There*.
* [@mobeenfikree](https://twitter.com/mobeenfikree) - Developing [*HYPER METEOR*](http://www.vertexpop.com/hypermeteor/).
* [@NicMagnier](https://twitter.com/nicmagnier) - Developing *Pick Pack Pup*.
* [@noblerobot](https://twitter.com/noblerobot) - Developing [*Widget Satchel II: Return of Sprocket*](https://noblerobot.com/widgetsatchel-ii).
* [@Radstronomical](https://twitter.com/Radstronomical) - Developing *Casual Birder*.
* [@RNGParty](https://twitter.com/RNGParty) - Developing *Poly's Roly Rumble*.
* [@Rokashi](https://twitter.com/Rokashi) - Developing *Faraway Fairway*.
* [@SamanthaZero](https://twitter.com/SamanthaZero) - Developing *Echoic Memory*.
* [@serenityforge](https://twitter.com/serenityforge) - Developing *Flipper Lifter*.
* [@SweetBabyInc](https://twitter.com/SweetBabyInc) - Developing *Lost Your Marbles*, *Recommendation Dog* and *Reel Steal*.
* [@tpmcosoftworks](https://twitter.com/tpmcosoftworks) - Developing *Battleship Godios*.
* [@uvulaLLC](https://twitter.com/uvulaLLC) - Developing [*Crankin's Time Travel Adventure*](https://uvula.jp/crankin).
* [@veubeke](https://twitter.com/veubeke) - Developing *Down the Oubliette*.

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md)

## Footnotes

### Official Links

* [Official Playdate Site](https://play.date)
* [Playdate Developers Site](https://play.date/dev)
* [Playdate Store](https://shop.play.date/)
* [Panic Official Site](https://panic.com/)
* [Panic Podcasts](https://podcast.panic.com/)
* [Panic Blog](https://panic.com/blog/)
* [Teenage Engineering](https://teenage.engineering/)
* [Playdate Media Kit & FAQ](https://play.date/mediakit/)
* [Panic Mastodon Instance](https://social.panic.com/)

### News, Background, and Fluff

#### Panic & TE Announcements

* [2021-07-29: Panic Podcast Episode 6: The Story of Playdate](https://bit.ly/2Vg3Hs5)
* [2021-06-08: Say Hello to Playdate! (Panic)](https://www.youtube.com/watch?v=HdF3CnFvxg4)
* [2021-06-08: Playdate Update - 6/8/2021 (Panic)](https://www.youtube.com/watch?v=DeWGukDrc1U)
* [2020-09-22: Make Games for Playdate (Panic)](https://www.youtube.com/watch?v=FH9HEmCwAvk)
* [2019-12-01: December 2019 Update](https://play.date/update-dec/)
* [2019-06-01: Small Wonder: Edge Magazine's Playdate Cover Story](https://imgur.com/a/CWMNBvI)
* [2019-05-31: "The Talk Show" - Interview with Cabel Sasser, Steven Frank, and Greg Maletic about Playdate](https://daringfireball.net/thetalkshow/2019/05/30/ep-252)
* [Teenage Engineering: Introducing Playdate](https://teenage.engineering/designs/playdate)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
