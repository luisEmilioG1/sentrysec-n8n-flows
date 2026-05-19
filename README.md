# Repositorio de Workflows para n8n

Este repositorio contiene una colección de workflows desarrollados en :contentReference[oaicite:0]{index=0} enfocados en automatización, integración de servicios, ciberseguridad, análisis de datos, productividad y uso de inteligencia artificial.

El objetivo del repositorio es centralizar flujos reutilizables, facilitar el aprendizaje práctico y servir como base para la construcción de automatizaciones más avanzadas dentro de entornos empresariales y de laboratorio.

---

# Características

- Workflows listos para importar en n8n
- Integraciones con APIs y servicios externos
- Automatizaciones orientadas a productividad y seguridad
- Ejemplos con IA, webhooks y procesamiento de datos
- Flujos documentados y organizados por categorías
- Repositorio pensado para aprendizaje y uso práctico

---

# Estructura del Repositorio

```bash
.
├── workflows/
│   ├── ai/
│   ├── cybersecurity/
│   ├── productivity/
│   ├── monitoring/
│   └── integrations/
├── assets/
├── docs/
└── README.md
```

---

# Tabla de Contenido

## Inteligencia Artificial

- [AI Chatbot with Gemini](#ai-chatbot-with-gemini)
- [AI Ticket Classification](#ai-ticket-classification)
- [AI Email Summarizer](#ai-email-summarizer)

## Ciberseguridad

- [Vulnerability Scanner Automation](#vulnerability-scanner-automation)
- [IOC Enrichment Workflow](#ioc-enrichment-workflow)
- [Threat Intelligence Collector](#threat-intelligence-collector)

## Productividad

- [Telegram Notification System](#telegram-notification-system)
- [Automatic Backup Workflow](#automatic-backup-workflow)

## Integraciones

- [Discord Webhook Integration](#discord-webhook-integration)
- [Google Sheets Data Sync](#google-sheets-data-sync)

---

# Workflows

---

## AI Chatbot with Gemini

### Descripción

Workflow que integra modelos de IA para responder preguntas mediante APIs y automatizar conversaciones.

### Características

- Integración con APIs de IA
- Manejo de contexto
- Respuestas automatizadas
- Compatible con webhooks

### Ruta

```bash
workflows/ai/ai-chatbot-gemini.json
```

---

## AI Ticket Classification

### Descripción

Clasificación automática de tickets utilizando IA y reglas de automatización.

### Ruta

```bash
workflows/ai/ai-ticket-classification.json
```

---

## AI Email Summarizer

### Descripción

Resume automáticamente correos electrónicos utilizando modelos de lenguaje.

### Ruta

```bash
workflows/ai/ai-email-summarizer.json
```

---

## Vulnerability Scanner Automation

### Descripción

Workflow orientado a automatizar procesos de escaneo de vulnerabilidades y consolidación de resultados.

### Características

- Integración con scanners
- Procesamiento de reportes
- Notificaciones automáticas

### Ruta

```bash
workflows/cybersecurity/vulnerability-scanner.json
```

---

## IOC Enrichment Workflow

### Descripción

Automatiza el enriquecimiento de indicadores de compromiso (IOC) utilizando APIs de threat intelligence.

### Ruta

```bash
workflows/cybersecurity/ioc-enrichment.json
```

---

## Threat Intelligence Collector

### Descripción

Recolecta información desde múltiples fuentes de inteligencia de amenazas y centraliza resultados.

### Ruta

```bash
workflows/cybersecurity/threat-intelligence-collector.json
```

---

## Telegram Notification System

### Descripción

Sistema de notificaciones automáticas mediante Telegram.

### Ruta

```bash
workflows/productivity/telegram-notifications.json
```

---

## Automatic Backup Workflow

### Descripción

Automatización de respaldos periódicos y almacenamiento seguro.

### Ruta

```bash
workflows/productivity/automatic-backup.json
```

---

## Discord Webhook Integration

### Descripción

Envía eventos y alertas a canales de Discord utilizando webhooks.

### Ruta

```bash
workflows/integrations/discord-webhook.json
```

---

## Google Sheets Data Sync

### Descripción

Sincroniza información automáticamente entre APIs y Google Sheets.

### Ruta

```bash
workflows/integrations/google-sheets-sync.json
```

---

# Cómo usar los workflows

1. Descargar o clonar el repositorio

```bash
git clone https://github.com/usuario/repositorio.git
```

1. Abrir n8n

2. Importar el archivo `.json` del workflow

3. Configurar credenciales y variables necesarias

4. Ejecutar el workflow

---

# Requisitos

- n8n instalado localmente o en servidor
- Credenciales/API Keys según el workflow
- Acceso a servicios externos utilizados

---

# Contribuciones

Las contribuciones son bienvenidas.

Puedes agregar nuevos workflows, mejorar documentación o reportar problemas mediante issues y pull requests.

---

# Licencia

Este proyecto se distribuye bajo la licencia MIT.
