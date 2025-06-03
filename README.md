# Crypto Recovery: Unleash the Power of Cryptocurrency Recovery with WalletGen

**Tired of lost crypto?**  **WalletGen** is your go-to, open-source solution for recovering access to your **Bitcoin (BTC)**, **Ethereum (ETH)**, **BNB**, **Polygon (MATIC)**, and other **EVM-compatible wallets**. This isn't just a wallet generator; it's a high-speed recovery tool built for efficiency, utilizing a robust C++ engine to give you an edge in the hunt for your lost digital assets.

<!--
Meta description:
Recover lost cryptocurrency with WalletGen, a fast, open-source tool for Bitcoin, Ethereum, and EVM chains. Features seed phrase brute-forcing, wallet generation, and real-time balance checks. Download now!
-->

## Quick Navigation
- [Unveiling the Mechanism: How WalletGen Operates](#how-it-works)
- [Why Choose WalletGen for Cryptocurrency Recovery?](#why-walletgen)
- [Key Features: What Makes WalletGen Stand Out](#features)
- [Getting Started: Download and Installation](#how-to-start)
- [Supercharge Your Search: Database Download](#download-and-use-database-for-more-speed)
- [Found a Wallet! Next Steps](#the-program-found-a-wallet--whats-next)
- [Recovering Your Bitcoin: A Step-by-Step Guide](#recovery-your-bitcoin-wallet)
- [Success Stories: My Personal Discoveries](#my-finds)
- [Frequently Asked Questions (FAQ)](#-frequently-asked-questions-faq)
- [Building WalletGen: Project Compilation](#building-the-project)
- [Support the Project: Donate](#donate)

[![platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20Android-blue)](https://github.com/tony-dev1/wallets-finder/releases/tag/walletgen)
![build](https://img.shields.io/badge/build-passing-brightgreen)
![discord](https://img.shields.io/badge/discord-tonydevbtc-blue.svg?logo=discord&label=discord)
[![x](https://img.shields.io/badge/@tonydevbtc-black.svg?logo=x)](https://x.com/tonydevbtc)

<p align="center">
    <img width="1000" alt="cryptocurrency recovery" title="WalletGen wallet generator" height="460" src="/themes/static.webp" />
</p>

⚠️ **Important Disclaimer**:  WalletGen is crafted for research and educational purposes only.  It is not designed for unauthorized access or any malicious activity. Always use this tool responsibly and only on wallets that you legally own or have permission to access.

## How It Works

At its core, WalletGen leverages the power of [BIP39](https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki), [BIP44](https://github.com/bitcoin/bips/blob/master/bip-0044.mediawiki), and [Bech32](https://en.bitcoin.it/wiki/Bech32) for Bitcoin wallet generation.  For EVM-based chains like Ethereum, it uses the robust [Keccak256](https://emn178.github.io/online-tools/keccak_256.html) hashing algorithm.

The software works by generating potential wallet addresses and then verifying their balance. This is accomplished either through real-time balance checks against public blockchain explorers or, more efficiently, by comparing generated addresses against pre-existing databases of known, funded addresses.   The C++ underpinnings of WalletGen gives it a significant speed advantage over Python-based alternatives, with processing dependent primarily on your CPU and GPU.

## Why WalletGen?

Why settle for slow brute-force methods? **WalletGen** is engineered in C++ and highly optimized to tap into the power of your CPU and GPU. It delivers up to **10x faster** performance than many alternatives. Whether you're on a quest to recover lost wallets, validating private key spaces, or attempting to reclaim your own lost holdings, WalletGen puts you in control with unparalleled efficiency and enhanced security.

## Features

- **Rapid Cryptocurrency Wallet Generation**:  WalletGen supports the creation of individual wallets for Bitcoin, Ethereum, BNB, MATIC, and many other cryptocurrencies.
- **Balance Discovery Through Brute-Force**:  Utilizing advanced brute-force techniques, WalletGen lets you search for wallets with existing balances across both the Bitcoin network and EVM chains.
- **Algorithm Support**:  Built-in support for Keccak256 for EVM wallets and the BIP39, BIP44, and Bech32 algorithms for Bitcoin ensures broad compatibility.
- **Database Integration**:  Optimize your search speed with downloadable databases to expedite the search for wallets with a balance, potentially reducing search times.
- **High-Speed Performance**:  WalletGen harnesses the power of your CPU and GPU, unlocking peak performance for unparalleled efficiency.
- **Bitcoin Wallet Recovery**:  Effortlessly recover your Bitcoin wallet using the mnemonic seed phrase.

## Supported Blockchains

- Bitcoin (BTC)
- Ethereum (ETH)
- Binance Smart Chain (BNB)
- Any EVM-compatible chain

# Demo

<p align="center">
    <img width="1000" height="460" alt="WalletGen search lost bitcoin wallets on Windows Demo" title="WalletGen search lost bitcoin wallets on Windows" src="/themes/open.webp" />
</p>


<p align="center">
    <img width="1000" height="460" alt="WalletGen search lost bitcoin wallets on Linux Demo" title="WalletGen search lost bitcoin wallets on Linux" src="/themes/dark.webp" />
</p>

# How to start

## Windows 
- Download [Release](../../releases) 
- Unpack anywhere
- Run `WalletGen.exe`

Or Just Download [Installer](../../releases)

## Linux (x86-64bit)

Use wget 
or download [Release for Linux](../../releases) 







## How to Search for Lost Bitcoin & Ethereum Wallets with Balance

**Wallet Gen** provides you with two primary methods to search for crypto wallets with funds, utilizing the brute-force technique.

### Bitcoin (BTC) Wallet Search:

*   Initiate the process by pressing key `3` in the menu, or run the `start_search_btc.bat` batch file, to launch an internet-based search for Bitcoin wallets. This method may take slightly longer as it queries wallet balances in real-time using blockchain explorers.
*   For a faster approach, select key `6` to scan Bitcoin wallets using the pre-built database.  This method is notably faster as it compares generated wallets against a known database of addresses with existing balances.

### EVM Wallet (Ethereum, BNB, MATIC, etc.) Search:

*   Press key `5` or run `start_search_evm.bat` to scan for EVM wallets through internet-based balance checks. This method verifies wallet balances in real-time through blockchain explorers.
*   For quicker scans, select key `6` to scan EVM wallets using a downloaded database. This method leverages a pre-existing address database, improving speed and efficiency.

### Performance Considerations:

*   The speed of your search is significantly influenced by your hardware, especially your graphics card (GPU). For the best performance and increased chances of finding a wallet with a balance, consider running multiple instances of the program (1 to 4 instances) simultaneously, depending on your system's capabilities.

By utilizing a database, you drastically streamline the search, eliminating the need for repeated blockchain queries for every generated wallet, leading to increased efficiency.

## The Program Found a Wallet — What’s Next?

Once a wallet with a balance is discovered, the program will:
*   **Halt** immediately.
*   **Display** the complete wallet details directly within the console.
*   **Save** all the relevant data into the ``found_wallets.txt`` file.

### Accessing Your Funds

1.  Import the **mnemonic seed phrase** of the discovered wallet into any compatible crypto wallet (such as Metamask, Trust Wallet, or Electrum).
2.  Once restored, you can then transfer the funds to your preferred wallet.

>  If your search is successful, consider sharing a portion of the found balance with the project creator as a gesture of thanks!

## Recovery Your Bitcoin Wallet

WalletGen is designed to assist you in recovering your Bitcoin wallet using the seed phrase (mnemonic phrase). You can input either the complete seed phrase or utilize wildcard characters to search for missing words.

### Process Breakdown

#### Searching for Missing Words:

If you're missing words in your seed phrase, replace those missing words with an asterisk (*). WalletGen will then search through all the possible word combinations in those spots, to hopefully find the correct seed phrase and restore access to the wallet.

#### Entering the Full Seed Phrase:

If you possess the complete 12-word seed, enter it accurately, separating words with spaces. WalletGen will generate different address types (Legacy, SegWit, P2SH) and verify their balances.

![recovery](/themes/shortcut.webp)

### Key Guidelines

*   Seed phrases must contain precisely 12 words.
*   Use the * symbol exclusively to represent missing words.
*   Be aware that searching for missing words can be time-intensive, especially if multiple words are missing.
*   Upon successfully recovering a wallet with a balance, the program will automatically halt and save the pertinent data.

## My Finds

![mywallet](/themes/simple.webp)

I've personally had the success of recovering two BTC wallets, both with a balance. The first had a balance of 0.000032 BTC, and the second contained 0.0528 BTC, equivalent to about $4800 at the time of discovery.  
Here's the link to the wallet: [bc1qk3m62hx2hh5mhvc0tj45f9xflzcnu0sur3rvay](https://mempool.space/address/bc1qk3m62hx2hh5mhvc0tj45f9xflzcnu0sur3rvay).

<p align="center">
    <img width="1000" height="460" alt="WalletGen found first lost bitcoin wallet" title="WalletGen found first lost bitcoin wallet" src="/themes/heap.webp" />
</p>

### Latest Find 4/9/2025

After a week of continuous searching, I discovered a [wallet](https://mempool.space/address/bc1q29c5m3w4jxtsj4vcd2ccw4t68xm8m7vs5vytu0) with 0.25 bitcoin (approximately $19k). This discovery is my biggest find yet.

![image](/themes/executable.webp)

## New Find 5/5/2025

[bc1qpm0k3kcmthwsa4zseh33g3hl7eju8u8nkt83kp](https://mempool.space/address/bc1qpm0k3kcmthwsa4zseh33g3hl7eju8u8nkt83kp)

![image](/themes/plan.webp)


## Building the Project

1.  Open the project file (`CryptoWalletGen.sln`) in Visual Studio or any compatible C++ compiler.
2.  Make sure to install and configure the necessary dependencies to compile the project.

```cmd
> git clone https://github.com/microsoft/vcpkg
> .\vcpkg\bootstrap-vcpkg.bat
> .\vcpkg\vcpkg integrate install
> .\vcpkg\vcpkg install openssl:x64-windows
```

3.  Start building the project.

## 🔍 Frequently Asked Questions (FAQ)

### ❓ Where can I download WalletGen?
You can find the latest WalletGen release on the [release download page](../../releases).

### ❓ How do I download a database of known addresses with balance?
The current database can be found on the [release page](../../releases).

### ❓ Can WalletGen help recover a lost Bitcoin wallet?
Yes, WalletGen can potentially help you recover lost Bitcoin wallets through brute-force seed phrase generation and comparing generated addresses against a database.

### ❓ Is WalletGen a seed phrase generator?
Absolutely. WalletGen has the functionality to generate **BIP39 seed phrases**, and it derives wallets for Bitcoin, Ethereum, and other EVM chains.

### ❓ Does database searching require an internet connection?
No, you do not need an internet connection while searching through the database, as the balance information is already known.

### ❓ Can I find Ethereum wallets with a balance?
Yes, WalletGen allows you to scan for **Ethereum wallets with a balance**, using brute-force techniques and a database of known addresses.

### ❓ Is WalletGen legal to use?
WalletGen is made solely for **educational and research purposes**. It is only permissible to use it on wallets you own or have explicitly been given permission to access.

## Todo
1. Search for missing words in a seed phrase. - **Done!**

## Contribute

We welcome contributions! If you have suggestions, bug reports, or would like to contribute to the codebase, please submit a pull request.

## Donate

If you're lucky enough to find a wallet with a balance, I encourage you to consider sending a small portion as a token of appreciation. Your support motivates me to continue improving the program and making it better!

**BTC:** bc1qeyrshy5ntsguwxe9m8tp2x2yqhddz7ymkj44h9

**ETH:** 0x76c2E75B92Eb340f01B378e332FC7d8954893693

## Credits
This project uses code from the [Trezor project](https://github.com/trezor/trezor-crypto). The code is licensed under the MIT License.

## License
This project is licensed under the [MIT License](/LICENSE)