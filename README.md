# Topico_Ing_Software

# Diagrama 1

```mermaid
graph TD
    A[ASEGURAMIENTO DE CALIDAD DE PROCESOS Y PRODUCTOS<br/>PPQA - Process and Product Quality Assurance]
    
    A --> B[OBJETIVO GENERAL]
    A --> C[PROPÓSITO ESTRATÉGICO]
    A --> D[NOTAS INTRODUCTORIAS]
    
    B --> B1[Proporcionar al personal y la gerencia<br/>una visión objetiva de los procesos<br/>y productos de trabajo asociados]
    B --> B2[Garantizar que los procesos definidos<br/>se ejecuten según lo planificado y<br/>cumplan con los estándares organizacionales]
    B --> B3[Identificar y documentar incumplimientos<br/>en procesos y productos para su<br/>resolución oportuna]
    B --> B4[Establecer mecanismos de retroalimentación<br/>que promuevan la mejora continua<br/>en toda la organización]
    
    C --> C1[Reducir costos asociados a defectos<br/>y retrabajos mediante detección temprana<br/>de desviaciones - ROI: 300-500%]
    C --> C2[Mantener conformidad con normativas<br/>ISO 9001, CMMI, ISO 27001, GDPR<br/>y regulaciones industriales específicas]
    C --> C3[Incrementar la confianza del cliente<br/>en la capacidad de entrega de<br/>productos de alta calidad]
    C --> C4[Habilitar certificaciones y auditorías<br/>externas que agreguen valor comercial<br/>y competitivo a la organización]
    
    D --> D1[CONTEXTO ORGANIZACIONAL:<br/>El PPQA opera como función transversal<br/>que atraviesa todos los proyectos<br/>y áreas de desarrollo de software]
    D --> D2[MÉTRICAS CLAVE:<br/>- Esfuerzo: 8-12% del esfuerzo total del proyecto<br/>- Tiempo: Revisiones cada 2-4 semanas<br/>- Cobertura: 100% de hitos críticos]
    D --> D3[ALCANCE:<br/>Incluye código fuente, documentación técnica,<br/>artefactos de diseño, casos de prueba,<br/>configuraciones, y entregables al cliente]
    D --> D4[INDEPENDENCIA:<br/>El equipo QA debe reportar a nivel<br/>organizacional, no al gerente de proyecto,<br/>para garantizar objetividad y autonomía]
    D --> D5[ENFOQUE PREVENTIVO Y CORRECTIVO:<br/>No solo detectar problemas sino prevenir<br/>su ocurrencia mediante capacitación,<br/>templates, checklists y automatización]
    D --> D6[INTEGRACIÓN CONTINUA:<br/>Integrar QA en DevOps/CI-CD pipeline<br/>con gates de calidad automatizados<br/>y métricas en tiempo real]
    
    style A fill:#2C3E50,stroke:#E74C3C,stroke-width:4px,color:#ECF0F1
    style B fill:#3498DB,stroke:#2980B9,stroke-width:3px,color:#FFF
    style C fill:#27AE60,stroke:#229954,stroke-width:3px,color:#FFF
    style D fill:#E67E22,stroke:#D35400,stroke-width:3px,color:#FFF
```

# Diagrama 2

