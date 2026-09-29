<div align="center">

# Alejo Fernández Di Piramo

### AI & Automation Engineer — LLM agents · RAG · Python backends

Montevideo, Uruguay (UTC-3) · Remote · [LinkedIn](https://www.linkedin.com/in/alejofernandezdipiramo) · alejofdipiramo@gmail.com

Construyo sistemas con IA que corren de verdad: agentes con aprobación humana, RAG local sobre GPU propia,
y backends con datos temporales e integridad auditable.
Vengo de operaciones IT (ITIL, ServiceNow, SLA) y automaticé con Python lo que antes era manual.

</div>

---

## Obra seleccionada

### 🔬 [llm-lab](https://github.com/Fernandezalejo1/llm-lab) — Laboratorio de LLM local con método
Cuatro fases medidas sobre una GPU de 16 GB: baseline, RAG híbrido, QLoRA y GRPO con recompensa
verificable. Harness congelado entre comparaciones y resultados negativos publicados tal cual
(el QLoRA attention-only no movió el agregado). Incluye las corridas crudas.
`Python · Unsloth · TRL · PEFT · llama.cpp`

### 🤖 [media-intel-agents](https://github.com/Fernandezalejo1/media-intel-agents) — Plataforma multi-agente con supervisión humana
Supervisor + cuatro agentes especialistas con tool calling, quality gate, human-in-the-loop con
aprobación y resume desde checkpoint, RAG, governance de costo/latencia y tracing estilo MLflow.
Motor de grafos con estado escrito desde cero (sin LangGraph).
`Python · FastAPI · 50 tests`

### ❄️ [carnetruck](https://github.com/Fernandezalejo1/carnetruck) — Monitoreo IoT de cadena de frío con trazabilidad auditable
Ingesta dual HTTP + MQTT con deduplicación idempotente, cadena de integridad SHA-256 encadenada por
lectura, multi-tenancy con JWT y certificados PDF regulatorios con endpoint que recomputa la integridad.
`FastAPI · TimescaleDB · React · Docker · 36 tests`

<a href="https://github.com/Fernandezalejo1/carnetruck"><img src="https://raw.githubusercontent.com/Fernandezalejo1/carnetruck/main/assets/screenshots/02-dashboard.png" alt="Carnetruck - Dashboard" width="720"></a>

### ⚡ [ironmind](https://github.com/Fernandezalejo1/ironmind) — RAG 100 % local en GPU
Pipeline YouTube → Whisper → embeddings → Qwen sobre el backend Vulkan de llama.cpp en una RDNA4,
con streaming y citas exactas de video y minuto. Cero bytes a la nube.
`Python · llama.cpp · faster-whisper · 21 tests`

<a href="https://github.com/Fernandezalejo1/ironmind"><img src="https://raw.githubusercontent.com/Fernandezalejo1/ironmind/main/assets/screenshots/01-chat-inicial.png" alt="IronMind - Chat" width="720"></a>

### 🔍 [project-analyzer](https://github.com/Fernandezalejo1/project-analyzer) — Auditor de código con reporte ejecutivo
Analiza arquitectura, dependencias, secretos filtrados, vulnerabilidades y performance, y entrega un
reporte puntuado. Corrigiendo el propio analizador aparecieron tres bugs reales: falsos positivos en
`.env.example`, CORS bloqueando el frontend y SQL por f-string no detectado.
`Python · FastAPI · React · Docker · 28 tests`

<a href="https://github.com/Fernandezalejo1/project-analyzer"><img src="https://raw.githubusercontent.com/Fernandezalejo1/project-analyzer/master/docs/screenshots/01-home.png" alt="project-analyzer - Inicio" width="720"></a>

### 🏋️ [kinetix](https://github.com/Fernandezalejo1/kinetix) — Entrenamiento basado en evidencia
Analytics de volumen (MEV/MAV/MRV), doble progresión, vault cifrado en reposo y **319 tests**.
[**Demo en vivo**](https://kinetix-science-based-hypertrophy-a.vercel.app) · `React · Vite · PWA`

<a href="https://github.com/Fernandezalejo1/kinetix"><img src="https://raw.githubusercontent.com/Fernandezalejo1/kinetix/master/screenshots/workout-home.png" alt="Kinetix - Inicio y Entreno" width="720"></a>

### 🚶 [mas-seguro](https://github.com/Fernandezalejo1/mas-seguro) — Navegación peatonal segura para Montevideo
Safety Score por tramo, comparación de rutas y reportes de ciudadanos sobre OpenStreetMap, con IA de
Google Gemini opcional y fallback heurístico cuando no hay API key.
`React · Supabase · Leaflet · TypeScript`

<a href="https://github.com/Fernandezalejo1/mas-seguro"><img src="https://raw.githubusercontent.com/Fernandezalejo1/mas-seguro/main/assets/Dashboard.png" alt="Más Seguro - Dashboard" width="720"></a>

### 💸 [conciliaya](https://github.com/Fernandezalejo1/conciliaya) — Conciliación bancaria con motor local de reglas
Matching difuso, alias aprendidos y un motor de reglas determinista para descripciones bancarias
crípticas, con aplicación de pagos parciales, reversión contable y asientos balanceados.
**Sin IA externa**: todo corre en el cliente y el cruce es reproducible.
[**Demo en vivo**](https://conciliaya.vercel.app) · `React · TypeScript · Vite`

<a href="https://github.com/Fernandezalejo1/conciliaya"><img src="https://raw.githubusercontent.com/Fernandezalejo1/conciliaya/master/assets/01-dashboard.png" alt="ConciliaYA - Dashboard" width="720"></a>

<sub>También en público: [contabilia](https://github.com/Fernandezalejo1/contabilia) (SaaS de conciliación contable, 12 reglas priorizadas).</sub>

---

## Stack que uso a diario

```
Python     FastAPI · Pydantic · SQLAlchemy 2 · Alembic · Celery · pytest
TypeScript React · Next.js · Vite · NestJS · Tailwind · PWA / Capacitor
Datos      PostgreSQL · TimescaleDB · Supabase · Prisma · SQLite
IA / LLM   agentes con tools · RAG (BM25 + denso) · embeddings · Whisper
           QLoRA + GRPO (Unsloth · TRL · PEFT) · llama.cpp (Vulkan) · Gemini
Infra      Docker / Compose · GitHub Actions (CI) · Vercel · Railway
```

---

<sub>Más de 400 tests escritos sobre mis propios proyectos, con CI en los principales. Estudio metodología de IA local (baselines medibles, QLoRA/GRPO con recompensa verificable) y documento también los resultados negativos.</sub>
