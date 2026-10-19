# Clean-Room Reimplementations (updated 2026-10-19)

> Open-source projects that rebuild closed software from the ground up

A curated index of clean-room reimplementations: projects that rebuild a specific closed-source product — an application, a game engine, a network protocol, an operating system — from scratch, rather than wrapping or forking the original. Every entry names the product being reimplemented and the language it is written in. Nothing here is a mirror or a repackaging.

> [!NOTE]
> Compiled from public sources — no independent testing of the linked projects. Star counts were read from the GitHub API on 2026-10-17 and drift daily. A high star count reflects attention, not correctness or completeness: several projects here are early and explicitly unfinished.

## Contents

- [🖥️ Applications](#applications)
- [🎮 Games and engines](#games-and-engines)
- [⚙️ Services, runtimes and platforms](#services-runtimes-and-platforms)

## 🖥️ Applications

Desktop software rebuilt from scratch. This group is currently dominated by a wave of Rust rewrites that each target one widely-used commercial application.

| Project | What it is | Tags |
|---|---|---|
| [PhotoCraft](https://github.com/storytold/photocraft) | A photo editor written from scratch to stand in for Adobe Photoshop, including layered editing and non-destructive adjustment. | `Photoshop`, `Rust` |
| [PdfCraft](https://github.com/storytold/pdfcraft) | A PDF reader and editor reimplemented in place of Acrobat, covering viewing, annotation and page manipulation. | `Acrobat`, `Rust` |
| [FilmCraft](https://github.com/storytold/filmcraft) | A non-linear video editor written to fill the role of Adobe Premiere, with a timeline and render pipeline of its own. | `Premiere`, `Rust` |
| [WordCraft](https://github.com/storytold/wordcraft) | A word processor reimplemented to cover the Microsoft Word feature set, including layout and document formatting. | `Microsoft Word`, `Rust` |
| [LightCraft](https://github.com/storytold/lightcraft) | A non-destructive photo editor targeting the Lightroom workflow: cataloguing, develop settings and batch processing. | `Lightroom`, `Rust` |
| [VectorCraft](https://github.com/storytold/vectorcraft) | A vector art tool rebuilt in place of Adobe Illustrator, with paths, anchors and scalable editing. | `Illustrator`, `Rust` |
| [EffectCraft](https://github.com/storytold/effectcraft) | Motion graphics and compositing written from scratch as an alternative to After Effects. | `After Effects`, `Rust` |
| [GridCraft](https://github.com/storytold/gridcraft) | A spreadsheet reimplemented along the lines of Microsoft Excel, covering formulas and cell-model editing. | `Excel`, `Rust` |
| [CadCraft](https://github.com/storytold/cadcraft) | Computer-aided design and drafting rebuilt as a standalone application, targeting the AutoCAD working model. | `CAD`, `Rust` |
| [DeckCraft](https://github.com/storytold/deckcraft) | A presentation and slideshow tool reimplemented in place of PowerPoint, with slide layout and sequencing. | `PowerPoint`, `Rust` |
| [SoundCraft](https://github.com/storytold/soundcraft) | A digital audio workstation rebuilt to occupy the Pro Tools niche: multitrack recording, editing and mixing. | `Pro Tools`, `Rust` |
| [FigCraft](https://github.com/storytold/figcraft) | Interface design and prototyping reimplemented as an alternative to Figma, covering frames, components and layout. | `Figma`, `Rust` |
| [paper-rs](https://github.com/michaelshimeles/paper-rs) | A native Rust infinite-canvas design app, also aiming at the Figma use case, built on egui and wgpu rather than a web stack. | `Figma`, `Rust` |
| [System7](https://github.com/Kelsidavis/System7) | An open-source reimplementation of Apple Macintosh System 7, including the classic desktop and window manager. | `System 7`, `C` |

## 🎮 Games and engines

The oldest and most established corner of the practice: game engines and services rebuilt from reverse-engineered behaviour or published specifications, usually because the original is abandoned or the servers are gone.

| Project | What it is | Tags |
|---|---|---|
| [SanAndreasUnity](https://github.com/in0finite/SanAndreasUnity) | An open-source reimplementation of the GTA: San Andreas engine in Unity, loading the original game assets into a new runtime. | `GTA: San Andreas`, `C#` |
| [Impostor](https://github.com/Impostor/Impostor) | A reimplementation of the Among Us server, letting players host their own games after the official matchmaking changed. | `Among Us`, `C#` |
| [Jazz² Resurrection](https://github.com/deathkiller/jazz2) | An open-source reimplementation of Jazz Jackrabbit 2, including the original level formats and game logic. | `Jazz Jackrabbit 2`, `C++` |
| [KisakCOD](https://github.com/SwagSoftware/KisakCOD) | An open-source reimplementation of the Call of Duty 4 engine, assembled from leaked and reverse-engineered sources. | `Call of Duty 4`, `C++` |
| [donut](https://github.com/plowteam/donut) | An open-source reimplementation of The Simpsons: Hit & Run, targeting the original game's engine behaviour. | `Simpsons Hit & Run`, `C++` |
| [Chariot](https://github.com/ChariotEngine/Chariot) | A cross-platform reimplementation of the Age of Empires engine, written in Rust. | `Age of Empires`, `Rust` |
| [Abyss Engine](https://github.com/AbyssEngine/AbyssEngine) | A clean-room reimplementation of the Diablo 2 engine, written in C with its own asset pipeline. | `Diablo 2`, `C` |
| [FreeHL](https://github.com/eukara/freehl) | A clean-room reimplementation of Half-Life deathmatch and its game logic, built on the FreeCS codebase. | `Half-Life`, `QuakeC` |
| [OpenBattlefield2](https://github.com/Moxnatiy/OpenBattlefield2) | A clean-room reimplementation of DICE's Refractor 2 engine, the technology behind Battlefield 2. | `Battlefield 2`, `C++` |
| [openDoJa](https://github.com/GrenderG/openDoJa) | A desktop-focused clean-room reimplementation of DoJa, the Java-based mobile platform used by early Japanese phones. | `DoJa`, `Java` |

## ⚙️ Services, runtimes and platforms

Not applications but infrastructure: protocols, servers, hardware runtimes and shells rebuilt so they can run without the vendor.

| Project | What it is | Tags |
|---|---|---|
| [usque](https://github.com/Diniboy1123/usque) | An open-source reimplementation of the Cloudflare WARP client, speaking the same protocol without the proprietary client. | `Cloudflare WARP`, `Go` |
| [OpenTPU](https://github.com/UCSBarchlab/OpenTPU) | An open-source reimplementation of Google's Tensor Processing Unit, reproduced from the published ISA documentation. | `TPU`, `Python` |
| [Pash](https://github.com/Pash-Project/Pash) | An open-source reimplementation of Windows PowerShell for Mono and .NET, so scripts can run off Windows. Archived upstream. | `PowerShell`, `C#`, `Archived` |
| [LuxonServer](https://github.com/niansa/LuxonServer) | A clean-room reimplementation of the Photon LoadBalancing server, the matchmaking layer many Unity games depend on. | `Photon`, `C` |
| [libdragon](https://github.com/DragonMinded/libdragon) | An open-source SDK for the Nintendo 64, built by reverse-engineering the official development libraries. Archived upstream; superseded by the community fork. | `Nintendo 64 SDK`, `C`, `Archived` |

---

## About this list

- **29** entries across **3** sections.
- Compiled from public sources; every linked project carries its own license.
- Last updated: **2026-10-17**.
- Data lives in `data/content.json` — this README is generated, do not edit by hand.

## License

The text and curation in this repository are licensed under CC BY 4.0. Linked projects keep their own licenses.
