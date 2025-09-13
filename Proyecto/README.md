# 📖 Justificación del Proyecto – Kartoffelmachine  

## Justificación de la problemática  
En el Perú, la papa es un alimento estratégico para la seguridad alimentaria y económica de miles de familias agricultoras. Sin embargo, una parte significativa de la producción se pierde en la etapa poscosecha debido a factores como: exposición excesiva a la luz (que produce papas verdes con solanina no aptas para consumo), almacenamiento inadecuado y clasificación manual poco precisa.  

Estudios sobre las causas de una mala cosecha muestran que problemas como **material de siembra de baja calidad, ausencia de rotación de cultivos, suelos empobrecidos, métodos de siembra inadecuados y cambios climáticos** afectan directamente la productividad y la calidad de la papa [2]. Estas condiciones, sumadas a la falta de monitoreo oportuno, generan pérdidas económicas, desperdicio de alimentos y limitan la competitividad de los agricultores.  

---

## Justificación del ODS 12  
El proyecto se fundamenta principalmente en el **ODS 12: Garantizar modalidades de consumo y producción sostenibles**, que busca reducir a la mitad el desperdicio de alimentos y fomentar sistemas más eficientes [1].  

Implementar un prototipo como **Kartoffelmachine** permite:  
- Reducir las pérdidas poscosecha al clasificar las papas de manera rápida y objetiva.  
- Prevenir el desperdicio de alimentos, que a nivel mundial alcanza 931 millones de toneladas al año [1].  
- Promover el uso de **tecnología asequible y sostenible** en comunidades rurales, mejorando la trazabilidad y calidad de los productos.  

Este enfoque responde directamente a la meta **12.3 del ODS 12**, que plantea disminuir el desperdicio mundial de alimentos en toda la cadena de suministro.  

---

## Justificación técnica  
El sistema propuesto combina **sensores de color (TCS34725), LDR y DHT11/DHT22**, junto con algoritmos básicos de machine learning para clasificar las papas según **variedad, color, tamaño y condiciones ambientales**.  

Además, se integra una **cámara (ESP32-CAM)** que captura imágenes de los tubérculos, permitiendo aplicar técnicas de **machine learning y visión por computadora**. De este modo, se pueden reconocer defectos visibles, diferencias de tamaño y síntomas tempranos de enfermedades, mejorando la precisión de la clasificación respecto a métodos puramente manuales o tradicionales.  

Este monitoreo en tiempo real permitirá a los productores:  
- Identificar papas verdes o con defectos antes de su distribución.  
- Controlar variables críticas como luz, temperatura y humedad en el almacenamiento.  
- Generar un **dataset visual de papas locales** que puede usarse para entrenar modelos de clasificación más robustos.  
- Optimizar la toma de decisiones en el manejo de la producción.  

---

## 📚 Bibliografía  
[1] Naciones Unidas. Objetivo 12: Garantizar modalidades de consumo y producción sostenibles. ONU. Disponible en: https://www.un.org/sustainabledevelopment/es/sustainable-consumption-production/

[2] Tomathouse. Mala cosecha de papa: causas y soluciones. Disponible en: https://ese.tomathouse.com/ploxoj-urozhaj-kartofelya-prichiny-i-resheniya/  
