# 🔌 Módulo Electrónico – Diseño del Circuito (EasyEDA)

Este módulo documenta el diseño electrónico del proyecto *Kartoffelmachine*, donde se desarrolló el esquema principal del sistema utilizando **EasyEDA**, integrando la ESP32-CAM, servomotores, pantalla OLED y la alimentación mediante batería LiPo.

---

## 📘 1. Diseño del Circuito en EasyEDA

El circuito fue desarrollado desde cero en EasyEDA, definiendo:

- La distribución y conexión de todos los componentes electrónicos.  
- Las señales del sistema (alimentación, control, comunicación).  
- La organización del diagrama mediante etiquetas y bloques funcionales.  
- El correcto acoplamiento entre la ESP32-CAM, el servomotor SG90 y la pantalla OLED.  

El diseño asegura una alimentación estable y conexiones limpias, evitando interferencias y facilitando la lectura del esquema.

### 📄 Esquemático final

Puedes visualizar el esquema completo aquí:

#### **`Schematic_New-Project_2025-11-14.pdf`**
👉 (se mostrará directamente en GitHub)

![Esquemático](Schematic_New-Project_2025-11-14.pdf)

---

## 🧩 Componentes principales del circuito

El diseño integra los siguientes elementos esenciales:

- **ESP32-CAM (U1)** – Unidad principal de procesamiento y captura.  
- **Pantalla OLED 0.96” I2C (U3)** – Visualización de estados y datos del sistema.  
- **Servomotor SG90 (U2)** – Mecanismo de movimiento del actuador.  
- **Converter 3.7V–5V (CN1)** – Paso de energía entre batería y ESP32-CAM.  
- **Batería LiPo 16000 mAh (U4)** – Fuente principal de alimentación del sistema.  

Cada uno está conectado cuidadosamente para garantizar el correcto funcionamiento del prototipo.

---

## ⚡ Conclusión

El módulo electrónico proporciona la base de funcionamiento del sistema, integrando alimentación, control y comunicación mediante una arquitectura sencilla pero eficiente.  
Este diseño permite ensamblar y verificar en hardware todos los subsistemas necesarios para *Kartoffelmachine*.

---



