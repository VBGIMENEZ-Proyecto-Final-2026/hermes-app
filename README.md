# hermes-app

Aplicación Android desarrollada con Kotlin Multiplatform (KMP) que permite a un usuario final registrarse, autenticarse, buscar profesionales y gestionar sus propias reservas de turnos, consumiendo directamente los dos servicios backend propios: atlas-catalogo para búsqueda de profesionales y cronos-turnos para autenticación, disponibilidad y reservas. No se comunica con el servicio central de la cátedra.

Documentación, contratos y plantillas: [alejandria-docs](https://github.com/VBGIMENEZ-Proyecto-Final-2026/biblioteca-alejandria/tree/main/alejandria-docs).

## Configuración

Las variables se declaran en `.env.example` (versionado, con placeholders). Para trabajar en local: `cp .env.example .env` (`.env` está ignorado por git). Nunca commitear valores reales ni IPs.
