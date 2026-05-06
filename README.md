# 🚀 Prototipo de Cohete Experimental
## 📌 Descripción

Este proyecto consiste en el desarrollo de un prototipo de cohete diseñado para alcanzar la mayor altitud posible, mientras recopila datos en tiempo real sobre condiciones ambientales, posición y orientación.

El sistema incluye un mecanismo autónomo de recuperación que despliega un paracaídas al detectar la fase de descenso, con el objetivo de preservar la integridad del dispositivo y permitir la recuperación de los datos recolectados.

## 🎯 Objetivos
Alcanzar la mayor altitud posible de forma segura
Medir variables ambientales durante el vuelo:
  Temperatura
  Presión
  Humedad
Determinar:
  Posición (GPS)
  Orientación (IMU: acelerómetro + giroscopio)
Detectar el punto de apogeo (altura máxima)
Activar automáticamente un sistema de paracaídas durante el descenso
Recuperar el prototipo y analizar los datos obtenidos

## ⚙️ Características del Sistema
📡 Telemetría en tiempo real (opcional)
💾 Registro de datos en memoria local (SD)
🧭 Sensores de orientación (IMU)
🌡️ Sensores ambientales
📍 Módulo GPS
🪂 Sistema de despliegue de paracaídas
🔋 Alimentación autónoma

## 🧠 Lógica de Funcionamiento
Lanzamiento
  El cohete despega y comienza la recolección de datos.
Ascenso
Se registran continuamente:
  Altitud (por presión o GPS)
  Orientación
  Variables ambientales
Detección de Apogeo
Se identifica cuando la altitud deja de aumentar.
Descenso
Al detectar caída:
  Se activa el mecanismo de liberación del paracaídas
Aterrizaje y Recuperación
  Se detiene el registro
    Se recupera el módulo
    Se analizan los datos
