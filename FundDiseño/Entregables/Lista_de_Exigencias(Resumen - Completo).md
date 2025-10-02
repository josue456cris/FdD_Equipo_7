# 📑 Informe Técnico – Lista de Exigencias  
**Proyecto:** Kartoffelmachine – Clasificador Inteligente de Papas Canchán  
**Equipo 7 – Fundamentos de Diseño 2025-2**  
**Cliente:** Universidad Peruana Cayetano Heredia  
**Integrantes:**  
- Josue Cristhian Mateo Mogollon Flores  
- Nicole Jacqueline Anyosa Barrientos  
- Mathias Dylan Henry Quispe Charres  
- Dayra Martina Kuang Mauricio  

---

## 📖 Artículos Científicos
1. **Automatic detecting and grading method of potatoes based on machine vision**  
   - Propone un método de detección y clasificación de papas mediante visión por computadora.  
   - [Enlace](https://www.researchgate.net/publication/287698787_Automatic_detecting_and_grading_method_of_potatoes_based_on_machine_vision)  

2. **Designing an FPGA Synthesizable Computer Vision Algorithm to Detect the Greening of Potatoes**  
   - Implementación de un algoritmo de visión en FPGA para detectar el verdor en papas.  
   - [Enlace](https://ijettjournal.org/assets/volume-8/number-8/IJETT-V8P275.pdf)  

3. **Enhanced YOLOv11n: A Method for Potato Peel Damage Detection**  
   - Uso de un modelo YOLO mejorado para detectar daños en la piel de las papas con alta precisión.  
   - [Enlace](https://pmc.ncbi.nlm.nih.gov/articles/PMC12227660/#fsn370576-sec-0019)  

---

## 📑 Patentes
1. **Equipo de detección de enfermedades de la papa**  
   - Solicitud: Mongolia Interior Zhongjia Agricultural Biotechnology Co. Ltd.  
   - Uso de sensores de color para identificar enfermedades en hojas de papa.  
   - [Enlace](https://worldwide.espacenet.com/patent/search/family/062686222/publication/CN207571014U)  

2. **Método, unidad sensora y máquina para detectar defectos de “Sugar Top” en papas**  
   - Solicitud: Markus Burgstaller y colaboradores (Austria).  
   - Usa fuentes de luz y fotosensores para detectar defectos en los extremos de la papa.  
   - [Enlace](https://worldwide.espacenet.com/patent/search/family/044352478/publication/US2014056482A1)  

3. **Grading type combined harvester for potatoes**  
   - Solicitud: Gansu Agricultural University.  
   - Cosechadora que además clasifica papas según tamaño y calidad con un sistema automatizado.  
   - [Enlace](https://worldwide.espacenet.com/patent/search/family/049183990/publication/CN103314698A)  

---

## 🛒 Productos Comerciales
1. **Sistema Automático para Clasificar Papas Andinas de Calidad (Perú)**  
   - Prototipo peruano desarrollado con apoyo de Concytec.  
   - Clasifica hasta 4 papas por segundo (2 ton/hora).  
   - [Enlace](https://proyectofortalecimientodelsinacti.prociencia.gob.pe/noticia/ingenieros-peruanos-crean-sistema-automatico-para-clasificar-papas-andinas-de-calidad)  

2. **TSI AirAssure 8144-6**  
   - Sensor comercial de calidad del aire que sirve como referencia tecnológica en IoT agrícola.  

3. **uHoo Smart Air Monitor / PurpleAir Touch**  
   - Monitores de aire aplicables como referencia en integración de sensores IoT.  
   - [PurpleAir](https://www2.purpleair.com)  

---
## 📋 Lista de Exigencias y Deseos – Kartoffelmachine  
**Proyecto:** Máquina de clasificación de calidad, tamaño y color de la papa nativa Canchán  
**Cliente:** Universidad Peruana Cayetano Heredia  
**Integrantes:**  
- Josue Cristhian Mateo Mogollon Flores (JM)  
- Nicole Jacqueline Anyosa Barrientos (N)  
- Mathias Dylan Henry Quispe Charres (DK)  
- Dayra Martina Kuang Mauricio (MQ)  

---

| Fecha   | E/D | Nombre : Descripción | Responsable |
|---------|-----|----------------------|-------------|
| 21/08   | E | Función principal: Clasificar papa Canchán en base a tamaño, color y calidad, determinando su estado para consumo. | DK |
| 28/08   | E | Geometría: El prototipo no debe superar 50 × 10 × 10 cm incluyendo cámara, sensores y panel solar. | JM |
| 04/09   | E | Cinemática: El prototipo debe capturar al menos 5 imágenes en un giro manual de 360° alrededor de la papa en menos de 30 segundos, sin dañar el cultivo. | N |
| 11/09   | E | Fuerzas: El peso total del prototipo no debe superar los 3 kg, para asegurar portabilidad en campo. | JM |
| 18/09   | E | Energía: El sistema funciona con panel solar de 5V / 3W (600 mA), garantizando autonomía en campo. | MQ |
| 25/09   | E | Materia: Materia de ingreso de prueba → 1 kg de papa Canchán en distintos estados post-cosecha (fresca, con brotes o dañada). | MQ |
| 02/10   | E | Señales (Información): La cámara ESP32-CAM captura imágenes con resolución mínima de 640 × 480 px y sensores de color registran variables. Los datos se almacenan en un dataset. | JM |
| 09/10   | E | Control: El sistema se controla con un microcontrolador ESP32, encargado de manejar cámara, sensores y comunicación IoT. | N |
| 16/10   | E | Electrónico (Hardware): Integración de cámara, tiras LED, fotosensor y drivers en un circuito estable conectado al ESP32 en protoboard. | JM |
| 23/10   | E | Software: El software debe implementar visión artificial con Machine Learning. Entrenamiento mínimo con 400 imágenes de papas Canchán. | N |
| 30/10   | E | Comunicaciones: La comunicación entre sensores, cámara y controlador será por cableado directo, asegurando interoperabilidad estable. | MQ |
| 06/11   | E | Seguridad: Todos los componentes eléctricos deben estar protegidos con cubiertas plásticas y aislante termoencogible, incluyendo botón de apagado seguro. Cumple normas ISO 468, ISO 22000, ISO 45001. | MQ |
| 13/11   | D | Ergonomía: El trípode debe permitir girar manualmente alrededor de la papa con un radio de 20–25 cm, facilitando el uso del operador. | MQ |
| 20/11   | D | Fabricación: El prototipo debe poder fabricarse con herramientas de taller básico y materiales accesibles como madera o acrílico. | DK |
| 27/11   | E | Control de Calidad: La precisión de clasificación debe ser ≥ 80% en pruebas controladas con dataset de papas Canchán. | DK |
| 04/12   | D | Montaje: El sistema debe ensamblarse en menos de 2 horas, con piezas modulares fáciles de conectar. | JM |
| 04/12   | D | Transporte: El trípode debe ser plegable y con peso máximo de 3 kg para permitir transporte manual en campo. | DK |
| 04/12   | D | Uso: El uso del prototipo se realiza bajo las condiciones del cultivo en diferentes condiciones ambientales, cómo humedad y altitud. Su uso se proyecta en la región de la Sierra del país  a condiciones de 2 000 a 3 500 metros sobre el nivel del mar, debido a que zonas sobre este nivel máximo son consideradas zonas de incidencia según el Ministerio de Agricultura. | N |
| 11/12   | D | Mantenimiento: El diseño de Kartoffeln maschine esta previsto con materiales de facil acceso por lo que permite la simple limpieza y reemplazo de sus componentes. | JM |
| 11/12   | E | Costos: El prototipo debe mantenerse entre 500 y 1000 soles, incluyendo estructura y componentes electrónicos. | DK |
| 11/12   | E | Plazos: El proyecto comenzará el jueves 25 de septiembre. Debe estar listo antes de la fecha de sustentación y se espera su culminación el miércoles 11 de diciembre a las 7:00 am. | N |

---

