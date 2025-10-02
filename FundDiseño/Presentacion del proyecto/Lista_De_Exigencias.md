# 📋 Lista de Exigencias y Deseos de Kartoffelmachine  

**Proyecto:** Máquina de clasificación de calidad, tamaño y color de la papa nativa Canchán  
**Cliente:** Universidad Peruana Cayetano Heredia  
**Integrantes:**  
- Josue Cristhian Mateo Mogollon Flores (JM)  
- Nicole Jacqueline Anyosa Barrientos (N)  
- Mathias Dylan Henry Quispe Charres (DK)  
- Dayra Martina Kuang Mauricio (MQ)  

---

| Fecha   | E/D | Nombre : Descripción | Responsable |
|---------|-----|--------------------------------|-------------|
| 21/08   | E | **Función principal:** El prototipo Kartoffelmachine tiene como objetivo clasificar la papa Canchán directamente en el cultivo, sin necesidad de extraerla del suelo. La clasificación se realiza según tamaño, color y calidad, lo que permite determinar si es apta o no para el consumo. Esto ayuda a reducir pérdidas postcosecha y brinda al agricultor una herramienta sencilla y confiable. | DK |
| 28/08   | E | **Geometría:** El prototipo no debe superar las dimensiones de 50 × 10 × 10 cm, incluyendo cámara, sensores, tiras LED y panel solar. Este límite asegura un diseño compacto y ligero, fácil de transportar y de colocar en campo sin dañar la planta. Mantener medidas reducidas es clave para la aceptación y uso práctico por parte de agricultores. | JM |
| 04/09   | E | **Cinemática:** El movimiento de análisis será manual. El operador debe girar el trípode 360° alrededor de la papa, capturando al menos cinco imágenes en menos de 30 segundos. Este mecanismo simple evita complicaciones mecánicas, reduce costos y permite un análisis rápido y seguro sin dañar el cultivo. | N |
| 11/09   | E | **Fuerzas:** El prototipo no debe superar un peso máximo de 3 kg. Este valor es comparable al peso de una mochila ligera, lo que asegura que pueda ser transportado fácilmente entre surcos. Mantener un peso bajo es esencial para su portabilidad y uso manual en campo. | JM |
| 18/09   | E | **Energía:** El sistema funcionará con un panel solar de 5V / 3W (600 mA), garantizando autonomía en zonas rurales sin electricidad. Esto permite su uso continuo en campo y promueve la sostenibilidad al alinearse con el ODS 7 (energía limpia y asequible). | MQ |
| 25/09   | E | **Materia:** La materia de prueba será 1 kg de papas Canchán en distintos estados postcosecha (frescas, germinadas o dañadas). El prototipo debe analizarlas directamente en el cultivo, simulando condiciones reales y entrenando al sistema para reconocer diferentes calidades. | MQ |
| 02/10   | E | **Señales – Información:** El prototipo usará una cámara ESP32-CAM con resolución mínima de 640 × 480 px y sensores de color y luz. Los datos obtenidos se almacenarán en un dataset para entrenar los algoritmos de clasificación, asegurando un análisis robusto y confiable. | JM |
| 09/10   | E | **Control:** El sistema será gestionado por un microcontrolador ESP32, encargado de coordinar cámara, sensores y transmisión de datos. Aunque el giro sea manual, el ESP32 asegura que el proceso de captura y almacenamiento sea centralizado y eficiente. | N |
| 16/10   | E | **Electrónico – Hardware:** La máquina integrará cámara, tiras LED, fotosensor y drivers en un circuito estable montado en protoboard, conectado al ESP32. Esta integración garantiza imágenes claras y funcionalidad confiable en condiciones variables de campo. | JM |
| 23/10   | E | **Software:** El sistema usará algoritmos de visión artificial con Machine Learning. Para el entrenamiento se emplearán al menos 400 imágenes de papas Canchán en diversos estados de calidad. Modelos ligeros como YOLO-tiny o MobileNet permitirán ejecutar el análisis en el ESP32. | N |
| 30/10   | E | **Comunicaciones:** La conexión entre cámara, sensores y microcontrolador será por cableado directo. Esto asegura una transmisión estable de datos en campo, donde las señales inalámbricas pueden ser poco confiables. | MQ |
| 06/11   | E | **Seguridad:** Todos los componentes eléctricos estarán protegidos con aislante termoencogible y cubiertas plásticas. Se incluirá un botón de apagado seguro. El diseño cumplirá con normas como ISO 468, ISO 22000 e ISO 45001, garantizando seguridad eléctrica, alimentaria y laboral. | MQ |
| 13/11   | D | **Ergonomía:** El trípode será ligero y permitirá un giro manual con un radio de 20–25 cm alrededor de la papa. Esto facilita la manipulación, evitando esfuerzos excesivos y permitiendo un uso cómodo por parte del agricultor en campo. | MQ |
| 20/11   | D | **Fabricación:** El prototipo debe construirse con materiales accesibles como madera o acrílico, y poder ensamblarse en talleres básicos. Este enfoque reduce costos y facilita que el diseño sea replicable en comunidades agrícolas. | DK |
| 27/11   | E | **Control de calidad:** El sistema debe alcanzar al menos un 80% de precisión en la clasificación de papas Canchán. Este valor asegura confianza en los resultados y supera la variabilidad del trabajo manual. | DK |
| 04/12   | D | **Montaje:** El prototipo debe ensamblarse en menos de 2 horas, con piezas modulares fáciles de unir. Esto permite un armado rápido en campo y mejora la practicidad para su transporte. | JM |
| 04/12   | D | **Transporte:** El prototipo debe ser plegable y mantener un peso ≤ 3 kg. De esta forma, puede trasladarse manualmente entre surcos de cultivo sin esfuerzo, aumentando su usabilidad. | DK |
| 04/12   | D | **Uso:** El prototipo debe poder operar bajo condiciones ambientales variables como polvo, humedad y cambios de luz. Además, su uso está proyectado en zonas andinas entre 2000 y 3500 msnm, de acuerdo con las áreas de incidencia agrícola reportadas por el Ministerio de Agricultura. | N |
| 11/12   | D | **Mantenimiento:** El diseño debe permitir limpieza rápida y el reemplazo de componentes (sensores o cámara) en menos de 5 minutos. Al usar materiales accesibles, el agricultor podrá realizar el mantenimiento sin asistencia técnica especializada. | JM |
| 11/12   | E | **Costos:** El costo del prototipo debe estar en un rango de 500 a 1000 soles, incluyendo estructura y electrónica. Este rango asegura que sea accesible para universidades y agricultores. | DK |
| 11/12   | E | **Plazos:** El proyecto debe estar finalizado antes de la sustentación del 11 de diciembre a las 7:00 a.m. Cumplir este plazo garantiza que se entregue un prototipo funcional y listo para su evaluación en campo. | N |

---
