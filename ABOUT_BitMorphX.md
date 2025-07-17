<p align="center">
  <img src="assets/ABOUT_BitMorphX.png" alt="About BitMorphX Cover" width="100%" />
</p>

## 👤 About BitMorphX – GitHub Profile

I am **BitMorphX** – an advanced independent researcher and developer specializing in open-source tools for Bitcoin key analysis, address derivation logic, and blockchain architecture exploration. Since 2013, I have focused on cryptographic structure, entropy modeling, derivation behavior, and cross-chain address logic across Bitcoin, Ethereum, BSC, Polygon, Solana, and other modern blockchain networks.

My work is guided by algorithmic transparency, deep structural insight, and a strict ethical framework. Every tool I publish is created for **educational**, **scientific**, and **analytical** purposes – with safeguards in place to prevent misuse. I do **not** release anything that could facilitate real-world harm.

**“BitMorphX” is not just a name – it’s a research philosophy.**  
It stands for clarity in cryptography, respect for blockchain architecture, and the pursuit of structural truth.

---

## 👁️ Vision

To illuminate blockchain internals and cryptographic structure through transparent, reproducible, and ethical research.

---

## 🔐 Core Principles

- **Ethics over Exploits**: Tools are built with safeguards; no real-user harm is ever acceptable.  
- **Privacy over Popularity**: I prioritize trust and integrity above fame or virality.  
- **Transparency in Logic**: Every algorithm can be inspected and verified.  
- **Offline by Default**: All tools are local unless explicitly stated otherwise.

---

## 🧪 Public Tools by BitMorphX

All public tools run **offline** (unless stated) and are made for research, analysis, and education only. Each one is licensed under [Apache License 2.0](./LICENSE).

### 🅰️ [BASE64 Decoder](https://github.com/BitMorphX/base64_decoder)  
Decodes Base64-encoded private keys into Bitcoin WIFs, HEX keys, and addresses.  
Color-coded terminal output for clarity.

### 🅱️ [Bitcoin Base58 to HEX Decoder](https://github.com/BitMorphX/btc_base58_decoder)  
Decodes Base58Check Bitcoin addresses into raw HEX.  
Verifies version, `hash160`, and checksum.

### 🅱️ [Bitcoin Key Explorer](https://github.com/BitMorphX/btc_key_explorer)  
Converts any integer into private key, public key, and addresses.  
Optional Base58 decoding and full WIF export.

### 🅱️ [bitpeek – Bitcoin Address Analyzer](https://github.com/BitMorphX/bitpeek)  
Checks address validity, entropy, and extracts hash160.  
Dual-mode (CLI + Flask GUI).

### 🅱️ [BTC Address Analyzer](https://github.com/BitMorphX/btc_address_analyzer)  
Educational decoder of Bitcoin addresses.  
Detects type (P2PKH, P2SH), mainnet/testnet flags, checksum validation.

### 🅱️ [BTC Address Sorter – By Type](https://github.com/BitMorphX/btc_address_sorter)  
High-speed address sorter (P2PKH, P2SH, Bech32).  
Multiprocessing-enabled. 50M+ addresses supported.

### 🅲 [Crypto Arbitrage Tracker Alert](https://github.com/BitMorphX/crypto_arbitrage_alert)  
Monitors live token prices across Binance, Kraken, and Coinbase.  
Detects arbitrage >1%, flags spreads >50%.

### 🅷 [HEX to WIF Converter](https://github.com/BitMorphX/hex_to_wif_converter)  
Converts HEX private keys to WIF formats.  
Reads from file, outputs with coloring and progress.

### 🅿️ [Public Key Bit Sorter](https://github.com/BitMorphX/public_key_bit_sorter)  
Analyzes uncompressed pubkeys and groups by entropy using 4 different scoring systems.

### 🅿️ [Public Key to Bitcoin Addresses](https://github.com/BitMorphX/public_key_to_btc_address)  
Converts public keys into compressed formats and full Bitcoin addresses.

### 🆃 [Tokens Contract Scanner](https://github.com/BitMorphX/tokens_scanner)  
Tracks new Ethereum and Polygon contracts in real-time via Mobula API.  
Saves logs locally and shows color-coded terminal updates.

### 🆆 [WhaleScope](https://github.com/BitMorphX/whalescope)  
Live Ethereum mempool monitor via WebSocket.  
Detects large ETH transfers and Uniswap/SushiSwap swaps.

---

## 🔐 Private Tools by BitMorphX

Private tools are **offline-only**, shared only with trusted researchers or sponsors. Each tool follows **strict ethical principles** and may be licensed under **BUSL-1.1** or **SCRL-CUSTOM**, depending on sensitivity.

---

### 🧮 ALL DISTANCES V1 / V2 / V3  
Compares private keys to a target public key using:  
- Hamming distance  
- Levenshtein distance  
- Euclidean distance  
- Heuristic scoring  

---

### 🧠 BITCOIN PUBLIC KEY CONVERTER  
Batch converter for public keys. Outputs:  
- Compressed/uncompressed forms  
- RIPEMD-160 hash  
- Base58Check Bitcoin address  

---

### 🧠 BITCOINCORE ADDRESS EXPLORER (V1 / V2)  
Connects to local Bitcoin Core node and scans block data to extract:  
- Public keys  
- Legacy addresses  
- UTXO info for pattern research  

