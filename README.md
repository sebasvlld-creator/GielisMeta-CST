# GielisMeta-CST

**GielisMeta-CST** es un proyecto académico y de investigación orientado al diseño, visualización, construcción y simulación de estructuras metamateriales basadas en curvas de Gielis, integrando herramientas como MATLAB, CST Studio Suite y tecnologías web.

El repositorio contiene dos versiones principales del sistema:

1. **Versión oficial en MATLAB App Designer**
2. **Versión estudiantil en JavaScript**

La versión oficial en MATLAB funciona como implementación de referencia desarrollada por el docente. La versión estudiantil en JavaScript será desarrollada por los estudiantes como ejercicio académico de diseño de interfaces, programación, conexión con MATLAB y preparación de modelos para CST Studio Suite.

---

## Objetivo general

Desarrollar una plataforma académica para generar estructuras electromagnéticas basadas en la fórmula de Gielis, visualizar su geometría, configurar parámetros físicos y preparar el flujo de automatización hacia CST Studio Suite para simulaciones electromagnéticas.

---

## Versiones del proyecto

### 1. Versión oficial en MATLAB

La versión oficial está desarrollada en **MATLAB App Designer** y permite:

* Ingresar parámetros de la ecuación de Gielis.
* Generar la curva base.
* Crear estructuras concéntricas.
* Configurar sustrato, conductor y dieléctrico.
* Seleccionar el modo de aplicación.
* Construir modelos en CST Studio Suite.
* Ejecutar simulaciones.
* Realizar postprocesamiento de resultados.

Esta versión será documentada mediante un **manual de usuario en inglés**.

Ubicación:

```text
matlab_app_version/
```

---

### 2. Versión estudiantil en JavaScript

La versión estudiantil será desarrollada por los estudiantes usando tecnologías web. Su objetivo es construir una interfaz propia que permita ingresar parámetros, visualizar la geometría y preparar la comunicación con MATLAB.

Esta versión debe contemplar:

* Interfaz web en JavaScript.
* Formulario de parámetros geométricos.
* Visualización 2D o 3D de la curva de Gielis.
* Organización de datos para MATLAB.
* Flujo conceptual de conexión con CST Studio Suite.
* Documentación técnica del desarrollo.

Ubicación:

```text
student_js_version/
```

---

## Modos de aplicación

El sistema contempla tres modos principales:

### Absorbedor

Modo orientado al diseño de estructuras metamateriales con plano de tierra, donde el resultado principal es la absorción electromagnética.

### Transmisor

Modo orientado al análisis de transmisión electromagnética mediante parámetros S, sin plano de tierra.

### Sensor

Modo orientado al diseño de sensores basados en línea microstrip y estructuras complementarias generadas a partir de curvas de Gielis.

---

## Estructura del repositorio

```text
GielisMeta-CST/
│
├── docs/
│   ├── manual_usuario_en/
│   ├── guias_estudiantes/
│   └── arquitectura/
│
├── matlab_app_version/
│   ├── app/
│   ├── cst_interface/
│   └── ejemplos/
│
├── student_js_version/
│   ├── frontend/
│   ├── backend/
│   └── ejemplos/
│
├── assets/
│   ├── logo/
│   ├── capturas_interfaz/
│   ├── figuras_gielis/
│   └── resultados_cst/
│
└── tests/
    ├── matlab_tests/
    ├── js_tests/
    └── integration_tests/
```

---

## Documentación

La documentación se divide en tres bloques:

### Manual de usuario

Ubicación:

```text
docs/manual_usuario_en/
```

Contendrá el manual de la versión oficial MATLAB en inglés.

### Guías para estudiantes

Ubicación:

```text
docs/guias_estudiantes/
```

Contendrá:

* Enunciado del proyecto.
* Entregables.
* Rúbrica de evaluación.
* Cronograma de trabajo.

### Documentación de arquitectura

Ubicación:

```text
docs/arquitectura/
```

Contendrá la explicación del flujo general:

```text
JavaScript → MATLAB → CST Studio Suite
```

y también la arquitectura de la versión oficial en MATLAB.

---

## Requisitos de software

### Para la versión MATLAB

* MATLAB
* MATLAB App Designer
* CST Studio Suite
* Clase o scripts de conexión MATLAB-CST

### Para la versión JavaScript

* Navegador web moderno
* Node.js
* JavaScript, HTML y CSS
* Servidor local o API intermedia para conexión con MATLAB

---

## Entregables esperados para estudiantes

Cada equipo deberá entregar:

1. Interfaz web funcional.
2. Formulario de parámetros de Gielis.
3. Visualización de la geometría generada.
4. Módulo de preparación o envío de datos a MATLAB.
5. Documentación de instalación y uso.
6. Capturas del funcionamiento.
---

## Estado del proyecto

El proyecto se encuentra en fase de desarrollo académico. La versión MATLAB se utiliza como referencia funcional, mientras que la versión JavaScript será construida progresivamente por los estudiantes.


* Simulación electromagnética.
* Documentación técnica de software científico.
