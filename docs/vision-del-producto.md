# Visión del producto


---

**Autor:** Victor Manuel Flores Venegas

**Fecha de la última versión:** 17/08/2026

**Repositorio:** https://github.com/Victorflores06/Proyecto-Ingenieria-de-Software

---

## 1. Descripción del sistema

**Nombre del sistema: TrackerPLEAS**

**Descripción:**

Es una plataforma web que funciona como un tablero digital donde los estudiantes pueden consultar en todo momento qué requisitos del programa PLEAS ya completaron y cuáles les faltan para poder graduarse. Al mismo tiempo, permite a los directores registrar y actualizar estos avances de forma rápida, manteniendo la información sincronizada y clara para todos sin necesidad de trámites ni revisiones manuales.

---

## 2. Problema y usuarios

**El problema:**

Los estudiantes no tienen certeza de su progreso ni de los requisitos pendientes para graduarse, lo que genera confusión, desinformación y el riesgo de retrasar su titulación. Por otro lado, la dirección invierte demasiado tiempo operativo recopilando y actualizando estos datos de forma manual para cada alumno.

**Cómo se resuelve hoy sin el sistema:**

Hoy en día, el proceso se gestiona mediante correos electrónicos, archivos de Excel desactualizados, listas en papel o citas presenciales donde el estudiante debe preguntar directamente a su director para revisar expediente por expediente cuál es su estatus actual.

**Usuarios del sistema:**

| Tipo de usuario | Qué necesita del sistema | Qué le preocupa |
|---|---|---|
|Director General de Programas | Visualizar el avance global e indicadores de todos los estudiantes a través de todos los programas de liderazgo.|Que la información no esté unificada o que no se puedan generar reportes globales de participación.|
|Director de Programa |Una herramienta ágil para actualizar y validar los requisitos cumplidos por los alumnos asignados a su programa específico. |Perder tiempo capturando datos uno por uno o cometer errores al registrar el cumplimiento de las actividades. |
|Estudiante |Consultar su porcentaje de avance en tiempo real y conocer los requisitos pendientes para completar su diplomado. |Que sus actividades entregadas no se vean reflejadas a tiempo o que la plataforma no sea clara respecto a lo que le falta. |


**Un conflicto entre usuarios:**

El Estudiante desea que cualquier requisito completado (sea una actividad pequeña o una clase) se refleje de manera inmediata en su barra de progreso para tener la certeza de que ya fue registrado. Sin embargo, el Director de Programa necesita mantener un proceso de revisión y verificación manual previa antes de autorizar y publicar el avance en las actividades más grandes, importantes o en la acreditación de materias, para garantizar que los criterios del programa realmente se cumplieron antes de hacer oficial el registro.

**Huecos encontrados:**
- Retirar responsabilidad directa de registro de la coordinación y automatizar con un API a Soy León
- Definir bien los usuarios --> Sus alcances y limitaciones
---

## 3. Alcance

*Instrucción: lo que escribes en "fuera del alcance" es lo que después evita que el proyecto crezca sin control. Sé específico: "reportes" no dice nada, "reportes de ventas mensuales exportables a PDF" sí.*

### Dentro del alcance

-
-
-
-

### Explícitamente fuera del alcance

-
-
-

**Por qué queda fuera:**

*Instrucción: para al menos una de las exclusiones, explica la razón. Puede ser tiempo, complejidad, o que no aporta al problema central.*

---

## 4. Tipo de sistema y restricciones

*Instrucción: identifica de qué tipo es tu sistema y qué te obliga a garantizar ese tipo. Un sistema de información y un sistema crítico no se diseñan igual.*

**Tipo de sistema:**

*(De información · Embebido · Crítico · Web y SaaS · De datos y análisis)*

**Por qué es de ese tipo:**

**Atributos de calidad que impone:**

| Atributo | Por qué importa en mi caso | Qué pasa si no se cumple |
|---|---|---|
| | | |
| | | |
| | | |

**Reglas de negocio que ya identifiqué:**

*Instrucción: reglas que no son obvias desde fuera y que alguien que conoce el dominio tendría que explicarte. Si no encuentras ninguna, tu caso puede ser demasiado simple.*

1.
2.
3.

---

## 5. Ciclo de vida elegido

*Instrucción: este apartado se trabaja en la semana 3, después de ver los modelos de desarrollo. La justificación pesa más que la elección: no hay un modelo correcto, hay uno defendible para tu caso.*

**Modelo elegido:**

**Por qué le conviene a este proyecto:**

*Instrucción: argumenta con las características reales de tu caso. Estabilidad de los requisitos, disponibilidad del cliente, nivel de riesgo, tamaño del equipo, frecuencia de entregas esperada.*

### Alternativas descartadas

**Alternativa 1:**

*Por qué la descarté:*

**Alternativa 2:**

*Por qué la descarté:*

---

## Antes de entregar

Reviso que el documento cumpla lo siguiente:

- [ ] La descripción del apartado 1 se entiende sin ser del área
- [ ] Hay al menos dos tipos de usuario con necesidades distintas
- [ ] Identifiqué un conflicto real entre usuarios
- [ ] El alcance dice qué queda fuera, no solo qué queda dentro
- [ ] Las exclusiones son específicas, no genéricas
- [ ] Identifiqué el tipo de sistema y al menos dos atributos de calidad
- [ ] Anoté al menos tres reglas de negocio no obvias
- [ ] Justifiqué el ciclo de vida contra dos alternativas descartadas
- [ ] El documento está en mi repositorio y se puede leer desde el navegador
- [ ] Borré todas las instrucciones en cursiva de la plantilla
