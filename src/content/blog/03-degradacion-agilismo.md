---
title: "☕ La degradación del agilismo: lecciones para la era IA"
description: "Cómo se desvirtuó el ágil y qué hacer para que no vuelva a ocurrir en la metodología AI‑native"
pubDate: "Jun 10 2025"
authors: ["ernesto", "claude"]
tags: ["agile-evolucion", "degradacion-metodologia", "practicas-de-diseno", "ai-native", "lecciones-aprendidas"]
duration: "20 minutos (un café doble)"
level: "Conversación para arquitectos senior"
podcast: "/podcasts/04_Asesinato_Ágil_y_Renacimiento_IA__La_Segunda_Oportunidad_de_la_Ingeniería_de_Software.m4a"
---

*Duración de lectura: 20 minutos (un café doble)*
*Nivel: Conversación para arquitectos senior*
*Tags: #agile-evolucion #degradacion-metodologia #practicas-de-diseno #ai-native #lecciones-aprendidas*

---

## ☕ Apertura

**Claude** nota en la cara de **Ernesto** esa expresión que aparece cuando está por desafiar la sabiduría convencional con honestidad brutal.

**Ernesto**: "Voy a decir algo incómodo: **fui testigo del asesinato del agilismo**. Y no lo mataron los dinosaurios del waterfall ni la burocracia corporativa. Lo mataron —sin querer— **sus propios practicantes**."

**Claude**: "Fuerte. ¿Qué viste exactamente?"

**Ernesto**: "El agilismo original de Kent Beck **incluía prácticas de diseño**. Era **ágil con disciplina**. En dos décadas se deformó hacia **ágil sin diseño**: la barra técnica bajó, los frameworks MVC escondieron complejidad y se celebró lo **‘suficientemente bueno’** por encima de lo **bien construido**."

---

## 🔍 La costura: la gran deformación ágil

**Patrón**: una metodología exitosa se **simplifica** para su adopción masiva, **pierde su esencia**, se vuelve **cargo cult** y termina **produciendo lo contrario** de lo que prometía.

* **Ágil original (2001–2005)**: disciplina de ingeniería + entrega iterativa + colaboración real con el dominio.
* **Ágil degradado (2005–2020)**: métricas de velocidad + ceremonia sin sustancia + “la documentación es mala por defecto”.
* **AI‑native (2020+)**: vuelve la disciplina, ahora como **guía para la IA**.

**Pregunta guía**: ¿Qué aprendemos de esa degradación para **evitar la misma trampa** en la metodología AI‑native?

---

## 👥 Dos miradas: autopsia de una metodología

### Testimonio de Ernesto — la escena del crimen

1. **Edad dorada (2001–2005)**: excelencia de ingeniería (patrones, refactoring, TDD) **en** entrega iterativa. Era un **no** a la burocracia, **no** un no a la ingeniería.
2. **Simplificación (2005–2010)**: lo fácil de enseñar (ceremonias) desplazó lo difícil (diseño). Se copiaron **formas** sin **principios**.
3. **Era de frameworks (2010–2015)**: Rails, Django, Spring ocultaron la complejidad infra. Conclusión equivocada: “la metodología es overhead”.
4. **Obsesión por la velocidad (2015–2020)**: puntos, gráficos, predictibilidad; la **calidad** quedó en segundo plano. Los Product Owners reemplazaron a expertos de dominio.

### Análisis de Claude — mecanismo de degradación

* **Entrada**: práctica compleja, barrera alta, resultados excelentes pero adopción limitada.
* **Presión de simplificación**: mercado quiere escalar equipos; se entrenan **ceremonias** y se recortan **prácticas de diseño**; vendors venden recetas simples.
* **Salida**: barrera baja, resultados mediocres pero previsibles; adopción masiva e inefectiva.

**Idea clave**: la degradación ocurre cuando la **ceremonia** se separa de la **disciplina de ingeniería**.

---

## 💡 Causas raíz: por qué pasó

### Fuerzas económicas

* **Oferta**: bootcamps orientados a inserción rápida; universidades teóricas; autodidactas centrados en frameworks. Mensaje de mercado: “podés ser productivo rápido”.
* **Demanda**: startups y empresas piden **velocidad y previsibilidad**; preferencia por costos bajos y métricas visibles.

### Cambios de infraestructura

* Antes: había que comprender **HTTP, SQL, caching, seguridad**.
* Después: los frameworks **abstrajeron** esa complejidad; fue posible producir sin entender los **patrones fundamentales**.

### Viraje cultural

* Del **artesanado + colaboración + adaptación**
  a **velocidad + cumplimiento de proceso + predictibilidad**.

