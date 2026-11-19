# Hola, soy Yoscar 👋

**Backend Engineer** · Node.js / NestJS / TypeScript · AWS
📍 Venezuela (remoto)

Llevo más de 7 años construyendo y operando sistemas backend en producción en el sector salud, y 10 años desarrollando software. Mi foco es la **ingesta y el procesamiento de datos de salud en tiempo real** desde wearables y sensores de glucosa (CGM): APIs, procesamiento asíncrono con colas y consistencia de datos frente a lecturas duplicadas, desordenadas o tardías.

## 🛠️ Stack

- **Backend:** Node.js · TypeScript · NestJS · Express · APIs REST · OpenAPI
- **Datos:** MongoDB / Atlas · Redis · MySQL · PostgreSQL
- **Cloud e infraestructura:** AWS (EC2, S3, SQS, ElastiCache, CloudFront, IAM) · Docker · GitHub Actions
- **Observabilidad:** Prometheus · Grafana · OpenTelemetry
- **Calidad:** Jest · code review
- **Desarrollo con IA:** Claude Code · Spec-Driven Development

## 🚀 Algunas cosas que he construido

- **Migración de Express a NestJS con el patrón strangler:** la API legada recibe todo el tráfico y reenvía a NestJS las rutas ya migradas. Migramos por etapas sin cambios para los clientes.
- **Ingesta de glucosa en tiempo real:** unas 47.000 peticiones diarias, con escrituras idempotentes y locks distribuidos para que ninguna lectura se pierda ni se duplique.
- **Motor de ingesta modular:** reemplacé un flujo secuencial de más de 1.000 líneas por un pipeline configurable de adaptación, validación, normalización y agregación.
- **Infraestructura AWS desde cero:** reconstruí QA y producción, y monté la plataforma de observabilidad.

> El código de mi trabajo es privado. Aquí iré publicando proyectos personales.

## 📚 Aprendiendo ahora

- Arquitectura hexagonal y DDD
- Kubernetes

## 📫 Contacto

[LinkedIn](https://www.linkedin.com/in/yoscar-rafael-hernandez-210a8a159)
