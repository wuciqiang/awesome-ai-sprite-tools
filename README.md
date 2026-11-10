# Awesome AI Sprite Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of tools for making animated 2D game sprites: AI generators that draw and animate characters, packers that build sprite sheets, editors for drawing frames by hand, free converters, and free assets you can ship.

> **Disclosure:** this list is maintained by the team behind [SpriteCanvas](https://spritecanvas.com/) and [SpritePacker](https://spritepacker.app/), which appear below and are marked *(ours)*. We list what each tool is best at, including where others beat us. Prices and free allowances were checked on 2026-11-03 (SpriteCanvas on 2026-11-05) on each tool's own site; they change, so check before you buy. Corrections and additions are welcome, see [Contributing](#contributing).

## Contents

- [AI sprite sheet generators](#ai-sprite-sheet-generators)
- [Sprite sheet packers](#sprite-sheet-packers)
- [Sprite editors](#sprite-editors)
- [Free converters and slicers](#free-converters-and-slicers)
- [Free assets](#free-assets)
- [Guides](#guides)
- [Contributing](#contributing)

## AI sprite sheet generators

Each of these takes a character from a text prompt or an image and gives you animated sprite sheets. The biggest difference is art style: most draw pixel art on small canvases, a few handle painted, cartoon or anime characters at larger sizes.

| Tool | Art style | Free allowance | Lowest paid plan | API or MCP |
|---|---|---|---|---|
| [PixelLab](https://www.pixellab.ai/) | Pixel art | 40 fast generations, then 5 a day | $12/month for 2,000 generations | Yes, free accounts too |
| [Ludo.ai](https://ludo.ai/) | Any style | 30 trial credits; downloads watermarked | $20/month for 250 credits | $50 Pro plan |
| [AutoSprite](https://www.autosprite.io/) | Any style | 15 credits a month plus 3 a day | $12/month for 500 credits | $29 Pro plan |
| [SpriteCanvas](https://spritecanvas.com/) *(ours)* | Any style | 40 credits at sign-up (7 days), then 3 a day that save up to 12 | $12/month, or $5 one-time pack | MCP server, free accounts too |
| [Gamelabs Studio](https://gamelabstudio.co/) | Any style | 20 credits | $10/month for 120 credits | All paid plans |
| [SpriteLab](https://spritelab.dev/) | Pixel art | 25 credits plus 5 a day | $7.99 for 400 credits | Yes |
| [Sprite AI](https://www.sprite-ai.art/) | Pixel art | 15 generations | $8/month for 100 tokens | Yes |
| [Spriteflow](https://spriteflow.io/) | Pixel, cartoon, anime | Daily free credits | $19.90/month for 200 credits | Yes |
| [Spritefy](https://spritefy.com/) | Pixel art and 2D | 80 credits at sign-up, no card; outputs public, no commercial use | €19/month for 2,000 credits | MCP server, free accounts too |
| [Retro Diffusion](https://retrodiffusion.ai/) | Pixel art | $0.50 for new accounts | Pay as you go from $5 | Yes |
| [God Mode AI](https://www.godmodeai.co/) | Any style, from your image | 3 credits | $29/month, or $32 for 30 credits | Not listed |
| [Scenario](https://www.scenario.com/) | Many models; sheets are pixel art | 50 credits a day, no commercial use | $15/month for 1,500 credits | Yes |

- [PixelLab](https://www.pixellab.ai/) - Pixel art drawn on a real pixel grid, inside Aseprite and Pixelorama, plus tilesets and maps.
- [Ludo.ai](https://ludo.ai/) - Game-making suite with a sprite generator (641 motion presets, moves up to 5 seconds), 3D, audio, video and market research; Unity plugin.
- [AutoSprite](https://www.autosprite.io/) - Character animations with engine presets for Unreal, GameMaker and RPG Maker, and an MCP server on Pro.
- [SpriteCanvas](https://spritecanvas.com/) *(ours)* - Characters in any art style animated from 5-second generated clips, with frame picking, loop check, foot pivot and a playable test stage; exports tested in Phaser and PixiJS and verified in Godot 4, Unity not verified yet.
- [Gamelabs Studio](https://gamelabstudio.co/) - Any-style characters with sprite sheet, MP4 and WebM export; API and MCP on every paid plan.
- [SpriteLab](https://spritelab.dev/) - Low-cost pixel art characters and animations; commercial use on every plan.
- [Sprite AI](https://www.sprite-ai.art/) - Pixel art generator with a built-in pixel editor and an Aseprite plugin.
- [Spriteflow](https://spriteflow.io/) - Pixel, cartoon and anime characters from 16 to 512 pixels, with JSON or XML atlases for Unity, Godot and Unreal.
- [Spritefy](https://spritefy.com/) - Pixel art and 2D characters, tiles, VFX and 8-direction animations, plus 3D models, sound effects and music in the same workspace; exports Godot SpriteFrames, a JSON atlas for Unity and Unreal, and GameMaker strips.
- [Retro Diffusion](https://retrodiffusion.ai/) - Pay-per-result pixel art images and animations, no subscription.
- [God Mode AI](https://www.godmodeai.co/) - Animates a character image you already have; exports PNG sheets with JSON and MP4, with Spine listed.
- [Scenario](https://www.scenario.com/) - General AI art platform for game studios with custom model training; sprite sheets are one feature.

A longer write-up of each, with how to choose, is in [Best AI sprite sheet generators](https://spritecanvas.com/docs/best-ai-sprite-sheet-generators/) *(ours)*.

## Sprite sheet packers

- [TexturePacker](https://www.codeandweb.com/texturepacker) - Desktop packer with the largest exporter catalog and command-line builds; $49.99 one-time, free trial.
- [Free Texture Packer](https://free-tex-packer.com/) - Free, open source packer for the browser or desktop with many export formats.
- [Leshy SpriteSheet Tool](https://www.leshylabs.com/apps/sstool/) - Free browser packer that also edits existing atlases; XML, JSON, CSS and ImageMagick maps.
- [SpritePacker](https://spritepacker.app/) *(ours)* - Free browser packer; trims edges, previews the loop and exports Phaser and PixiJS JSON, Unity XML or CSS without uploading your images.

## Sprite editors

- [Aseprite](https://www.aseprite.org/) - The standard pixel art animation editor, with layers, tags, onion skin and sprite sheet export; $19.99.
- [LibreSprite](https://libresprite.github.io/) - Free, open source fork of the last GPL version of Aseprite.
- [Pixelorama](https://orama-interactive.itch.io/pixelorama) - Free, open source pixel art editor built with Godot.
- [Piskel](https://www.piskelapp.com/) - Free, open source sprite editor in the browser, exporting GIFs and PNG sheets.

## Free converters and slicers

- [ezgif sprite cutter](https://ezgif.com/sprite-cutter) - Cuts a sheet into frames online among many GIF tools; uploads your file to its server.
- [SpritePacker Frame Extractor](https://spritepacker.app/tools/frame-extractor) *(ours)* - Cuts a sheet back into frames inside the browser.
- [SpritePacker GIF to sprite sheet](https://spritepacker.app/tools/gif-to-sprite-sheet) *(ours)* - Turns a GIF into a sheet, and [back again](https://spritepacker.app/tools/sprite-sheet-to-gif).
- [SpriteCanvas video to sprite sheet](https://spritecanvas.com/video-to-sprite-sheet/) *(ours)* - Turns an MP4 or WebM clip into a sprite sheet in the browser, no account.
- [SpriteCanvas sprite sheet slicer](https://spritecanvas.com/sprite-sheet-slicer/) *(ours)* - Slices a sheet by grid into frames, no account.
- [Spritefy GIF to sprite sheet](https://spritefy.com/free-tools/gif-to-sprite-sheet) - Turns a GIF into a sprite sheet, no account.
- [Spritefy sprite sheet cutter](https://spritefy.com/free-tools/sprite-sheet-cutter) - Cuts a sheet into frames by grid, no account.

## Free assets

- [Kenney](https://kenney.nl/assets) - Thousands of CC0 game assets, including 2D characters and tiles.
- [OpenGameArt](https://opengameart.org/) - Community art library; licenses vary, so filter by CC0 or check each one.
- [itch.io free game assets](https://itch.io/game-assets/free) - Free sprite packs from many artists; read each pack's license.
- [SpriteCanvas free sprite sheets](https://spritecanvas.com/free-sprite-sheets/) *(ours)* - CC0 animated characters in both directions with a Godot 4 scene, plus effects, monsters and props, also on [itch.io](https://spritecanvas.itch.io/).

## Guides

- [What is a sprite sheet](https://spritecanvas.com/docs/what-is-a-sprite-sheet/) *(ours)* - Frames, atlases, pivots and frame timing explained.
- [Godot sprite sheet animation](https://spritecanvas.com/docs/godot-sprite-sheet-animation/) *(ours)* - Importing a sheet into Godot 4 step by step.
- [Sprite sheet export troubleshooting](https://spritepacker.app/blog/sprite-sheet-export-troubleshooting) *(ours)* - Fixing blurry, shifted or bleeding frames after export.

## Contributing

Open a pull request or an issue. To add a tool, put it in the right section in alphabetical-or-table order with a one-line description of what it is best at, a link to its own site, and, for paid tools, a price you checked with the date. Tools you make are welcome too; please say so in the pull request, as we do above.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this list.
