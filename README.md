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

OSaml is an offline auditor for SAML, SSO and OIDC configurations. It inspects metadata, SAML Responses/Assertions and OIDC discovery/client documents using a hardened XML parser, checking signatures, certificates, algorithms and replay protections. Findings are graded and mapped to CWE, OWASP and MITRE references.

---

## ✨ Features

- Audits SAML metadata, Responses/Assertions and OIDC discovery/client JSON with auto-detection
- Hardened expat XML ingestion that rejects DTD/entities to defeat XXE and billion-laughs
- base64/URL/DEFLATE and SAMLResponse decoding
- Built-in X.509 DER reader for expiry, key and signature-algorithm checks
- Unsigned-assertion, XML Signature Wrapping and comment-truncation detection
- alg:none, PKCE, redirect-URI and scope checks with A+ to F grading and multiple export formats

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OSaml -p metadata.xml --metadata
./OSaml -p response.b64 --response --json -o report.json
./OSaml --dir ./saml --fail-on high
./OSaml --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
