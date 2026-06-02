# Laboratorio No. 2 — Planificación y Gestión de Proyectos de Software

> **SIGL — Sistema de Información para Gestión Logística**  
> Planificación integral mediante Odoo Projects + Microsoft Excel con análisis CPM

---

**Asignatura:** Integración de Sistemas de Información  
**Institución:** Fundación Universitaria Internacional de La Rioja (UNIIR)  
**Programa:** Ingeniería Informática — Séptimo Semestre  
**Profesor:** Ing. Edwin Eduardo Millán Rojas  
**Estudiante:** Alejandro De Mendoza  
**Fecha de entrega:** 02 de junio de 2026

---

## Tabla de Contenido

1. [Descripción del Laboratorio](#descripción-del-laboratorio)
2. [Contenido del Repositorio](#contenido-del-repositorio)
3. [Ficha del Proyecto SIGL](#ficha-del-proyecto-sigl)
4. [Justificación de Herramientas](#justificación-de-herramientas)
5. [Fases del Proyecto](#fases-del-proyecto)
6. [Planificación de Actividades](#planificación-de-actividades)
7. [Equipo de Trabajo](#equipo-de-trabajo)
8. [Diagrama de Gantt](#diagrama-de-gantt)
9. [Camino Crítico — Método CPM](#camino-crítico--método-cpm)
10. [Actividades con Holgura](#actividades-con-holgura)
11. [Resolución de Conflictos de Recursos](#resolución-de-conflictos-de-recursos)
12. [Modelo de Costos](#modelo-de-costos)
13. [Archivo Excel Complementario](#archivo-excel-complementario)
14. [Acceso al Proyecto en Odoo](#acceso-al-proyecto-en-odoo)
15. [Conclusiones](#conclusiones)
16. [Bibliografía](#bibliografía)

---

## Descripción del Laboratorio

El presente laboratorio corresponde a la **Actividad No. 2** de la asignatura Integración de Sistemas de Información. Desarrolla la **planificación integral** del proyecto *Sistema de Información para Gestión Logística (SIGL)*, aplicando principios de administración de proyectos y utilizando como herramientas principales **Odoo Projects** y **Microsoft Excel**.

El objetivo central es estructurar, organizar y programar las 18 actividades necesarias para la ejecución del proyecto, definiendo:

- Dependencias entre tareas (método CPM — Critical Path Method)
- Asignación de responsables por perfil técnico
- Tiempos de ejecución y fechas planeadas
- Diagrama de Gantt completo (junio 2026 → febrero 2028)
- Análisis de holguras y resolución de conflictos por concurrencia de recursos

Este laboratorio parte de los resultados del **Laboratorio No. 1**, donde se definieron los requerimientos, el equipo humano y el presupuesto total del proyecto.

---

## Contenido del Repositorio

| Archivo | Descripción |
|---|---|
| `Desarrollo Proyecto Alejandro De Mendoza.pdf` | Informe completo del laboratorio en PDF (45 páginas) — incluye toda la documentación, evidencias de Odoo, análisis CPM, Gantt y conclusiones |
| `Desarrollo Proyecto Alejandro De Mendoza.docx` | Versión editable del informe en formato Word |
| `Lab2_Planificacion_SIGL.xlsx` | Archivo Excel complementario con 3 hojas: tabla de planificación, diagrama de Gantt visual y tabla de recursos humanos |
| `Tareas.pdf` | Reporte Gantt mensual exportado directamente desde Odoo Projects — 21 páginas (una por mes, de junio 2026 a febrero 2028), con granularidad diaria |

---

## Ficha del Proyecto SIGL

| Parámetro | Detalle |
|---|---|
| **Nombre del sistema** | Sistema de Información para Gestión Logística (SIGL) |
| **Empresa cliente** | Distribuidora de Productos Electrónicos S.A.S. (caso de estudio) |
| **Tipo de desarrollo** | Software a medida — ciclo de vida cascada con sprints Scrum |
| **Fecha de inicio** | 01 de junio de 2026 |
| **Fecha de finalización** | 22 de febrero de 2028 |
| **Duración total** | 632 días calendario / 432 días laborales hábiles |
| **Total de actividades** | 18 actividades en 7 fases |
| **Total de horas** | 4,200 horas de trabajo del equipo |
| **Equipo** | 11 personas en 10 perfiles de recurso humano |
| **Presupuesto total** | $638,337,986 COP (precio de venta con margen del 30%) |
| **Herramientas** | Odoo Projects (axentdev.odoo.com) + Microsoft Excel |
| **Gerente del proyecto** | Alejandro De Mendoza |
| **Ciudad de ejecución** | Colombia — Bogotá D.C. |
| **Legislación aplicada** | Código Sustantivo del Trabajo colombiano — prestaciones sociales 52% |

### Alcance Funcional del Sistema

El SIGL integra los siguientes módulos funcionales:

- **Gestión de inventarios** — control de entradas, salidas y alertas de stock mínimo
- **Pedidos y órdenes de compra** — gestión con proveedores nacionales e internacionales
- **Trazabilidad y despachos** — seguimiento en tiempo real de entregas a clientes
- **Business Intelligence** — dashboards con KPIs logísticos y financieros
- **APIs de integración** — conectores con el ERP existente de la empresa cliente
- **Gestión de usuarios y roles** — control de acceso por perfil (administrador, operador, auditor)
- **Facturación electrónica DIAN** — cumplimiento regulatorio colombiano
- **Documentación técnica y manual de usuario** — entregables de cierre

---

## Justificación de Herramientas

Aunque el enunciado especifica MS Project 2013, el docente **Ing. Edwin Eduardo Millán Rojas** autorizó el uso de herramientas alternativas por ser de acceso libre. Se seleccionaron:

### Odoo Projects (plataforma principal)
- Acceso gratuito en la nube, sin instalación local
- Soporte nativo para dependencias entre tareas (campo **"Bloqueado por"**) — equivalente al campo de predecesores de MS Project
- Generación automática del diagrama de Gantt desde las fechas planeadas
- Gestión de recursos humanos mediante usuarios del sistema
- Registro de horas estimadas por tarea (campo **"Tiempo asignado"**)
- Vista Kanban por etapas para seguimiento del avance
- Instancia creada: **axentdev.odoo.com** (empresa "AxentDev")

### Microsoft Excel (soporte complementario)
- Consolidación de información en formato de hoja de cálculo
- Construcción de diagrama de Gantt con resaltado condicional
- Generación de reportes de planificación y recursos humanos
- Compatibilidad universal (Excel / LibreOffice Calc)

---

## Fases del Proyecto

El proyecto se estructuró en 7 fases correspondientes al ciclo de vida completo del desarrollo de software:

| No. | Fase | Descripción | Actividades |
|---|---|---|---|
| 1 | **Análisis** | Levantamiento y especificación de requerimientos | Act. 1 |
| 2 | **Diseño** | Arquitectura del sistema, modelo de datos e interfaz de usuario | Acts. 2, 3, 4 |
| 3 | **Desarrollo** | Implementación del backend, frontend y APIs | Acts. 5, 6, 7 |
| 4 | **Integración** | Integración de todos los módulos y pruebas unitarias | Acts. 8, 9 |
| 5 | **Pruebas** | Pruebas de integración, UAT y corrección de errores | Acts. 10, 11, 12 |
| 6 | **Implantación** | Despliegue en producción, capacitación y documentación técnica | Acts. 13, 14, 15 |
| 7 | **Cierre** | Documentación final, mantenimiento inicial y evaluación del proyecto | Acts. 16, 17, 18 |

---

## Planificación de Actividades

### Metodología de Cálculo de Fechas

- Jornada laboral: **8 horas/día**, lunes a viernes (5 días hábiles/semana)
- Exclusión de **18 festivos colombianos** en 2026 y 18 en 2027
- Horas estimadas convertidas a días laborales dividiendo entre 8 horas/día
- Las dependencias determinan la fecha de inicio (siguiente día hábil tras finalizar predecesoras)
- Actividades con mismas predecesoras pueden ejecutarse **en paralelo**

**Total horas:** 4,200h | **Total días laborales:** 432 días | **Duración calendario:** 632 días

### Tabla Completa de las 18 Actividades

Las actividades en **negrita** pertenecen al camino crítico (holgura = 0 días).

| # | Actividad | Fase | Inicio | Fin | Días | Horas | Responsable | Dep. | CP |
|---|---|---|---|---|---|---|---|---|---|
| **1** | **Levantamiento de requerimientos** | Análisis | 01/06/2026 | 03/09/2026 | 63 | 504 | Analista de Sistemas | — | ✓ |
| **2** | **Diseño de arquitectura del sistema** | Diseño | 04/09/2026 | 04/12/2026 | 63 | 504 | Arquitecto de Software | 1 | ✓ |
| 3 | Diseño de base de datos | Diseño | 04/09/2026 | 02/10/2026 | 21 | 168 | DBA | 1 | — |
| **4** | **Diseño de interfaz UI/UX** | Diseño | 07/12/2026 | 04/02/2027 | 42 | 336 | Diseñador UI/UX | 2 | ✓ |
| 5 | Desarrollo backend | Desarrollo | 07/12/2026 | 04/05/2027 | 105 | 840 | Backend Senior 1 y 2 | 2, 3 | — |
| **6** | **Desarrollo frontend** | Desarrollo | 05/02/2027 | 02/06/2027 | 84 | 672 | Frontend Developer | 4 | ✓ |
| 7 | Desarrollo de APIs | Desarrollo | 07/12/2026 | 04/02/2027 | 42 | 336 | Backend Senior 1 | 2, 3 | — |
| **8** | **Integración de módulos** | Integración | 03/06/2027 | 30/07/2027 | 42 | 336 | Backend Senior 1 y 2 | 5, 6, 7 | ✓ |
| 9 | Pruebas unitarias | Integración | 03/06/2027 | 01/07/2027 | 21 | 168 | QA Tester | 5, 6, 7 | — |
| **10** | **Pruebas de integración** | Pruebas | 02/08/2027 | 30/08/2027 | 21 | 168 | QA Tester | 8, 9 | ✓ |
| **11** | **Pruebas UAT** | Pruebas | 31/08/2027 | 28/09/2027 | 21 | 168 | QA Tester | 10 | ✓ |
| **12** | **Corrección de errores y ajustes** | Pruebas | 29/09/2027 | 27/10/2027 | 21 | 168 | Backend Senior 1 | 11 | ✓ |
| **13** | **Despliegue en producción** | Implantación | 28/10/2027 | 25/11/2027 | 21 | 168 | DevOps Engineer | 12 | ✓ |
| **14** | **Capacitación a usuarios** | Implantación | 26/11/2027 | 24/12/2027 | 21 | 168 | Analista de Sistemas | 13 | ✓ |
| 15 | Documentación técnica | Implantación | 02/08/2027 | 30/08/2027 | 21 | 168 | Analista de Sistemas | 8 | — |
| **16** | **Documentación de usuario final** | Cierre | 27/12/2027 | 24/01/2028 | 21 | 168 | Analista de Sistemas | 14, 15 | ✓ |
| **17** | **Mantenimiento inicial post-despliegue** | Cierre | 26/11/2027 | 24/01/2028 | 42 | 336 | DevOps Engineer | 13 | ✓ |
| **18** | **Evaluación final y cierre del proyecto** | Cierre | 25/01/2028 | 22/02/2028 | 21 | 168 | Gerente de Proyecto | 16, 17 | ✓ |

> CP = Camino Crítico | Total: 4,200 horas | 432 días laborales

---

## Equipo de Trabajo

El proyecto cuenta con **11 personas en 10 perfiles** técnicos y de gestión, registrados como usuarios internos en la instancia Odoo Projects:

| # | Perfil | Usuario Odoo | Área | Actividades | Horas | Costo Lab 1 |
|---|---|---|---|---|---|---|
| 1 | Gerente de Proyecto | gerente@axentdev.odoo.com | Dirección | Act. 18 | 168 | $18,480,000 |
| 2 | Analista de Sistemas | analista@axentdev.odoo.com | Análisis | Acts. 1, 14, 15, 16 | 1,008 | $60,480,000 |
| 3 | Arquitecto de Software | arquitecto@axentdev.odoo.com | Diseño | Act. 2 | 504 | $45,360,000 |
| 4 | DBA | dba@axentdev.odoo.com | Diseño | Act. 3 | 168 | $15,120,000 |
| 5 | Diseñador UI/UX | disenador@axentdev.odoo.com | Diseño | Act. 4 | 336 | $20,160,000 |
| 6 | Backend Senior 1 | backend1@axentdev.odoo.com | Desarrollo | Acts. 5, 7, 8, 12 | 1,680 | $100,800,000 |
| 7 | Backend Senior 2 | backend2@axentdev.odoo.com | Desarrollo | Acts. 5, 8 | 1,176 | $70,560,000 |
| 8 | Frontend Developer | frontend@axentdev.odoo.com | Desarrollo | Act. 6 | 672 | $40,320,000 |
| 9 | QA Tester | qa@axentdev.odoo.com | Calidad | Acts. 9, 10, 11 | 504 | $25,200,000 |
| 10 | DevOps Engineer | devops@axentdev.odoo.com | Infraestructura | Acts. 13, 17 | 504 | $35,280,000 |
| | **TOTAL** | | | **18 actividades** | **6,720** | **$431,760,000** |

---

## Diagrama de Gantt

El diagrama de Gantt fue generado automáticamente por Odoo Projects a partir de las fechas planeadas en cada tarea. Las barras representan la duración de cada actividad y las flechas indican las dependencias entre tareas.

El diagrama está organizado por **responsable (Planeación)**, lo que permite detectar conflictos de concurrencia de recursos. La línea vertical verde marca el inicio del proyecto (01/06/2026).

### Cronograma Resumido por Semestre

| Período | Actividades activas |
|---|---|
| Jun – Sep 2026 | Act. 1: Levantamiento de requerimientos |
| Sep – Oct 2026 | Acts. 2 y 3: Diseño de arquitectura + Diseño de BD (paralelo) |
| Oct – Dic 2026 | Act. 2: Diseño de arquitectura (continúa) |
| Dic 2026 – Feb 2027 | Acts. 4, 5, 7: UI/UX + Backend + APIs (paralelo) |
| Feb – Jun 2027 | Acts. 5 y 6: Backend + Frontend (paralelo) |
| Jun – Jul 2027 | Acts. 8 y 9: Integración de módulos + Pruebas unitarias (paralelo) |
| Ago 2027 | Acts. 10 y 15: Pruebas de integración + Doc. técnica (paralelo) |
| Sep 2027 | Act. 11: Pruebas UAT |
| Oct 2027 | Act. 12: Corrección de errores |
| Nov 2027 | Act. 13: Despliegue en producción |
| Nov – Dic 2027 | Acts. 14 y 17: Capacitación + Mantenimiento (paralelo) |
| Dic 2027 – Ene 2028 | Acts. 16 y 17: Doc. usuario final + Mantenimiento (paralelo) |
| Ene – Feb 2028 | Act. 18: Evaluación final y cierre |

El archivo `Tareas.pdf` contiene el Gantt completo exportado desde Odoo con granularidad **diaria** (21 páginas, una por mes).

---

## Camino Crítico — Método CPM

### Metodología aplicada

Se aplicó el **Método de la Ruta Crítica (CPM — Critical Path Method)** mediante dos pasadas:

- **Forward Pass** → Calcula la Fecha de Inicio Temprana (ES) y Fin Temprano (EF)
- **Backward Pass** → Calcula la Fecha de Inicio Tardía (LS) y Fin Tardío (LF)
- **Holgura total (TF)** = LS − ES. Si TF = 0, la actividad es **crítica**

### Secuencia del Camino Crítico

```
Act. 1 → Act. 2 → Act. 4 → Act. 6 → Act. 8 → Act. 10 → Act. 11
       → Act. 12 → Act. 13 → Act. 14 → Act. 16 → Act. 17 → Act. 18
```

**13 de 18 actividades son críticas (72.2%)** — proyecto de alta interdependencia.

### Tabla Análisis CPM Completa

| # | Actividad | ES | EF | LS | LF | Holgura | Crítica |
|---|---|---|---|---|---|---|---|
| 1 | Levantamiento de requerimientos | 01/06/26 | 03/09/26 | 01/06/26 | 03/09/26 | **0** | ✓ |
| 2 | Diseño de arquitectura | 04/09/26 | 04/12/26 | 04/09/26 | 04/12/26 | **0** | ✓ |
| 3 | Diseño de base de datos | 04/09/26 | 02/10/26 | 07/12/26 | 02/01/27 | 63 días | — |
| 4 | Diseño UI/UX | 07/12/26 | 04/02/27 | 07/12/26 | 04/02/27 | **0** | ✓ |
| 5 | Desarrollo backend | 07/12/26 | 04/05/27 | 07/01/27 | 04/06/27 | 21 días | — |
| 6 | Desarrollo frontend | 05/02/27 | 02/06/27 | 05/02/27 | 02/06/27 | **0** | ✓ |
| 7 | Desarrollo de APIs | 07/12/26 | 04/02/27 | 06/04/27 | 02/06/27 | 84 días | — |
| 8 | Integración de módulos | 03/06/27 | 30/07/27 | 03/06/27 | 30/07/27 | **0** | ✓ |
| 9 | Pruebas unitarias | 03/06/27 | 01/07/27 | 02/07/27 | 30/07/27 | 21 días | — |
| 10 | Pruebas de integración | 02/08/27 | 30/08/27 | 02/08/27 | 30/08/27 | **0** | ✓ |
| 11 | Pruebas UAT | 31/08/27 | 28/09/27 | 31/08/27 | 28/09/27 | **0** | ✓ |
| 12 | Corrección de errores | 29/09/27 | 27/10/27 | 29/09/27 | 27/10/27 | **0** | ✓ |
| 13 | Despliegue en producción | 28/10/27 | 25/11/27 | 28/10/27 | 25/11/27 | **0** | ✓ |
| 14 | Capacitación a usuarios | 26/11/27 | 24/12/27 | 26/11/27 | 24/12/27 | **0** | ✓ |
| 15 | Documentación técnica | 02/08/27 | 30/08/27 | 26/11/27 | 24/12/27 | 84 días | — |
| 16 | Doc. de usuario final | 27/12/27 | 24/01/28 | 27/12/27 | 24/01/28 | **0** | ✓ |
| 17 | Mantenimiento post-despliegue | 26/11/27 | 24/01/28 | 26/11/27 | 24/01/28 | **0** | ✓ |
| 18 | Evaluación final y cierre | 25/01/28 | 22/02/28 | 25/01/28 | 22/02/28 | **0** | ✓ |

---

## Actividades con Holgura

Las **5 actividades no críticas** (27.8%) tienen los siguientes márgenes de flexibilidad:

| # | Actividad | Holgura | Impacto |
|---|---|---|---|
| 3 | Diseño de base de datos | **63 días (~3 meses)** | Puede retrasarse hasta 63 días sin afectar el proyecto |
| 5 | Desarrollo backend | **21 días (~1 mes)** | Permite ajustes de hasta 1 mes sin impacto en entrega |
| 7 | Desarrollo de APIs | **84 días (~4 meses)** | Mayor holgura del proyecto — máxima flexibilidad operativa |
| 9 | Pruebas unitarias | **21 días (~1 mes)** | QA Tester puede ajustar inicio hasta 02/07/2027 |
| 15 | Documentación técnica | **84 días (~4 meses)** | Puede ejecutarse en cualquier momento entre agosto y diciembre 2027 |

---

## Resolución de Conflictos de Recursos

Se identificaron **4 conflictos potenciales** por concurrencia de recursos y se aplicaron estrategias de resolución:

### Conflicto 1 — Backend Senior (Dic 2026 – May 2027)
- **Problema:** Acts. 5 y 7 requieren perfil Backend simultáneamente (105 + 42 días en paralelo)
- **Resolución:** Se asignaron **dos perfiles** distintos — Backend Senior 1 cubre APIs (Act. 7) y comparte el desarrollo backend (Act. 5) con Backend Senior 2

### Conflicto 2 — QA Tester (Jun – Jul 2027)
- **Problema:** Acts. 8 y 9 inician simultáneamente el 03/06/2027, generando presión sobre QA
- **Resolución:** Act. 9 tiene holgura de 21 días; QA puede ajustar inicio hasta 02/07/2027 sin impacto en la entrega final

### Conflicto 3 — DevOps Engineer (Nov 2027 – Ene 2028)
- **Problema:** Acts. 13 y 17 parecen solaparse para el DevOps
- **Resolución:** Las actividades están correctamente **secuenciadas** — Act. 17 inicia el día hábil siguiente a que finaliza Act. 13, sin solapamiento real

### Conflicto 4 — Analista de Sistemas (Implantación y Cierre)
- **Problema:** Acts. 14, 15 y 16 requieren al mismo Analista en fases cercanas
- **Resolución:** Las actividades están **secuenciadas en el tiempo** — Act. 15 en agosto 2027, Acts. 14 y 16 en diciembre 2027 → enero 2028. Sin solapamiento

---

## Modelo de Costos

El costo fue calculado en el **Laboratorio No. 1** mediante un modelo de contabilidad analítica en Microsoft Excel (13 hojas interconectadas), conforme a la legislación laboral colombiana vigente.

### Supuestos
- Duración base: 8 meses calendario
- Jornada: 8 horas/día, 173 horas/mes
- Prestaciones sociales: **52%** sobre salario base (prima, vacaciones, cesantías, ARL, EPS, pensión)
- IVA recursos tecnológicos: **19%**
- Imprevistos: **10%** sobre costo operacional
- Margen de ganancia: **30%** sobre inversión total

### Resumen de Costos

| Componente | Valor (COP) | % del Total |
|---|---|---|
| Costo base de nómina (salarios brutos) | $229,000,000 | 35.9% |
| Prestaciones sociales (52%) | $119,080,000 | 18.7% |
| **Subtotal costo laboral** | **$348,080,000** | **54.5%** |
| Recursos técnicos (hardware + software + IVA 19%) | $98,310,200 | 15.4% |
| **Subtotal costo operacional** | **$446,390,200** | **69.9%** |
| Imprevistos (10%) | $44,639,020 | 7.0% |
| **INVERSIÓN TOTAL** | **$491,029,220** | **77.0%** |
| Ganancia esperada (30%) | $147,308,766 | 23.1% |
| **PRECIO DE VENTA FINAL AL CLIENTE** | **$638,337,986** | **100%** |

### Indicadores Financieros

| Indicador | Valor |
|---|---|
| ROI (Retorno sobre inversión) | **30.0%** |
| Utilidad sobre ventas | 23.1% |
| Punto de equilibrio | 76.9% del precio de venta |
| Participación de RR.HH. en costos | 70.8% |

---

## Archivo Excel Complementario

El archivo `Lab2_Planificacion_SIGL.xlsx` contiene **3 hojas de trabajo interconectadas**:

| Hoja | Nombre | Contenido |
|---|---|---|
| 1 | **Planificación** | Tabla completa de las 18 actividades con fechas, horas, responsables, dependencias, holgura, indicador de camino crítico y estado en Odoo. Resaltado condicional: **amarillo = actividades críticas** |
| 2 | **Gantt** | Diagrama de Gantt visual por mes (jun 2026 → feb 2028). Barras **azules** = actividades críticas; barras **verdes** = actividades con holgura. Fila de resumen con conteo de actividades críticas por mes |
| 3 | **Recursos Humanos** | Tabla de los 10 perfiles con usuario Odoo, área, actividades asignadas, fechas de participación, horas totales y costo Lab 1. Total: 11 personas, 4,200 horas, $431,760,000 COP en nómina base |

---

## Acceso al Proyecto en Odoo

| Campo | Detalle |
|---|---|
| **Plataforma** | Odoo Projects (Edición Enterprise) |
| **Instancia / Empresa** | AxentDev — axentdev.odoo.com |
| **Nombre del proyecto** | Sistema de Información para Gestión Logística |
| **Administrador** | Alejandro De Mendoza — alejandro.mendoza.techengineer@gmail.com |
| **Tareas registradas** | 18 tareas en 7 etapas |

> Para acceso de revisión al proyecto en Odoo, contactar al estudiante vía correo electrónico. Se agregará como colaborador con permisos de lectura en un plazo no mayor a 24 horas.

---

## Resumen de Resultados

| Parámetro | Resultado |
|---|---|
| Herramienta principal | Odoo Projects (axentdev.odoo.com) + Microsoft Excel |
| Fecha de inicio | 01 de junio de 2026 |
| Fecha de finalización | 22 de febrero de 2028 |
| Duración total (calendario) | 632 días |
| Duración total (laborales) | 432 días hábiles |
| Total de actividades | 18 actividades en 7 fases |
| Total de horas planificadas | 4,200 horas |
| Actividades en camino crítico | **13 de 18 (72.2%)** — Acts. 1, 2, 4, 6, 8, 10, 11, 12, 13, 14, 16, 17, 18 |
| Actividades con holgura | 5 de 18 (27.8%) — Acts. 3, 5, 7, 9, 15 |
| Mayor holgura identificada | 84 días laborales (Acts. 7 y 15) |
| Perfiles de recurso humano | 10 perfiles, 11 personas |
| Costo total del proyecto | $638,337,986 COP |
| ROI del proyecto | 30% sobre la inversión total |

---

## Conclusiones

- La planificación mediante **Odoo Projects** permitió modelar con precisión las 18 actividades, sus dependencias y responsables, generando un cronograma técnicamente viable del 01/06/2026 al 22/02/2028.
- La aplicación del **método CPM** identificó 13 actividades críticas (72.2%), revelando la alta interdependencia del proyecto. Cualquier retraso en esas actividades impacta directamente la fecha de entrega.
- La **ejecución paralela** de actividades (diseño, desarrollo y pruebas donde aplica) redujo significativamente la duración total respecto a un cronograma completamente secuencial.
- Las 5 actividades con holgura (máx. 84 días en APIs y Documentación técnica) proporcionan **flexibilidad operativa** sin comprometer la fecha de finalización.
- Los **conflictos de concurrencia de recursos** fueron resueltos mediante la asignación de perfiles adicionales (2 Backend Senior) y el aprovechamiento de las holguras disponibles.
- La integración **Odoo Projects + Microsoft Excel** ofreció dos mecanismos complementarios: gestión dinámica de tareas en Odoo y consolidación/reporting estructurado en Excel.
- La unión de los resultados del **Lab 1** (presupuesto: $638M COP) y **Lab 2** (cronograma: 432 días laborales) construye una visión integral y completa del proyecto SIGL.

---

## Bibliografía

- Odoo S.A. (2024). *Odoo 17 Project Management — Official Documentation*.
- Project Management Institute. (2021). *PMBOK® Guide — Seventh Edition*. PMI.
- Pressman, R. S., & Maxim, B. R. (2015). *Ingeniería del software: Un enfoque práctico* (8.ª ed.). McGraw-Hill.
- Sommerville, I. (2016). *Ingeniería de software* (10.ª ed.). Pearson Educación.
- Ministerio del Trabajo de Colombia. (2024). *Código Sustantivo del Trabajo — Prestaciones sociales 2026*.
- Gido, J., Clements, J., & Baker, R. (2018). *Administración exitosa de proyectos* (6.ª ed.). Cengage Learning.
- Millán Rojas, E. E. (2026). *Sesión magistral Laboratorio No. 2 — Planificación de Proyectos*. Asignatura: Integración de Sistemas de Información. UNIIR.

---

*Laboratorio No. 2 — Integración de Sistemas de Información — UNIIR — 2026*  
*Alejandro De Mendoza — alejandro.mendoza.techengineer@gmail.com*
