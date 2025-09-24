# 🤖 Chatbot Workflows - N8N Collection

Este documento presenta una compilación completa de **todos los workflows relacionados con chatbots** encontrados en la colección de n8n-workflows. La colección incluye chatbots para múltiples plataformas, con diferentes niveles de complejidad y funcionalidades.

**Total de Workflows de Chatbots:** 23
**Última actualización:** Enero 2025

---

## 📊 Resumen por Categorías

### Por Plataforma:
- **Telegram Bots:** 13 workflows
- **AI/Web Chatbots:** 4 workflows  
- **Line Chatbots:** 2 workflows
- **Slack Chatbots:** 1 workflow
- **Bitrix24 Chatbots:** 2 workflows
- **Otros:** 1 workflow

### Por Complejidad:
- **Alta (16+ nodos):** 18 workflows
- **Media (6-15 nodos):** 5 workflows
- **Baja (≤5 nodos):** 0 workflows

---

## 🔍 Listado Completo de Workflows

### 1. Telegram AI Bots (13 workflows)

#### 🤖 AI Powered RAG Chatbot for Your Docs + Google Drive + Gemini + Qdrant
**Archivo:** `1185_Telegram_Wait_Automate_Webhook.json`
**Descripción:** Chatbot RAG avanzado que procesa documentos con Google Drive, Gemini AI y Qdrant
**Complejidad:** Alta (50 nodos)
**Estado:** Inactivo
**Trigger:** Complex
**Integraciones:** Textsplittertokensplitter, Splitinbatches, Lmchatgooglegemini, OpenAI, Google Drive, Lmchatopenai, Telegram, Webhook, Extractfromfile, Embeddingsopenai, Informationextractor, Agent, Google Docs, Documentdefaultdataloader, Vectorstoreqdrant, Chat, Memorybufferwindow

---

#### 📱 Telegram ChatBot with multiple sessions
**Archivo:** `1244_Telegram_GoogleSheets_Automate_Triggered.json`
**Descripción:** Bot de Telegram con manejo de múltiples sesiones usando Google Sheets
**Complejidad:** Alta (38 nodos)
**Estado:** Inactivo
**Trigger:** Complex
**Integraciones:** OpenAI, Telegram, Google Sheets, Chainllm, Chainsummarization, Memorybufferwindow

---

#### 🔊 Telegram AI multi-format chatbot
**Archivo:** `1485_Telegram_Stickynote_Automate_Triggered.json`
**Descripción:** Bot de Telegram que maneja múltiples formatos de entrada
**Complejidad:** Media (15 nodos)
**Estado:** Inactivo
**Trigger:** Complex
**Integraciones:** Telegram, Agent, Memorybufferwindow, OpenAI

---

#### 🎧 HR & IT Helpdesk Chatbot with Audio Transcription
**Archivo:** `1487_Telegram_Extractfromfile_Automate_Webhook.json`
**Descripción:** Bot de soporte técnico con transcripción de audio
**Complejidad:** Alta (27 nodos)
**Estado:** Inactivo
**Trigger:** Complex
**Integraciones:** OpenAI, Telegram, Agent, Extractfromfile, Vectorstorepgvector, Httprequest, PostgreSQL, Documentdefaultdataloader, Textsplitterrecursivecharactertextsplitter, Toolvectorstore

---

#### 🛒 WooCommerce AI Chatbot Workflow for Post-Sales Support
**Archivo:** `1575_Telegramtool_Woocommercetool_Automate_Webhook.json`
**Descripción:** Bot de soporte post-venta para WooCommerce
**Complejidad:** Alta (31 nodos)
**Estado:** Inactivo
**Trigger:** Complex
**Integraciones:** Textsplittertokensplitter, OpenAI, Google Drive, Lmchatopenai, Agent, Toolworkflow, Httprequest, Documentdefaultdataloader, Vectorstoreqdrant, Telegramtool, Chat, Executeworkflow, Cal.com, Woocommercetool, Memorybufferwindow, Toolvectorstore

---

