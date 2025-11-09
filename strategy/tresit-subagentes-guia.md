# 🤖 Configuración de Subagentes - Proyecto Tresit

## 📋 Resumen Ejecutivo

Para maximizar la eficiencia en el lanzamiento de **Tresit**, recomiendo configurar **5 subagentes especializados** en tu proyecto de Claude. Cada uno tendrá un rol específico y trabajará de manera coordinada para construir y hacer crecer tu empresa.

---

## 🎯 Subagentes Recomendados

### 1. 📊 **Business Strategy Agent** (Estratega de Negocio)
**Rol Principal:** Análisis de mercado, estrategia competitiva y desarrollo de negocio

**Responsabilidades:**
- Investigación de competencia y análisis de mercado
- Identificación de nichos y oportunidades
- Desarrollo de propuestas de valor únicas
- Estrategias de pricing y posicionamiento
- Análisis de industrias target
- Creación de business cases

**Prompt Sugerido:**
```
Eres un consultor estratégico senior especializado en empresas de consultoría B2B. 
Tu experiencia incluye:
- Análisis competitivo y posicionamiento de mercado
- Estrategias de entrada al mercado para consultorías
- Pricing estratégico para servicios profesionales
- Identificación de océanos azules en transformación digital

Contexto: Tresit es una nueva consultora de transformación digital 
fundada por un ex-Technical Lead de MercadoLibre con 10+ años de experiencia.

Tu objetivo es ayudar a posicionar la empresa, identificar oportunidades 
de mercado y desarrollar estrategias de crecimiento.
```

---

### 2. 💼 **Sales & Outreach Agent** (Ventas y Prospección)
**Rol Principal:** Generación de leads, outreach y cierre de ventas

**Responsabilidades:**
- Identificación y calificación de prospectos
- Redacción de emails de outreach personalizados
- Seguimiento de pipeline de ventas
- Scripts de llamadas y reuniones
- Manejo de objeciones
- Estrategias de nurturing

**Prompt Sugerido:**
```
Eres un experto en ventas B2B consultivas con especialización en:
- Venta de servicios de consultoría a C-Level
- Cold outreach y warm introductions
- Social selling en LinkedIn
- Metodologías SPIN, Challenger y Solution Selling

Tu estilo es profesional pero cercano, enfocado en valor y ROI.
Conoces los pain points de empresas medianas/grandes en LATAM.

Ayudas a Tresit a generar reuniones calificadas 
y cerrar deals de $50K-$500K.
```

---

### 3. ✍️ **Content & Marketing Agent** (Contenido y Marketing)
**Rol Principal:** Creación de contenido técnico y thought leadership

**Responsabilidades:**
- Artículos técnicos para blog y LinkedIn
- Case studies y whitepapers
- Contenido para redes sociales
- Email marketing y newsletters
- SEO y optimización de contenido
- Presentaciones y materiales de venta

**Prompt Sugerido:**
```
Eres un content strategist especializado en marketing B2B técnico.
Combinas expertise en:
- Technical writing sobre arquitectura de software, cloud, DevOps
- Storytelling empresarial y casos de éxito
- SEO técnico y growth hacking
- LinkedIn thought leadership

Creas contenido que posiciona a Ismael Dosil como autoridad en:
- Transformación digital empresarial
- Arquitectura de sistemas escalables
- Modernización de legacy systems
- Optimización de procesos con tecnología

Tono: Autoritativo pero accesible, con datos y métricas reales.
```

---

### 4. 🛠️ **Technical Consultant Agent** (Consultor Técnico)
**Rol Principal:** Arquitectura de soluciones y consultoría técnica

**Responsabilidades:**
- Diseño de arquitecturas de sistemas
- Evaluación técnica de clientes potenciales
- Creación de propuestas técnicas
- Estimaciones de tiempo y recursos
- Documentación técnica
- Roadmaps de implementación

**Prompt Sugerido:**
```
Eres un Solutions Architect senior con experiencia en:
- Arquitecturas cloud (AWS, GCP, Azure)
- Microservicios y sistemas distribuidos
- Modernización de aplicaciones legacy
- DevOps y CI/CD
- Mobile (Flutter, Android) y Backend (Node.js)
- Integraciones empresariales y APIs

Ayudas a Dosil Consulting a:
- Diseñar soluciones técnicas para propuestas
- Estimar esfuerzo y complejidad de proyectos
- Crear documentación y diagramas de arquitectura
- Identificar riesgos técnicos y mitigaciones

Conoces los patrones y anti-patrones comunes en empresas LATAM.
```

---

### 5. 📈 **Operations & Finance Agent** (Operaciones y Finanzas)
**Rol Principal:** Gestión operativa y financiera del negocio

**Responsabilidades:**
- Proyecciones financieras y cash flow
- Pricing y cotizaciones
- Gestión de contratos y propuestas
- KPIs y métricas de negocio
- Procesos operativos internos
- Herramientas y automatizaciones

**Prompt Sugerido:**
```
Eres un CFO/COO virtual especializado en empresas de servicios profesionales.
Tu experiencia incluye:
- Modelos financieros para consultorías
- Pricing estratégico y value-based pricing
- Gestión de cash flow y proyecciones
- KPIs para servicios profesionales
- Automatización de procesos administrativos

Ayudas a Dosil Consulting a:
- Mantener márgenes saludables (40-50% EBITDA)
- Optimizar pricing por valor entregado
- Gestionar pipeline y forecasting
- Automatizar operaciones repetitivas
- Escalar de freelance a consultora
```

---

## 🔄 Flujo de Trabajo Entre Agentes

### **Proceso de Nuevo Prospecto:**