```mermaid
graph TB
    START[INICIO DEL CICLO DE ASEGURAMIENTO DE CALIDAD]
    
    START --> PLAN[PLANIFICACIÓN DEL ASEGURAMIENTO DE CALIDAD]
    
    PLAN --> PLAN1[Establecer objetivos específicos de QA<br/>alineados con metas organizacionales<br/>y requisitos del proyecto]
    PLAN --> PLAN2[Definir criterios de aceptación objetivos<br/>y medibles para procesos y productos<br/>Ej: Code coverage >80%, Zero critical bugs]
    PLAN --> PLAN3[Identificar procesos críticos a auditar<br/>Requisitos, Diseño, Implementación,<br/>Testing, Despliegue, Mantenimiento]
    PLAN --> PLAN4[Asignar recursos: presupuesto 10-15%,<br/>personal QA certificado ISTQB/CSTE,<br/>herramientas SonarQube, JIRA, Selenium]
    PLAN --> PLAN5[Crear Plan de Aseguramiento de Calidad<br/>QAP documentando schedule, deliverables,<br/>responsabilidades y riesgos]
    
    PLAN1 & PLAN2 & PLAN3 & PLAN4 & PLAN5 --> EVAL
    
    EVAL[EVALUACIÓN OBJETIVA]
    
    EVAL --> EVAL1[EVALUACIÓN DE PROCESOS<br/>Auditar adherencia a procesos definidos<br/>mediante observación, entrevistas,<br/>revisión de registros y evidencias]
    EVAL --> EVAL2[EVALUACIÓN DE PRODUCTOS<br/>Revisar productos de trabajo contra<br/>estándares y criterios establecidos<br/>usando checklists y herramientas automatizadas]
    EVAL --> EVAL3[Realizar evaluaciones programadas<br/>en hitos predefinidos: Kick-off, Design Review,<br/>Code Freeze, UAT, Go-Live]
    EVAL --> EVAL4[Conducir evaluaciones no programadas<br/>cuando se detecten riesgos emergentes<br/>o solicitudes de stakeholders clave]
    
    EVAL1 & EVAL2 & EVAL3 & EVAL4 --> REG
    
    REG[REGISTRO Y DOCUMENTACIÓN]
    
    REG --> REG1[Documentar hallazgos en<br/>Sistema de Gestión de Incidencias<br/>con severidad: Crítico/Alto/Medio/Bajo]
    REG --> REG2[Categorizar no conformidades:<br/>Defectos de producto, Desviaciones de proceso,<br/>Gaps de documentación, Riesgos de seguridad]
    REG --> REG3[Generar reportes ejecutivos con<br/>dashboards visuales: tendencias, hotspots,<br/>comparativas con baselines históricos]
    REG --> REG4[Mantener trazabilidad completa:<br/>Hallazgo → Acción correctiva → Verificación<br/>usando matriz de seguimiento]
    
    REG1 & REG2 & REG3 & REG4 --> ESC
    
    ESC[ESCALAMIENTO Y RESOLUCIÓN]
    
    ESC --> ESC1[Comunicar hallazgos al equipo<br/>de proyecto en reuniones formales<br/>con evidencias y recomendaciones]
    ESC --> ESC2[Escalar incumplimientos críticos<br/>a Gerencia Senior cuando no se resuelven<br/>en tiempos acordados - SLA: 48-72hrs]
    ESC --> ESC3[Facilitar resolución mediante<br/>sesiones de trabajo colaborativo,<br/>análisis de causa raíz - RCA, 5 Whys]
    ESC --> ESC4[Verificar implementación de<br/>acciones correctivas con evidencia<br/>objetiva antes de cerrar hallazgos]
    
    ESC1 & ESC2 & ESC3 & ESC4 --> RET
    
    RET[RETROALIMENTACIÓN Y MEJORA CONTINUA]
    
    RET --> RET1[Analizar tendencias y patrones<br/>de defectos para identificar<br/>causas sistémicas y áreas de mejora]
    RET --> RET2[Proponer actualizaciones a procesos<br/>organizacionales basadas en lecciones<br/>aprendidas - Kaizen approach]
    RET --> RET3[Compartir mejores prácticas<br/>entre proyectos mediante Communities<br/>of Practice y knowledge bases]
    RET --> RET4[Actualizar assets organizacionales:<br/>Templates, checklists, training materials,<br/>automation scripts]
    RET --> RET5[Medir eficacia del QA mediante KPIs:<br/>Defect Detection Rate, Escaped Defects,<br/>Process Compliance %, Cost of Quality]
    
    RET1 & RET2 & RET3 & RET4 & RET5 --> DECISION{¿Ciclo de proyecto<br/>continúa?}
    
    DECISION -->|SÍ - Nueva Iteración/Sprint| EVAL
    DECISION -->|NO - Cierre de Proyecto| CLOSE
    
    CLOSE[CIERRE Y LECCIONES APRENDIDAS]
    CLOSE --> CLOSE1[Generar reporte final de QA<br/>con métricas consolidadas y<br/>evaluación de cumplimiento]
    CLOSE --> CLOSE2[Archivar evidencias en repositorio<br/>organizacional para auditorías<br/>y consultas futuras]
    CLOSE --> CLOSE3[Sesión de retrospectiva con<br/>stakeholders: qué funcionó, qué mejorar,<br/>acciones para próximos proyectos]
    
    CLOSE1 & CLOSE2 & CLOSE3 --> END[FIN DEL CICLO]
    
    style START fill:#8E44AD,stroke:#6C3483,stroke-width:3px,color:#FFF
    style PLAN fill:#3498DB,stroke:#2874A6,stroke-width:2px,color:#FFF
    style EVAL fill:#27AE60,stroke:#1E8449,stroke-width:2px,color:#FFF
    style REG fill:#F39C12,stroke:#CA6F1E,stroke-width:2px,color:#FFF
    style ESC fill:#E74C3C,stroke:#C0392B,stroke-width:2px,color:#FFF
    style RET fill:#16A085,stroke:#138D75,stroke-width:2px,color:#FFF
    style DECISION fill:#E67E22,stroke:#BA4A00,stroke-width:3px,color:#FFF
    style CLOSE fill:#95A5A6,stroke:#707B7C,stroke-width:2px,color:#FFF
    style END fill:#34495E,stroke:#2C3E50,stroke-width:3px,color:#FFF
```

