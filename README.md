<!--
══════════════════════════════════════════════════════════════════════════════
  GitHub Profile README
  Author: Juan Dominid Muñoz Eslava
  Username: DominidM
══════════════════════════════════════════════════════════════════════════════
-->

<div align="center">

<img
  width="100%"
  src="https://capsule-render.vercel.app/api?type=waving&height=160&color=0:020617,45:0F172A,100:0284C7&text=Juan%20Dominid%20Mu%C3%B1oz%20Eslava&fontColor=F8FAFC&fontSize=36&fontAlignY=35&desc=Software%20Architecture%20%E2%80%A2%20Full%20Stack%20Development%20%E2%80%A2%20Technology&descAlignY=58&descSize=16&animation=fadeIn"
/>

<a href="https://github.com/DenverCoder1/readme-typing-svg">
  <img
    src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=38BDF8&center=true&vCenter=true&width=850&height=70&lines=Co-Founder+%40+Solvegrades+Technology;Software+Architecture+%26+Full+Stack+Development;ERPs+%7C+Microservices+%7C+Cloud+Solutions;Spring+Boot+%7C+NestJS+%7C+Angular;Hexagonal+Architecture+%7C+Clean+Architecture;Building+technology+with+real-world+impact"
    alt="Typing introduction"
  />
</a>

<br>

<a href="https://dominidm.github.io/">
  <img src="https://img.shields.io/badge/Portfolio-Explore_my_work-020617?style=for-the-badge&logo=githubpages&logoColor=38BDF8" alt="Portfolio">
</a>
<a href="https://solvegrades.com/nosotros/">
  <img src="https://img.shields.io/badge/Solvegrades-Co--Founder-4C1D95?style=for-the-badge&logo=rocket&logoColor=white" alt="Solvegrades">
</a>
<a href="https://www.linkedin.com/in/juan-dominid-mu%C3%B1oz-eslava-50b68828a/">
  <img src="https://img.shields.io/badge/LinkedIn-Let's_connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>
<a href="https://leetcode.com/u/Dominid/">
  <img src="https://img.shields.io/badge/LeetCode-Solve_with_me-FFA116?style=for-the-badge&logo=leetcode&logoColor=111827" alt="LeetCode">
</a>

<br><br>

<img
  src="https://komarev.com/ghpvc/?username=DominidM&label=Profile+views&color=0284C7&style=flat"
  alt="Profile views"
/>

</div>

---

## `> whoami`

```yaml
name: Juan Dominid Muñoz Eslava
role: Co-Founder & Full Stack Developer
company: Solvegrades Technology
focus:
  - Software Architecture
  - Enterprise Resource Planning
  - Microservices
  - Cloud-native Applications
  - Real-time Systems
education:
  degree: Computer Systems Engineering
  institution: UPN
  status: Final academic stage
currently_building:
  - Scalable business platforms
  - Citizen-impact technology
  - Environmental monitoring solutions
```

Soy desarrollador Full Stack orientado a la **arquitectura de software**, con experiencia diseñando soluciones empresariales desde cero y convirtiendo necesidades complejas en sistemas seguros, escalables y mantenibles.

Como **Co-Founder de Solvegrades Technology**, participo en el análisis, arquitectura y desarrollo de plataformas a medida, especialmente ERPs, sistemas de logística, aplicaciones cloud y servicios con comunicación en tiempo real.

- Arquitectura de sistemas con enfoque **hexagonal y clean architecture**.
- Diseño de **ERPs para importación, logística y gestión empresarial**.
- Integración de autenticación y autorización mediante **JWT + RBAC**.
- Implementación de comunicación en tiempo real con **WebSockets**.
- Integración de servicios relacionados con **facturación electrónica SUNAT**.
- Diseño de APIs, microservicios y sistemas desplegados en infraestructura cloud.
- Interés en proyectos con impacto **educativo, social y ambiental**.

---

## 🧭 Engineering mindset

