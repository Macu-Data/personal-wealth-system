# 💰 Personal Wealth System

> Proyecto personal para transformar un sistema real de control financiero en una herramienta simplificada, escalable e inteligente de gestión financiera y patrimonial.

---

## 📌 Descripción del proyecto

Este proyecto nace a partir de un sistema personal de control financiero desarrollado y utilizado desde **2020**, construido inicialmente con **Excel y Power BI**.

El sistema original fue desarrollado buscando representar con la mayor fidelidad posible la realidad económica y financiera personal, utilizando una lógica basada en contabilidad, patrimonio, ingresos, gastos, activos, pasivos, resultados, liquidez e indicadores financieros.

La idea es transformar progresivamente ese sistema en un **software propio**, manteniendo la lógica financiera desarrollada durante estos años pero simplificando su utilización y haciéndola más escalable.

A largo plazo, el proyecto podría evolucionar desde un sistema de finanzas personales hacia una plataforma de **gestión patrimonial personal**, incorporando inversiones, proyecciones, objetivos, automatización e inteligencia artificial.

---

# 🎯 Objetivo principal

Construir progresivamente un sistema que permita integrar:

* Finanzas personales
* Patrimonio
* Inversiones
* Análisis financiero
* Proyecciones
* Alertas
* Automatizaciones
* Inteligencia artificial

El objetivo inicial **no es construir inmediatamente una aplicación completa**.

La primera meta técnica es:

> **Reproducir con Python y SQL los resultados del sistema actual de Excel + Power BI.**

El sistema original será utilizado como **modelo de referencia y validación** durante la transición.

---

# 🧠 Principio central

## Datos primero. Lógica después. Interfaz después. IA al final.

Orden general previsto:

```text
DATOS REALES
      ↓
MODELO DE DATOS
      ↓
LÓGICA FINANCIERA
      ↓
PYTHON + SQL
      ↓
VALIDACIÓN
      ↓
BACKEND / API
      ↓
APLICACIÓN
      ↓
INVERSIONES
      ↓
IA + AUTOMATIZACIÓN
      ↓
AGENTES
```

La prioridad será siempre la **exactitud y confiabilidad de los datos y cálculos** antes que la estética de la aplicación.

---

# 🏦 Sistema financiero actual

El sistema original está construido principalmente con:

* Excel
* Power BI
* Lógica contable
* Modelo financiero propio
* Datos históricos desde 2020

El modelo utiliza estructuras de cuentas, clasificaciones contables, activos, pasivos, patrimonio, resultados y diferentes indicadores financieros.

El sistema actual continuará funcionando como **referencia** mientras se desarrolla la nueva versión.

### Principio de validación

El nuevo sistema deberá progresivamente reproducir los resultados del modelo actual:

```text
Resultado Power BI
        =
Resultado Python / SQL
```

Algunas de las métricas que deberán poder validarse:

```text
Total Activo
Total Pasivo
Patrimonio Neto
Ingresos
Gastos
Resultado
Liquidez
Meses de cobertura
Evolución patrimonial
Coste de inversiones
Valor de inversiones
Rentabilidad
Distribución de cartera
```

Cualquier diferencia entre ambos sistemas deberá ser investigada antes de considerar correcto el nuevo cálculo.

---

# 💰 Módulo de finanzas

Primera gran área del proyecto.

### Ingresos

* Ingresos mensuales
* Clasificación
* Evolución histórica
* Tendencias

### Gastos

* Gastos esenciales
* Gastos no esenciales
* Gastos administrativos
* Gastos comerciales
* Concentración de gastos
* Top de gastos
* Evolución mensual
* Alertas

### Patrimonio

* Activos
* Pasivos
* Patrimonio Neto
* Resultados acumulados
* Evolución histórica
* Variación respecto a períodos anteriores

### Liquidez

* Dinero disponible
* Gasto promedio mensual
* Meses de cobertura
* Alertas de liquidez

### Resultados

* Resultado mensual
* Resultado de 12 meses
* Períodos de análisis
* Evolución histórica

