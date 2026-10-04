<!-- Nombre y título -->
<p align="center">
  <img src="https://github.com/Lamk-S/Lamk-S/blob/main/lamk.svg" width="720" />
</p>

<p align="center">
  <strong>Full Stack Developer | React, Next.js, Laravel, Flutter, Supabase</strong><br>
  Transformo problemas reales en productos escalables con arquitectura offline-first y DDD.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/lamk-sd"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:kunlancelot@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/Lamk-S"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/></a>
  <img src="https://img.shields.io/badge/Remote-EU%20%7C%20CET-0969DA?style=flat-square" alt="Remote CET"/>
  <img src="https://img.shields.io/badge/Location-Trujillo%20PE%20%7C%20Remote-lightgrey?style=flat-square" alt="Location"/>
</p>

---

### Sobre mí

Full Stack Developer (Ingeniería de Sistemas – UNT) enfocado en producto. Mi trabajo va más allá del feature: diseño arquitecturas que sobreviven sin internet, con datos financieros inmutables y sincronización resiliente.

- **Actualmente:** Construyendo plataformas PWA y sistemas POS para retail con Next.js 19, Supabase (RLS) y Flutter Clean Architecture.
- **Especialidad:** Offline-first con Dexie.js/IndexedDB, Row Level Security en PostgreSQL, anti time-spoofing y trazabilidad de auditoría.
- **Buscando:** Oportunidades remotas EU (CET) como Full Stack / Frontend Heavy. Autónomo, incorporación inmediata.

---

### Proyectos Destacados

> Todos con CI, testing y documentación técnica. Código abierto, pensado para producción.

#### 1. [LamkSew: Sistema de Producción Offline-First](https://github.com/Lamk-S/sewing-system)
PWA transaccional para gestión de pagos a destajo en manufactura textil. Diseñada para operar 100% sin conexión en talleres con WiFi inestable.

**Decisiones de ingeniería:**
- Sync resiliente con `local_id` (UUID) e idempotencia en upserts a Supabase
- Inmutabilidad financiera (`precio_aplicado`) + triggers PostgreSQL contra manipulación de reloj
- RBAC real con RLS: `trabajador_id = auth.uid()` y `get_user_rol()` en JWT
- `useLiveQuery` (Dexie) para operarios, TanStack Query para dashboard admin

`React 19` `TypeScript` `Supabase (PostgreSQL + RLS)` `Dexie.js` `TanStack Query` `Tailwind v4` `Playwright`

#### 2. [Ecosistema Lamk Shop](https://github.com/Lamk-S/lamk-shop) + [LamkScan Mobile](https://github.com/Lamk-S/lamk-sp-scanner)
Sistema POS & inventario para retail deportivo + app móvil de escaneo. Flujo de caja optimizado para alto volumen.

**Decisiones de ingeniería:**
- Catálogo multidimensional: variantes SKU, líneas/marcas y calibres de tallas
- Pagos mixtos (Efectivo, Tarjeta, Yape, Plin) y creación de cliente en tiempo real
- Auditoría completa: timestamp, usuario e IP por movimiento
- App Flutter Clean Architecture con `mobile_scanner`, mecanismo de cooldown anti-duplicados e historial local persistente

`Laravel 12` `PHP 8.x` `MySQL` `Bootstrap 5` `Flutter` `Dart` `Clean Architecture`

#### 3. [PokeGuide – Competitive Pokémon Intelligence Platform](https://github.com/Lamk-S/PokeGuide)
Plataforma que unifica motores competitivos con reglas generacionales precisas (Gen III vs Gen IX). Mi proyecto más orientado a DDD y calidad.

**Decisiones de ingeniería:**
- Dominio 100% aislado de React – Stat Engine generation-aware sin `if` anidados
- Breeding Planner con BFS deduplicada mediante State Hashing
- Validación inteligente EVs: `maxForThisStat = min(252, remaining)` y naturaleza i18n ES
- Quality Gate: Vitest + Playwright + typecheck + lint en GitHub Actions

`Next.js 16` `TypeScript` `Vitest` `Playwright` `Biome` `PokeAPI`

---

### Stack

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=ts,js,python,react,nextjs,vue,laravel,supabase,postgresql,mysql,dart,flutter,nodejs,git,docker,linux&perline=8" alt="Tech Stack" />
  </a>
</p>

**Frontend:** React 19, Next.js 15, Vue.js, Tailwind CSS v4, Radix UI, Bootstrap 5  
**Backend:** Laravel, Node.js / Express, Django, Flask, Supabase (Auth, RLS, Realtime)  
**Mobile:** Flutter (Clean Arch), Ionic  
**Data:** PostgreSQL, MySQL, SQL Server, IndexedDB (Dexie.js), BigQuery  
**Testing & DevOps:** Vitest, Playwright, GitHub Actions, pnpm, Vite

---

### Principios de trabajo

- **Zero Trust en BD:** La lógica crítica vive en PostgreSQL (RLS + triggers), no solo en la UI.
- **Offline-first real:** Primero IndexedDB, luego sync. No "loading" que bloquea al operario.
- **Código medible:** Typecheck estricto contra schema de Supabase, tests de mutaciones offline con fake-indexeddb.

---

### Métricas

<p align="center">
  <!-- Estadísticas Generales -->
  <picture>
    <source srcset="https://github-readme-stats.anuraghazra1.vercel.app/api?username=Lamk-S&show_icons=true&theme=transparent&hide_border=true&title_color=0969da&text_color=24292f&icon_color=0969da">
    <img alt="Estadísticas de Melvin" src="https://github-readme-stats.anuraghazra1.vercel.app/api?username=Lamk-S&show_icons=true&theme=transparent&hide_border=true&title_color=58A6FF&text_color=C9D1D9&icon_color=58A6FF" width="48%" />
  </picture>

  <!-- Racha de GitHub (Streak) -->
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=Lamk-S&theme=transparent&hide_border=true&title_color=58A6FF&text_color=C9D1D9&icon_color=58A6FF">
    <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com/?user=Lamk-S&theme=transparent&hide_border=true&title_color=0969da&text_color=24292f&icon_color=0969da">
    <img alt="Racha de GitHub" src="https://streak-stats.demolab.com/?user=Lamk-S&theme=transparent&hide_border=true&title_color=58A6FF&text_color=C9D1D9&icon_color=58A6FF" width="48%" />
  </picture>
</p>

<p align="center">
  <i>"Construyendo software que funciona donde otros fallan: sin internet."</i><br>
  <sub>Trujillo, Perú · Remoto CET · <a href="mailto:kunlancelot@gmail.com">kunlancelot@gmail.com</a> · Última actualización: Octubre 2026</sub>
</p>
