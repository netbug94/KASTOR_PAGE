# Kastor Vault - Página del Proyecto

Este repositorio aloja la página de inicio pública y el sitio de documentación del proyecto **Kastor Vault**.

* **Sitio Web en Vivo:** [https://www.netbug94.com/KASTOR_PAGE/](https://www.netbug94.com/KASTOR_PAGE/)

---

## Acerca de Kastor Vault

Kastor Vault es una solución segura y descentralizada para el registro de conexiones y el almacenamiento de parámetros, inspirada en el ingeniero más meticuloso de la naturaleza: el castor (Kastor). El sistema está construido bajo una **Arquitectura de Zero-Knowledge** (Conocimiento Cero), lo que garantiza que las credenciales de conexión, llaves y endpoints de las API se cifren del lado del cliente y nunca se expongan al servidor en texto plano.

### Pilares Arquitectónicos:
* **Cifrado del Lado del Cliente:** Derivación de la llave maestra local mediante el algoritmo PBKDF2-HMAC-SHA256 con 600,000 iteraciones.
* **Protección de Datos:** Cifrado simétrico local de los slots de conexión utilizando AES-256-GCM.
* **Compatibilidad Multiplataforma:** Parámetros de seguridad unificados que se comparten de manera transparente entre el panel de administración, el portal del cliente y el cliente móvil nativo (`Flumen Mobile`).

---

## Aviso de Proyecto Privado

> [!IMPORTANT]
> Los repositorios de código fuente de los componentes centrales de Kastor Vault son de código cerrado por motivos de seguridad y licenciamiento:
> * `kastor-api` (Servicio central y base de datos)
> * `kastor-portal-admin` (Panel de administración)
> * `kastor-portal-client` (Portal de clientes)
> * `Flumen Mobile` (Aplicación móvil nativa para iOS y Android escrita con Kotlin Multiplatform)
>
> Para revisiones del programa de socios o solicitudes de acceso, por favor ponte en contacto directamente con el equipo de desarrollo.
