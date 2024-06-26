# Awesome Offensive Rust [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<img src="https://github.com/ebalo55/crabby/raw/main/.assets/crab.png" align="right" width="250">

> Curated list of resources about Rust language used for offensive security & red teaming.

_List inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing._

## Contents

- [Awesome Offensive Rust](#awesome-offensive-rust-)
    - [Contents](#contents)
    - [Community](#communities)
    - [Articles](#articles)
    - [Boilerplates](#boilerplates)
    - [Books](#books)
    - [Projects](#projects)
    - [Useful Libraries](#useful-libraries)
    - [Contributing](#contributing)
    - [License](#license)

## Communities

- [Official Rust communities](https://www.rust-lang.org/community)

## Articles

- [Coffee: A COFF loader made in Rust](https://labs.hakaioffsec.com/coffee-a-coff-loader-made-in-rust/)
- [Rasta Mouse Custom Beacon Artifacts](https://rastamouse.me/custom-beacon-artifacts/)
- [Writing Sliver C2 Extensions in Rust](https://blog.paradoxis.nl/writing-sliver-c2-extensions-in-rust-a95f620266de)

## Books

- [Black Hat Rust](https://github.com/skerkour/black-hat-rust) - Applied offensive security with Rust.

## Boilerplates

> Boilerplates for Rust language used for offensive security & red teaming.
> 
> ... Coming soon

## Projects

- [ADPT](https://github.com/Kudaes/ADPT) - DLL proxying for lazy people.
- [DInvoke_rs](https://github.com/Kudaes/DInvoke_rs) - Dynamically invoke arbitrary unmanaged code.
- [Dumpy](https://github.com/Kudaes/Dumpy) - Reuse open handles to dynamically dump LSASS.
- [Bin Finder](https://github.com/Kudaes/Bin-Finder) - Detect EDR's exceptions by inspecting processes' loaded modules.
- [Shelter](https://github.com/Kudaes/Shelter) - ROP-based sleep obfuscation to evade memory scanners.
- [Unwinder](https://github.com/Kudaes/Unwinder) - Call stack spoofing for Rust.
- [RustChain](https://github.com/Kudaes/RustChain) - Hide memory artifacts using ROP and hardware breakpoints.
- [CustomEntryPoint](https://github.com/Kudaes/CustomEntryPoint) - Select any exported function in a dll as the new dll's entry point.
- [Split](https://github.com/Kudaes/Split) - Apply a divide and conquer approach to bypass EDRs.
- [Fiber](https://github.com/Kudaes/Fiber) - Using fibers to run in-memory code.
- [EPI](https://github.com/Kudaes/EPI) - Threadless Process Injection through entry point hijacking.
- [RustHollow](https://github.com/Kudaes/RustHollow) - Inject a shellcode in a remote process using Process Hollowing.
- [Eagle-rs](https://github.com/memN0ps/eagle-rs) - Rusty Rootkit - Windows Kernel Rookit in Rust (Codename: Eagle).
- [Illusion-rs](https://github.com/memN0ps/illusion-rs) - Rusty Hypervisor - Windows UEFI Blue Pill Type-1 Hypervisor in Rust (Codename: Illusion).
- [Matrix-rs](https://github.com/memN0ps/matrix-rs) - Rusty Hypervisor - Windows Blue Pill Type-2 Hypervisor in Rust (Codename: Matrix)
- [Venom-rs](https://github.com/memN0ps/venom-rs) - Rusty Injection - Shellcode Reflective DLL Injection (sRDI) in Rust (Codename: Venom).
- [Arsenal-rs](https://github.com/memN0ps/arsenal-rs) - Rusty Arsenal - A collection of experimental Process Injection and Post-Exploitation Techniques in Rust.
- [Redlotus-rs](https://github.com/memN0ps/redlotus-rs) - Rusty Bootkit - Windows UEFI Bootkit in Rust (Codename: RedLotus).
- [Crabby](https://github.com/ebalo55/crabby) - WebShell for Red Teams, just easily.
- [Cerbero](https://github.com/zer1t0/cerbero) - Kerberos protocol attacker.
- [RustHound](https://github.com/NH-RED-TEAM/RustHound) - Active Directory data collector for BloodHound written in Rust.
- [Feroxbuster](https://github.com/epi052/feroxbuster) - A fast, simple, recursive content discovery tool written in Rust.
- [Offensive Rust](https://github.com/winsecurity/Offensive-Rust) - A collection of offensive security tools written in Rust.
- [OffensiveRust](https://github.com/trickster0/OffensiveRust) - Rust Weaponization for Red Team Engagements.
- [RustRedOps](https://github.com/joaoviictorti/RustRedOps) - RustRedOps is a repository dedicated to gathering and sharing advanced techniques and offensive malware for Red Team, with a specific focus on the Rust programming language.
- [RustScan](https://github.com/RustScan/RustScan) - The Modern Port Scanner.
- [Sniffglue](https://github.com/kpcyrd/sniffglue) - Secure multithreaded packet sniffer.
- [Goblin](https://github.com/m4b/goblin) - An impish, cross-platform binary parsing crate, written in Rust.
- [Ripgrep](https://github.com/BurntSushi/ripgrep) - Ripgrep recursively searches directories for a regex pattern while respecting your gitignore.
- [Rust for Malware Development](https://github.com/Whitecat18/Rust-for-Malware-Development) - Rust for malware development and for low level stuffs.
- [Moonwalk Back](https://github.com/Aditya-dom/moonwalk-back) - Cover your tracks during Linux Exploitation by leaving zero traces on system logs and filesystem timestamps.
- [Bore](https://github.com/ekzhang/bore) - bore is a simple CLI tool for making tunnels to localhost.
- [Ppfuzz](https://github.com/dwisiswant0/ppfuzz) - A fast tool to scan client-side prototype pollution vulnerability written in Rust.
- [Ripgen](https://github.com/resyncgg/ripgen) - Rust-based high performance domain permutation generator.
- [Pyscan](https://github.com/aswinnnn/pyscan) - Python dependency vulnerability scanner, written in Rust.
- [Freeze.rs](https://github.com/optiv/Freeze.rs) - Freeze.rs is a payload toolkit for bypassing EDRs using suspended processes, direct syscalls written in RUST.
- [Haylxon](https://github.com/pwnwriter/haylxon) - Blazing-fast tool to grab screenshots of your domain list right from terminal.
- [WStunnel](https://github.com/erebe/wstunnel) - Tunnel all your traffic over Websocket or HTTP2 - Bypass firewalls/DPI - Static binary available.
- [Hrekt](https://github.com/ethicalhackingplayground/hrekt) - A really fast http prober.
- [Qscan](https://github.com/0xor0ne/qscan) - Quick network scanner library.
- [Osintui](https://github.com/wssheldon/osintui) - OSINT from your favorite services in a friendly terminal user interface - integrations for Virustotal, Shodan, and Censys.
- [Skanuvaty](https://github.com/Esc4iCEscEsc/skanuvaty) - Dangerously fast DNS/network/port scanner
- [Noseyparker](https://github.com/praetorian-inc/noseyparker) - Nosey Parker is a command-line program that finds secrets and sensitive information in textual data and Git history.
- [Rusty Hog](https://github.com/newrelic/rusty-hog) - A suite of secret scanners built in Rust for performance. Based on TruffleHog.
- [Lorsrf](https://github.com/knassar702/lorsrf) - Fast CLI tool to find the parameters that can be used to find SSRF or Out-of-band resource load.
- [Scrying](https://github.com/nccgroup/scrying) - A tool for collecting RDP, web and VNC screenshots all in one place.
- [X8](https://github.com/Sh1Yo/x8) - Hidden parameters discovery suite
- [Findomain](https://github.com/Findomain/Findomain) - The fastest and complete solution for domain recognition. Supports screenshoting, port scan, HTTP check, data import from other tools, subdomain monitoring, alerts via Discord, Slack and Telegram, multiple API Keys for sources and much more.
- [Legba](https://github.com/evilsocket/legba) - A multiprotocol credentials bruteforcer / password sprayer and enumerator.
- [Rust Syscall](https://github.com/janoglezcampos/rust_syscalls) - Single stub direct and indirect syscalling with runtime SSN resolving for windows.
- [GhostDriver](https://github.com/BlackSnufkin/GhostDriver) - GhostDriver is a Rust-built AV killer tool using BYOVD.
- [NovaLdr](https://github.com/BlackSnufkin/NovaLdr.git) - Threadless Module Stomping In Rust with some features (In memory of those murdered in the Nova party massacre).


## Useful Libraries

- [Litcrypt](https://github.com/anvie/litcrypt.rs) - A Rust compiler plugin to encrypt string literal at compile time.
- [LibAFL](https://github.com/AFLplusplus/LibAFL) - Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no_std, ...

## Contributing

Found an awesome package, article, blog, video etc.? Send me a pull request! Just follow the [guidelines](/CONTRIBUTING.md). Thank you!

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
