## 👤 About BitMorphX – GitHub Profile

I am **BitMorphX** – an advanced independent researcher and developer specializing in open-source tools for Bitcoin key analysis, address derivation logic, and blockchain architecture exploration. With over a decade of experience (since 2013), I focus on cryptographic structure, key entropy, derivation patterns, and cross-chain validation logic across Bitcoin, Ethereum, BSC, Polygon, Solana, and other modern networks.

My work is driven by research precision, algorithmic transparency, and a deep respect for ethical boundaries in blockchain development. Every tool I publish is designed for educational, analytical, and secure research purposes. I do not release anything that could facilitate misuse or real-world harm.

**“BitMorphX” is not just a name – it’s a research philosophy.** It represents methodical analysis, cryptographic integrity, and a commitment to demystifying blockchain internals.

**I support reproducible research and am open to collaboration with academic institutions or independent analysts.**

## 🧪 Public Tools by BitMorphX

A collection of open-source tools focused on Bitcoin address logic, key format conversions, and blockchain observation. All tools are designed for **educational**, **analytical**, and **research purposes only**. Every utility runs fully offline unless otherwise specified and adheres to strict ethical standards.

---

### 🅰️ BASE64 Decoder
Decodes Base64-encoded private keys into complete Bitcoin key data:
- Compressed & uncompressed Bitcoin addresses  
- WIF formats  
- Public & private keys in HEX  
Includes color-coded terminal output for clarity.

---

### 🅱️ Bitcoin Base58 to HEX Decoder
Decodes Bitcoin Base58 addresses into their raw HEX structure. Extracts:
- Version prefix  
- `hash160`  
- Checksum (and verifies it)  
Useful for understanding how Base58Check works internally.

---

### 🅱️ Bitcoin Key Explorer
Offline tool that converts any integer into a Bitcoin private key and generates:
- Public key (HEX)  
- WIF (compressed & uncompressed)  
- Bitcoin addresses  
Includes optional Base58 decoding. Great for theoretical analysis and learning.

---

### 🅱️ bitpeek – Bitcoin Address Analyzer
CLI and Flask-based address analyzer that:
- Verifies address format and checksum  
- Extracts `hash160`  
- Calculates entropy via symbol frequency  
Dual-mode operation (CLI + GUI), designed for structural address insight.

---

### 🅱️ BTC Address Analyzer
Educational CLI tool that:
- Decodes Bitcoin Base58Check addresses  
- Validates version, payload, checksum  
- Detects address type (P2PKH/P2SH, mainnet/testnet)  
Excellent for Bitcoin learners or script developers.

---

### 🅱️ BTC Address Sorter – By Type
Efficient high-speed sorter for massive BTC address lists. Classifies addresses by type:
- P2PKH (Legacy)  
- P2SH (SegWit)  
- Bech32 (Native SegWit)  
Supports 50M+ address runs, uses multiprocessing, and shows real-time progress.

---

### 🅲 Crypto Arbitrage Tracker Alert
Terminal-based app that monitors prices from:
- Binance  
- Coinbase  
- Kraken  
Highlights arbitrage opportunities >1% and flags abnormal spreads >50%. Auto-refreshes per batch and displays clean live stats.

---

### 🅷 HEX to WIF Converter
Multi-threaded converter that transforms HEX private keys into:
- Compressed WIF  
- Uncompressed WIF  
Reads from file and outputs results to text files. Includes progress bar and terminal coloring for usability.

---

### 🅿️ Public Key Bit Sorter
Analyzes uncompressed ECDSA public keys (format `04...`) and groups them by entropy/bit strength using four methods:
1. Classic – Total HEX bits  
2. Dynamic – Real binary X+Y lengths  
3. Legacy – Max HEX X or Y  
4. Binary-Max – Max binary bit length  
Useful for anomaly detection or weak key scanning research.

---

### 🅿️ Public Key to Bitcoin Addresses
Converts uncompressed public keys into:
- Compressed public keys  
- Corresponding Bitcoin addresses (both formats)  
Implements Base58Check logic. Offers CLI-based interaction with colorized output.

---

### 🆃 Tokens Contract Scanner
Real-time tracker for newly created Ethereum and Polygon token contracts. Features:
- Live data via Mobula API  
- Colorized terminal output  
- Logs saved to `eth_new_contracts.txt` and `pol_new_contracts.txt`  
Auto-refresh every 0.5–3 seconds. Ideal for analysts and developers.

---

### 🆆 WhaleScope
Live Ethereum mempool monitor using Infura WebSocket. Detects:
- ETH transfers ≥ 50 ETH  
- Token swaps on Uniswap & SushiSwap  
Extracts token data from smart contracts and logs large transactions.

