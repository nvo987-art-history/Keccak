# NEXARIUM Keccak-256 & Whirlpool Generator

**Professional Client-Side Cryptographic Hash Utility**

Official application:
https://keccak.nvo987.us

Organization:
NEXARIUM – Open Decentralized Web Infrastructure

Developer:
Nicholas Van-Orton

Website:
https://www.nvo987.us

Digital Identity:
did:web:identity.nvo987.us

---

## 1. Overview

NEXARIUM Keccak-256 & Whirlpool Generator is a
browser-based cryptographic hashing utility designed
for local processing of text and files.

The application provides two cryptographic hash
algorithms:

- Keccak-256
- Whirlpool

The utility is designed to operate directly within
the user's browser without intentionally transmitting
submitted text or file contents to the operator's
servers for hash calculation.

No registration or user account is required.

---

## 2. Features

### Cryptographic Algorithms

**Keccak-256**
- Output size: 256 bits
- Output length: 32 bytes
- Hexadecimal representation: 64 characters

**Whirlpool**
- Output size: 512 bits
- Output length: 64 bytes
- Hexadecimal representation: 128 characters

### Text Hashing

- Generate hashes from arbitrary text.
- UTF-8 input encoding.
- Display character count.
- Display byte count.
- Measure hash generation time.
- Display hexadecimal output length.

### File Hashing

- Select a local file.
- Calculate its cryptographic hash.
- Display file name and size.
- Process file contents in the browser.

### Hash Verification

- Compare a generated digest with an expected digest.
- Validate hexadecimal input length.
- Support Keccak-256 and Whirlpool formats.
- Display matching or non-matching results.

### Export

- Copy hash output.
- Export TXT files.
- Export JSON files.

### Keyboard Shortcut

Ctrl + Enter:
Generate hash.

---

## 3. Technical Architecture

The application uses:

- HTML5
- CSS3
- JavaScript ES Modules
- WebAssembly
- TextEncoder API
- File API
- Blob API
- Clipboard API
- hash-wasm

Cryptographic dependency:

https://cdn.jsdelivr.net/npm/hash-wasm@4.12.0/dist/index.esm.js

Library repository:

https://github.com/Daninet/hash-wasm

---

## 4. Privacy Architecture

The application is designed for browser-side
cryptographic processing.

Text and selected file contents are passed to the
local browser-side hashing implementation.

The application does not intentionally upload
submitted text or file contents to the operator's
servers for hash calculation.

No application-level user registration is required.

The application does not intentionally implement:

- Advertising systems
- Analytics platforms
- Cross-site tracking
- User profiling
- Application-level cookies

Third-party infrastructure and CDN providers may
process ordinary technical connection information,
including IP addresses and request metadata.

Browser extensions, compromised devices, operating
systems, and other local software may also affect
the confidentiality of user input.

This application does not claim to provide absolute
confidentiality or anonymity.

---

## 5. Cryptographic Information

Keccak-256 and SHA3-256 are related but distinct
cryptographic hash functions.

They use different padding and domain-separation
conventions and therefore produce different digests
for the same input in general.

Whirlpool is a separate 512-bit cryptographic
hash function.

A cryptographic hash is not encryption.

It is not designed to recover the original input
from the resulting digest.

A matching hash can support integrity verification
but does not independently establish authenticity,
authorship, ownership, provenance, or legality.

---

## 6. Installation

The application is designed to run as a static
browser-based website.

No backend hashing service is required.

The main HTML document can be deployed on a
compatible static web hosting platform.

The cryptographic dependency is imported as
an ES module.

A modern browser supporting JavaScript ES modules,
WebAssembly, TextEncoder, and the File API is required.

---

## 7. Usage

1. Open the application.
2. Select Keccak-256 or Whirlpool.
3. Enter text or select a file.
4. Generate the hash.
5. Copy or export the resulting digest.
6. Use the verification interface to compare
   the generated digest with an expected value.

---

## 8. Security Considerations

Users should independently validate cryptographic
results before relying upon them in security-critical
environments.

The application does not replace:

- Digital signatures
- Authenticated communication
- Key management systems
- Secure archival systems
- Independent cryptographic verification

The security of browser-side processing depends
on the browser, device, operating system, installed
extensions, and external dependencies.

For production deployment, dependency integrity,
version pinning, supply-chain security, and
independent testing are recommended.

---

## 9. Third-Party Software

hash-wasm

Repository:
https://github.com/Daninet/hash-wasm

License:
MIT License

The third-party software retains its own copyright
and licensing terms.

See LICENSE for additional information.

---

## 10. Project Information

Application:
NEXARIUM Keccak-256 & Whirlpool Generator

Domain:
https://keccak.nvo987.us

Infrastructure:
https://nexarium.us

Developer:
Nicholas Van-Orton

Organization:
NVO987

https://www.nvo987.us

Digital Identity:
did:web:identity.nvo987.us

Contact:
nvo@nvo987.us

---

## 11. License

Original website materials are subject to the
LICENSE file.

Third-party software remains subject to its
respective license.

---

NEXARIUM
Professional Cryptographic Utilities

Copyright (c) 2026 Nicholas Van-Orton. 