### Proyecciones

* Evolución esperada de ingresos
* Evolución esperada de gastos
* Capacidad de ahorro
* Escenarios
* Proyecciones financieras de largo plazo

---

# 📈 Módulo de inversiones

Segunda gran área del proyecto.

El primer broker considerado será:

**Interactive Brokers (IBKR)**

Posibles funcionalidades:

* Depósitos
* Retiros
* Compras
* Ventas
* Dividendos
* Retenciones
* Operaciones
* Coste de adquisición
* Valor actual
* Rentabilidad
* Distribución de cartera
* Concentración
* Volatilidad
* Máximo Drawdown
* Sharpe Ratio
* Evolución de aportaciones
* Evolución patrimonial

Conceptualmente:

```text
FINANZAS PERSONALES
        +
INVERSIONES
        ↓
PATRIMONIO TOTAL
```

El objetivo será tratar ambos componentes como partes de un mismo sistema de gestión patrimonial.

---

# 🤖 Módulo de inteligencia artificial

La inteligencia artificial será incorporada **después de construir una base de datos y un motor financiero confiables**.

Algunas posibilidades futuras:

### Asistente financiero

Ejemplo:

> ¿Por qué cambió mi patrimonio este mes?

El sistema podría:

```text
1. Consultar los datos
2. Calcular indicadores
3. Comparar períodos
4. Detectar cambios relevantes
5. Identificar los principales factores
6. Generar una explicación
```

### Automatización

Posible flujo:

```text
IBKR / Datos financieros
          ↓
        Python
          ↓
       Base SQL
          ↓
Cálculos financieros
          ↓
 Alertas / análisis
          ↓
          IA
          ↓
 Informe / notificación
```

---

# 🧩 Visión de largo plazo

El proyecto podría evolucionar hacia un sistema personal más amplio:

```text
                     PERSONAL SYSTEM
                           │
          ┌────────────────┼────────────────┐
          ↓                ↓                ↓
      FINANZAS         INVERSIONES         TIEMPO
          │                │                │
          ↓                ↓                ↓
      PATRIMONIO        CARTERA        PRODUCTIVIDAD
          │                │                │
          └────────────────┼────────────────┘
                           ↓
                         OBJETIVOS
                           ↓
                           IA
```

Posibles módulos futuros:

* Gestión del tiempo
* Productividad
* Objetivos personales
* Planificación
* Proyecciones
* Automatizaciones
* Asistente personal mediante IA

Estos módulos pertenecen a la **visión de largo plazo** y no al primer MVP.

---

# 🛠️ Tecnologías y orden de aprendizaje

Orden orientativo:

```text
1. Python
2. SQL
3. Git / GitHub
4. Pandas
5. PostgreSQL
6. Proyecto financiero
7. FastAPI / Backend
8. Frontend
9. Integración de inversiones / IBKR
10. APIs
11. IA / LLM
12. Automatización
13. Agentes de IA
```

La intención no es dominar una tecnología completamente antes de avanzar.

La idea es:

> **Aprender → aplicar → construir → probar → documentar → mejorar.**

---

# 📚 Roadmap de aprendizaje

## Fase 1 — Python + SQL + Git

**Duración estimada: 0–3 meses**

Dedicación orientativa:

**7–10 horas por semana**

### Python

* Variables
* Tipos de datos
* Listas
* Diccionarios
* Condiciones
* Bucles
* Funciones
* Módulos
* Manejo de errores
* Archivos
* Entornos virtuales
* Programación orientada a objetos básica

### SQL

* SELECT
* WHERE
* GROUP BY
* ORDER BY
* CASE
* JOIN
* Subqueries
* CTE
* Window Functions
* Agregaciones
* Fechas

### Git / GitHub

* Repositorios
* Commits
* Push
* Pull
* Branches
* Merge
* Pull Requests
* Issues
* Projects
* Markdown
* README

### Primer proyecto práctico

Construir un:

> **Analizador de gastos personales**

Entrada:

