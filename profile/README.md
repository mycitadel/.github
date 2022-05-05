<big>**MyCitadel is a suite of software, hardware and Internet services focused on digital individual sovereignty and privacy[^ack].**</big>

### MyCitadel Wallet

The main component of the suite is Bitcoin, Lightning and RGB wallet. It enables real-world usage of **bitcoin, digital assets and bitcoin finance (#BiFi)**, including reliable hodling (with inheritance options), corporate & organization use, current accounts with instant Lightning payments, bitcoin staking (through routing, storage, computing, DEX, liquidity pool services provided by Lightning node). Technically it can work with *single- and multisig setups*, based on *hardware, air-gaped, cold and server-side hot key storage*, involving arbitrary complex time-lock scripts (with *miniscript*) and wide interoperability (because of use of *wallet descriptors*). MyCitadel is a taproot-enabled wallet from day one, including multisig- and script-based taproot.

MyCitadel Wallet was the first consumer-facing wallet supporting taproot scripts with timelocks & miniscript, and the first wallet working with [RGB smart contracts](https://github.com/RGB-WG).

The wallet suite includes the following existing and future consumer-facing apps:
- [Desktop app](https://github.com/mycitadel/mycitadel-desktop) for Linux, Windows and MacOS;
- [Mobile app for Apple platforms](https://github.com/mycitadel/mycitadel-apple): MacOS, iOS, iPadOS, which in the future will be extended with watchOS support;
- Android mobile app (work in progress);
- **[MyCitadel Node](https://github.com/mycitadel/mycitadel-node)** - server-side daemon supporting operations in company/organization/multi-device setups and used for running Lightning-based services;
- **MyCitadel Box** - personal server appliance running MyCitadel Node;
- **MyCitadel Cloud** - subscription-based cloud service providing MyCitadel Node as a private cloud virtual machine;

Additionally, wallet developers may use **[Citadel Runtime](https://github.com/mycitadel/citadel-runtime)** - a rust-based library providing taproot-, miniscript-, multisig-, lightning & RGB wallet; and languague-specific wrappers for using this library on different platforms: C ([libcitadel](https://github.com/mycitadel/libcitadel)), Swift for iOS/MacOS ([CitadelKit](https://github.com/mycitadel/mycitadel-node)). Other language wrappers are work in progress (CitadelJ for Android, desktop & server-side Java, CitadelWASM, CitadelJS for JavaScriptm PyCitadel for Python).


### MyCitadel Contacts

Web-of-Trust contact managing application using bitcoin & RGB-based digital identity and Lightning network-based key servers instead of legacy WoT infrastructure. Work in progress.


### MyCitadel Chat

End-to-end ecnrypted chats over Lightning network, using lightning & RGB payments, personal lightning-node-based multi-device synchronization and WoT-based identity & contact management.


[^ack]: MyCitadel suite is based on the [LNP/BP Standards Association](https://github.com/LNP-BP) libraries & products, including RGB, Bifrost and Storm protocols; RGB Node, BP Node and LNP Node software.
