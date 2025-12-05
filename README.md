# 🎯 CS2 HUB: AIM GOD v30 - ULTIMATE EDITION

> **La suite definitiva "All-in-One". Ahora con Aim Trainer integrado, Contador de Usuarios en Vivo y Algoritmo de Sensibilidad Áurea.**

![Version](https://img.shields.io/badge/version-v30.0-00e676?style=for-the-badge)
![Game](https://img.shields.io/badge/game-CS2-ff1744?style=for-the-badge)
![Status](https://img.shields.io/badge/status-LIVE%20ONLINE-ff0055?style=for-the-badge&animate=pulse)
[![Platform](https://img.shields.io/badge/platform-Web%20%2F%20Mobile-2979ff?style=for-the-badge)](https://pssa-code.github.io/cs2-sens-tuner/)

## 📋 Descripción

**CS2 HUB: AIM GOD v30** es la evolución final de la herramienta de optimización para Counter-Strike 2. Ya no es solo una calculadora; es un ecosistema completo que vive en un solo archivo HTML.

Esta versión introduce conectividad en tiempo real mediante **Firebase** para ver cuántos jugadores están optimizando su juego simultáneamente, y un **Aim Trainer** nativo para calentar la muñeca sin abrir el juego.

🔗 **Acceder a la herramienta web:** [Tu Link de GitHub Pages Aquí]

---

## 🔥 Nuevas Características (v30)

### 1. 📡 Live User Counter (Tecnología Firebase)
Sistema de monitorización en tiempo real situado en la barra lateral.
* **Backend:** Conectado a Google Firebase Realtime Database.
* **Lógica Inteligente:** Detecta usuarios únicos mediante `localStorage` para evitar duplicados al recargar (F5).
* **Seguridad:** Reglas de validación JSON implementadas para prevenir inyecciones de datos o borrados masivos.
* **Indicador Visual:** Animación de pulso "Live" cuando estás conectado.

### 2. 🎮 Reflex Aim Trainer (Canvas Engine)
Minijuego de entrenamiento integrado directamente en el navegador.
* **Estilo Gridshot:** 3 objetivos simultáneos que reaparecen al instante.
* **Métricas en Vivo:**
    * 🎯 **Score:** Puntuación basada en velocidad.
    * ⏱️ **Tiempo:** Cuenta regresiva de 30s para presión competitiva.
    * 📊 **Precisión:** % de clicks efectivos.
    * ⚡ **KPS:** Kills Per Second (la métrica clave de los Pros).
* **Sincronización:** Muestra tu sensibilidad calculada por el PSA directamente en la pantalla de carga del juego.

---

## 🛠️ Herramientas Core

### 3. 🎯 Calibrador PSA (Golden Ratio v27)
Algoritmo matemático de búsqueda binaria mejorado con la proporción áurea (Phi).
* **Precisión:** 6 decimales.
* **Perfiles Nuevos:** Se añadieron perfiles para *Wrist Aim* y *Entry Fragger*.
* **Feedback Visual:** Medidor de "Agresividad" del algoritmo según la ronda.

### 4. ➕ Pro Crosshairs Database (2025)
Base de datos masiva con códigos de importación directa.
* **Nuevas Adiciones:** donk, m0NESY, malbsMd, jl, w0nderful, frozen, entre otros.
* **Roles:** Clasificados por AWP, Rifler, Entry e IGL.

### 5. 🚀 FPS Pro Extremo & Hardware
La guía de optimización más agresiva hasta la fecha.
* **FPS Ultra:** Variables ocultas del motor Source 2 (`r_drawmodeldecals 0`, `cl_ragdoll_force_count 0`, etc.).
* **Registry Tweaks:** Modificaciones al registro de Windows para priorizar la GPU y reducir la latencia DPC.
* **Launch Options:** Parámetros seguros y experimentales para gamas altas (RTX 4090) y bajas.

### 6. ⚡ Optimización de Latencia (Input Lag)
* **Windows Core:** Desactivación de *Core Isolation* y *SysMain*.
* **HPET:** Instrucciones para deshabilitar el *High Precision Event Timer* en BIOS y Windows.
* **Red:** Algoritmo *CTCP* (Compound TCP) y eliminación de bufferbloat.
* **Mouse:** Fix de registro para aumentar el buffer de datos del ratón (`MouseDataQueueSize`).

---

## 💻 Instalación y Uso

### Opción A: Uso Web (Recomendado)
Simplemente entra al enlace de GitHub Pages. La base de datos ya está conectada.

### Opción B: Uso Local / Clonar
Si descargas el código, necesitas tu propia base de datos para el contador:
1. Crea un proyecto en [Firebase Console](https://console.firebase.google.com/).
2. Crea una **Realtime Database**.
3. Copia tu `firebaseConfig` (API Key, ProjectId, etc.).
4. Reemplaza la variable `const firebaseConfig` al final del archivo `index.html`.

---

## ⚠️ Advertencia y Responsabilidad

> **USO AVANZADO:**
> Las pestañas marcadas con ⚠️ o **"Extremo"** contienen comandos que modifican profundamente Windows.
> * **FPS Pro:** Desactiva efectos visuales del juego que no se pueden revertir sin quitar el autoexec.
> * **Registry:** Siempre haz un backup antes de ejecutar archivos `.reg`.
> * **Launch Options:** Si el juego se cierra, borra los parámetros de lanzamiento.

---

## 🏗️ Stack Tecnológico

* **Frontend:** HTML5, CSS3 (Variables, Flexbox, Animations).
* **Scripting:** JavaScript Vanilla (ES6+).
* **Backend:** Firebase SDK 8.10.1 (Realtime Database).
* **Graphics:** HTML5 Canvas API (para el Aim Trainer).

---

## 📝 Créditos

Creado para la comunidad competitiva.
* **Datos de Pro Players:** HLTV & ProSettings.net
* **Optimización:** Basado en documentación técnica de Source 2 y Windows Kernel.

---
*CS2 HUB: AIM GOD v30 © 2025*
