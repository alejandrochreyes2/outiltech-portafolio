# Outiltech — Portafolio de Documentación del Proyecto

> Repositorio de documentación oficial del proyecto **Outiltech E-Commerce Platform** — tienda en línea para venta de tecnología en Colombia.

**URL de la tienda:** https://outiltech.co  
**Cliente:** Jhonnathan Hernández Medina — Gerente y propietario de Outiltech  
**Desarrollado por:** Alejandro Chaparro Reyes · alejandrochreyes2@gmail.com · WhatsApp 3133082905  
**Período:** 21 Marzo – 26 Abril 2026 · **Inversión:** $20.000.000 COP

> **Punto de partida:** Antes del 21 de marzo de 2026, Outiltech **no tenía ninguna presencia en internet** — cero página web, cero plataforma digital. Todo lo que existe hoy en outiltech.co fue construido desde cero en 36 días.

---

## Arquitectura del Proyecto

```
outiltech-entrega-portafolio/
│
├── docs/
│   ├── 01_MANUAL_TECNICO_PRUEBA.md        ← Pruebas técnicas + guía admin servidor
│   ├── 02_MANUAL_USUARIO.md               ← Manual no técnico para el cliente
│   ├── 03_PMO_PLAN_PROYECTO.md            ← Plan PMO + checklist de entrega
│   ├── 04_POSTMAN_GUIA.md                 ← Guía de pruebas con Postman (24 requests)
│   ├── 05_SWAGGER_DOCUMENTACION.md        ← Documentación completa de la API REST
│   ├── 06_README.md                       ← README de documentación
│   ├── 07_PORTAFOLIO.md                   ← Portafolio del desarrollador
│   ├── 08_PROJECT_CHARTER.md              ← Carta del proyecto + plan capacitación
│   ├── 09_CONTRATO_DE_SERVICIOS_TECNOLOGICOS.md
│   └── 10_TERMINOS_DE_USO_Y_PRIVACIDAD.md
│
├── postman/
│   └── ProyectoPedidos.postman_collection.json
│
├── presentacion/
│   └── PRESENTACION_EJECUTIVA.md
│
└── contratos_firmados/
    └── 11_ACTA_DE_ENTREGA.md
```

---

## Stack Tecnológico

| Capa | Tecnología |
|------|-----------|
| Frontend | Angular 21, TypeScript 5, Signals API |
| Backend | .NET 8 ASP.NET Core — 3 microservicios |
| API Gateway | YARP Reverse Proxy |
| Base de datos | PostgreSQL 15 + MongoDB 6 + Supabase |
| Pagos | Wompi (tarjeta/PSE) + Nequi/Daviplata QR |
| Email | EmailJS + Gmail SMTP |
| Infraestructura | Hetzner VPS, Coolify, Docker, Cloudflare |
| Dominio | outiltech.co (Namecheap) |

---

## Documentos del Proyecto (13 entregables)

| # | Documento | Descripción |
|---|----------|------------|
| 01 | [Manual Técnico](docs/01_MANUAL_TECNICO_PRUEBA.md) | Pruebas, endpoints, guía de administración del servidor |
| 02 | [Manual de Usuario](docs/02_MANUAL_USUARIO.md) | Guía no técnica para el cliente |
| 03 | [PMO Plan](docs/03_PMO_PLAN_PROYECTO.md) | Plan de proyecto + checklist de entrega |
| 04 | [Postman Guía](docs/04_POSTMAN_GUIA.md) | Guía de pruebas con 24 requests |
| 05 | [Swagger API](docs/05_SWAGGER_DOCUMENTACION.md) | Documentación completa de la API REST |
| 06 | [README](docs/06_README.md) | README de documentación del proyecto |
| 07 | [Portafolio](docs/07_PORTAFOLIO.md) | Portafolio del desarrollador |
| 08 | [Project Charter](docs/08_PROJECT_CHARTER.md) | Carta del proyecto + plan de capacitación + propuesta comercial |
| 09 | [Contrato](docs/09_CONTRATO_DE_SERVICIOS_TECNOLOGICOS.md) | Contrato de servicios tecnológicos |
| 10 | [Términos](docs/10_TERMINOS_DE_USO_Y_PRIVACIDAD.md) | Términos de uso y política de privacidad |
| 11 | [Acta de Entrega](contratos_firmados/11_ACTA_DE_ENTREGA.md) | Acta formal de aceptación del cliente |
| — | [Presentación Ejecutiva](presentacion/PRESENTACION_EJECUTIVA.md) | Presentación de la demo final |
| — | [Postman Collection](postman/ProyectoPedidos.postman_collection.json) | Colección Postman con 24 requests |

---

## Funcionalidades Principales

- ✅ Tienda e-commerce con **114 productos** (iPhone, Samsung, Mac, Android, Segway…)
- ✅ Carrito de compras con persistencia
- ✅ Checkout completo con validación
- ✅ Pago con **Wompi** (tarjeta + PSE)
- ✅ Pago con **Nequi/Daviplata** (QR + comprobante)
- ✅ Emails automáticos de confirmación (EmailJS)
- ✅ Panel admin con dashboard en tiempo real (Supabase)
- ✅ CRUD de pedidos con estados y comprobantes
- ✅ Autenticación JWT con roles (Admin / Vendedor)
- ✅ HTTPS + CDN global (Cloudflare)

---

## Contacto

**Alejandro Chaparro Reyes**  
Desarrollador Full-Stack Senior — Bogotá, Colombia  
📧 alejandrochreyes2@gmail.com  
📱 WhatsApp: 3133082905  
🐙 https://github.com/alejandrochreyes2

---

*Outiltech E-Commerce — Documentación del Proyecto — Abril 2026*