```text
Understand the problem
        ↓
Model the business domain
        ↓
Design clear boundaries
        ↓
Build secure and testable components
        ↓
Measure, improve and scale
```

> No desarrollo solamente funcionalidades. Diseño sistemas capaces de evolucionar sin convertir cada nuevo requerimiento en un problema.

---

## 🚀 Selected projects

### 🌐 ComuniRed

Una plataforma de participación ciudadana diseñada para registrar reportes comunitarios y facilitar que las entidades municipales puedan realizar seguimiento, gestionar evidencias y comunicar soluciones.

```yaml
architecture:
  backend: Spring Boot
  frontend: Angular
  database: MongoDB Atlas
  api: GraphQL
  realtime: WebSockets
  cloud: Azure
  edge_and_security: Cloudflare
```

**Principales retos abordados:**

- Comunicación en tiempo real.
- Seguimiento del ciclo de vida de los reportes.
- Organización de información georreferenciada.
- Separación de responsabilidades entre ciudadanos y entidades.
- Diseño de infraestructura preparada para crecimiento.

---

### 🌊 OceanEyes

**Proyecto participante en Hult Prize UPN 2026**

Plataforma tecnológica orientada a la protección de ecosistemas marinos y al monitoreo de actividades relacionadas con la pesca ilegal.

```yaml
ecosystem:
  mobile_application:
    technology: Flutter
    capabilities:
      - GPS
      - Citizen reports
      - Field evidence

  monitoring_devices:
    capabilities:
      - Water quality sensors
      - Environmental telemetry

  web_dashboard:
    technology: Angular
    capabilities:
      - Georeferenced visualization
      - Incident monitoring
      - Environmental data analysis
```

El objetivo es conectar aplicaciones móviles, dispositivos de monitoreo y dashboards web en un ecosistema tecnológico que permita transformar datos ambientales en acciones oportunas.

---

## 🏗️ Architecture toolbox

<div align="center">

```mermaid
flowchart LR
    C[Clients] --> G[API Gateway]
    G --> A[Authentication]
    G --> S1[Business Service]
    G --> S2[Notification Service]
    G --> S3[Reporting Service]

    S1 --> DB1[(SQL Database)]
    S2 --> MQ[(RabbitMQ)]
    S3 --> DB2[(MongoDB)]

    MQ --> WS[WebSocket Gateway]
    WS --> C
```

</div>

Mi enfoque arquitectónico suele considerar:

- Separación entre dominio, aplicación e infraestructura.
- Límites claros entre módulos y servicios.
- Seguridad basada en roles y permisos.
- Eventos y mensajería para procesos desacoplados.
- Observabilidad y control de errores.
- Estrategias de despliegue con contenedores.
- Diseño preparado para evolución progresiva.

---

## 🧰 Technology stack

### Backend & APIs

<div align="center">

<img src="https://skillicons.dev/icons?i=spring,nestjs,nodejs,express,java,ts,js&theme=dark" alt="Backend technologies">

</div>

### Frontend & Mobile

<div align="center">

<img src="https://skillicons.dev/icons?i=angular,nextjs,react,flutter,html,css&theme=dark" alt="Frontend technologies">

</div>

### Databases & Messaging

<div align="center">

<img src="https://skillicons.dev/icons?i=postgres,mongodb,mysql,rabbitmq,supabase&theme=dark" alt="Database technologies">

<br>

<img
  src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"
  alt="SQL Server"
/>

</div>

### Cloud, DevOps & Tools

<div align="center">

<img src="https://skillicons.dev/icons?i=azure,docker,cloudflare,git,github,postman,linux,vscode&theme=dark" alt="Cloud and development tools">

</div>

---

## 🧬 Developer profile

