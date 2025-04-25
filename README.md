# APS Schema Repository

Welcome to the **Agent Performance Script (APS)** schema repository! 🌍

APS defines a **common language** for describing **multimodal, time-based actions** by AI agents or humans in interactive environments, especially for social games and simulations.

This repository contains the schema and initial documentation needed to **build, validate, and extend** APS-compliant systems.

---

## 📄 About the APS Schema

- **Format:** JSON Schema Draft 2020-12
- **Current Version:** 2.0.2
- **Purpose:** Standardize agent behaviors such as speaking, gazing, moving, and emotional expressions for consistent evaluation.
- **Scope:** Supports decentralized identities, parallel and dependent actions, dynamic environment positions, custom action extensions, and human translation compatibility.

> **Note:** Version 2.0.2 is the first public release, and is **incompatible** with earlier internal v1 schemas due to alignment with JSON Schema Draft 2020-12.

---

## 📂 Repository Structure

```
aps-schema/
├── schema/
│   └── aps.schema.json               # The core schema (v2.0.2)
├── README.md
├── LICENSE
```

Future releases may add:
- Examples
- Validation scripts
- Extended documentation

---

## 🔧 How to Use

1. **Reference the schema**
   - Validate your JSON data against `schema/aps.schema.json`
   - Libraries: `jsonschema` (Python), `ajv` (JavaScript), etc.

2. **Stay Updated**
   - Keep an eye on version tags and release notes.

3. **Contribute**
   - Feedback and suggestions are welcome via Issues and Discussions.

---

## 🔒 License

This project is licensed under the [Apache 2.0 License](LICENSE).

---

## ✨ Goals of APS

- Enable *fair comparison* between different agents or humans.
- Allow *decentralized development* of compatible agents.
- Support *future extensions* without breaking past work.
- Promote *transparent evaluation* of multimodal behavior.

---

## 🔗 Related Projects

- [Werewolf Judge Platform](https://github.com/CollComm/WerewolfJudgePlatform)

---

## ❓ Questions?

Open an issue or start a discussion! We welcome curious minds and constructive skeptics.