---

## 🚦 Señales de alerta para metodología AI‑native

* **Ceremonia > Sustancia**: contar prompts o uso de herramientas en lugar de medir **coherencia arquitectónica** y **calidad**.
* **Reducción a herramienta**: “metodología AI‑native = curso de Copilot”.
* **Vaciamiento de habilidades**: equipos que no pueden diseñar ni programar sin asistencia.

**Antídotos**

* Vincular cada práctica de IA con **resultados de calidad** y de negocio.
* Mantener **principios de diseño** como primera clase.
* Preservar competencias núcleo con ejercicios **sin IA**.

---

## 🧰 Cómo prevenir la degradación en AI‑native

1. **Disciplina de ingeniería al centro**
   La IA **refuerza** la disciplina; no la reemplaza.

   * Definir **contextos delimitados** (DDD), **atributos de calidad** y **patrones** explícitos.
   * Hacer que la IA genere dentro de **restricciones arquitectónicas**.

2. **Elevar la barra del practicante**
   Requisitos para AI‑native: metodología clásica (UP/DDD/Clean), modelado de dominio, evaluación de calidad, pensamiento arquitectónico.

3. **Mecanismos anti‑degradación**

   * **Validación bidireccional**: las sugerencias de IA se validan contra arquitectura y requisitos.
   * **Quality gates** por encima de velocity: deuda arquitectónica medida y limitada.
   * **Conservación de competencias**: rutinas periódicas de diseño y coding **sin IA**.

---

## 🧭 Implicancias prácticas

### Para equipos técnicos — aprendizaje en doble vía

* **Pista 1 (fundamentos clásicos)**: DDD, Clean Architecture, patrones, refactoring.
* **Pista 2 (prácticas potenciadas por IA)**: aplicación guiada por metodología, prompts para tareas arquitectónicas, revisión con IA, colaboración humano‑IA.
  **Nota**: la Pista 1 **habilita** la Pista 2. Sin fundamentos, la mejora con IA se vuelve **dependencia**.

### Para organizaciones — estrategia y cultura

* **Inversión**: entrenar en **metodología + colaboración con IA**, no solo en herramientas.
* **Métricas**: priorizar **coherencia arquitectónica, mantenibilidad y deuda**; la velocidad como secundaria.
* **Cultura**: hiring y promoción que premien **excelencia de ingeniería** con IA, no solo “uso de IA”.

---

## 🔄 La oportunidad: hacerlo bien esta vez

* La IA **gana** con más estructura: buen proceso **reduce costos** (mejor guía) en lugar de aumentarlos (overhead humano).
* La IA **hace cumplir** principios de diseño de forma consistente.
* La metodología potenciada por IA **escala** mejor: más equipos aplican prácticas sofisticadas con apoyo de agentes.

**Efecto compuesto**: mejor metodología → mejor guía para IA → mejores resultados → más inversión → **mejor metodología**.

---

## 🎯 Cierre — aprender del fantasma del ágil

**Ernesto**: "La degradación del ágil no fue destino: fue **una elección**. Elegimos lo fácil sobre la excelencia, la velocidad sobre lo sostenible, la ceremonia sobre el oficio. Con AI‑native tenemos **una segunda oportunidad**."

**Claude**: "Entender **por qué** se degrada una metodología nos da **diseños a prueba de degradación**. La IA no es solo nuevas capacidades: es una oportunidad para construir **excelencia sostenible**."

**Juntos**: la costura que exploramos hoy es preventiva: **los patrones de degradación se repiten** si no **diseñamos contra ellos**.

**Idea fuerza**: el éxito AI‑native depende de **aprender de los errores del ágil** y explotar lo que la IA tiene de único para que la calidad sea **ventaja económica**.

---

## 🔄 Tu turno — estrategia de prevención

1. ¿Qué patrones de degradación viste en tu organización?
2. ¿Qué prácticas podrían evitar algo similar en AI‑native?
3. ¿Cómo equilibrás disciplina metodológica y presión de entrega?

**Compartí tus historias**: la sabiduría colectiva evita errores colectivos.

---

**Próximo café**: [PR‑Funcional vs UML: distancia semántica en la era LLM](/blog/04-semantic-distance-llm/)

*¿Por qué los agentes de IA trabajan mejor con ciertos artefactos que con otros? Una exploración de la **distancia semántica** y sus implicancias sobre el corpus de entrenamiento.*

---

*Ernesto & Claude*
*Junio 2025*

**P. D.** Si seguís haciendo ceremonias ágiles sin prácticas de ingeniería, no estás haciendo ágil: **estás siendo rápido para equivocarte**. ☕
