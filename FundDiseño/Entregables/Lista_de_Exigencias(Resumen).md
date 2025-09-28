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

## 📋 Lista de Exigencias – Kartoffelmachine  
**Proyecto:** Máquina de clasificación de calidad, tamaño y color de la papa nativa Canchán  
**Cliente:** Universidad Peruana Cayetano Heredia  
**Integrantes:**  
- Josue Cristhian Mateo Mogollon Flores (JM)  
- Nicole Jacqueline Anyosa Barrientos (N)  
- Mathias Dylan Henry Quispe Charres (DK)  
- Dayra Martina Kuang Mauricio (MQ)  

---

| Fecha   | Deseo o Exigencia | Nombre : Descripción | Responsable |
|---------|-------------------|----------------------|-------------|
| 21/08   | E | Función principal: La función principal es clasificar la papa Canchán en base a tamaño, color y calidad, para poder determinar su estado para consumo. | DK |
| 28/08   | E | Geometría: El tamaño en conjunto, tomando en cuenta sensores, tiras LED, cámara ESP32-CAM, etc., no debe exceder de 50 × 10 × 10 cm. | JM |
| 04/09   | E | Cinemática: La máquina debe ser capaz de clasificar las papas a una velocidad adecuada, sin dañar el producto. | N |
| 11/09   | E | Fuerzas: El peso máximo es de 3 kg para su uso portátil. | JM |
| 18/09   | E | Energía: La energía mínima necesaria para el panel solar es de 5V / 3W (600 mA). | MQ |
| 25/09   | E | Materia: Materia de ingreso: papa Canchán de 1 kg en diferentes estados post-cosecha. | MQ |
| 02/10   | E | Señales (Información): La cámara captará imágenes y los sensores medirán variables de clasificación, la información se almacenará en dataset. | JM |
| 09/10   | E | Control: El sistema debe ser controlado por un microcontrolador (ESP32) capaz de gestionar visión artificial e IoT. | N |
| 16/10   | E | Electrónico (Hardware): Se deben integrar cámara, tiras LED, fotosensor y drivers con el microcontrolador en un circuito estable. | JM |
| 23/10   | E | Software: El software debe implementar visión artificial con Machine Learning para clasificar imágenes. | N |
| 30/10   | E | Comunicaciones: La comunicación entre controlador, sensores y actuadores será directa a través de cableado, garantizando interoperabilidad. | MQ |
| 06/11   | E | Seguridad: La máquina debe proteger componentes eléctricos y evitar riesgos al usuario (ISO 468, ISO 22000, ISO 45001). | MQ |
| 13/11   | E | Ergonomía: El diseño debe permitir fácil manipulación, carga y descarga de papas por el operador. | MQ |
| 20/11   | E | Fabricación: El prototipo debe ser fabricable con herramientas de taller básico y materiales accesibles. | DK |
| 27/11   | E | Control de Calidad: La precisión de clasificación debe superar el 80% en pruebas controladas. | DK |
| 04/12   | E | Montaje: El sistema debe ensamblarse en menos de 2 horas y con piezas modulares. | JM |
| 04/12   | E | Transporte: El sistema debe tener un peso adecuado para su uso manual (uso personal). | DK |
| 04/12   | E | Uso: El prototipo debe poder utilizarse en condiciones reales de cultivo y diferentes ambientes. | N |
| 11/12   | E | Mantenimiento: El diseño debe permitir limpieza y reemplazo de componentes fácilmente. | JM |
| 11/12   | E | Costos: El prototipo debe mantenerse en un costo estimado de 500 a 1000 soles. | DK |
| 11/12   | E | Plazos: El prototipo funcional debe estar listo antes de la sustentación. | N |

---


---