```typescript
type Architecture =
  | "Hexagonal Architecture"
  | "Clean Architecture"
  | "Modular Monolith"
  | "Microservices";

interface DeveloperProfile {
  role: string[];
  architecture: Architecture[];
  backend: string[];
  frontend: string[];
  infrastructure: string[];
  principles: string[];
}

const dominid: DeveloperProfile = {
  role: [
    "Co-Founder",
    "Software Architect",
    "Full Stack Developer"
  ],

  architecture: [
    "Hexagonal Architecture",
    "Clean Architecture",
    "Modular Monolith",
    "Microservices"
  ],

  backend: [
    "Spring Boot",
    "NestJS",
    "Express",
    "GraphQL",
    "WebSockets"
  ],

  frontend: [
    "Angular",
    "Next.js",
    "Flutter"
  ],

  infrastructure: [
    "Docker",
    "Azure",
    "Cloudflare",
    "RabbitMQ",
    "Supabase"
  ],

  principles: [
    "Security by design",
    "Maintainability",
    "Clear boundaries",
    "Business-oriented software",
    "Continuous improvement"
  ]
};

function buildSolution(problem: string): string {
  return `Analyze ${problem}, model the domain, design the architecture and ship value.`;
}
```

---

## 📊 GitHub analytics

<div align="center">

<img
  height="180"
  src="https://github-readme-stats.vercel.app/api?username=DominidM&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&theme=github_dark&title_color=38BDF8&icon_color=38BDF8&text_color=CBD5E1&bg_color=0D1117"
  alt="GitHub statistics"
/>

<img
  height="180"
  src="https://github-readme-stats.vercel.app/api/top-langs/?username=DominidM&layout=compact&hide_border=true&langs_count=8&theme=github_dark&title_color=38BDF8&text_color=CBD5E1&bg_color=0D1117"
  alt="Most used languages"
/>

</div>

> Las estadísticas de lenguajes representan principalmente la composición de los repositorios públicos y no determinan por sí solas el nivel de dominio técnico.

<div align="center">

<img
  width="95%"
  src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=DominidM&theme=github_dark"
  alt="GitHub profile summary"
/>

</div>

---

## 🐍 Contribution activity

<div align="center">

<img
  src="https://raw.githubusercontent.com/DominidM/DominidM/output/github-contribution-grid-snake-dark.svg"
  alt="Contribution snake animation"
/>

</div>

> Si la animación todavía no aparece, debes instalar el workflow incluido más abajo.

---

## 🎯 Current roadmap

```text
[████████████████░░░░] Software Architecture
[███████████████░░░░░] Distributed Systems
[██████████████░░░░░░] Cloud Engineering
[████████████░░░░░░░░] DevOps & Observability
[██████████░░░░░░░░░░] Artificial Intelligence Integration
```

Actualmente estoy profundizando en:

- Patrones para sistemas distribuidos.
- Observabilidad y monitoreo de aplicaciones.
- Arquitecturas orientadas a eventos.
- Automatización de despliegues.
- Optimización de rendimiento.
- Integración responsable de inteligencia artificial en productos de software.

---

## 🤝 Let's build something meaningful

Estoy abierto a colaborar en:

- Plataformas educativas.
- Sistemas empresariales y ERPs.
- Aplicaciones de impacto ciudadano.
- Tecnología para sostenibilidad y medioambiente.
- Arquitecturas backend y APIs escalables.
- Proyectos open source.

<div align="center">

<a href="https://www.linkedin.com/in/juan-dominid-mu%C3%B1oz-eslava-50b68828a/">
  <img src="https://img.shields.io/badge/Let's_connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Contact on LinkedIn">
</a>

<a href="https://dominidm.github.io/">
  <img src="https://img.shields.io/badge/View_my_portfolio-020617?style=for-the-badge&logo=githubpages&logoColor=38BDF8" alt="View portfolio">
</a>

</div>

<br>

<div align="center">

### “Architecture is not about adding complexity. It is about controlling it.”

<img
  width="100%"
  src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:0284C7,55:0F172A,100:020617&section=footer"
/>

</div>