#### 🧠 AI Agent Chatbot + LONG TERM Memory + Note Storage + Telegram
**Archivo:** `1610_Telegram_Googledocs_Automate_Triggered.json`
**Descripción:** Bot con memoria a largo plazo y almacenamiento en Google Docs
**Complejidad:** Alta (21 nodos)
**Estado:** Inactivo
**Trigger:** Complex
**Integraciones:** Lmchatopenai, Google Docs, Telegram, Googledocstool, Agent, Chat, Memorybufferwindow

---

#### 🔊 Telegram AI multi-format chatbot (v2)
**Archivo:** `1686_Telegram_Stickynote_Automate_Triggered.json`
**Descripción:** Segunda versión del bot multi-formato
**Complejidad:** Media (15 nodos)
**Estado:** Inactivo
**Trigger:** Complex
**Integraciones:** Telegram, Agent, Memorybufferwindow, OpenAI

---

#### 🤖 Telegram AI-bot
**Archivo:** `0248_Openai_Telegram_Automate_Triggered.json`
**Descripción:** Bot básico de Telegram con OpenAI
**Complejidad:** Alta (16 nodos)
**Estado:** Activo
**Trigger:** Webhook
**Integraciones:** Telegram, OpenAI

---

#### 📧 e-mail Chatbot with both semantic and structured RAG, using Telegram and Pgvector
**Archivo:** `1843_Telegram_Code_Automate_Triggered.json`
**Descripción:** Bot de email con RAG semántico y estructurado
**Complejidad:** Alta (20 nodos)
**Estado:** Activo
**Trigger:** Complex
**Integraciones:** Splitinbatches, OpenAI, Telegram, Embeddingsollama, Agent, PostgreSQL, Chat, Cal.com, Memorybufferwindow

---

#### 🌐 Confluence Page AI Powered Chatbot
**Archivo:** `1919_Telegram_Splitout_Automate_Webhook.json`
**Descripción:** Bot con integración a páginas de Confluence
**Complejidad:** Alta (16 nodos)
**Estado:** Inactivo
**Trigger:** Complex
**Integraciones:** Markdown, Lmchatopenai, Manualchat, Agent, Telegram, Splitout, Httprequest, Memorybufferwindow

---

#### 🧠 Give Your AI Agent Chatbot Long Term Memory Tools Router
**Archivo:** `1950_Telegram_Googledocs_Automate_Triggered.json`
**Descripción:** Bot con herramientas de memoria a largo plazo y enrutamiento
**Complejidad:** Alta (39 nodos)
**Estado:** Inactivo
**Trigger:** Complex
**Integraciones:** OpenAI, Google Docs, Telegram, Agent, Gmail, Toolworkflow, Chat, Executeworkflow, Memorybufferwindow

---

#### 🎧 HR & IT Helpdesk Chatbot with Audio Transcription (v2)
**Archivo:** `2038_Telegram_Extractfromfile_Automate_Webhook.json`
**Descripción:** Segunda versión del bot de soporte con transcripción
**Complejidad:** Alta (27 nodos)
**Estado:** Inactivo
**Trigger:** Complex
**Integraciones:** OpenAI, Telegram, Agent, Extractfromfile, Vectorstorepgvector, Httprequest, PostgreSQL, Documentdefaultdataloader, Textsplitterrecursivecharactertextsplitter, Toolvectorstore

---

#### 🧠 AI Agent Chatbot + LONG TERM Memory + Note Storage + Telegram (v2)
**Archivo:** `2053_Telegram_Googledocs_Automate_Triggered.json`
**Descripción:** Segunda versión del bot con memoria a largo plazo
**Complejidad:** Alta (21 nodos)
**Estado:** Inactivo
**Trigger:** Complex
**Integraciones:** Lmchatopenai, Google Docs, Telegram, Googledocstool, Agent, Chat, Memorybufferwindow

---

### 2. Line Chatbots (2 workflows)

#### 💰 Line_Chatbot_Extract_Text_from_Pay_Slip_with_Gemini
**Archivo:** `1811_HTTP_GoogleSheets_Automate_Webhook.json`
**Descripción:** Bot de Line que extrae texto de recibos de pago usando Gemini
**Complejidad:** Alta (17 nodos)
**Estado:** Activo
**Trigger:** Complex
**Integraciones:** Lmchatgooglegemini, Google Sheets, Agent, Webhook, Httprequest, Chainllm, Memorybufferwindow