---

### 🔐 BTC ADDRESS GENERATOR  
Multithreaded Bitcoin address generator. Outputs:  
- Private keys (HEX)  
- WIF (compressed & uncompressed)  
- Corresponding addresses  

---

### 📐 EUCLIDEAN DISTANCE V1  
Measures proximity between public keys using (X, Y) coordinates and Euclidean distance.

---

### 🔐 EXTREME IX – HEX → WIF / ETH CONVERTER  
Converts HEX-format private keys to:  
- Bitcoin WIFs (Legacy, SegWit)  
- Ethereum addresses  
Includes multiprocessing + file output.

---

### 🧪 HEX MUTATION GENERATOR / EXTREME  
Generates all one-symbol mutations of 64-character HEX keys. Useful for:  
- Entropy analysis  
- Fuzz testing  
- Symbolic drift tracking  

---

### 🧠 HAMMING DISTANCE V1 / V2 / V3 / PUBKEYS  
Compares RIPEMD160(pubkey) hashes to a target hash using bit-level Hamming distance.  
Results are scored, sorted, and exported.

---

### 📐 HASHCLASH – HASH PREFIX MATCHER  
Compares hash prefixes (RIPEMD160) between generated and target public keys.  
Ranks matches based on shared leading bytes.

---

### 🧬 KEY ORBIT  
Explores entropy anomalies, palindromes, and repeating patterns in keyspace.  
Supports visualization and analysis logs.

---

### 🧮 MANHATTAN DISTANCE V1  
Calculates Manhattan distance between public key coordinates.  
Useful for public key proximity ranking.

---

### 🧠 MNEMONIC GENERATOR – BIP39  
Generates 12-word mnemonic phrases and derives ETH/BTC addresses.  
> ⚠️ For testing and research only. **Do not use with real funds.**

---

### 🔍 VANITY PREFIX GEN EXTREME  
Multithreaded vanity address generator with custom prefix targeting.  
Logs full key details upon match.

---

### 🔍 VANITY RIMPED  
Compares multiple RIPEMD160(pubkey) hashes against a reference.  
Scores percent match, detects recurring byte patterns, and saves results.

---

## ⚠️ Disclaimer

All tools are made **strictly for educational, scientific, and ethical research**.  
BitMorphX does **not** support or condone illegal activity. Every user is solely responsible for their own actions.

> Tools must not be used to target real addresses, users, or assets without consent.  
> Respect laws, blockchain terms, and ethical boundaries.

---

## 🛡️ ETHICS

- No tools are built to attack, exploit, or endanger users.  
- All public tools are **offline-first**, transparent, and research-focused.  
- Tools with misuse potential remain **private or restricted**.  
- **No scanning or testing against live users’ addresses without permission.**

> *"Ethics begin with responsibility, and BitMorphX chooses understanding over exploitation."*

See [ETHICS.md](./ETHICS.md) and [NOTICE](./NOTICE) for full ethical declaration and license intent.

---

## ⚖️ Licensing

### 🔓 Public Repos  
All public tools: [Apache License 2.0](./LICENSE) – free use, reuse, modification with attribution.

### 🔐 Private Tools  
Licensed under:  
- [Apache 2.0](./LICENSE) – for educational or structural tools  
- [BUSL-1.1](./BUSL-1.1_LICENSE) – for controlled, non-commercial use  
- [SCRL-CUSTOM](./SCRL-CUSTOM_LICENSE) – for sensitive cryptographic research tools

> ⚠️ Each user is responsible for reviewing individual license terms.  
> Some tools may not be used commercially or automated without permission.

---

## 🧬 Research Direction

### 🔍 Origins (2010–2013)

I began analyzing flaws in early Bitcoin implementations:
- Weak private keys  
- Predictable BIP32/BIP44 paths  
- Public key recovery via scriptSig  
- Overexposed blockchain APIs

This evolved into a philosophy of **offline**, **secure**, and **structurally sound** blockchain research tools.

Current focus includes:
- Address generation logic  
- Derivation path validation (BIP32/44/49/84)  
- `asm` and script analysis  
- Public key entropy scoring  

**Metrics Used:**
- Hamming, Levenshtein, Euclidean distance  
- Entropy modeling  
- Heuristics & address clustering  
- ECDSA reconstruction logic (`r`, `s`, `z`)

---

## 🚀 QuantumChain (philosophy, not a product)

Before quantum disruption arrives, we must understand **legacy resilience**.  
I analyze:

- **CryptoNote** systems (Bytecoin, Monero)  
- **DAG** models (Nano, IOTA)  
- **Experimental derivation systems**

*QuantumChain* explores:
- Address reproducibility  
- Script and hash structure  
- Long-term keyspace entropy patterns

---

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

🙏 *Thank you for supporting independent research and ethical cryptography.*

---

**“I morph bits, not to break, but to understand.” – BitMorphX**  
💼 *Open to research collaboration, freelance auditing, or educational workshops.*

---

## 📡 Contact

- 🔗 GitHub: [https://github.com/BitMorphX](https://github.com/BitMorphX)  
- ✉️ Email: [BitMorphX@proton.me](mailto:BitMorphX@proton.me)  
- 💬 Telegram: [https://t.me/BitMorphX](https://t.me/BitMorphX)

---

🕒 Last updated: 2025-07-17  
© BitMorphX – All rights reserved.
