<div align="center">

# 👑 KINGDOM .INC

### Modding

Home to **Foundation**, the shared modding framework for **Kingdom Inc**, and the mods, tools, and experiments built around it.

[All Projects](https://github.com/orgs/KingdomIncModding/repositories) · [Foundation](https://github.com/KingdomIncModding/Foundation) · [Wiki](https://github.com/KingdomIncModding/Wiki) · [Support on Ko-fi](https://ko-fi.com/S6V62AX30M)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/S6V62AX30M)

</div>

---

<div align="center">

## 🏛️ Foundation

**The shared framework at the heart of KingdomIncModding.**

**[Get Foundation & the SDK](https://github.com/KingdomIncModding/Foundation#downloads)** · **[Explore the Framework](https://github.com/KingdomIncModding/Foundation#readme)**

</div>

Foundation is the lifeblood of this collection. It connects mods to Kingdom Inc's own systems and gives them common tools for research, machines, interfaces, settings, and saved data. That shared groundwork lets each mod concentrate on what it brings to your kingdom.

| Part of your kingdom | What Foundation makes possible |
| :--- | :--- |
| **Research & new content** | Separate mod research views, technology branches, custom workspace nodes, and registration for supported game content. |
| **Machines & logistics** | Shared access to machines, ports, connections, item transfers, and observed throughput. |
| **A familiar interface** | A common Mod Bar, in-game mod settings, and reusable windows and controls styled for the game. |
| **Mods working together** | Shared events, service discovery, and mod-owned data stored with the game's saves. |
| **Tools for creators** | A C# SDK and documentation for building on the same game integrations. |

For players, Foundation provides the common controls and required runtime used by many of the mods below. For creators, it provides the building blocks behind a blueprint library, a production ledger, a magical conduit, or the next addition to the workshop.

**Start with Foundation, then choose the mods that belong in your kingdom.** Check each project's README for its required framework version.

---

## 🔮 Machines & Leylines

New nodes for your production lines and adventuring parties.

| Mod | What it adds |
| :--- | :--- |
| **[Party-Up](https://github.com/KingdomIncModding/PartyNode)** | Assemble up to five adventurers in a Party Node, dispatch them together, and research automatic sending. |
| **[Leyline Conduits](https://github.com/KingdomIncModding/LeylineConduits)** | Transfer items through named magical conduits, including between workshop tabs. |
| **[Ledger](https://github.com/KingdomIncModding/LedgerMod)** | Place a ledger in a production line to track passing items, chain costs, and profit or loss without storing inventory. |

## ⚙️ The Workshop

Capture, arrange, rebuild, and refine your factories.

| Mod | What it adds |
| :--- | :--- |
| **[Sharable Blueprints](https://github.com/KingdomIncModding/SharableBlueprints)** | Capture factory layouts, organize blueprint books, and exchange compact share codes. |
| **[Port Layouts](https://github.com/KingdomIncModding/PortLayouts)** | Choose the sides used by building inputs and outputs while keeping machine icons upright. |
| **[Snappy](https://github.com/KingdomIncModding/Snappy)** | Finer snapping for buildings, pipe bends, decorations, and container resizing. |
| **[Better Deconstruct](https://github.com/KingdomIncModding/BetterDeconstruct)** | Select an area for demolition, filter its contents, and review building counts and refunds before confirming. |
| **[Undo](https://github.com/KingdomIncModding/Undo)** | Undo and redo factory edits, including grouped moves, connections, and supported batch deletions. |
| **[Unstacker](https://github.com/KingdomIncModding/Unstacker)** | Remove one building stack level at a time and refund its current building price. |

## 🪙 The Treasury & Production Lines

Follow your economy and find out where the machinery stalls.

| Mod | What it adds |
| :--- | :--- |
| **[Global Ledger](https://github.com/KingdomIncModding/GlobalLedger)** | The original kingdom-wide overview of currency earnings, operating expenses, and item production. |
| **[Global Ledger HD](https://github.com/KingdomIncModding/GlobalLedgerV2)** | The redesigned edition, with aligned In / Out / Net columns, compact controls, and detailed source views. |
| **[Bottleneck Heatmap](https://github.com/KingdomIncModding/BottleneckHeatmap)** | Colored overlays reveal running lines, starved machines, clogged pipes, full storage, and idle nodes. |
| **[Path Finder](https://github.com/KingdomIncModding/PathFinder)** | Hover or pin a node to highlight its direct input and output paths with distinct neon colors. |

Global Ledger and Global Ledger HD are alternative editions. See their READMEs when choosing or switching between them.

## 🧰 Your Kingdom, Your Controls

More room to see, more ways to organize, and fewer interruptions.

| Mod | What it adds |
| :--- | :--- |
| **[Better Zoom](https://github.com/KingdomIncModding/BetterZoom)** | Extended workshop and research-tree zoom with configurable limits and cursor anchoring. |
| **[Container Colors](https://github.com/KingdomIncModding/ContainerColors)** | Custom colors for containers and labels, with a live picker, hex entry, opacity, and swatches. |
| **[Hotkey Customizer](https://github.com/KingdomIncModding/HotkeyCustomizer)** | Custom key combinations, building shortcuts, and a collapsible building hotbar. |
| **[Audio Manager](https://github.com/KingdomIncModding/AudioManager)** | Separate volume controls for music, interface sounds, crafting, machines, economy, combat, and participating mods. |
| **[Right Click Fix](https://github.com/KingdomIncModding/RightClickFix)** | Close menus and cancel tool modes with right click while preserving right-drag panning and existing actions. |
| **[Guild House & Armory Cleanup](https://github.com/KingdomIncModding/GuildhouseCleanup)** | Hide empty troop and equipment slots in supported storage menus; restore them when stock returns. |
| **[HD Snapshot](https://github.com/KingdomIncModding/HDSnapshot)** | Capture a selected workshop area or a panoramic view of your production lines in high definition. |

## 📚 The Archives & Artificer's Bench

References, integrations, and tools for experimenting with the game.

| Project | What it provides |
| :--- | :--- |
| **[Kingdom Inc Wiki](https://github.com/KingdomIncModding/Wiki)** | An independent offline reference for mechanics, recipes, research, buildings, currencies, quests, and more. |
| **[DevSpawner](https://github.com/KingdomIncModding/DevSpawner)** | A sandbox and testing utility that enables the native Spawner to produce chosen items without production inputs. |

## 🏰 Enter the Kingdom

1. **Choose your mods.** Open a project's README for its features, requirements, and downloads.
2. **Prepare your game.** Install the required BepInEx version and Foundation where the mod requires them.
3. **Check compatibility.** Match each mod and its dependencies to your installed game version.
4. **Head to the workshop.** Follow the project's installation, research, and controls guide.

Each project's README covers its own compatibility and removal guidance, including Undo's transition when built-in undo and redo become available.

## 🔨 Build Something of Your Own

Explore **[Foundation's documentation and SDK](https://github.com/KingdomIncModding/Foundation#readme)** for shared game integrations and reusable mod interfaces.

For bug reports and suggestions, use the relevant project's Issues tab. Include your game and mod versions, steps to reproduce the problem, and useful logs or screenshots. Check the project's license and contribution guidance before submitting code.

## ☕ Support the Project

Every mod, tool, and framework update in KingdomIncModding is built and maintained independently. If these projects make your kingdom run smoother, consider buying a coffee on Ko-fi!

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/S6V62AX30M)

---

<div align="center">

**[KingdomIncModding](https://github.com/KingdomIncModding)**

Independent community projects for Kingdom Inc.<br>
Not affiliated with or endorsed by the game's developers.<br>
Kingdom Inc and its artwork belong to their respective owners.

</div>
