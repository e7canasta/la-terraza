---
title: '☕ PR-Funcional vs UML: Semantic Distance en la Era LLM'
description: 'Part A: Los Fundamentos - Por Qué Algunos Artifacts Funcionan Mejor Con AI'
pubDate: 'Jul 15 2025'
heroImage: '../../assets/blog-placeholder-4.jpg'
authors: ['ernesto', 'claude']
tags: ['semantic-distance', 'llm-corpus', 'ai-collaboration', 'methodology-effectiveness']
duration: '18 minutos (un café)'
level: 'Senior architect conversation'
podcast: '/podcasts/03_Distancia_Semántica__¿UML_o_PRs_para_la_IA__Cómo_Optimizar_Tu_Código_y_Diseñar_Mejor_.m4a'
---

*Duración de lectura: 18 minutos (un café)*
*Nivel: Conversación para arquitectos senior*
*Tags: #semantic-distance #llm-corpus #ai-collaboration #efectividad-metodológica*

---

## ☕ Apertura

**Ernesto**: Noté algo que va contra la intuición: cuando trabajo con agentes IA para generar código, **las descripciones de PR** (pull requests) rinden mejor que **los diagramas UML**. Un texto tipo *“fix auth bug in login controller”* parece más efectivo que un **Use Case** impecable. ¿Por qué?

**Claude**: Porque toca una idea central: **distancia semántica**. Hay artefactos que están **más cerca** del **corpus de entrenamiento** de los modelos (lo que han visto millones de veces) y por eso los entienden mejor.

---

## 🔍 La costura: corpus de entrenamiento vs elegancia metodológica

* **Supuesto clásico**: *mejor metodología → mejor documentación → mejores resultados*.
* **Realidad con IA**: *densidad del corpus → cercanía semántica → mayor efectividad*.
* **Pregunta estratégica**: ¿optimizamos artefactos para **humanos** o para **colaborar con IA**?

**Tesis**: No es “o humanos o IA”. Es **elegir el artefacto correcto según el contexto**, entendiendo el sesgo del corpus.

---

## 👥 Dos miradas: arqueología del corpus

### La experiencia de Ernesto — el “gap” de efectividad

**PR‑funcional (alta efectividad para IA)**

* “Add user authentication to payment flow”
* “Fix memory leak in image processing service”
* “Implement rate limiting for API endpoints”

**Respuesta típica de la IA**: comprensión inmediata, propuestas contextualizadas y cambios coherentes con la arquitectura.

**UML/UP (menor efectividad para IA)**

* Casos de uso con actores, precondiciones, poscondiciones.
* Diagramas de clases con agregaciones y estrategias.
* Actividades con bifurcaciones y flujos alternativos.

**Respuesta típica de la IA**: interpretaciones genéricas, *pattern‑matching* sin contexto, omisiones del dominio.

### El análisis de Claude — densidad y proximidad

* **PRs y issues**: abundan en GitHub y vienen **emparejados con diffs reales** → mapeo directo a código.
* **UML académico**: menos volumen, ejemplos sintéticos, poca variabilidad de dominios → **mayor distancia** a la implementación.

**Insight**: **A mayor densidad del corpus, menor distancia semántica** y mayor efectividad del agente.

---

## 💡 Implicancias: elegir el artefacto según el terreno

### Donde PR‑funcional brilla (y conviene usarlo como artefacto primario)

* **Desarrollo incremental** en apps web/Microservicios comunes.
* **Bugs concretos** y **refactorings localizados**.
* **Patrones conocidos** (auth, caché, pooling, rate‑limit, paginación, CQRS básico).

Ejemplos de PR efectivos:

```text
feat(cart): persistir el carrito en la sesión del usuario
fix(auth): corregir condición de carrera en registro concurrente
refactor(payments): extraer PaymentProcessor como servicio de dominio
```

### Donde la metodología formal sigue ganando (y debe liderar)

* **Modelado de dominio complejo** (salud, finanzas reguladas, industria).
* **Integración de múltiples sistemas** y contratos entre equipos.
* **Atributos de calidad** (disponibilidad, resiliencia, seguridad, latencia, costo).

Acá los **modelos y decisiones arquitectónicas** (UML, C4, catálogos de decisiones) aclaran **el porqué** y **el cómo** a nivel sistema.

---

## 🧪 Estrategia híbrida consciente del corpus

**Principio**: *Human‑first para entender; AI‑first para ejecutar*.

1. **Diseño y análisis (human‑optimized)**

* Casos de uso, modelos de dominio, diagramas de componentes/despliegue.
* Decisiones y atributos de calidad.

2. **Plan de implementación (AI‑optimized)**

* Traducir los artefactos anteriores a **PRs funcionales** atómicos y priorizados.

3. **Generación y revisión**

* La IA implementa siguiendo los PRs.
* Validación humana contra **la intención arquitectónica**.

**Patrón de traducción** (de modelos a PRs):

1. **Use Case** → lista de historias y PRs por escenario.
2. **Componentes** → PRs por puerto/adapter/contrato.
3. **Atributos de calidad** → PRs de *non‑functionals* (observabilidad, timeouts, idempotencia, *rate limits*).
4. **Riesgos** → PRs de *spikes* y pruebas de arquitectura.

---

## 🎚️ El umbral de complejidad

Cuando superamos cierto **umbral de complejidad**, la balanza se inclina hacia **metodología + IA** (no solo PR‑funcional):

* Varios agentes autónomos coordinándose en tiempo real.
* Novedad arquitectónica (patrones poco representados en el corpus abierto).
* Integración *cross‑domain* con fuertes restricciones regulatorias.
* Requisitos de seguridad/safety y auditoría estricta.

> Señal práctica: si tu PR necesita tres párrafos para explicar **contexto de negocio y trade‑offs**, probablemente primero necesitabas **modelado**.

---

## 🎯 Cierre — el sesgo del corpus como restricción de diseño

* La **proximidad semántica** al corpus importa más que la **corrección metodológica** para la **efectividad de la IA**… **hasta que la complejidad supera la cobertura del corpus**.
* La estrategia ganadora es **híbrida**: modelos para pensar y coordinar, PRs para ejecutar con IA.

**Idea fuerza**: elige el artefacto por **valor de comunicación** (humano) y por **distancia semántica** (IA), no por tradición.

---

## 🔄 Tu turno — chequeo de experiencia

1. ¿Qué artefactos te funcionan mejor con IA en tu dominio?
2. ¿Dónde ves que el sesgo del corpus afecta la efectividad?
3. ¿Cómo equilibrás rigor metodológico y colaboración con IA?

**Compartí tus observaciones**: estamos aprendiendo en conjunto.

---

**Próximo café**: [UML/UP/ADOO vs PR‑funcional: bidireccionalidad en arquitecturas complejas](/blog/04-profundizando-la-bidireccionalidad-arquitecturas-complejas/)

*Parte B: ¿Qué pasa cuando salimos del territorio familiar de las apps web y entramos en sistemas multiagente, multimodales y ubicuos?*

---

*Ernesto & Claude*
*Junio 2025*
