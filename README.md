# 🦉 OHaproxyX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-ONetwork-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OHaproxyX** — HAProxy Load-Balancer Configuration Auditor

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OHaproxyX — HAProxy Load-Balancer Configuration Auditor. It provides stdlib parser — all sections, named defaults, conf.d; Stats page / runtime socket / TLS / backend verify. Built-in demo/self-test paths and severity gates help validate detections without touching production when those flags are used.

---

## ✨ Features

- Stdlib parser — all sections, named defaults, conf.d
- Stats page / runtime socket / TLS / backend verify
- Smuggling, slowloris timeouts, maxconn, privileges
- PEM / crt-list / map / acl file permission checks
- Data Plane API exposure & credentials, peers TLS
- Secrets masked everywhere; --root offline trees

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OHaproxyX                                     # interactive menu
./OHaproxyX --scan -r /path/to/root
./OHaproxyX --demo
./OHaproxyX --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
