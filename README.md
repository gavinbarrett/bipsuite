## Description
This is a Python3 implementation of the BIP39 and BIP32 protocols for handling Bitcoin keys and generating HD wallets.

![](https://github.com/gavinbarrett/BIP39_Suite/workflows/Build/badge.svg)
![](https://github.com/gavinbarrett/BIP39_Suite/workflows/Mnemonic%20Generation/badge.svg)
![](https://github.com/gavinbarrett/BIP39_Suite/workflows/Seed%20Generation/badge.svg)
![](https://github.com/gavinbarrett/BIP39_Suite/workflows/xprv%20Derivation/badge.svg)
![](https://github.com/gavinbarrett/BIP39_Suite/workflows/xpub%20Derivation/badge.svg)
![](https://github.com/gavinbarrett/BIP39_Suite/workflows/Elliptic%20Point%20Addition/badge.svg)
![](https://github.com/gavinbarrett/BIP39_Suite/workflows/Elliptic%20Point%20Multiplication/badge.svg)

## Testing

You can test the BIP32/39 modules by running:
    ./tests/run_tests.sh

This will test 1) the generation of bits of entropy and a corresponding mnemonic recovery phrase for crypto wallets, 2) the derivation of a corresponding root seed used for deriving the BIP32 main node of the crypto wallet, 3) the correctness of secp256k1 elliptic curve arithmetic module, and 4) the derivation of a [base58check-encoded](https://en.bitcoin.it/wiki/Base58Check_encoding) master key pair.
