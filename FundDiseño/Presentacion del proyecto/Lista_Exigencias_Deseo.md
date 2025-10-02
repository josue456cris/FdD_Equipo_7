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
| 21/08   | E | **Función principal:** El prototipo Kartoffelmachine tiene como objetivo clasificar papas Canchán en etapa de postcosecha. La clasificación se realiza según **tamaño, color y calidad**, separando las papas aptas de las no aptas. Esto permite reducir pérdidas y mejorar la comercialización. | DK |
| 28/08   | E | **Geometría:** El prototipo no debe superar las dimensiones de **50 × 10 × 10 cm**, incluyendo cámara, sensores, LEDs y panel solar. Un diseño compacto garantiza portabilidad y facilidad de uso en espacios de almacenamiento postcosecha. | JM |
| 04/09   | E | **Cinemática:** El análisis será **manual**: el agricultor coloca las papas en el área de prueba y la máquina captura al menos cinco imágenes en menos de 30 segundos. Este mecanismo es simple, económico y rápido. | N |
| 11/09   | E | **Fuerzas:** El prototipo no debe superar un peso máximo de **3 kg**, similar a una mochila ligera. Esto asegura que pueda ser transportado fácilmente entre diferentes zonas de acopio o almacenamiento. | JM |
| 18/09   | E | **Energía:** Funcionará con un **panel solar de 5V / 3W**, garantizando autonomía en zonas rurales sin electricidad. Promueve sostenibilidad al alinearse con el ODS 7 (energía limpia y asequible). | MQ |
| 25/09   | E | **Materia:** La materia de prueba será **1 kg de papas Canchán postcosecha** en distintos estados (frescas, germinadas o dañadas). Esto asegura que el sistema aprenda a reconocer condiciones reales. | MQ |
| 02/10   | E | **Señales – Información:** Se usará una **cámara ESP32-CAM** (mínimo 640 × 480 px) y sensores de color y luz. Los datos recolectados se almacenarán en un dataset para entrenar los algoritmos de clasificación. | JM |
| 09/10   | E | **Control:** El sistema será gestionado por un **ESP32**, encargado de coordinar la cámara, sensores y transmisión de datos. Garantiza un proceso de captura y almacenamiento centralizado y eficiente. | N |
| 16/10   | E | **Electrónico – Hardware:** La máquina integrará cámara, tiras LED, fotosensor y drivers en un circuito estable. Esta integración asegura imágenes claras incluso con cambios de luz en ambientes postcosecha. | JM |
| 23/10   | E | **Software:** Usará algoritmos de **visión artificial con Machine Learning**, entrenados con al menos **400 imágenes de papas Canchán** en diversos estados de calidad. Se aplicarán modelos ligeros como YOLO-tiny o MobileNet. | N |
| 30/10   | E | **Comunicaciones:** La conexión entre cámara, sensores y microcontrolador será por **cableado directo**, lo que asegura estabilidad en zonas rurales donde la señal inalámbrica es poco confiable. | MQ |
| 06/11   | E | **Seguridad:** Todos los componentes eléctricos estarán protegidos con aislante termoencogible y cubiertas plásticas, además de un botón de apagado seguro. El diseño cumplirá con normas como **ISO 22000** e **ISO 45001**. | MQ |
| 13/11   | D | **Ergonomía:** El prototipo será ligero y de uso intuitivo, permitiendo que el agricultor coloque y retire las papas fácilmente, evitando esfuerzos innecesarios. | MQ |
| 20/11   | D | **Fabricación:** El diseño debe construirse con **materiales accesibles** (madera o acrílico) y ensamblarse en talleres básicos. Esto permite replicarlo en comunidades agrícolas a bajo costo. | DK |
| 27/11   | E | **Control de calidad:** El sistema debe alcanzar al menos un **80% de precisión** en la clasificación de papas Canchán, garantizando confianza y reduciendo errores en comparación con la clasificación manual. | DK |
| 04/12   | D | **Montaje:** El prototipo será modular y podrá ensamblarse en menos de **2 horas**, facilitando transporte, armado y reparaciones. | JM |
| 04/12   | D | **Transporte:** El prototipo debe ser plegable y mantener un peso ≤ **3 kg**. Esto facilita su traslado entre almacenes o zonas de clasificación. | DK |
| 04/12   | D | **Uso:** El prototipo debe poder operar bajo condiciones reales de postcosecha: polvo, humedad, variaciones de luz, y en zonas andinas entre **2000 y 3500 msnm**. | N |
| 11/12   | D | **Mantenimiento:** El diseño permitirá limpieza rápida y reemplazo de componentes (sensores o cámara) en menos de **5 minutos**, sin necesidad de asistencia técnica especializada. | JM |
| 11/12   | E | **Costos:** El costo total del prototipo debe estar entre **500 y 1000 soles**, incluyendo estructura y electrónica. Esto asegura accesibilidad económica. | DK |
| 11/12   | E | **Plazos:** El proyecto debe estar finalizado antes de la sustentación del **11 de diciembre a las 7:00 a.m.**, garantizando la entrega de un prototipo funcional y listo para evaluación. | N |
