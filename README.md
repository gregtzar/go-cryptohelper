# go-cryptohelper

The `cryptohelper` package contains a collection of helper functions designed to streamline and document some common cryptographic patterns in golang web applications, using only the standard go crypto library.

The functions can be used in your own project or copied and modified as a starting point for your own library. They are designed with secure best-practice considerations and are production ready.

The package is intended to be self-documenting and complete for the patterns it includes, and as such it may contain several functions such as `CompareHMAC`, `EncodeHex`, and `EncodeB64` which are very simple wrappers for equally simple underlying core library functions, but have been included for semantic consistency and completeness.

## Supported Patterns

The library currently supports the following patterns:

* Psuedo-random security code / pin number generation
* Cryptographically secure key generation
  * AES 128-bit
  * AES 192-bit
  * AES 256-bit
  * HMAC SHA-256
  * HMAC SHA-512
  * Custom / any length
* AES encryption/decryption
* HMAC hashing
* String encoding/decoding of keys, ciphers, etc
  * Hexadecimal
  * Base64