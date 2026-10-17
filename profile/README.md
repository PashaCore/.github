<div align="center">

# Pasha Core

**Open-source IT operations software, built in public and transparent by design.**

[![Website](https://img.shields.io/badge/Website-pashacore.com.tr-2563EB?style=flat-square&logo=googlechrome&logoColor=white)](https://pashacore.com.tr)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Pasha%20Core-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/company/pasha-core)
[![POps stars](https://img.shields.io/github/stars/PashaCore/POps?label=POps&style=flat-square&logo=github)](https://github.com/PashaCore/POps/stargazers)

</div>

---

We build software that helps schools and IT teams run their computers: inventory, remote support, software
deployment, updates and audit. It is open source and self-hosted, and one rule comes before the others:

> **Administrators should have powerful tools. Users should always know when those tools are being used.**

---

## Products

### [POps — Pasha Operations Platform](https://github.com/PashaCore/POps)

Open-source, self-hosted management for school computer labs and Windows/Linux fleets.

| | |
| :--- | :--- |
| **Know the fleet** | Live state, hardware and software inventory, Windows Update, licences and reports. |
| **Act on it** | Task queue and terminal, software deployment with winget, Vision remote support, exam mode, file transfer, power actions and messages, Wake-on-LAN and quarantine. |
| **Keep it safe** | ed25519-signed agent updates that roll back on their own, features that can be turned off per PC, a hash-chained audit log, 2FA, and LDAP/AD or OpenID Connect sign-in. |
| **Run it calmly** | Helpdesk from the tray, notifications by e-mail or webhook, tested nightly backups, server self-update with rollback, and organisational units for districts and schools. |
| **Grow with it** | One backend process held 5,000 simulated agents; several workers with Redis are optional. A versioned REST API with tokens and a GLPI export. |

**Transparent by design:** a screen session starts only after the user accepts it or sees a countdown, the tray icon
is always visible, and there is no stealth mode or keystroke logging.

The panel is in Turkish and English. Agents run on Windows (.NET 10) and on Linux and Pardus (Python, `.deb`).
Licensed Apache-2.0; still alpha ([releases](https://github.com/PashaCore/POps/releases)).

**[Try the read-only demo](https://demo.pashacore.com.tr)** (user `demo`, password `demo`) ·
[Quick start](https://github.com/PashaCore/POps#-quick-start) ·
[Documentation](https://github.com/PashaCore/POps/tree/main/docs) ·
[Türkçe](https://github.com/PashaCore/POps/blob/main/README.tr.md)

---

## Built with

`C# / .NET 10` · `Python / FastAPI` · `PHP 8` · `JavaScript` · `PostgreSQL` · `Redis` · `WebSockets` · `Docker` · `Linux`

---

## Contributing

We build in the open, and outside contributors are already helping.

- **Start here:** [good first issues](https://github.com/PashaCore/POps/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22),
  and for Turkish speakers the [`türkçe` issues](https://github.com/PashaCore/POps/issues?q=is%3Aissue+is%3Aopen+label%3At%C3%BCrk%C3%A7e).
- **How we work:** [CONTRIBUTING](https://github.com/PashaCore/POps/blob/main/CONTRIBUTING.md) and the
  [Code of Conduct](https://github.com/PashaCore/POps/blob/main/CODE_OF_CONDUCT.md).
- **Security issues:** please report them privately as described in
  [SECURITY.md](https://github.com/PashaCore/POps/blob/main/SECURITY.md), not in a public issue.

> 🇹🇷 Pasha Core, okullar ve BT ekipleri için açık kaynak yönetim yazılımı geliştirir. Türkçe katkılar da memnuniyetle
> karşılanır: [`türkçe` etiketli işler](https://github.com/PashaCore/POps/issues?q=is%3Aissue+is%3Aopen+label%3At%C3%BCrk%C3%A7e).

---

## Connect

- 🌐 [pashacore.com.tr](https://pashacore.com.tr)
- 💼 [LinkedIn](https://linkedin.com/company/pasha-core)
- 👤 Maintainer: [@TheP4SHA](https://github.com/TheP4SHA)
