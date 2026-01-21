# tgapis

**tgapis** is an organization dedicated to collecting, maintaining, and distributing **Telegram API–related specifications, schemas, and tooling** in a clean, structured, and automation‑friendly way.

The goal of **tgapis** is simple:

> **Make Telegram APIs easier to consume, track, and integrate across languages and tools.**

---

## 🎯 What this organization focuses on

* 📦 **Telegram API specifications** (Bot API, MTProto, TDLib‑related data)
* 🔄 **Auto‑updated API data** tracked directly from upstream sources
* 🧩 **Machine‑readable formats** (JSON / structured data)
* ⚙️ **Developer‑friendly repos** usable in generators, SDKs, and tooling
* 🧠 **No SDK lock‑in** — data first, language agnostic

This org is intentionally **low‑level and infrastructure‑oriented**.

---

## 📚 Repositories

### 🔹 `tgdocsapi`

Structured Telegram API documentation data.

* Extracted & normalized API docs
* Useful for generators, static sites, and tooling
* Designed for automation & diffs

### 🔹 `x`

Telegram Bot API / related schema snapshots.

* JSON‑based API data
* Ideal for code generation
* Tracks upstream changes

### 🔹 `td`

TDLib‑related data and experiments.

* Focused on MTProto / TDLib ecosystem
* Not an SDK — raw, inspectable data

> Repositories may update automatically via GitHub Actions.

---

## 🔄 Update strategy

* Sources are pulled directly from **official Telegram repositories**
* Updates are:

  * Scheduled (time‑based)
  * Or triggered by upstream changes
* History is preserved for:

  * Diffs
  * Rollbacks
  * Compatibility tracking

---

## 🧠 Who this is for

* SDK / library maintainers
* Tooling & generator authors
* Telegram client developers
* Bot framework developers
* Researchers & power users

If you are building:

* a Telegram SDK
* a code generator
* an API explorer
* or automation around Telegram APIs

👉 **tgapis is for you.**

---

## 🚫 What this org is NOT

* ❌ Not a bot framework
* ❌ Not a ready‑to‑use SDK
* ❌ Not opinionated about languages

It provides **data and structure**, not abstractions.

---

## 🤝 Contributions

Contributions are welcome, especially:

* API diffs & corrections
* Automation improvements
* Documentation clarity

Please:

* Keep changes minimal and atomic
* Avoid breaking schema changes without discussion

---

## 📄 License

Each repository contains its own license.
Unless stated otherwise, data is derived from **official Telegram sources/public github source** and follows their respective terms.

---

## ⭐ Philosophy

> *Clean data outlives libraries.*

`tgapis` exists so Telegram API data can be:

* tracked
* reused
* regenerated
* and trusted

without rewriting the same logic in every project.
