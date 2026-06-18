# Kastor Vault - Project Homepage

This repository hosts the public-facing landing page and documentation website for the **Kastor Vault** project.

* **Live Landing Page:** [https://<your-username>.github.io/<your-repo-name>](https://<your-username>.github.io/<your-repo-name>)

---

## About Kastor Vault

Kastor Vault is a secure, decentralized connection registry and parameter storage solution. It is built on a **Zero-Knowledge Architecture**, ensuring that connection configurations, API endpoints, and credential keys are encrypted client-side and never exposed to the server in plaintext.

### Key Architectural Pillars:
* **Client-Side Cryptography:** Master key derivation using PBKDF2-HMAC-SHA256 with 600,000 iterations.
* **Payload Protection:** Client-side local encryption of connection slots using AES-256-GCM.
* **Cross-Platform Compatibility:** Unified security parameters shared seamlessly between the administration panel, user portal, and native mobile clients.

---

## Private Project Notice

> [!IMPORTANT]
> The source code repositories for the core components of Kastor Vault are closed-source:
> * `kastor-api` (Core DB & Session routing)
> * `kastor-portal-admin` (Administrative panel)
> * `kastor-portal-client` (Client dashboard)
> * `Flumen Mobile` (Native iOS/Android Kotlin Multiplatform app)
>
> For security and licensing reasons, these repositories are hosted privately. For access inquiries or partner program reviews, please contact the development team directly.
