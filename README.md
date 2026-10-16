# 🦉 OSaml

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OWeb-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OSaml** — SAML / SSO / OIDC Configuration Auditor

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

SAML / SSO / OIDC Configuration Auditor

---

## ✨ Features

- Offline SAML metadata, Response/Assertion and OIDC discovery/client auditor with auto-detection
- Hardened expat ingestion (no DTD/entities, caps)
- base64 / URL / DEFLATE / SAMLResponse= decoding
- Built-in X.509 DER reader: expiry, key, sig alg
- Unsigned assertion, XSW, comment-truncation checks
- Conditions, audience, replay, RelayState, algorithms
- alg:none, implicit, PKCE, redirect-URI, scope checks
- CWE/OWASP/MITRE rule catalog, A+…F grade, CI gates
- TXT / MD / JSON / CSV / SARIF export, --demo self-test

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OSaml
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
