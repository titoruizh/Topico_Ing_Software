# Aseguramiento de calidad de procesos y productos

# Diagrama 1: Aseguramiento de Calidad de Procesos y Productos – Visión General
### Este diagrama es la introducción conceptual, muestra el objetivo, propósito y notas clave de la gestión de calidad a nivel organizacional. Es general, estratégico y descriptivo.

```mermaid
graph LR
    A[🎯 ASEGURAMIENTO DE CALIDAD<br/>PROCESOS Y PRODUCTOS]
    
    A --> B1[📌 OBJETIVOS]
    A --> B2[🎯 PROPÓSITO]
    A --> B3[📝 NOTAS CLAVE]

    B1 --> C1[Visión objetiva de procesos]
    B1 --> C2[Cumplimiento de estándares]
    B1 --> C3[Mejora continua]

    B2 --> C4[Reducción de retrabajos]
    B2 --> C5[Compliance ISO/CMMI/GDPR]
    B2 --> C6[Confianza del cliente]

    B3 --> C7[Esfuerzo: 8-12% del proyecto]
    B3 --> C8[Revisiones periódicas]
    B3 --> C9[Integrado en DevOps/CI-CD]

    style A fill:#2C3E50,stroke:#1A252F,stroke-width:4px,color:#FFF
    style B1 fill:#3498DB,stroke:#2874A6,color:#FFF
    style B2 fill:#27AE60,stroke:#1E8449,color:#FFF
    style B3 fill:#E67E22,stroke:#CA6F1E,color:#FFF
```

# Diagrama 2: Ciclo de Aseguramiento de Calidad – Planificación y Evaluación
### Aquí se muestra el flujo repetible del proceso QA, desde planificación hasta retroalimentación y mejora continua. Este es operativo, describe actividades, decisiones y entregables.

```mermaid
graph LR
    A[CICLO DE<br/>ASEGURAMIENTO<br/>DE CALIDAD] --> B[Planificación]
    A --> C[Evaluación]
    A --> D[Registro]
    A --> E[Mejora<br/>Continua]

    B --> B1[Objetivos y<br/>criterios medibles]
    B --> B2[Recursos y<br/>herramientas]

    C --> C1[Auditoría de<br/>procesos]
    C --> C2[Evaluación<br/>de productos]

    D --> D1[Hallazgos y<br/>no conformidades]
    D --> D2[Reportes<br/>ejecutivos]

    E --> E1[Analizar<br/>tendencias]
    E --> E2[Actualizar<br/>procesos]

    style A fill:#2C3E50,stroke:#1A252F,stroke-width:2px,color:#FFF
    style B fill:#3498DB,stroke:#2874A6,color:#FFF
    style C fill:#27AE60,stroke:#1E8449,color:#FFF
    style D fill:#F39C12,stroke:#CA6F1E,color:#FFF
    style E fill:#16A085,stroke:#138D75,color:#FFF
```

# Diagrama 3: Matriz de Responsabilidades y Participación en QA
### Este diagrama detalla a los actores (Alta Dirección, Dirección de Calidad, Jefe de Proyecto, Dev, QA, externos) y su interacción, incluyendo la mejora continua. Es útil para entender quién hace qué y cómo se conectan los roles.

```mermaid
graph LR
    A[🎯 ASEGURAMIENTO<br/>DE CALIDAD]
    
    A --> B[👔 Alta Dirección]
    A --> C[👨‍💼 Dirección QA]
    A --> D[📊 Jefe Proyecto]
    A --> E[💻 Desarrollo]
    A --> F[🔍 Equipo QA]
    A --> H[🤝 Externos]
    
    B --> B1[Políticas y presupuesto]
    
    C --> C1[Estrategia y métricas]
    C --> C2[Dirección equipo QA]
    
    D --> D1[Integra QA en cronograma]
    D --> D2[Define criterios de aceptación]
    
    E --> E1[Unit tests]
    E --> E2[CI/CD + quality gates]
    
    F --> F1[Auditorías]
    F --> F2[Testing funcional]
    F --> F3[Reportes de métricas]
    
    H --> H1[Cliente - UAT]
    H --> H2[Auditor - Compliance]
    
    F --> I[🔄 Mejora Continua]
    I --> A
    
    style A fill:#2C3E50,stroke:#1A252F,stroke-width:4px,color:#FFF
    style B fill:#2980B9,stroke:#1F618D,color:#FFF
    style C fill:#27AE60,stroke:#1E8449,color:#FFF
    style D fill:#E67E22,stroke:#BA4A00,color:#FFF
    style E fill:#9B59B6,stroke:#7D3C98,color:#FFF
    style F fill:#C0392B,stroke:#922B21,color:#FFF
    style H fill:#7F8C8D,stroke:#626567,color:#FFF
    style I fill:#16A085,stroke:#117864,stroke-width:3px,color:#FFF
```



# Diagrama 4: Tecnología / Herramientas
### Este último diagrama muestra la infraestructura y herramientas que soportan QA: dashboards, gestión de proyectos, análisis de código, pruebas, seguridad, CI/CD, datos y notificaciones. Es técnico y operativo.

```mermaid
graph LR
    START[🎯 STACK TECNOLÓGICO DE QA]

    %% Agrupando herramientas por áreas clave
    START --> A[📊 Visualización]
    START --> B[🛠️ Gestión]
    START --> C[📏 Código]
    START --> D[🧪 Testing]
    
    A --> A1[Power BI / Grafana<br>Métricas en tiempo real]
    
    B --> B1[JIRA / Azure DevOps<br>TestRail / Zephyr]
    
    C --> C1[SonarQube<br>GitHub / GitLab]
    
    D --> D1[JUnit / Selenium<br>Postman / JMeter]

    %% Seguridad y despliegue
    START --> E[🔐 Seguridad]
    START --> F[🚀 CI/CD]
    
    E --> E1[Fortify / OWASP ZAP<br>Snyk / Vault]
    
    F --> F1[Jenkins / GitHub Actions<br>Docker / Kubernetes]
    
    %% Ciclo completo
    F1 --> FIN[✅ Monitoreo y alerta<br>Prometheus / Slack]
    FIN -.->|Retroalimentación| A1

    %% Estilos
    style START fill:#8E44AD,stroke:#6C3483,stroke-width:4px,color:#FFF
    style A fill:#3498DB,stroke:#2874A6,color:#FFF
    style B fill:#1ABC9C,stroke:#148F77,color:#FFF
    style C fill:#27AE60,stroke:#1E8449,color:#FFF
    style D fill:#F39C12,stroke:#CA6F1E,color:#FFF
    style E fill:#E74C3C,stroke:#C0392B,color:#FFF
    style F fill:#9B59B6,stroke:#7D3C98,color:#FFF
    style FIN fill:#16A085,stroke:#138D75,stroke-width:4px,color:#FFF
```
    
