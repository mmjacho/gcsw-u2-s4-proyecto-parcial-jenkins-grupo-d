# Proyecto del Primer Parcial: Pipeline CI/CD con Jenkins — Grupo D

**Universidad de Guayaquil**  
**Facultad de Ciencias Matemáticas y Físicas**  
**Carrera de Software**  
**Asignatura:** Gestión de la Configuración del Software (Unidad 2 — Semana 4)  
**Docente:** Ph.D. Franklin Ricardo Parrales Bravo  
**Grupo:** Grupo D  

---

## 🎥 Video de Entrega (YouTube)

> **Enlace al video de evidencia:** *(Pendiente de publicar — pegar aquí el enlace de YouTube)*  
> `https://youtu.be/PENDIENTE`

El video documentará la secuencia completa de pasos y la ejecución exitosa del pipeline en Jenkins:
- Configuración inicial de Jenkins y sus plugins necesarios.
- Estructura del proyecto en GitHub (código fuente, pruebas unitarias y `Jenkinsfile`).
- Configuración del **Webhook** en GitHub y disparo (*trigger*) automático ante nuevos *commits*.
- Ejecución completa de las etapas del pipeline CI/CD (**Build**, **Test** y **Deploy**).
- Evidencia de las notificaciones automáticas del estado del pipeline y despliegue funcional.

---

## 🎯 Objetivo de Aprendizaje

Aplicar estrategias de integración y despliegue continuo (**CI/CD**) mediante el uso de **Jenkins** para automatizar el proceso de construcción, pruebas y despliegue de un proyecto de software, asegurando la gestión eficiente de versiones y cambios.

---

## 👥 Integrantes — Grupo D

| # | Integrante | Rol |
| :-: | :--- | :--- |
| 1 | Jefferson Xamir Anchundia Peñaherrera | Estudiante — Grupo D |
| 2 | María Fernanda Chourio Linares | Estudiante — Grupo D |
| 3 | Everaldo Alejandro Fernández Villamar | Estudiante — Grupo D |
| 4 | Mario Mauricio Jacho Cedeño | Estudiante — Grupo D |
| 5 | Rubén Alfredo Quiroga Peralta | Estudiante — Grupo D |
| 6 | Ronny Andrés Sánchez Moriel | Estudiante — Grupo D |
| 7 | Alonso Mikkail Serrano Abarca | Estudiante — Grupo D |
| 8 | Elías Hernán Vera Landázuri | Estudiante — Grupo D |
| 9 | Danna Briggitte Vera Moreira | Estudiante — Grupo D |
| 10 | Luis Enrique Vera Sabando | Estudiante — Grupo D |

---

## 🛠️ Orden y Procedimiento del Proyecto

### 1. Configuración Inicial
- Instalar **Jenkins** en un entorno local o en una instancia en la nube, con los plugins necesarios.
- Configurar este repositorio en **GitHub** con código fuente, pruebas unitarias y el archivo declarativo `Jenkinsfile`.

### 2. Creación del Pipeline (`Jenkinsfile`)
Definir e implementar las siguientes etapas automatizadas:
- **Build:** Compilación / preparación del código fuente.
- **Test:** Ejecución automática de pruebas unitarias.
- **Deploy:** Despliegue automatizado en un entorno de prueba (e.g., Docker o servidor local).

### 3. Automatización
- Configurar **Webhooks** en GitHub para el disparo (*trigger*) automático del pipeline ante nuevos *commits*.
- Implementar **notificaciones** (e.g., correo electrónico o Slack/Discord) para informar el resultado de cada ejecución del pipeline.

### 4. Documentación
- Redactar un **Informe Técnico en PDF (3–5 páginas)** que incluya:
  - Arquitectura del pipeline, descripción paso a paso y capturas de pantalla (*printscreens*).
  - Herramientas utilizadas con sus respectivas versiones.
  - Problemas encontrados y soluciones aplicadas.
  - Enlace al video de YouTube con la evidencia de la secuencia de pasos.

---

## 📦 Entregables y Estado de Avance

| Entregable | Descripción | Estado |
| :--- | :--- | :-: |
| **Repositorio GitHub** | Código fuente, pruebas unitarias y `Jenkinsfile` | 🚧 En desarrollo (repositorio inicializado) |
| **Pipeline Funcional** | Ejecución exitosa en Jenkins (Build, Test, Deploy) con Webhook y notificaciones | ⏳ Pendiente |
| **Video en YouTube** | Evidencia en video de la secuencia de pasos y ejecución del pipeline | ⏳ Pendiente |
| **Informe Técnico (PDF)** | Documento de 3–5 páginas con arquitectura, capturas, versiones y problemas/soluciones | ⏳ Pendiente |

---

## 📂 Estructura Planificada del Repositorio

```text
gcsw-u2-s4-proyecto-parcial-jenkins-grupo-d/
├── README.md               # Documentación general, integrantes y enlace al video de YouTube
├── Jenkinsfile             # Definición del pipeline CI/CD (Build, Test, Deploy) [Por implementar]
├── Dockerfile              # Contenedor para despliegue automatizado [Por implementar]
├── src/                    # Código fuente del proyecto [Por implementar]
├── tests/                  # Pruebas unitarias [Por implementar]
└── docs/                   # Informe técnico (PDF) y capturas de evidencia [Por implementar]
```

---

## 📊 Rúbrica de Evaluación

| Criterio | Excelente (3 pts) | Bueno (2 pts) | Regular (1 pt) | Deficiente (0 pts) |
| :--- | :--- | :--- | :--- | :--- |
| **Configuración de Jenkins** | Jenkins instalado y configurado correctamente con todos los plugins necesarios. | Configuración funcional pero con plugins faltantes o ajustes menores. | Configuración básica lograda, pero con errores en plugins o conexiones. | Jenkins no funciona o falta la mayoría de los plugins esenciales. |
| **Pipeline CI/CD** | Pipeline completo con etapas de build, test y deploy, totalmente automatizado. | Pipeline funcional pero con una etapa incompleta (e.g., deploy manual). | Pipeline ejecutable pero con errores en pruebas o despliegue. | Pipeline no ejecuta las etapas críticas (build/test/deploy). |
| **Integración con GitHub** | Webhooks configurados correctamente para trigger automático y notificaciones. | Webhooks configurados pero sin notificaciones o triggers inconsistentes. | Configuración parcial; requiere intervención manual para ejecutar. | Sin integración con GitHub. |
| **Informe Técnico** | Documento detallado con explicaciones claras, problemas/soluciones y evidencia en YouTube. | Informe completo con video de YouTube pero con falta de profundidad en algunos aspectos. | Informe básico con video de YouTube pero con omisiones importantes. | Informe incompleto o sin evidencia del pipeline. |
| **Calidad del Código** | Código bien estructurado, con pruebas unitarias y comentarios explicativos. | Código funcional pero con pruebas limitadas o falta de comentarios. | Código funciona pero es confuso o sin pruebas. | Código incompleto o con errores graves. |