---

#### 🦙 Line Chatbot Handling AI Responses with Groq and Llama3
**Archivo:** `2019_HTTP_Stickynote_Automate_Webhook.json`
**Descripción:** Bot de Line con respuestas IA usando Groq y Llama3
**Complejidad:** Media (9 nodos)
**Estado:** Activo
**Trigger:** Webhook
**Integraciones:** Httprequest, Webhook

---

### 3. Slack Chatbots (1 workflow)

#### 💼 Slack AI Chatbot with RAG for company staff
**Archivo:** `1643_Slack_Manual_Automate_Webhook.json`
**Descripción:** Bot de Slack con RAG para personal de empresa
**Complejidad:** Alta (21 nodos)
**Estado:** Inactivo
**Trigger:** Complex
**Integraciones:** Textsplittertokensplitter, OpenAI, Google Drive, Agent, Anthropic, Httprequest, Documentdefaultdataloader, Vectorstoreqdrant, Cal.com, Memorybufferwindow, Slack

---

### 4. Bitrix24 Chatbots (2 workflows)

#### 📈 Bitrix24 Chatbot Application Workflow example with Webhook Integration
**Archivo:** `1354_HTTP_Respondtowebhook_Automate_Webhook.json`
**Descripción:** Ejemplo de workflow para aplicación de chatbot en Bitrix24
**Complejidad:** Media (13 nodos)
**Estado:** Activo
**Trigger:** Webhook
**Integraciones:** Httprequest, Webhook, Respondtowebhook

---

#### 📈 Bitrix24 Chatbot Application Workflow example with Webhook Integration (v2)
**Archivo:** `1827_HTTP_Respondtowebhook_Automate_Webhook.json`
**Descripción:** Segunda versión del workflow de Bitrix24
**Complejidad:** Media (13 nodos)
**Estado:** Activo
**Trigger:** Webhook
**Integraciones:** Httprequest, Webhook, Respondtowebhook

---

### 5. AI/Web Chatbots (4 workflows)

#### 🧠 Chatbot AI
**Archivo:** `1868_HTTP_Stickynote_Automate_Webhook.json`
**Descripción:** Chatbot AI genérico basado en web
**Complejidad:** Media (14 nodos)
**Estado:** Inactivo
**Trigger:** Complex
**Integraciones:** OpenAI, Webhook, Agent, Httprequest, Form Trigger

---

#### 📊 ✨Multi-AI Agent Chatbot for Postgres/Supabase DB and QuickCharts + Tool Router
**Archivo:** `1558_HTTP_Stickynote_Automate_Webhook.json`
**Descripción:** Chatbot multi-agente para bases de datos con gráficos
**Complejidad:** Alta (40 nodos)
**Estado:** Inactivo
**Trigger:** Complex
**Integraciones:** Executeworkflow, Lmchatopenai, Agent, Toolworkflow, Outputparserstructured, Httprequest, PostgreSQL, Chat, Postgrestool

---

#### 🎬 Building RAG Chatbot for Movie Recommendations with Qdrant and Open AI
**Archivo:** `1363_Splitout_GitHub_Create_Webhook.json`
**Descripción:** Bot de recomendaciones de películas con RAG
**Complejidad:** Alta (27 nodos)
**Estado:** Inactivo
**Trigger:** Complex
**Integraciones:** Textsplittertokensplitter, GitHub, OpenAI, Splitout, Agent, Extractfromfile, Httprequest, Documentdefaultdataloader, Vectorstoreqdrant, Chat, Executeworkflow, Cal.com, Memorybufferwindow

---

#### 🎬 Building RAG Chatbot for Movie Recommendations with Qdrant and Open AI (v2)
**Archivo:** `1798_Splitout_GitHub_Create_Webhook.json`
**Descripción:** Segunda versión del bot de recomendaciones de películas
**Complejidad:** Alta (27 nodos)
**Estado:** Inactivo
**Trigger:** Complex
**Integraciones:** Textsplittertokensplitter, GitHub, OpenAI, Splitout, Agent, Extractfromfile, Httprequest, Documentdefaultdataloader, Vectorstoreqdrant, Chat, Executeworkflow, Cal.com, Memorybufferwindow

