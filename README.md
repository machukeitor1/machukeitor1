# Cristian Machuca

**Desarrollador Full Stack** · Chillán, Chile · Disponible para trabajo remoto

Desarrollo aplicaciones web y móviles de punta a punta, desde el diseño de la base de datos y las APIs hasta la interfaz y el despliegue. Actualmente desarrollo y mantengo en producción el catálogo web y el sistema de cotizaciones de una empresa de materiales de construcción.

Analista Programador (INACAP) y estudiante de tercer año de Ingeniería en Informática. Certificado en Desarrollo Full Stack e Infraestructura TI Segura (INACAP), con certificaciones adicionales de Google y Microsoft.

[LinkedIn](https://www.linkedin.com/in/cristianmachuca-dev) · [Email](mailto:c.machucariquelme@gmail.com) · Español (nativo), inglés (intermedio)

---

## Tecnologías

| Área | Tecnologías |
|------|-------------|
| **Lenguajes** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |
| **Frontend** | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) |
| **Backend** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![DRF](https://img.shields.io/badge/DRF-A30000?style=flat-square&logo=django&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) |
| **Móvil** | ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white) ![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white) ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) |
| **Bases de datos** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) |
| **Cloud y DevOps** | ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Fly.io](https://img.shields.io/badge/Fly.io-8B5CF6?style=flat-square&logo=flydotio&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |
| **Calidad y seguridad** | ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Locust](https://img.shields.io/badge/Locust-2E8B57?style=flat-square&logo=locust&logoColor=white) ![Bandit](https://img.shields.io/badge/Bandit-CC0000?style=flat-square&logo=python&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) |

---

## Proyectos destacados

### Revestimientos Chillán — Catálogo web y sistema de cotizaciones
**Proyecto para cliente, en producción** · Next.js 14 · TypeScript · Prisma · PostgreSQL · Vercel

- Catálogo público de productos con precios por m² y por unidad, y solicitud de cotización por WhatsApp
- Panel de administración con CRUD completo e importación masiva de productos desde Excel
- Portal de vendedores que genera cotizaciones y las exporta a PDF y Word
- Autenticación por roles (administrador / vendedor) con JWT y bcrypt

**[Sitio en producción](https://www.revestimientoschillan.cl)** · **[Demo del código fuente](https://github.com/machukeitor1/demopisos-catalog)**

### OB Care — Sistema de Gestión Obstétrica
**Proyecto Integrado INACAP, equipo de 5 Integrantes** · Django 5 · MySQL · Django REST Framework

- Sistema clínico con cinco roles de usuario y fichas obstétricas, de parto y de recién nacido
- Mi aporte: módulo Médico, módulo de integración con el sistema heredado, mejoras de interfaz del módulo Matrona, avisos de cumplimiento de la Ley 19.628 de protección de datos, y testing y seguridad con pytest, Locust y Bandit

**[Repositorio](https://github.com/rjoserivera/OB_Care_Sistema_de_Gestion_Obstetrica)**

### Búsqueda por Rol CL — Consulta de propiedades (Android + Web)
Kotlin · Coroutines · Node.js · Express

- Consulta el ROL de avalúo de una propiedad por dirección usando servicios públicos del SII, y descarga en PDF el certificado de deuda de contribuciones de la TGR
- App Android nativa y versión web con API propia en Express

**[App Android](https://github.com/machukeitor1/Busqueda-por-Rol-CL)** · **[Versión web](https://github.com/machukeitor1/busquedapropietarioweb)**

### Gestor NFC — App Android para tags NFC
Kotlin · Jetpack Compose · MVVM

- Lee tags NFC (NTAG21x, Ultralight EV1, MIFARE Classic) con UID, contenido NDEF y verificación de la firma de originalidad NXP (ECDSA) para detectar clones
- Escribe URL, redes sociales, Wi-Fi, vCard y más, en serie o desde plantillas; protección con contraseña y bloqueo permanente

**[Repositorio](https://github.com/machukeitor1/gestor-nfc)**

---

## In English

Full-stack developer based in Chile, open to remote work. I build web and mobile applications end to end — database design, APIs, user interfaces and deployment — mainly with **Next.js, TypeScript, Node.js, Django and PostgreSQL**. I currently develop and maintain a production product catalog and sales-quoting platform for a building-materials company ([live site](https://www.revestimientoschillan.cl) · [source code demo](https://github.com/machukeitor1/demopisos-catalog)). Analista Programador (INACAP) and third-year Computer Engineering student.
