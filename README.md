# Kastor Vault - Project Homepage / Página del Proyecto

This repository hosts the public-facing landing page and documentation website for the **Kastor Vault** project. It is localized in Spanish (for Mexican users) and English.

* **Live Landing Page:** [https://<your-username>.github.io/<your-repo-name>](https://<your-username>.github.io/<your-repo-name>)

---

## About Kastor Vault / Acerca de Kastor Vault

Kastor Vault is a secure, decentralized connection registry and parameter storage solution inspired by nature's finest engineer, the beaver (Kastor/Castor). It is built on a **Zero-Knowledge Architecture**, ensuring that connection configurations, API endpoints, and credential keys are encrypted client-side and never exposed to the server in plaintext.

Kastor Vault es una solución segura de almacenamiento de credenciales y parámetros de conexión inspirada en el ingeniero más meticuloso de la naturaleza: el castor. Está construido sobre una **arquitectura de Zero-Knowledge** que garantiza que los datos se cifren del lado del cliente y nunca se expongan al servidor.

### Key Architectural Pillars / Pilares Clave:
* **Client-Side Cryptography (Cifrado Local):** Master key derivation using PBKDF2-HMAC-SHA256 with 600,000 iterations.
* **Payload Protection (Protección de Datos):** Client-side local encryption of connection slots using AES-256-GCM.
* **Cross-Platform Compatibility (Multiplataforma):** Unified security parameters shared seamlessly between the administration panel, user portal, and native mobile clients (`Flumen Mobile`).

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
