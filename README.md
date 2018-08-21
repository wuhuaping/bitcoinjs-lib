Deprecation
===

Just for information

After some testing, I will deprecate this library and we will start using this one

https://github.com/trezor/bitcoinjs-trezor

Unlike this one, bitcoinjs-trezor has only the functions that we use in Trezor web wallet, but does NOT have functions that we don't use. Specifically, it does not have transaction signing, since that happens in Trezor.

You are free to fork this library and keep maintaining it (if it is in npm, I will link it in readme)

Original readme
===

This is a fork of https://github.com/bitcoinjs/bitcoinjs-lib with very simple support for zcash (parsing transactions + multibyte addresses).

You should not use this if you don't have to support zcash, since it's not as well maintained and tested as bitcoin.js.

Read README at original bitcoinjs-lib

## versions

Version 3.3.2 is rebased on upstream 3.3.2

## LICENSE [MIT](LICENSE)
