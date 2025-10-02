<!-- Encabezado -->
<h1 align="center">Equipo 7 — Fundamentos de Diseño 2025-2</h1>
<p align="center"><b>Kartoffelmachine</b> · Clasificador inteligente de papas</p>
<p align="center">
  <em>ODS 12 — Producción y Consumo Responsables</em>
</p>

<p align="center">
  <img alt="UPCH" src="https://img.shields.io/badge/Universidad-UPCH-0B7A75?style=flat-square">
  <img alt="Curso" src="https://img.shields.io/badge/Curso-Fundamentos%20de%20Diseño-1F2937?style=flat-square">
  <img alt="Estado" src="https://img.shields.io/badge/Estado-En%20desarrollo-334155?style=flat-square">
  <img alt="ODS 12" src="https://img.shields.io/badge/ODS-12-DAA520?style=flat-square">
</p>
<p align="center">
  <img src="recursos/imagenes/ODS12.gif" alt="ODS 12 - Producción y consumo responsables" width="300"/>
</p>

---

## 🧭 Descripción
El **Equipo 7** desarrolla *Kartoffelmachine*, un clasificador inteligente de papas que combina **ESP32-CAM, sensores y machine learning** para identificar tamaño, variedad y calidad (detectando papas verdes o dañadas).  
El objetivo es **reducir pérdidas poscosecha** y apoyar la **ODS 12: Producción y Consumo Responsables**.

ODS relacionadas:  
- ♻️ ODS 12: Producción y Consumo Responsables  
- 🌾 ODS 2: Hambre Cero  
- ❤️ ODS 3: Salud y Bienestar  
- 🌍 ODS 13: Acción por el Clima  

---

## 📑 Contenido
- [ODS 12](#🌍-ods-12)  
- [Materiales](#🛠️-materiales)  
- [Metodología](#🧩-metodología)  
- [Temática](#🎯-temática)  
- [Integrantes](#👥-integrantes)  
- [Docentes](#👩‍🏫-docentes)  

---

## 🌍 ODS 12
La **ODS 12** busca garantizar producción y consumo sostenibles, minimizando desperdicios.  
*Kartoffelmachine* se inspira en este objetivo para mejorar la clasificación de papas y aprovechar al máximo los cultivos.

---

## 🛠️ Materiales
| Material | Cantidad | Función |
|----------|----------|---------|
| ESP32-CAM | 1 | Captura imágenes y ejecuta el modelo ML. |
| USB to Serial Converter | 1 | Programación de la ESP32-CAM. |
| Pantalla OLED 0.96" | 1 | Muestra resultados de clasificación. |
| Sensor TCS34725 | 1 | Mide color y verdor. |
| LDR | 1 | Detecta luz ambiental (riesgo de enverdecimiento). |
| DHT22 (o DHT11) | 1 | Mide temperatura y humedad. |
| Bluetooth HC-05 | 1 | Envía resultados a celular/PC. |
| Panel solar + batería 18650 | 1 | Alimentación sostenible. |
| Aro/tira LED | 1 | Iluminación constante para la cámara. |
| Papas de muestra (Conchán) | 1 kg c/u | Dataset real para entrenamiento ML. |

---

## 🧩 Metodología
1. **Investigación** → desperdicio poscosecha y necesidades de clasificación.  
2. **Diseño** → integración de ESP32-CAM, sensores y estructura reciclada.  
3. **Programación** → lectura de sensores y ejecución del modelo ML.  
4. **Pruebas** → clasificación por tamaño y calidad con dataset real.  
5. **Iteración** → mejoras en precisión y sostenibilidad.  

---

## 🎯 Temática
*Kartoffelmachine* combina **IoT + visión artificial + machine learning** para:  
- ⚖️ Clasificar papas por **tamaño** (pequeña, mediana, grande).  
- 👀 Revisar la **calidad**, detectando papas verdes o con defectos.  
- ♻️ Reducir **pérdidas poscosecha** y fomentar consumo responsable.  

---

## 📸 Fotografía del Equipo
![IMG-20250828-WA0004 1](https://github.com/user-attachments/assets/0a4e330e-6d46-49d8-8c06-36d7d69c9a28)

---

## 👥 Integrantes del Equipo  

| Foto                                                                 | Nombre                                | Rol                          | Intereses                                      |
|----------------------------------------------------------------------|---------------------------------------|------------------------------|------------------------------------------------|
| <img src="recursos/imagenes/Josue.jpg" alt="Josue" width="80"/>    | **Josue Cristhian Mateo Mogollon Flores** | Líder del equipo            | Innovación social, sostenibilidad              |
| <img src="recursos/imagenes/DylanXD.jpg" alt="Dylan" width="80"/>  | **Mathias Dylan Henry Quispe Charres**  | Diseñador                   | Diseño de prototipos, creatividad aplicada     |
| <img src="recursos/imagenes/Foto1.jpg" alt="Nicole" width="80"/>   | **Nicole Jacqueline Anyosa Barrientos** | Responsable de investigación | Gestión ambiental, desarrollo comunitario      |
| <img src="recursos/imagenes/Dayra.jpg" alt="Dayra" width="80"/>    | **Dayra Martina Kuang Mauricio**        | Encargada de documentación  | Comunicación científica, redacción técnica     |

---

## 👩‍🏫 Docentes
- Jhomer Rodrigo Contreras Paucca  
- Julissa Elvira Venancio Huerta  

---

## 📝 Resumen
El prototipo **Kartoffelmachine** usa **sensores, cámara y ML** para clasificar papas canchan en base al  tamaño y calidad, apoyando el consumo responsable y la sostenibilidad agrícola.