# Diagrama 3

```mermaid
graph TD
    START[🎯 INICIO DEL PROCESO DE ASEGURAMIENTO DE CALIDAD]
    
    subgraph NIVEL1["📋 NIVEL ESTRATÉGICO - DEFINICIÓN"]
        DIR[👔 Alta Dirección<br/>CEO / Gerencia General]
        DIR --> DIR1[Define políticas de calidad organizacional]
        DIR --> DIR2[Asigna presupuesto y recursos para QA]
        DIR --> DIR3[Aprueba estándares y certificaciones]
        
        QAMGR[👨‍💼 Director de Calidad / QA Manager]
        DIR1 & DIR2 & DIR3 --> QAMGR
        QAMGR --> QM1[Establece estrategia de aseguramiento]
        QAMGR --> QM2[Define métricas y KPIs de calidad]
        QAMGR --> QM3[Lidera equipo de QA]
        
        PMO[🏢 Oficina de Proyectos - PMO]
        QM1 & QM2 & QM3 --> PMO
        PMO --> PMO1[Valida planes de calidad en proyectos]
        PMO --> PMO2[Monitorea cumplimiento de estándares]
    end
    
    subgraph NIVEL2["⚙️ NIVEL TÁCTICO - PLANIFICACIÓN"]
        PM[📊 Jefe de Proyecto / Scrum Master]
        PMO1 & PMO2 --> PM
        PM --> PM1[Integra QA en cronograma del proyecto]
        PM --> PM2[Coordina recursos y entregas]
        PM --> PM3[Facilita acceso a información]
        
        PO[📝 Product Owner / Analista de Negocio]
        PM1 & PM2 & PM3 --> PO
        PO --> PO1[Define criterios de aceptación]
        PO --> PO2[Prioriza correcciones de defectos]
        PO --> PO3[Valida cumplimiento de requisitos]
        
        ARQ[🏗️ Arquitecto de Software]
        PO1 & PO2 --> ARQ
        ARQ --> ARQ1[Establece estándares técnicos]
        ARQ --> ARQ2[Define lineamientos de diseño]
        ARQ --> ARQ3[Revisa decisiones arquitectónicas]
    end
    
    subgraph NIVEL3["🔧 NIVEL OPERATIVO - EJECUCIÓN"]
        DEV[💻 Equipo de Desarrollo]
        ARQ1 & ARQ2 & ARQ3 --> DEV
        DEV --> DEV1[Implementa funcionalidades según estándares]
        DEV --> DEV2[Ejecuta pruebas unitarias y code reviews]
        DEV --> DEV3[Corrige defectos identificados]
        DEV --> DEV4[Documenta código y cambios]
        
        DEVOPS[🚀 Ingeniero DevOps]
        DEV1 & DEV2 --> DEVOPS
        DEVOPS --> DO1[Configura pipelines CI/CD]
        DEVOPS --> DO2[Implementa quality gates automatizados]
        DEVOPS --> DO3[Gestiona ambientes de pruebas]
    end
    
    subgraph NIVEL4["🔍 NIVEL DE ASEGURAMIENTO - VALIDACIÓN"]
        QALEAD[🎯 Líder de QA / Quality Engineer]
        DEV3 & DEV4 & DO1 & DO2 & DO3 --> QALEAD
        QALEAD --> QL1[Ejecuta auditorías de procesos]
        QALEAD --> QL2[Revisa productos de trabajo]
        QALEAD --> QL3[Documenta no conformidades]
        QALEAD --> QL4[Facilita sesiones de mejora]
        
        TESTER[🧪 Equipo de Testers / QA Analysts]
        QL1 & QL2 --> TESTER
        TESTER --> T1[Ejecuta pruebas funcionales]
        TESTER --> T2[Ejecuta pruebas de regresión]
        TESTER --> T3[Reporta defectos con evidencias]
        TESTER --> T4[Valida correcciones]
        
        AUTOQA[🤖 Ingeniero de Automatización QA]
        T1 & T2 --> AUTOQA
        AUTOQA --> AQ1[Desarrolla scripts de automatización]
        AUTOQA --> AQ2[Mantiene frameworks de testing]
        AUTOQA --> AQ3[Integra tests en CI/CD]
        
        SECQA[🔐 Especialista en Seguridad QA]
        AQ3 --> SECQA
        SECQA --> SQ1[Ejecuta pruebas de seguridad SAST/DAST]
        SECQA --> SQ2[Audita cumplimiento de seguridad]
        SECQA --> SQ3[Valida encriptación y autenticación]
    end
    
    subgraph NIVEL5["📈 NIVEL DE REPORTE - RETROALIMENTACIÓN"]
        METRICS[📊 Analista de Métricas]
        T3 & T4 & QL3 & QL4 & SQ1 & SQ2 & SQ3 --> METRICS
        METRICS --> M1[Consolida KPIs de calidad]
        METRICS --> M2[Genera dashboards ejecutivos]
        METRICS --> M3[Analiza tendencias y patrones]
        
        REPORT[📋 Reportes a Stakeholders]
        M1 & M2 & M3 --> REPORT
        REPORT --> R1[Informa a Alta Dirección]
        REPORT --> R2[Informa a Jefe de Proyecto]
        REPORT --> R3[Informa a Equipo de Desarrollo]
    end
    
    subgraph NIVEL6["👥 STAKEHOLDERS EXTERNOS"]
        CLIENT[🤝 Cliente / Usuario Final]
        R1 --> CLIENT
        CLIENT --> C1[Participa en UAT - Pruebas de Aceptación]
        CLIENT --> C2[Provee feedback de producto]
        CLIENT --> C3[Aprueba releases]
        
        AUDITOR[✅ Auditor Externo / Certificador]
        R1 --> AUDITOR
        AUDITOR --> AU1[Conduce auditorías independientes]
        AUDITOR --> AU2[Valida compliance con normativas]
        AUDITOR --> AU3[Emite certificaciones ISO/CMMI]
    end
    
    START --> DIR
    
    R1 & R2 & R3 -.->|Ciclo de Mejora Continua| QAMGR
    C1 & C2 & C3 -.->|Feedback del Cliente| PO
    AU1 & AU2 & AU3 -.->|Hallazgos de Auditoría| DIR
    
    style START fill:#8E44AD,stroke:#6C3483,stroke-width:4px,color:#FFF
    style NIVEL1 fill:#3498DB,stroke:#2874A6,stroke-width:3px,color:#FFF
    style NIVEL2 fill:#1ABC9C,stroke:#148F77,stroke-width:3px,color:#FFF
    style NIVEL3 fill:#27AE60,stroke:#1E8449,stroke-width:3px,color:#FFF
    style NIVEL4 fill:#F39C12,stroke:#CA6F1E,stroke-width:3px,color:#FFF
    style NIVEL5 fill:#E67E22,stroke:#BA4A00,stroke-width:3px,color:#FFF
    style NIVEL6 fill:#E74C3C,stroke:#C0392B,stroke-width:3px,color:#FFF
```