---

## ⚠️ Disclaimer

All tools listed above are developed and published strictly for **educational, scientific, and ethical research purposes**.  
They are intended for **offline use only** and do not interact with third-party systems unless explicitly mentioned.

> BitMorphX does **not** support or condone any illegal activity or misuse of these tools.  
> Every user is fully responsible for their own usage and compliance with local laws and blockchain network rules.

All public repositories are licensed under the **Apache 2.0 License**, ensuring transparency, openness, and responsible reuse.

---

## 🛡️ ETHICS

**BitMorphX always follows ethical principles:**

- All tools are created for **educational and scientific purposes**.
- Tools that could be misused or are potentially harmful are **not publicly distributed**.
- Each project is **local and does not connect to third-party systems**.
- **No testing on real users' addresses without consent**.

> "Ethics begin with responsibility, and BitMorphX chooses understanding over exploitation."

**⛐ Each user assumes full responsibility for any use of the tools.**  
BitMorphX accepts no liability for illegal or harmful actions performed using the provided code.

See [ETHICS.md](./ETHICS.md) for the full statement on responsible and ethical use of these tools.  
See [NOTICE](./NOTICE) for attribution, licensing intent, and author rights.

## ⚖️ Licensing

All projects listed under this account are governed by **open-source or source-restricted licenses**, depending on their purpose, sensitivity, and intended usage.  
Licenses are chosen with care to promote transparency, responsibility, and ethical research.

---

### 🔓 Public Projects

All publicly available tools are licensed under:

- **[Apache License 2.0](./LICENSE)**  
A permissive open-source license allowing use, modification, and distribution, provided attribution and license terms are respected.

---

### 🔐 Private & Restricted Projects

Private tools that are not publicly shared may fall under one of the following licenses:

- **[Apache License 2.0](./LICENSE)** – for tools intended solely for research, education, or structural analysis  
- **[BUSL-1.1 (Business Source License)](./BUSL-1.1_LICENSE)** – applied to limited-distribution tools with defined conditions for commercial use  
- **[SCRL-CUSTOM License](./SCRL-CUSTOM_LICENSE)** – a specialized license for sensitive cryptographic analysis tools; tailored per project

---

> ⚠️ **Important:** Each user is fully responsible for reviewing and complying with the license terms of each individual project.  
> Tools with restricted licensing may not be used for commercial or automated purposes without explicit permission.

---

Built with respect for privacy, freedom, and individual accountability.

## 🔐 Private Tools by BitMorphX

This is a curated collection of non-public tools designed for cryptographic analysis, key structure evaluation, format conversion, and entropy measurement. All tools are intended strictly for **offline**, **local**, and **educational use** only.

---

### 🧮 ALL DISTANCES V1 / V2 / V3
A set of tools that compare generated private keys to a target Bitcoin public key using Hamming, Euclidean, Heuristic, and Levenshtein distance metrics. Ideal for vanity address exploration and scoring research.

---

### 🧠 BITCOIN PUBLIC KEY CONVERTER
Converts public keys between compressed and uncompressed formats. Shows RIPEMD‑160 hashes and Base58Check Bitcoin addresses. Supports batch mode and terminal output.

---

### 🧠 BITCOINCORE ADDRESS EXPLORER / V1 / V2
Connects to a local Bitcoin Core node and scans blocks sequentially. Extracts public keys, compressed formats, and legacy addresses with UTXO info. Data is saved for research and pattern discovery.

---

### 🔐 BTC ADDRESS GENERATOR
Multi-core Bitcoin address generator. Outputs compressed and uncompressed keys, WIF formats, and structured results in aligned tables. Suitable for experimental workflows.

---

### 📐 EUCLIDEAN DISTANCE V1
Calculates Euclidean distance between elliptic curve public key coordinates (X, Y) and a specified target key. Useful for ranking proximity in key space.

---

### 🔐 EXTREME IX – HEX → WIF / ETH Converter
Converts HEX-format private keys into:
- Bitcoin (WIF, P2WPKH, hybrid)
- Ethereum (Keccak256-based)  
Supports multiprocessing and generates structured `.txt` outputs.

---

### 🧪 HEX MUTATION GENERATOR / EXTREME / BY SYMBOLS
Generates all 1-symbol mutations of 64-character HEX private keys. Designed for fuzzing, entropy exploration, and symbol-change impact analysis. Uses multiprocessing and outputs clean mutation files.

---

### 🧠 HAMMING DISTANCE V1 / V2 / V3 / PUBKEYS
Compares generated public keys (from private keys) to a target RIPEMD-160 hash using bit-level Hamming distance. Results are scored, sorted, and saved for analysis.