---

### 6. Otros Chatbots (3 workflows)

#### 📞 Build a Chatbot, Voice Agent and Phone Agent with Voiceflow, Google Calendar and RAG
**Archivo:** `1361_GoogleCalendar_Webhook_Create_Webhook.json`
**Descripción:** Bot con capacidades de voz y teléfono usando Voiceflow
**Complejidad:** Alta (34 nodos)
**Estado:** Inactivo
**Trigger:** Complex
**Integraciones:** Textsplittertokensplitter, OpenAI, Google Drive, Webhook, Agent, Outputparserstructured, Httprequest, Chainllm, Vectorstoreqdrant, Documentdefaultdataloader, Cal.com, Toolvectorstore

---

#### 📋 POC - Chatbot Order by Sheet Data
**Archivo:** `1060_Automate_Webhook.json`
**Descripción:** Prueba de concepto para chatbot con datos de hojas de cálculo
**Complejidad:** Media (8 nodos)
**Estado:** Inactivo
**Trigger:** Webhook
**Integraciones:** Toolhttprequest, OpenAI, Agent, Chat, Cal.com, Memorybufferwindow

---

#### 🔧 modelo do chatbot
**Archivo:** `1350_Mysqltool_Stickynote_Automate_Webhook.json`
**Descripción:** Modelo de chatbot con base de datos MySQL
**Complejidad:** Media (12 nodos)
**Estado:** Inactivo
**Trigger:** Complex
**Integraciones:** Toolhttprequest, OpenAI, Mysqltool, PostgreSQL, Chat

---

## 🛠️ Tecnologías y Integraciones Comunes

### AI/LLM Providers:
- **OpenAI:** 16 workflows
- **Google Gemini:** 4 workflows
- **Anthropic:** 1 workflow
- **Groq/Llama3:** 1 workflow
- **Ollama:** 1 workflow

### Plataformas de Messaging:
- **Telegram:** 13 workflows
- **Line:** 2 workflows
- **Slack:** 1 workflow

### Sistemas de Memoria/Storage:
- **Google Drive/Docs:** 8 workflows
- **Google Sheets:** 3 workflows
- **PostgreSQL:** 4 workflows
- **Qdrant (Vector DB):** 6 workflows
- **Redis:** 1 workflow

### RAG y Vector Stores:
- **Qdrant:** 6 workflows
- **Pgvector:** 2 workflows
- **Document loaders:** 6 workflows
- **Text splitters:** 6 workflows

---

## 📝 Cómo Usar Estos Workflows

### Pasos para Importar:
1. **Descargar el archivo JSON** del workflow deseado desde la carpeta `workflows/`
2. **Abrir n8n** en tu instancia
3. **Ir a Menú (☰) → Import workflow**
4. **Seleccionar el archivo JSON**
5. **Configurar credenciales** y URLs de webhook antes de activar

### Consideraciones Importantes:
- ⚠️ **Actualizar credenciales** - Todos los workflows requieren configuración de API keys
- ⚠️ **Verificar webhooks** - URLs de webhook necesitan ser actualizadas
- ⚠️ **Dependencias** - Algunos workflows requieren nodos de comunidad adicionales
- ⚠️ **Versión n8n** - Verificar compatibilidad con tu versión de n8n

---

## 🏷️ Etiquetas de Búsqueda

`telegram-bot` `chatbot` `ai-assistant` `rag` `openai` `langchain` `webhook` `voice-bot` `helpdesk` `customer-support` `multi-session` `memory` `vector-database` `document-processing` `audio-transcription` `woocommerce` `slack-bot` `line-bot` `bitrix24` `confluence` `google-drive` `postgresql` `qdrant` `gemini` `anthropic`

---

*Esta documentación se genera automáticamente a partir de los archivos de workflow en el repositorio. Para contribuir con nuevos chatbots o mejorar los existentes, por favor sigue las pautas de contribución del proyecto.*