```text
CSV / Excel
```

Procesamiento:

```text
Python
+
Pandas
```

Resultados:

```text
Ingresos
Gastos
Categorías
Evolución mensual
Top gastos
Ahorro
```

---

# Fase 2 — Pandas + PostgreSQL

**Duración estimada: meses 3–5**

Objetivos:

* Limpieza de datos
* Transformación
* Fechas
* Agrupaciones
* Agregaciones
* Merge
* Series temporales
* Validación
* Calidad de datos
* Pandas
* PostgreSQL

Arquitectura:

```text
CSV / Excel
      ↓
    Python
      ↓
    Pandas
      ↓
 PostgreSQL
      ↓
Lógica financiera
```

---

# Fase 3 — Backend

**Duración estimada: meses 5–8**

Tecnología candidata:

**FastAPI**

Base de datos:

**PostgreSQL**

Arquitectura inicial:

```text
USUARIO
   ↓
FRONTEND
   ↓
FASTAPI
   ↓
LÓGICA DE NEGOCIO
   ↓
POSTGRESQL
```

---

# Fase 4 — Aplicación

**Duración estimada: meses 8–11**

Tecnologías posibles:

* HTML
* CSS
* JavaScript
* React

Primera interfaz orientativa:

```text
┌──────────────────────────────────────┐
│        SITUACIÓN FINANCIERA          │
├──────────┬──────────┬───────┬────────┤
│Patrimonio│Ingresos  │ Gastos│Resultado│
├──────────┴──────────┴───────┴────────┤
│                                      │
│       Evolución del patrimonio       │
│                                      │
├──────────────────┬───────────────────┤
│ Distribución     │ Alertas            │
│ de activos       │ financieras        │
└──────────────────┴───────────────────┘
```

La estética será secundaria respecto de la lógica financiera.

---

# Fase 5 — Inversiones

**Duración estimada: meses 10–14**

Incorporación del módulo de inversiones e integración con IBKR.

Áreas iniciales:

* Operaciones
* Cartera
* Aportaciones
* Dividendos
* Coste
* Valor
* Rentabilidad
* Riesgo
* Distribución
* Proyecciones

---

# Fase 6 — Inteligencia artificial

**Etapa posterior al MVP**

Temas a estudiar:

* LLM
* Prompting
* Structured Output
* Tool / Function Calling
* APIs
* Embeddings
* RAG
* Evaluación
* Gestión de contexto
* Costes
* Seguridad

La IA debe apoyarse sobre datos y funciones confiables.

---

# Fase 7 — Automatización y agentes

Etapa futura.

Arquitectura aproximada:

```text
DATOS
  ↓
BASE DE DATOS
  ↓
FUNCIONES / HERRAMIENTAS
  ↓
MODELO DE IA
  ↓
AGENTE
  ↓
AUTOMATIZACIÓN
```

Ejemplo:

> Analizar mis finanzas de los últimos 12 meses y detectar cambios importantes.

Posible proceso:

```text
→ Consultar SQL
→ Calcular KPIs
→ Comparar períodos
→ Detectar anomalías
→ Analizar inversiones
→ Generar informe
→ Enviar notificación
```

---

# ⏱️ Cronograma general estimado

Para una persona que trabaja y estudia aproximadamente **7–10 horas semanales**:

```text
2026
├── Python
├── SQL
├── Git / GitHub
└── Primeros proyectos de datos

2027
├── Pandas
├── PostgreSQL
├── Motor financiero
├── FastAPI
├── Backend
├── Aplicación inicial
└── Módulo de inversiones

2028+
├── APIs
├── IA
├── Automatización
├── Agentes
└── Evaluación de monetización
```

Las fechas son orientativas.

La prioridad es mantener una evolución sostenible y constante.

---

# 💻 Hardware

No se necesita inicialmente una computadora especializada para IA.

### Mínimo recomendado

* CPU moderna de 6+ núcleos
* 16 GB RAM
* SSD de 512 GB

### Preferido

