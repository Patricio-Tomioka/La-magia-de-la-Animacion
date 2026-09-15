# Contenido estructurado

## De la intención de comunicación a la estructura de información

**Organizar antes de diseñar.**

Esta guía propone un proceso para **investigar, seleccionar, jerarquizar y documentar contenido en Markdown** antes de convertirlo en un documento digital. El objetivo es producir información clara, consistente, reutilizable y fácil de interpretar por personas, sistemas digitales y asistentes de inteligencia artificial.

---

## Índice

1. [¿Qué es el contenido estructurado?](#1-qué-es-el-contenido-estructurado)
2. [Intención de comunicación](#2-intención-de-comunicación)
3. [Del universo al alcance](#3-del-universo-al-alcance)
4. [Investigar y seleccionar](#4-investigar-y-seleccionar)
5. [Unidades, atributos y relaciones](#5-unidades-atributos-y-relaciones)
6. [Jerarquizar el contenido](#6-jerarquizar-el-contenido)
7. [Identidad, intención y alcance](#7-identidad-intención-y-alcance)
8. [Markdown como especificación](#8-markdown-como-especificación)
9. [Construir un sistema de información](#9-construir-un-sistema-de-información)
10. [Trabajar con inteligencia artificial](#10-trabajar-con-inteligencia-artificial)
11. [Proceso de trabajo](#11-proceso-de-trabajo)
12. [Criterios de validación](#12-criterios-de-validación)

---

## 1. ¿Qué es el contenido estructurado?

Un documento digital no comienza con código, color o tipografía. Comienza con una pregunta:

> **¿Qué queremos comunicar?**

Una colección de datos no constituye por sí misma un mensaje. Los datos adquieren sentido cuando se **seleccionan, nombran, agrupan, ordenan y relacionan** de acuerdo con una intención.

El **contenido estructurado** es información dividida en partes identificables, organizadas mediante una jerarquía y descritas con reglas consistentes. No se piensa como una página terminada, sino como un sistema de piezas que pueden comprenderse, actualizarse, reutilizarse y transformarse.

Cada pieza debe responder:

1. **¿Qué información contiene?**
2. **¿Qué función cumple?**
3. **¿Cómo se relaciona con las demás?**

Para trabajar con claridad debemos distinguir tres capas:

- **Contenido:** lo que el documento comunica.
- **Estructura:** cómo se organizan y relacionan sus partes.
- **Presentación:** cómo se hacen visibles mediante tipografía, color, espacio y composición.

En esta etapa trabajaremos con **contenido y estructura**. La presentación visual vendrá después.

---

## 2. Intención de comunicación

La **intención de comunicación** es la idea que dirige el documento. No es solamente el tema: es la lectura específica que queremos construir sobre él.

Debe definir:

- **Tema:** de qué trata.
- **Enfoque:** desde qué perspectiva se aborda.
- **Propósito:** para qué existe.
- **Audiencia:** para quién se construye.
- **Transformación:** qué debería comprender, sentir, cuestionar o hacer el usuario.
- **Tono:** qué actitud tendrá la comunicación.

La intención permite decidir qué información pertenece al proyecto y cuál debe quedar fuera. También orienta la jerarquía, el lenguaje y las relaciones que deberán hacerse visibles.

> **La intención no aparece al final de la estructura: la estructura nace de ella.**

---

## 3. Del universo al alcance

Todo tema forma parte de un universo más amplio. Intentar comunicarlo por completo suele producir documentos extensos y dispersos.

**Delimitar** significa establecer el territorio concreto del proyecto:

- qué aspecto se investigará;
- qué periodo, contexto o categoría se incluirá;
- qué preguntas busca responder;
- qué nivel de profundidad tendrá;
- qué contenido queda fuera.

Delimitar no empobrece la información. Le proporciona dirección y permite investigar con mayor profundidad.

El alcance debe ser suficientemente específico para sostener una lectura clara y suficientemente amplio para que la intención pueda desarrollarse.

---

## 4. Investigar y seleccionar

La estructura debe surgir del conocimiento del tema, no de una plantilla impuesta antes de investigar.

La investigación permite descubrir conceptos, entidades, atributos, categorías, relaciones, patrones y vacíos de información. Durante este proceso conviene distinguir:

- **Hechos:** información verificable mediante fuentes.
- **Interpretaciones:** lecturas argumentadas a partir de los hechos.
- **Decisiones editoriales:** elecciones sobre qué incluir y cómo organizarlo.
- **Pendientes:** datos incompletos, dudosos o contradictorios.

Toda información importante debe conservar su **fuente, fecha y estado de verificación**. Una estructura consistente pierde valor si contiene datos imprecisos o imposibles de rastrear.

Investigar amplía el universo; estructurar exige reducirlo. Cada pieza puede clasificarse como:

- **Esencial:** necesaria para comprender la intención.
- **De apoyo:** amplía, demuestra o contextualiza.
- **Complementaria:** enriquece, pero puede omitirse.
- **Excluida:** repite, desvía o pertenece a otro alcance.

> **Incluir más información no significa comunicar mejor.**

---

## 5. Unidades, atributos y relaciones

Una **unidad de contenido** es una pieza del sistema que puede identificarse y comprenderse por sí misma: una persona, obra, acontecimiento, lugar, concepto o proceso.

Cada unidad necesita:

- una identidad clara;
- una función dentro del documento;
- atributos definidos;
- relaciones con otras unidades;
- reglas sobre qué información es obligatoria u opcional.

Para modelar el contenido debemos reconocer:

- **Entidad:** elemento principal que se documenta.
- **Atributo:** característica que describe a la entidad.
- **Categoría:** criterio para agrupar entidades.
- **Relación:** vínculo entre elementos o conceptos.
- **Metadato:** información que identifica o administra el contenido.
- **Acción:** posibilidad que se ofrece al usuario.

Nombrar estas partes reduce ambigüedades y permite construir un modelo repetible. En lugar de redactar cada página desde cero, creamos una estructura capaz de recibir distintos contenidos sin perder coherencia.

---

## 6. Jerarquizar el contenido

La **jerarquía** establece niveles de importancia y dependencia. Indica qué presenta el documento, qué ideas lo desarrollan y qué información las amplía.

Una jerarquía clara permite:

- reconocer el tema principal;
- recorrer el documento sin leerlo completo;
- comprender qué ideas dependen de otras;
- distinguir contenido principal y complementario;
- traducir posteriormente la estructura a HTML semántico.

Los títulos identifican niveles; los párrafos desarrollan ideas; las listas agrupan elementos equivalentes y el énfasis señala conceptos relevantes sin crear nuevas secciones.

La jerarquía no consiste en hacer una frase visualmente más grande. Consiste en asignarle una **función estructural**.

El índice es una prueba de esa organización. Si al leer únicamente los títulos y subtítulos no se comprende el recorrido, la arquitectura todavía necesita trabajo.

---

## 7. Identidad, intención y alcance

La entrada de un documento debe comunicar rápidamente tres funciones:

1. **Identidad:** qué es.
2. **Intención:** qué idea lo orienta.
3. **Alcance:** qué encontrará el usuario y para qué le servirá.

Estas funciones pueden expresarse mediante **título, tagline y descriptor**, pero no constituyen una fórmula obligatoria.

### Título

Identifica el proyecto o documento. Debe ser breve y reconocible.

### Tagline

Condensa la intención en una frase breve. Posiciona el proyecto sin repetir el título.

### Descriptor

Explica con mayor precisión el tema, el enfoque y el propósito.

Según el tipo de documento, esta entrada también puede adoptar otras formas: título y resumen, categoría y título, pregunta y respuesta o título, metadatos e introducción.

La estructura adecuada no depende de una plantilla universal, sino de la información que el usuario necesita comprender primero.

---

## 8. Markdown como especificación

Markdown es un formato de texto plano para escribir documentos estructurados mediante marcas legibles. En este proyecto funcionará como una **especificación de información** entre la investigación y la implementación.

Cada recurso debe cumplir una función:

- **Títulos y subtítulos:** representan niveles jerárquicos.
- **Negritas:** destacan conceptos o decisiones centrales.
- *Itálicas:* introducen un énfasis moderado o una variación de voz.
- **Párrafos:** desarrollan una idea a la vez.
- **Listas:** agrupan pasos, condiciones o elementos equivalentes.
- **Citas:** aíslan principios, preguntas o fragmentos provenientes de una fuente.
- **Enlaces:** conectan con fuentes, referencias o acciones.
- **Imágenes:** aportan información y necesitan descripción y procedencia.

La **negrita comunica importancia, no decoración**. La *itálica modifica el tono o énfasis de una frase*. Los encabezados no deben utilizarse sólo para producir diferencias de tamaño.

Markdown no define la apariencia final. Hace explícita la función de cada parte para que el contenido pueda leerse, revisarse, versionarse y transformarse.

---

## 9. Construir un sistema de información

Una estructura se convierte en **sistema** cuando establece reglas que pueden aplicarse a múltiples unidades.

El sistema define:

- qué unidades y atributos existen;
- cuáles son obligatorios u opcionales;
- cómo se nombran y ordenan;
- qué relaciones pueden establecerse;
- qué reglas deben mantenerse.

Debe ser **estable en sus reglas y flexible en sus contenidos**. La consistencia permite reconocer un patrón; la homogeneidad vuelve comparables las unidades y la variación conserva sus diferencias reales.

Separar contenido y presentación facilita modificar el diseño sin reescribir la información y producir distintas interfaces desde una misma fuente.

Para poder migrar, el contenido debe ser:

- **modular:** cada unidad puede trasladarse;
- **explícito:** su función está nombrada;
- **predecible:** conserva reglas;
- **trazable:** sus fuentes pueden verificarse;
- **actualizable:** una parte puede cambiar sin reconstruir todo.

> **El diseño visual hace perceptible la estructura; no debe inventarla después.**

---

## 10. Trabajar con inteligencia artificial

La inteligencia artificial puede investigar, sintetizar, clasificar, detectar inconsistencias y transformar contenido. Para obtener resultados consistentes necesita instrucciones que definan:

- intención, alcance y audiencia;
- estructura y jerarquía;
- criterios de inclusión y exclusión;
- fuentes y restricciones;
- formato y resultado esperado.

La IA puede asistir en la ejecución, pero no sustituye las decisiones del autor. La responsabilidad sobre la intención, la veracidad y la pertinencia permanece en quien construye el documento.

El autor debe definir el enfoque, verificar los datos, distinguir hechos de interpretaciones, revisar omisiones y documentar el uso de IA.

> **La calidad del resultado depende de la calidad de las decisiones que el prompt logra expresar.**

---

## 11. Proceso de trabajo

1. **Reconocer:** identificar el universo del tema.
2. **Delimitar:** definir el alcance.
3. **Investigar:** reunir información y fuentes.
4. **Formular:** establecer intención, audiencia y tono.
5. **Seleccionar:** conservar lo que sostiene la intención.
6. **Modelar:** definir unidades, atributos y relaciones.
7. **Jerarquizar:** ordenar por importancia y dependencia.
8. **Escribir:** documentar la estructura en Markdown.
9. **Revisar:** comprobarla mediante el índice.
10. **Validar:** verificar claridad, consistencia y fuentes.
11. **Transformar:** utilizar el documento como origen de otros formatos.

---

## 12. Criterios de validación

Antes de considerar terminado el documento, debemos comprobar:

### Intención y alcance

- ¿Comunica una idea específica y mantiene el enfoque?
- ¿La audiencia, el propósito y los límites son claros?
- ¿Toda la información incluida cumple una función?

### Investigación

- ¿Los datos y fuentes pueden verificarse?
- ¿Se distinguen hechos, interpretaciones y pendientes?

### Estructura

- ¿Cada sección y unidad cumple una función?
- ¿Los atributos equivalentes conservan nombres consistentes?
- ¿El índice permite comprender el recorrido?
- ¿La jerarquía puede trasladarse a HTML?

### Reutilización e IA

- ¿El contenido puede separarse de su presentación?
- ¿La estructura puede aplicarse a otras unidades y formatos?
- ¿Las instrucciones dadas a la IA son claras?
- ¿El resultado fue revisado y no presenta invenciones como hechos?

---

## Principio general

> **La intención determina qué información necesitamos. La estructura organiza sus relaciones. La jerarquía establece cómo se comprende. Markdown documenta esas decisiones para que puedan revisarse, reutilizarse y transformarse.**

Un documento digital comienza cuando una colección de datos se convierte en una estructura capaz de comunicar con claridad.

---

## Referencias conceptuales

- [An introduction to structured content — Digital.gov](https://digital.gov/resources/an-introduction-to-structured-content)
- [Writing for Web Accessibility — W3C Web Accessibility Initiative](https://www.w3.org/WAI/tips/writing/)
- [CommonMark Specification](https://spec.commonmark.org/)