# Diagrama 4

```mermaid
graph TB
    START[🎯 IMPLEMENTACIÓN TÉCNICA DE ASEGURAMIENTO DE CALIDAD]
    
    subgraph CAPA1["📊 CAPA 1: GOBERNANZA Y VISIBILIDAD"]
        DASH[Dashboard Ejecutivo<br/>Power BI / Tableau / Grafana]
        DASH --> D1[Métricas en tiempo real]
        DASH --> D2[Tendencias de calidad]
        DASH --> D3[ROI de inversión en QA]
        
        WIKI[Repositorio de Conocimiento<br/>Confluence / SharePoint / Notion]
        D1 & D2 & D3 --> WIKI
        WIKI --> W1[Políticas y procedimientos]
        WIKI --> W2[Plantillas y checklists]
        WIKI --> W3[Lecciones aprendidas]
        
        CERT[Gestión de Certificaciones<br/>ISO 9001 / CMMI / ISO 27001]
        W1 --> CERT
        CERT --> CE1[Evidencias de auditoría]
        CERT --> CE2[Reportes de cumplimiento]
    end
    
    subgraph CAPA2["📋 CAPA 2: GESTIÓN DE PROYECTOS"]
        JIRA[Sistema de Gestión<br/>JIRA / Azure DevOps / Monday]
        CE1 & CE2 --> JIRA
        JIRA --> J1[Seguimiento de defectos]
        JIRA --> J2[Workflows de aprobación]
        JIRA --> J3[Planificación de sprints]
        
        TESTMGMT[Gestión de Pruebas<br/>TestRail / Zephyr / qTest]
        J1 & J2 --> TESTMGMT
        TESTMGMT --> TM1[Casos de prueba]
        TESTMGMT --> TM2[Ejecución y resultados]
        TESTMGMT --> TM3[Matriz de trazabilidad]
        
        AUDIT[Gestión de Auditorías<br/>Planificación y seguimiento]
        TM1 & TM2 --> AUDIT
        AUDIT --> AU1[Calendario de auditorías]
        AUDIT --> AU2[Checklists de compliance]
        AUDIT --> AU3[Registro de hallazgos]
    end
    
    subgraph CAPA3["💻 CAPA 3: CALIDAD DE CÓDIGO"]
        SONAR[Análisis Estático<br/>SonarQube / SonarCloud]
        AU1 & AU2 & AU3 --> SONAR
        SONAR --> SO1[Detección de code smells]
        SONAR --> SO2[Cobertura de código >80%]
        SONAR --> SO3[Technical debt tracking]
        SONAR --> SO4[Quality gates automáticos]
        
        LINT[Linters y Formatters<br/>ESLint / Prettier / Pylint]
        SO4 --> LINT
        LINT --> L1[Validación de estilo]
        LINT --> L2[Best practices]
        LINT --> L3[Auto-formatting]
        
        REVIEW[Code Review<br/>GitHub / GitLab / Bitbucket]
        L1 & L2 & L3 --> REVIEW
        REVIEW --> CR1[Pull Request reviews]
        REVIEW --> CR2[Comentarios y aprobaciones]
        REVIEW --> CR3[Merge con validaciones]
    end
    
    subgraph CAPA4["🧪 CAPA 4: PRUEBAS AUTOMATIZADAS"]
        UNIT[Pruebas Unitarias<br/>JUnit / pytest / NUnit / Jest]
        CR3 --> UNIT
        UNIT --> U1[Cobertura >80%]
        UNIT --> U2[Ejecución en cada commit]
        UNIT --> U3[Feedback rápido - segundos]
        
        INTEG[Pruebas de Integración<br/>Postman / RestAssured / Pact]
        U1 & U2 --> INTEG
        INTEG --> I1[Testing de APIs]
        INTEG --> I2[Contract testing]
        INTEG --> I3[Validación de datos]
        
        E2E[Pruebas End-to-End<br/>Selenium / Cypress / Playwright]
        I1 & I2 --> E2E
        E2E --> EE1[Automatización de UI]
        E2E --> EE2[Testing cross-browser]
        E2E --> EE3[Regression suites]
        
        PERF[Pruebas de Rendimiento<br/>JMeter / Gatling / K6]
        EE1 & EE2 --> PERF
        PERF --> P1[Load testing]
        PERF --> P2[Stress testing]
        PERF --> P3[Validación de SLAs]
    end
    
    subgraph CAPA5["🔐 CAPA 5: SEGURIDAD"]
        SAST[Análisis Estático de Seguridad<br/>Fortify / Checkmarx / SonarQube]
        P1 & P2 & P3 --> SAST
        SAST --> SA1[Escaneo de vulnerabilidades en código]
        SAST --> SA2[Detección de patrones inseguros]
        
        DAST[Análisis Dinámico de Seguridad<br/>OWASP ZAP / Burp Suite]
        SA1 & SA2 --> DAST
        DAST --> DA1[Testing en runtime]
        DAST --> DA2[Detección XSS / SQL Injection]
        
        SCA[Análisis de Dependencias<br/>Snyk / Dependabot / WhiteSource]
        DA1 & DA2 --> SCA
        SCA --> SC1[Librerías vulnerables]
        SCA --> SC2[Compliance de licencias]
        
        SECRETS[Gestión de Secretos<br/>HashiCorp Vault / AWS Secrets]
        SC1 & SC2 --> SECRETS
        SECRETS --> SE1[Credenciales encriptadas]
        SECRETS --> SE2[Rotación automática]
        SECRETS --> SE3[Auditoría de accesos]
    end
    
    subgraph CAPA6["🚀 CAPA 6: CI/CD E INFRAESTRUCTURA"]
        CICD[Pipeline CI/CD<br/>Jenkins / GitHub Actions / GitLab CI]
        SE1 & SE2 & SE3 --> CICD
        CICD --> CI1[Build automatizado]
        CICD --> CI2[Quality gates obligatorios]
        CICD --> CI3[Deploy automatizado]
        
        DOCKER[Contenedores<br/>Docker / Kubernetes]
        CI1 & CI2 --> DOCKER
        DOCKER --> DO1[Ambientes consistentes]
        DOCKER --> DO2[Isolation de pruebas]
        DOCKER --> DO3[Escalabilidad]
        
        MONITOR[Monitoreo<br/>Prometheus / New Relic / Datadog]
        CI3 & DO1 --> MONITOR
        MONITOR --> MO1[Performance de aplicación]
        MONITOR --> MO2[Tracking de errores]
        MONITOR --> MO3[Analytics de usuarios]
        
        IaC[Infraestructura como Código<br/>Terraform / Ansible / CloudFormation]
        DO2 & DO3 --> IaC
        IaC --> IA1[Provisioning automatizado]
        IaC --> IA2[Configuración versionada]
        IaC --> IA3[Reproducibilidad]
    end
    
    subgraph CAPA7["💾 CAPA 7: DATOS Y CUMPLIMIENTO"]
        DB[Bases de Datos<br/>PostgreSQL / MongoDB / MySQL]
        MO1 & MO2 & MO3 --> DB
        DB --> DB1[Encriptación en reposo]
        DB --> DB2[Backups automáticos]
        DB --> DB3[Control de accesos]
        
        ENCRYPT[Encriptación<br/>TLS 1.3 / AES-256]
        DB1 --> ENCRYPT
        ENCRYPT --> EN1[Datos en tránsito]
        ENCRYPT --> EN2[Datos en reposo]
        ENCRYPT --> EN3[Key management]
        
        AUTH[Autenticación<br/>OAuth 2.0 / JWT / SAML]
        DB3 & EN3 --> AUTH
        AUTH --> AT1[Single Sign-On - SSO]
        AUTH --> AT2[Multi-Factor Authentication]
        AUTH --> AT3[Control basado en roles - RBAC]
        
        GDPR[Cumplimiento Normativo<br/>GDPR / CCPA / LGPD]
        AT1 & AT2 & AT3 --> GDPR
        GDPR --> GD1[Privacidad de datos]
        GDPR --> GD2[Derecho al olvido]
        GDPR --> GD3[Gestión de consentimientos]
    end
    
    subgraph CAPA8["🔔 CAPA 8: INTEGRACIÓN Y NOTIFICACIONES"]
        API[API Gateway<br/>Kong / Apigee / AWS API Gateway]
        GD1 & GD2 & GD3 --> API
        API --> AP1[Rate limiting]
        API --> AP2[Autenticación centralizada]
        API --> AP3[Logging y trazabilidad]
        
        WEBHOOK[Notificaciones<br/>Slack / MS Teams / Email]
        AP3 --> WEBHOOK
        WEBHOOK --> WH1[Alertas en tiempo real]
        WEBHOOK --> WH2[Notificaciones de status]
        WEBHOOK --> WH3[Escalamiento automático]
    end
    
    FINAL[✅ CICLO COMPLETO DE ASEGURAMIENTO]
    WH1 & WH2 & WH3 --> FINAL
    FINAL -.->|Métricas y Feedback| DASH
    
    START --> DASH
    
    style START fill:#8E44AD,stroke:#6C3483,stroke-width:4px,color:#FFF
    style CAPA1 fill:#3498DB,stroke:#2874A6,stroke-width:3px,color:#FFF
    style CAPA2 fill:#1ABC9C,stroke:#148F77,stroke-width:3px,color:#FFF
    style CAPA3 fill:#27AE60,stroke:#1E8449,stroke-width:3px,color:#FFF
    style CAPA4 fill:#F39C12,stroke:#CA6F1E,stroke-width:3px,color:#FFF
    style CAPA5 fill:#E74C3C,stroke:#C0392B,stroke-width:3px,color:#FFF
    style CAPA6 fill:#9B59B6,stroke:#7D3C98,stroke-width:3px,color:#FFF
    style CAPA7 fill:#E67E22,stroke:#BA4A00,stroke-width:3px,color:#FFF
    style CAPA8 fill:#34495E,stroke:#2C3E50,stroke-width:3px,color:#FFF
    style FINAL fill:#16A085,stroke:#138D75,stroke-width:4px,color:#FFF
```
    