* CPU moderna de gama media/alta
* 32 GB RAM
* SSD de 1 TB

Una GPU de alta gama no es una prioridad inicial.

---

# 🧱 Principios del proyecto

### 1. Exactitud antes que estética

Los números deben ser correctos antes de diseñar una interfaz compleja.

### 2. Aprender construyendo

Cada etapa de aprendizaje debería generar algo tangible.

### 3. Pequeñas iteraciones

Evitar desarrollar grandes bloques sin validar.

### 4. Validación contra el sistema original

Excel + Power BI serán la referencia inicial.

### 5. Trazabilidad

Las transformaciones y cálculos relevantes deberán poder explicarse.

### 6. Simplicidad

No incorporar tecnologías o infraestructura innecesaria.

### 7. No empezar por IA

Primero datos y lógica.

### 8. Controlar el alcance

El proyecto puede crecer indefinidamente.

El primer objetivo sigue siendo:

> **Un sistema financiero confiable y útil.**

---

# 📋 Estrategia de desarrollo

```text
SISTEMA ORIGINAL
Excel + Power BI
        ↓
PYTHON + SQL
        ↓
REPRODUCCIÓN DEL MODELO
        ↓
MOTOR FINANCIERO
        ↓
BASE DE DATOS
        ↓
BACKEND
        ↓
MVP
        ↓
INVERSIONES
        ↓
IA
        ↓
AUTOMATIZACIÓN
        ↓
SISTEMA PERSONAL MÁS AMPLIO
```

---

# 📅 Inicio del proyecto

**Fecha de inicio:** 21/09/2026

### Estado inicial

* [x] Sistema financiero existente
* [x] Datos históricos desde 2020
* [x] Experiencia con Excel
* [x] Experiencia con Power BI
* [x] Modelo financiero y contable
* [x] Base de SQL
* [x] Base de Git / GitHub
* [ ] Reforzar Python
* [ ] Reforzar SQL
* [ ] Aprender Pandas
* [ ] Crear primer proyecto financiero en Python
* [ ] Crear modelo financiero en SQL
* [ ] Validar contra Power BI
* [ ] Diseñar arquitectura
* [ ] Crear motor financiero
* [ ] Crear backend
* [ ] Crear aplicación
* [ ] Incorporar inversiones
* [ ] Incorporar IA
* [ ] Incorporar automatizaciones
* [ ] Investigar agentes
* [ ] Evaluar monetización

---

# 📈 Filosofía de progreso

El objetivo no es simplemente:

> "Terminar cursos."

El objetivo es:

> **Convertir conocimiento en proyectos reales.**

Ciclo de aprendizaje:

```text
APRENDER
   ↓
PRACTICAR
   ↓
CONSTRUIR
   ↓
PROBAR
   ↓
DOCUMENTAR
   ↓
COMMIT
   ↓
MEJORAR
```

---

# 📝 Registro del proyecto

## 21/09/2026

Inicio oficial del proyecto.

Se define como estrategia inicial:

* Utilizar GitHub como centro principal del proyecto.
* Mantener documentación, roadmap y aprendizaje separados del futuro código de la aplicación.
* Reforzar Python y SQL antes de entrar en el desarrollo completo.
* Utilizar el sistema Excel + Power BI como modelo de referencia.
* Priorizar la exactitud financiera antes que la interfaz.
* Construir progresivamente.
* Mantener abierta la posibilidad de incorporar inversiones, automatización e inteligencia artificial.

### Primer objetivo práctico

> **Reproducir una parte real del sistema financiero actual utilizando Python y SQL.**

---

# 🚀 Enfoque actual

**Python + SQL + Git/GitHub**

### Próximo hito

Crear el primer pequeño proyecto de análisis de datos financieros utilizando Python y SQL.

---

## ⚠️ Nota

Este proyecto es una iniciativa personal de aprendizaje, desarrollo de software y análisis financiero.

Las funcionalidades relacionadas con inversiones están destinadas al seguimiento y análisis de información y no constituyen, por sí mismas, asesoramiento financiero.
