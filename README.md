# UEA: Interfaces de Usuario

## 🌱 TECNOBOTANIC – Sistema de Riego Automatizado con Interfaz Web

Combina un sistema físico de riego automatizado con una interfaz de usuario moderna e intuitiva desarrollada en **Figma**, evaluada por criterios de usabilidad y diseñada bajo el patrón de arquitectura **MVC**.

---

## 🎯 Objetivo del Proyecto

Diseñar una solución tecnológica que optimice el riego de plantas en espacios domésticos mediante un sistema que:

- Detecte el nivel de humedad de la tierra
- Active una bomba de agua de forma automática o manual
- Permita al usuario interactuar mediante una interfaz web y comandos de voz
- Brinde información en tiempo real sobre el estado de cada planta

---

##  🛠️  Componentes del Sistema

### 🖥️  Software

- `C++` para control en **Arduino**
- `MySQL` para gestión de usuarios y perfiles de riego
- `HTML + CSS` para la interfaz web
- `Figma` para el diseño y prototipado de interfaces

### ⚙️ Hardware

- Arduino Pro Mini
- Sensor higrómetro
- Pantalla TFT ST7789
- Módulo L298N (control de motores)
- Bomba de agua
- Protoboard, resistencias, cables, programador FTDI

---

## 💡 Funcionamiento del Sistema

El sistema cuenta con dos modos de riego:

- **Automático:** Se activa al detectar un nivel de humedad por debajo del umbral configurado.
- **Manual:** El usuario puede activar el riego mediante la interfaz web o comandos de voz.

Además, el sistema:

- Muestra notificaciones sobre el estado de cada planta.
- Visualiza gráficamente el nivel de humedad (por ejemplo, gotas que representan porcentaje).
- Permite crear perfiles personalizados de plantas con nombre, nivel óptimo de humedad y fotografía.

---

## 🧩 Principios de Diseño Aplicados

- **Usabilidad y accesibilidad:** Interfaces simples, colores informativos, íconos claros.
- **Multi-modalidad:** Interacción vía comandos de voz o GUI.
- **Persistencia y recuperación:** Guardado de configuraciones y posibilidad de restaurar.
- **Personalización:** El usuario define parámetros por planta y perfil.
- **Evaluación de usabilidad:** Se aplicó el cuestionario SUS con puntajes mayores a 85 sobre 100.

---

## 🎨 Prototipo de Interfaz

Las interfaces fueron diseñadas y simuladas en Figma:

- 🔗 [Prototipo interactivo en Figma](https://www.figma.com/file/X7aSVcs7Nr9YJLwGFPPGog/Proyecto-Interfaces?node-id=0%3A1)
- 📽 [Video de interacción entre interfaces](https://drive.google.com/file/d/1eO_lY-NAUyeQgTBSePyev0ScWUWlDkLs/view?usp=sharing)
- 📈 [Evaluación SUS – Google Forms](https://docs.google.com/forms/d/e/1FAIpQLScsMSvX93XqW3NsQf64D0qgB-JWRnkBDR6UiEcPf08NPKBpGw/viewform)

---