---

### 📐 HASHCLASH – Hash Prefix Matcher
Analyzes prefix similarity in RIPEMD160(SHA256(pubkey)) hashes between generated keys and a target. Scores based on matching byte count from the beginning of the hash.

---

### 🧬 KEY ORBIT
Random key generator with pattern detection logic. Scans for entropy anomalies, repeated structures, palindromes, and symmetry in Bitcoin hashes and addresses. Supports visual exports.

---

### 🧮 MANHATTAN DISTANCE V1
Measures Manhattan distance between (x, y) coordinates of ECDSA public keys and a target public key. Outputs sorted match results using multiprocessing.

---

### 🧠 MNEMONIC GENERATOR – BIP39 Phrase Generator
Educational tool that generates BIP39 12-word phrases and derives Bitcoin and Ethereum keys.  
> ⚠️ For testing purposes only. **Do not use real phrases for storage or value.**

---

### 🔍 VANITY PREFIX GEN EXTREME
Multithreaded Bitcoin address generator for custom vanity prefixes. Supports dynamic private key generation and WIF export. Logs matching results with full key details.

---

### 🔍 VANITY RIMPED
Compares multiple public key hashes (RIPEMD-160) to a primary key. Calculates % match, detects recurring hex patterns, and exports results to structured files.

---

## 🧬 My Research Direction

### 🔍 Origins (2010–2013)

**My research began by investigating vulnerabilities in early Bitcoin implementations:**

1. **Weak private keys** – reused or insecure sequences  
2. **Incorrect BIP32/BIP44 paths** – repeatable or predictable addresses  
3. **Public key reconstruction** – sometimes possible via scriptSig  
4. **Overly exposed APIs** – insecure analytical capabilities

This led to the creation of **local, secure tools** for research and educational use.

**My tools now support:**
- address generation principles
- derivation path analysis (BIP32, BIP44, BIP49, BIP84)
- script analysis (e.g., scriptSig, asm)
- asynchronous data processing

**📈 Metrics used:**
- **Hamming distance** – for structural similarity
- **Levenshtein** – for typo tolerance testing
- **Euclidean algorithm** – for indexing and mathematical analysis
- **Heuristics** – for risk and cluster detection
- **Derivation path logic** – for structural wallet analysis

I also explore private key reconstruction using ECDSA parameters (`r`, `s`, `z`) and historical address conversion methods (`asm`, `scriptSig`).

## 🚀 QuantumChain (thinking beyond classical cryptography)

**Before we enter the quantum era, it's important to understand stable legacy systems.**

Example: **Bytecoin (BCN)** – the first CryptoNote-based network. Together with Monero (XMR), they serve as long-lasting examples of value and security.

**🔹 I also analyze:**
- CryptoNote coins (BCN, XMR)
- DAG networks (Nano, IOTA)
- Experimental blockchains with alternative derivation models

**QuantumChain** is a philosophy, not a product. It is based on:
- address structure,
- key reproducibility,
- script behavior,
- derivation integrity.

## 🎁 Support

★ **Bitcoin (BTC)**  
`1MorphXyhHpgmYSfvwUpWojphfLTjrNXc7`

★ **Monero (XMR)**  
`86VAmEogaZF5WDwR3SKtEC6HSEUh6JPA1gVGcny68XmSJ1pYBbGLmdzEB1ZzGModLBXkG3WbRv12mSKv4KnD8i9w7VTg2uu`

★ **Dash (DASH)**  
`XtNuNfgaEXFKhtfxAKuDkdysxUqaZm7TDX`

**We also value early privacy coins such as:**  
★ **Bytecoin (BCN)**  
`bcnZNMyrDrweQgoKH6zpWaE2kW1VZRsX3aDEqnxBVEQfjNnPK6vvNMNRPA4S7YxfhsStzyJeP16woK6G7cRBydZm2TvLFB2eeR`

🙏 *Thank you for supporting independent research and ethical technology.*

---

**Created with dedication to education, blockchain exploration, and ethical research.**  
*“I morph bits, not to break, but to understand.” — BitMorphX*

**💼 Open to research collaborations, part-time freelance, or blockchain security audits.**

## 📡 Contact

- 🔗 GitHub Profile: [https://github.com/BitMorphX](https://github.com/BitMorphX)  
- ✉️ Email: [BitMorphX@proton.me](mailto:BitMorphX@proton.me)  
- 💬 Telegram: [https://t.me/BitMorphX](https://t.me/BitMorphX)

---

🕒 Last updated: 2025-07-17

© BitMorphX – All rights reserved.
