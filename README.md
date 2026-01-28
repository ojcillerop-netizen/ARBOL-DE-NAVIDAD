# ARBOL-DE-NAVIDAD
Diseño de un arbol de navidad, mediante un sensor de movimiento activaremos unas luces led y sonara el conocido villancinco "Jingle Bells" durante quince segundos.
# 🎄 Árbol de Navidad Interactivo con ESP32

Este proyecto consiste en un árbol navideño inteligente que utiliza un sensor de movimiento para activar una secuencia de luces y música.

## 🚀 Funcionalidades
* **Detección de presencia:** Activación automática mediante sensor PIR HC-SR501.
* **Música dinámica:** Reproducción de *Jingle Bells* durante 15 segundos.
* **Espectáculo de luces:** 6 LEDs sincronizados que parpadean al ritmo de la música.
* **Cerebro:** Basado en el potente microcontrolador **ESP32-WROOM-32D**.

## 🛠️ Componentes
* ESP32 DevKit V1 / NodeMCU-32S
* Sensor PIR HC-SR501
* 6 LEDs (Rojos y Verdes) + Resistencias 330Ω
* Buzzer Pasivo
* Carcasa diseñada e impresa en 3D

## 🔧 Configuración y Montaje
1. Conectar los componentes según el diagrama de pines (ver código).
2. Instalar el soporte de ESP32 en el IDE de Arduino.
3. Cargar el código proporcionado en la carpeta `/src`.
4. Calibrar la sensibilidad del sensor PIR mediante los potenciómetros físicos.

## 📜 Licencia
Este proyecto es de código abierto bajo la licencia MIT.
