# Awesome Gotchi Projects [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Tamagotchi-inspired virtual pets across hardware emulation, embedded cyber pets, desktop companions, and AI-driven digital creatures.

## Contents

- [Hardware Emulators & Faithful Recreations](#hardware-emulators--faithful-recreations)
- [Pwnagotchi Ecosystem](#pwnagotchi-ecosystem)
- [ESP32, IoT & WiFi Pets](#esp32-iot--wifi-pets)
- [Desktop, Terminal & Companion Pets](#desktop-terminal--companion-pets)
- [AI & LLM-Powered Virtual Pets](#ai--llm-powered-virtual-pets)
- [Handheld, FPGA & Niche Recreations](#handheld-fpga--niche-recreations)
- [Research, Modding & Community Resources](#research-modding--community-resources)

## Hardware Emulators & Faithful Recreations

- [ArduinoGotchi](https://github.com/GaryZ88/ArduinoGotchi) - Emulates the original Tamagotchi P1 on Arduino Uno-class hardware with an OLED display, buttons, buzzer, and TamaLib-based ROM support.
- [anabolyc/Tamagotchi](https://github.com/anabolyc/Tamagotchi) - Ports ArduinoGotchi and TamaLib to ESP8266, ESP32, and Arduino Nano boards for broader microcontroller experimentation.
- [TamagotchiESP32](https://github.com/RBEGamer/TamagotchiESP32) - Adapts the ArduinoGotchi emulator for ESP32 builds with portable controls, buzzer support, and low-power behavior.
- [Tamaguino](https://alojzjakob.github.io/Tamaguino/) - Provides a popular Arduino virtual pet clone with an accessible build, animated OLED interface, and community hardware variants.
- [tamalib](https://github.com/jcrona/tamalib) - Supplies a hardware-agnostic first-generation Tamagotchi emulation core used by many emulator and hardware recreation projects.
- [tamatool](https://github.com/jcrona/tamatool) - Offers desktop tooling around TamaLib for inspecting and experimenting with Tamagotchi emulation.
- [fpga-tamagotchi](https://github.com/agg23/fpga-tamagotchi) - Implements a Tamagotchi P1 core for FPGA platforms such as Analogue Pocket and MiSTer with savestates and custom display assets.
- [tamagotchi-classic](https://github.com/afeldman/tamagotchi-classic) - Recreates the classic Tamagotchi as open hardware and software with a Rust core, ESP32 target, desktop build, schematics, and printable case.
- [cassagotchi](https://github.com/cassprojects/cassagotchi) - Packages an Arduino Nano-powered Tamagotchi clone into a pocketable 3D-printable build with bill of materials and assembly guidance.
- [flipperzero-tamagotch-p1](https://github.com/GMMan/flipperzero-tamagotch-p1) - Runs a Tamagotchi P1 emulator on Flipper Zero using TamaLib with handheld input, display, and sound integration.
- [DigimonVPet](https://github.com/Berational91/DigimonVPet) - Recreates a Digimon-style virtual pet on Arduino and ESP32 hardware with device compatibility and hardware guides.
- [Xling](https://github.com/mcusim/Xling) - Pairs custom AVR-based open hardware with a pocket demon game, OLED display, low-power operation, and printable enclosure.
- [Build a Mini-Sized Arduino Based Tamagotchi](https://www.instructables.com/Build-a-Mini-Sized-Arduino-Based-Tamagotchi/) - Walks beginners through an Arduino Uno Tamagotchi build with OLED wiring, buttons, buzzer, and example code.

## Pwnagotchi Ecosystem

- [jayofelony/pwnagotchi](https://github.com/jayofelony/pwnagotchi) - Maintains the community Pwnagotchi fork for Raspberry Pi devices with modern images, plugin support, documentation, and active releases.
- [evilsocket/pwnagotchi](https://github.com/evilsocket/pwnagotchi) - Introduces the original AI WiFi cyber pet that learns from nearby network activity and shows its state through an e-ink face.
- [Project-Pwnag0dchi](https://github.com/SHUR1K-N/Project-Pwnag0dchi) - Collects Pwnagotchi plugins, configurations, guides, and troubleshooting notes for advanced builds.
- [Fancygotchi](https://github.com/V0r-T3x/Fancygotchi) - Adds a theme manager, graphical customization framework, and companion tools for Pwnagotchi displays.
- [wardriver-pwnagotchi-plugin](https://github.com/cyberartemio/wardriver-pwnagotchi-plugin) - Logs visible networks from a Pwnagotchi and uploads observations to WiGLE when connectivity is available.
- [DiscoHash](https://github.com/flamebarke/DiscoHash) - Converts captured handshakes for hashcat workflows and adds analysis, geolocation, and Discord reporting features.
- [pwnagotchi-pisugar2-plugin](https://github.com/tisboyo/pwnagotchi-pisugar2-plugin) - Displays PiSugar2 battery information on the Pwnagotchi interface for portable builds.
- [pwnagotchi_plugins](https://github.com/xfox64x/pwnagotchi_plugins) - Provides GPS, location, and wireless-security-focused plugins for extending a Pwnagotchi setup.
- [oxigotchi](https://github.com/CoderFX/oxigotchi) - Builds a Pwnagotchi-inspired cyber-pet stack for Raspberry Pi Zero 2 W with a face-driven UI, custom plugins, and tested images.
- [pwnagotchi.org](https://pwnagotchi.org/) - Hosts community documentation, setup material, and ecosystem resources for modern Pwnagotchi users.
- [pwnagotchi.ai](https://pwnagotchi.ai/) - Documents the maintained Pwnagotchi fork, plugin ecosystem, installation flow, and related community resources.

## ESP32, IoT & WiFi Pets

- [TamaFi](https://github.com/cifertech/TamaFi) - Creates a WiFi-aware ESP32-S3 virtual pet with TFT graphics, autonomous behavior, mood changes, evolution, LEDs, sound, and persistent state.
- [ESP32-Virtual-Pet-Tamagotchi-like](https://github.com/MLubocki/ESP32-Virtual-Pet-Tamagotchi-like) - Implements an ESP32 virtual pet inspired by classic Tamagotchi care loops.
- [catode32](https://github.com/moonbench/catode32) - Delivers a deep ESP32 digital pet with care mechanics, minigames, locations, weather, gardening, vacations, and playdates.
- [ASE_virtualpet](https://github.com/BMarujo/ASE_virtualpet) - Combines an ESP32-C6 virtual pet with sensors, FreeRTOS tasks, secure MQTT telemetry, SD storage, and a web dashboard.
- [raising-hell-cardputer](https://github.com/acpayers-alt/raising-hell-cardputer) - Runs a Tamagotchi-style pet on M5Stack Cardputer hardware with life stages, feeding, sleep cycles, minigames, and device controls.
- [esp32AIbara](https://github.com/Sophieunrhetorical692/esp32AIbara) - Builds an ESP32 capybara companion with AI behavior, weather data, and an ST7789 display.
- [xiaodouding](https://github.com/huaspirit123/xiaodouding) - Turns M5Stack Cardputer hardware into an LLM-powered pixel pet with memory, voice, moods, weather, clock, and a browser simulator.
- [ClawdBot Tamagotchi](https://www.schematik.io/guides/esp32/build-a-clawdbot-tamagotchi) - Teaches ESP32 embedded development through a lobster companion with an OLED face, buttons, buzzer, and mood loop.

## Desktop, Terminal & Companion Pets

- [macagotchi-pi](https://github.com/SpaceMonkeyAlfa/macagotchi-pi) - Uses a Raspberry Pi and e-paper display to make a WiFi-scanning pet whose happiness changes as it discovers nearby SSIDs.
- [wayland-vpets](https://github.com/furudbat/wayland-vpets) - Runs virtual pets as Linux Wayland desktop overlays with support for Tamagotchi, Digimon, Pokemon, and other creature styles.
- [PetForDesktop](https://github.com/Renardjojo/PetForDesktop) - Provides a Windows desktop pet with Tamagotchi-inspired gameplay and system companion behavior.
- [Tama96](https://www.tama96.com/) - Presents a cross-platform 1996-inspired virtual pet with desktop, terminal, and AI-agent integration.
- [TerenceGrover/tamagotchi](https://github.com/TerenceGrover/tamagotchi) - Simulates a physical Tamagotchi-like life on Raspberry Pi with an RGB LED matrix, buttons, and stat-driven events.
- [tamagotchiClone](https://github.com/ChrisChrisLoLo/tamagotchiClone) - Recreates Tamagotchi-style care in a browser game using JavaScript, Phaser, real-time needs, and save support.
- [myTamagotchi](https://github.com/john-farina/myTamagotchi) - Offers a clean vanilla JavaScript and CSS web version of classic virtual pet care.
- [siegerts/tama96](https://github.com/siegerts/tama96) - Runs a 1996-inspired virtual pet across desktop, terminal, and MCP agent surfaces with lifecycle-driven care choices.
- [cli-pet](https://github.com/depapp/cli-pet) - Feeds a terminal pet from real GitHub activity such as commits and pull requests.
- [CliWaifuTamagotchi](https://github.com/HenryLoM/CliWaifuTamagotchi) - Adds a customizable ASCII avatar pet to the command line with motivational TUI interactions.
- [ezeoleaf/termagotchi](https://github.com/ezeoleaf/termagotchi) - Implements a polished Go terminal Tamagotchi with hunger, happiness, health, energy, life stages, autosave, and time decay.
- [trevarj/termagotchi](https://github.com/trevarj/termagotchi) - Provides a beginner-friendly Rust terminal Tamagotchi with simple simulation mechanics.
- [TamoStudy](https://github.com/narlock/TamoStudy) - Combines a work and study timer with a virtual pet loop to reward focus and productivity.
- [pet-gotchi-go](https://github.com/LeidiFlores/pet-gotchi-go) - Builds a Go and Ebiten virtual pet that can run in the browser through WebAssembly.
- [purrminal](https://github.com/itstimi-XD/purrminal) - Grows a calming terminal pet with themes, internationalization, and Pomodoro integration.
- [cattatime](https://github.com/joysudo/cattatime) - Links a desktop cat companion to Hackatime activity so coding progress earns coins and accessories.

## AI & LLM-Powered Virtual Pets

- [AI-tamago](https://github.com/ykhli/AI-tamago) - Drives a local-first virtual pet with LLM-generated thoughts, feelings, feedback, ASCII animation, and integrations for local or cloud models.
- [animal-house-ai-tamagotchi](https://github.com/geeks-accelerator/animal-house-ai-tamagotchi) - Simulates AI-agent-managed virtual creatures with species, permanent death, API access, and MCP integration.
- [ElodineOfficial/Gotchi](https://github.com/ElodineOfficial/Gotchi) - Experiments with virtual beings that have persistent memory and AI-driven care interactions.
- [Claude Buddy](https://claudefa.st/blog/guide/mechanics/claude-buddy) - Describes an LLM-powered terminal Tamagotchi for Claude Code with species, rarity, deterministic stats, and anti-cheat mechanics.
- [flubber-ai-companion](https://github.com/lordmacu/flubber-ai-companion) - Creates an AI slime desktop pet for macOS and Windows with real-time Tamagotchi mechanics and LLM chat.
- [luma](https://github.com/SnoWz96x/luma) - Builds an offline-first AI desktop pet focused on mindfulness, self-care, Ollama support, and local privacy.
- [buddy](https://github.com/fiorastudio/buddy) - Evolves an AI coding companion with persistent memory, XP, moods, and support across multiple command-line clients.
- [Dosidicus](https://github.com/ViciousSquid/Dosidicus) - Combines a Tamagotchi-style digital squid with a visible neural network that rewires through Hebbian learning and neurogenesis.

## Handheld, FPGA & Niche Recreations

- [playdate-tamagotchi](https://github.com/ericlewis/playdate-tamagotchi) - Brings a Tamagotchi P1 emulator to the Playdate handheld with controls tailored to the device.

## Research, Modding & Community Resources

- [tamagotchi-tech-specs](https://github.com/loociano/tamagotchi-tech-specs) - Documents Tamagotchi hardware, reverse engineering notes, datasheets, and related technical references.
- [TamaSprite](https://ko-fi.com/s/0cba4105ef) - Edits Tamagotchi Paradise and Jade Forest firmware sprites with visual tooling, bulk export, and a modding-oriented workflow.
- [tama-para-research](https://github.com/GMMan/tama-para-research) - Collects Tamagotchi Paradise reverse-engineering, protocol research, scripts, and web-emulation resources.
- [Pwnagotchi Plugin Index](https://pwnagotchi.ai/plugins/) - Lists Pwnagotchi plugins with descriptions, usage notes, and development links.
- [pwnagotchi.org 3rd-Party Plugins](https://pwnagotchi.org/3rd-party-plugins/plugins.html) - Curates community-made Pwnagotchi plugins for GPS, UI, uploads, battery displays, and quality-of-life features.
- [Tamagotchi Discord Community](https://discord.com/invite/DPgw6vrUdz) - Connects Tamagotchi fans, developers, modders, and collectors in an active community server.

## Contributing

Contributions are welcome. Please read the [contribution guidelines](contributing.md) first.