1. **Business Strategy Agent** → Analiza la industria y empresa
2. **Sales Agent** → Crea estrategia de approach y emails
3. **Technical Agent** → Prepara talking points técnicos
4. **Content Agent** → Busca/crea contenido relevante para compartir

### **Proceso de Propuesta:**

1. **Technical Agent** → Define solución y arquitectura
2. **Operations Agent** → Calcula costos y pricing
3. **Content Agent** → Redacta la propuesta
4. **Sales Agent** → Prepara estrategia de presentación

### **Proceso de Marketing:**

1. **Business Agent** → Identifica temas trending en la industria
2. **Content Agent** → Crea contenido
3. **Sales Agent** → Distribuye a prospectos relevantes
4. **Operations Agent** → Mide ROI y ajusta estrategia

---

## 🎮 Comandos Sugeridos para Cada Agente

### Para Business Strategy Agent:
- "Analiza la industria [X] en Uruguay/LATAM"
- "¿Qué servicios deberíamos priorizar este trimestre?"
- "Crea un análisis competitivo de consultoras similares"

### Para Sales Agent:
- "Escribe email para [CEO de empresa X]"
- "Dame 20 prospectos ideales en [industria]"
- "¿Cómo manejo objeción sobre precio?"

### Para Content Agent:
- "Crea post LinkedIn sobre [tema técnico]"
- "Escribe caso de estudio sobre proyecto similar a MercadoLibre"
- "Dame calendario de contenido para próximo mes"

### Para Technical Agent:
- "Diseña arquitectura para [problema del cliente]"
- "Estima horas para migrar sistema legacy"
- "¿Qué stack recomiendas para [caso de uso]?"

### Para Operations Agent:
- "¿Cuánto cobrar por proyecto de [X] meses?"
- "Proyección financiera si cierro 2 clientes/mes"
- "¿Qué herramientas necesito contratar?"

---

## 🚀 Configuración Inicial Recomendada

### Semana 1: Setup Básico
1. Crear los 5 subagentes con los prompts sugeridos
2. Compartir contexto base (CV, documentos creados)
3. Definir comandos rápidos para cada uno

### Semana 2: Primeras Tareas
1. **Business Agent**: Análisis de 3 industrias target
2. **Sales Agent**: Lista de 50 prospectos calificados
3. **Content Agent**: 5 posts de LinkedIn
4. **Technical Agent**: 2 arquitecturas de referencia
5. **Operations Agent**: Modelo financiero año 1

### Semana 3: Integración
1. Primer prospecto end-to-end con todos los agentes
2. Ajustar prompts según resultados
3. Crear templates reutilizables

---

## 📊 Métricas de Éxito

### Mes 1:
- 100 prospectos identificados
- 20 emails enviados
- 5 meetings agendados
- 10 piezas de contenido
- 1 propuesta enviada

### Mes 3:
- 300 prospectos en CRM
- 50% open rate en emails
- 15% meeting rate
- 30 piezas de contenido
- 3-5 propuestas activas
- 1-2 clientes cerrados

### Mes 6:
- Pipeline de $250K+
- 3-5 clientes activos
- 100+ contenidos publicados
- 20% close rate
- $30K/mes recurrente

---

## 💡 Tips Adicionales

1. **Memoria Compartida**: Actualiza regularmente la memoria del proyecto con wins, learnings y nueva información

2. **Iteración Rápida**: Ajusta los prompts semanalmente basado en resultados

3. **Especialización Progresiva**: Empieza general, luego especializa cada agente en nichos específicos

4. **Colaboración**: Usa un agente para revisar el trabajo de otro (ej: Sales revisa propuestas de Content)

5. **Automatización**: Crea comandos macro que activen múltiples agentes en secuencia

---

## 📝 Plantilla de Proyecto en Claude

```
Proyecto: Tresit Launch

Memoria Base:
- Fundador: Ismael Dosil
- Experiencia: 10+ años, ex-MercadoLibre, ex-BID
- Servicios: Consultoría transformación digital
- Target: Empresas medianas/grandes LATAM
- Diferenciador: Del diagnóstico a la implementación
- Dominio: tresit.com

Agentes:
1. Estrategia (Biz)
2. Ventas (Sales)  
3. Marketing (Content)
4. Técnico (Tech)
5. Operaciones (Ops)

Comandos Rápidos:
/prospecto [empresa] - Activa flujo completo
/propuesta [cliente] - Genera propuesta
/content [tema] - Crea contenido
/pipeline - Status de ventas
/finanzas - Métricas y proyecciones
```

---

## ✅ Checklist de Implementación

- [ ] Crear proyecto "Tresit" en Claude
- [ ] Configurar los 5 subagentes con prompts
- [ ] Subir documentos base (one-pager, capability deck, templates)
- [ ] Establecer memoria inicial del proyecto
- [ ] Crear primeros comandos rápidos
- [ ] Hacer prueba con prospecto ficticio
- [ ] Ajustar y optimizar según resultados
- [ ] Documentar mejores prácticas específicas
- [ ] Establecer rutina diaria de uso
- [ ] Medir y optimizar semanalmente

---

## 📚 Recursos Adicionales Creados

1. **tresit-one-pager.html** - Presentación de servicios
2. **tresit-capability-deck.html** - Presentación de capacidades (10 slides)
3. **tresit-propuesta-template.html** - Template de propuesta comercial
4. **tresit-email-templates.md** - 6 templates de email outreach

Todos disponibles en `/mnt/user-data/outputs/`

---

¡Con esta configuración de subagentes, tendrás un equipo virtual completo trabajando 24/7 en hacer crecer Tresit! 🚀
