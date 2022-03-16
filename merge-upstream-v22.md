---
layout: fr
title: Merge in upstream Bitcoin v22.0 to Vertcoin-Core
author: vertion
date: December 27, 2021
amount: 10000
milestones:
- name: Reviewed and merged into Vertcoin-Core
  funds: 10000 VTC
  done:
  status: unfinished
  payouts:
- date:
  amount:
---
# Proposal

I have completed a merge of the latest upstream Bitcoin-Core release, v22.0, to Vertcoin-Core.  You can see the release notes as to what this includes [here](https://github.com/bitcoin/bitcoin/blob/master/doc/release-notes/release-notes-22.0.md).  What I am most excited for about this release is increased functionality to descriptor wallets making the importing of descriptors easier for use in taproot and multisig.   This release also adds support for external hardware signers which means that you can use Vertcoin-Core instead of Trezor Suite, Ledger Live, etc. to create addresses and transactions while still signing securely on the external hardware.

As part of this release, I have ensured that it builds properly using the new guix-based build system which is used to perform [bootstrappable](https://github.com/bitcoin/bitcoin/blob/master/contrib/guix/README.md) Vertcoin Core builds.  [Bootstrappability](https://bootstrappable.org/) furthers our binary security guarantees by allowing us to audit and reproduce our toolchain instead of blindly trusting binary downloads.  Using this process, anyone people can build Vertcoin-Core and verify that they have built the exact same executables as those being downloaded on Github.  By having multiple people run the build process and attest to the SHA256 checksums of the resulting executables, trust in the release manager who is supplying those binaries is removed because we can verify their authenticity as a community.  This process would mean there is no more need for binaries to be signed by the release manager's PGP key.

Additional updates include:
- Fixing the startup command flags `-skip-startup-verify` and `-full-startup-verify`, the former or which allows one to skip the `Checking POW for block ...` lines at startup and greatly increase the speed of launching Vertcoin-Core

- Updated seednodes

- A functional Windows installer

- Support for riscv64, powerpc64 and powerpc64le systems

I am asking for 10000 VTC to compensate my time spent on this which involved taking time off from my normal line of work.  Once this is funded, I will release my work publicly and make a pull request to Vertcoin-Core.  Only once this is reviewed and merged may funds be released to me.
