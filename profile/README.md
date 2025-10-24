![alt text](https://github.com/ZKNoxHQ/.github/blob/main/zknoxlogo.jpeg)

# Introducing ZKNOX
 

 
## Advancing Hardware Security & Cryptography.

Today, we’re excited to introduce ZKNOX, a new venture founded by three experts in hardware security and cryptography (ECC, ZK, MPC) this February 2025. With deep expertise in securing critical systems, our mission is to advance secure hardware, cryptographic protocols, and blockchain-integrated security solutions—with a strong alignment to Ethereum, defensive and decentralized technologies.

We’re bringing deep expertise and innovation to every challenge on the whole security chain, from user end (be it secure enclaves, hardware wallets), back end (TEE, HSMs) or on-chain (smart contracts).

Stay tuned for updates as we share insights, breakthroughs, and product developments. If you're interested in collaborating or learning more, reach out to us—we’re just getting started.


## The team


- Bacca Nicolas - Co-founder and ex-CTO of the unicorn Ledger, with 25+ years of experience in building and breaking secure solutions. Realizations include giving birth to Nano, Ledger best seller.
- Dubois Renaud - Cryptologist with 20 years of experience (Thales Defense, Ledger). Realizations include several [publications](https://dblp.org/pid/26/211.html) and [patents](https://patents.google.com/?inventor=Renaud+Dubois), and delivering the fastest generic [ecc](https://github.com/rdubois-crypto/FreshCryptoLib/blob/master/README.md) implementations, including passkeys integrated in Coinbase Smart Wallet.  
- Masson Simon - Cryptologist with 8 years of experience (Thales, Anoma).
Realizations include several [publications](https://dblp.org/pid/218/7096.html) including Bandersnatch, a fast embedded curve for ECDSA verification circuit.


## Realizations

### 2025

#### Ethereum Post Quantum Transition: 
- Contribution to DILITHIUM (EIP-8051) and FALCON (EIP-8052) EIPs:
    * https://ethereum-magicians.org/t/eip-8051-ml-dsa-verification/25857
    * https://ethereum-magicians.org/t/eip-8052-precompile-for-falcon-support/25860
- Solidity implementations of (EIP-8051) and FALCON (EIP-8052):
    * https://github.com/ZKNoxHQ/ETHFALCON
    * https://github.com/ZKNoxHQ/ETHDILITHIUM
- Hardware implementation of Dilithium (EIP_8051)
    * https://github.com/ZKNoxHQ/ZKN-PRIVACYHW
- FALZKON, a zk-friendly falcon in Cairo
    * https://github.com/ZKNoxHQ/falzkon


#### Improve ECC circuit verification

- [Fast elliptic curve scalar multiplications in SN(T)ARK circuits](https://eprint.iacr.org/2025/933)

In this work, we provide new techniques for reducing the time corresponding to proving a scalar multiplication, using integer lattice reduction or a (half) extended Euclidean algorithm in a ring of integers. A joint work with Liam Eagen (Alpen Labs), Youssef El Housni (Linea), Simon Masson (ZKNox) and 
Thomas Piellard  (Linea).


#### ZK-friendly primitives in hardware
- EDDSA Poseidon, circomlib compliant hardware integration (Ledger Nano Device)
    * https://github.com/ZKNoxHQ/ZKN-PRIVACYHW
- BABYFROST, a FROST implementation, compatible with circomlib eddsaposeidon
    * (WIP)

#### Account abstraction

- PRs for major hardware wallets 7702 integration:
    * Trezor: https://github.com/trezor/trezor-firmware/pull/4945
    * Ledger: https://github.com/LedgerHQ/app-ethereum/pull/739
    * KeyStone: https://github.com/KeystoneHQ/keystone3-firmware/pull/1727

#### White Hat

- A responsible disclosure of potential [supply chain attack](https://x.com/KeystoneWallet/status/1909214655270056143) on Keystone wallet
 <img width="584" height="111" alt="image" src="https://github.com/user-attachments/assets/cd70f72d-2edf-4da7-a8e1-6514d9773bfb" />



 
## Reach us

🔐 Practical security on the whole chain.

[Website](https://www.zknox.com) | [Twitter](https://x.com/zknoxhq) | [Blog](https://zknox.eth.limo) | [Contact Info](mailto:gm@zknox.com)
