# Vista de Contexto (Modelo C4)

Este sistema consiste en un portafolio web que permite a los usuarios consultar información profesional y acceder a medios de contacto.

## Diagrama de contexto

```mermaid
graph TD
    Usuario -->|Visita el sitio| PortafolioWeb
    PortafolioWeb -->|Se despliega en| FirebaseHosting
    PortafolioWeb -->|Se versiona en| GitHub
    PortafolioWeb -->|Redirige contacto a| WhatsApp
