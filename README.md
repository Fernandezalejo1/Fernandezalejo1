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

### 🤖 media-intel-agents — Plataforma multi-agente con supervisión humana
Supervisor + cuatro agentes especialistas con tool calling, quality gate, human-in-the-loop con
aprobación y resume desde checkpoint, RAG, governance de costo/latencia y tracing estilo MLflow.
Motor de grafos con estado escrito desde cero (sin LangGraph).
`Python · FastAPI · 50 tests`

### ❄️ carnetruck — Monitoreo IoT de cadena de frío con trazabilidad auditable
Ingesta dual HTTP + MQTT con deduplicación idempotente, cadena de integridad SHA-256 encadenada por
lectura, multi-tenancy con JWT y certificados PDF regulatorios con endpoint que recomputa la integridad.
`FastAPI · TimescaleDB · React · Docker · 36 tests`

### ⚡ ironmind — RAG 100 % local en GPU
Pipeline YouTube → Whisper → embeddings → Qwen sobre el backend Vulkan de llama.cpp en una RDNA4,
con streaming y citas exactas de video y minuto. Cero bytes a la nube.
`Python · llama.cpp · faster-whisper · 21 tests`

### 💰 contabilia — SaaS de conciliación contable
Monorepo Turborepo con motor de 12 reglas priorizadas, cash application con pagos parciales y
aprendizaje continuo de alias. `NestJS · Next.js · Prisma · PostgreSQL`

### 🧾 conciliaya — Conciliación bancaria con IA (en producción)
Matching difuso (Levenshtein, RUT/CI, alias aprendidos) + Gemini para descifrar descripciones
bancarias. [**Demo en vivo**](https://conciliaya.vercel.app) · `TypeScript · React`

### 🏋️ kinetix — Entrenamiento basado en evidencia
Analytics de volumen (MEV/MAV/MRV), doble progresión, vault cifrado en reposo y **319 tests**.
[**Demo en vivo**](https://kinetix-science-based-hypertrophy-a.vercel.app) · `React · Vite · PWA`

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
