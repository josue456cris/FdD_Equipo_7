## 📊 Diagrama de flujo — Lógica de la App

                 ┌───────────────────────┐
                 │   PANTALLA PRINCIPAL  │
                 └───────────┬───────────┘
                             │
        ┌────────────────────┼─────────────────────────┐
        │                    │                         │
        ▼                    ▼                         ▼
┌──────────────┐    ┌────────────────┐        ┌──────────────────┐
│  ESCANEAR    │    │   DETENER      │        │   OPCIONES       │
└──────┬───────┘    └──────┬─────────┘        │  AVANZADAS       │
       │                    │                  └─────────┬────────┘
       │                    │                            ▼
       ▼                    ▼                   ┌───────────────────┐
┌──────────────┐    ┌──────────────┐            │  PANTALLA OPCIONES│
│ Enviar URL   │    │ Enviar URL   │            └─────────┬─────────┘
│ /INICIAR     │    │ /PARAR_TODO  │                      │
└──────┬───────┘    └──────┬───────┘                      │
       │                    │                              │
       ▼                    ▼                              │
┌──────────────┐    ┌──────────────┐                      │
│ Mostrar       │    │ Mostrar       │                      │
│ "Escaneando…" │    │ "Proceso      │                      │
│               │    │ detenido"     │                      │
└──────────────┘    └──────────────┘                      │
                                                         │
                   ┌──────────────────────────────────────┘
                   ▼
       ┌────────────────────────────────────────────┐
       │     OPCIONES AVANZADAS (LED / MOTOR / FOTO)│
       └───────────────────────────┬────────────────┘
                                   │
     ┌─────────────────────────────┼──────────────────────────────┐
     │                             │                              │
     ▼                             ▼                              ▼
┌──────────────┐         ┌────────────────┐           ┌───────────────────┐
│ LED ON        │         │  MOTOR ON      │           │   TOMAR FOTO      │
└──────┬────────┘         └──────┬─────────┘           └──────────┬────────┘
       │                          │                                │
       ▼                          ▼                                ▼
┌──────────────┐         ┌──────────────┐                 ┌──────────────┐
│ Retornar     │         │ Retornar     │                 │ Retornar      │
│ "LED_ON"     │         │ "MOTOR_ON"   │                 │ "CAPTURAR"    │
└──────────────┘         └──────────────┘                 └──────────────┘

     ┌─────────────────────────────┼──────────────────────────────┐
     │                             │                              │
     ▼                             ▼                              ▼
┌──────────────┐         ┌────────────────┐            ┌──────────────────┐
│ LED OFF       │         │ MOTOR OFF       │            │   VOLVER         │
└──────┬────────┘         └──────┬──────────┘            └────────┬─────────┘
       │                          │                               │
       ▼                          ▼                               ▼
┌──────────────┐         ┌──────────────┐                ┌──────────────────┐
│ Retornar     │         │ Retornar     │                │ Regresar a       │
│ "LED_OFF"    │         │ "MOTOR_OFF"  │                │ pantalla principal│
└──────────────┘         └──────────────┘                └──────────────────┘

---

## Evidencias del desarrollo de la aplicación

A continuación, se muestran las pantallas y bloques de programación utilizados para el funcionamiento de la app **Kartoffelmachine**, desarrollada en MIT App Inventor. Estas imágenes permiten visualizar tanto la interfaz de usuario como la lógica interna que controla el LED, el motor y la captura de fotografías.

---

### Pantalla Principal
#### `Principal.jpeg`
![Principal](Principal.jpeg)

Esta es la pantalla principal de la aplicación.  
Desde aquí el usuario puede:

- Iniciar el proceso de escaneo automático.  
- Detener el proceso actual.  
- Acceder a las opciones avanzadas donde se controlan el LED, el motor y la captura.  

Su diseño es simple y accesible, pensado para facilitar la interacción en campo.

---

### Código de la Pantalla Principal
#### `Principal Codigo.png`
![Principal Codigo](Principal Codigo.png)

Este bloque de código contiene:

- El envío de comandos a la ESP32-CAM mediante URLs.  
- La recepción de respuestas desde el servidor de la cámara.  
- La lógica que interpreta los resultados devueltos desde la pantalla de Opciones Avanzadas.  

Aquí se gestionan las acciones **INICIAR**, **DETENER**, **LED**, **MOTOR** y **FOTO**.

---

### Pantalla de Opciones Avanzadas
#### `Opciones Avanzadas.jpeg`
![Opciones Avanzadas](Opciones Avanzadas.jpeg)

Esta pantalla permite controlar manualmente:

- Encendido y apagado del **LED**.  
- Activación y desactivación del **motor**.  
- Toma de fotografía mediante la cámara.  
- Regresar a la pantalla principal.  

Cada botón envía un comando específico a la lógica del programa.

---

### Código de Opciones Avanzadas
#### `Opciones Avanzadas Codigo.png`
![Opciones Avanzadas Codigo](Opciones Avanzadas Codigo.png)

Aquí se puede ver:

- El bloque que cierra la pantalla y retorna el comando seleccionado.  
- La estructura que envía mensajes como `"LED_ON"`, `"MOTOR_OFF"` o `"CAPTURAR"`.  
- Esta lógica permite que la pantalla principal reciba el comando y ejecute la acción correspondiente.

Este módulo es clave para el funcionamiento manual del sistema.

---

