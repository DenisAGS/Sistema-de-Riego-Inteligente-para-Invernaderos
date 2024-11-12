# 🌱 Sistema de Riego Inteligente para Invernaderos 💧

## 📝 Descripción
El Sistema de Riego Inteligente para Invernaderos está diseñado para optimizar el uso del agua y mejorar las condiciones de cultivo dentro de un invernadero. Este proyecto tiene como objetivo crear una interfaz web que permita a los usuarios monitorear y controlar el riego, la temperatura, la humedad, y otros factores clave que influyen en el crecimiento de los cultivos.

## 🌟 Características Principales
* __📡 Conexión MQTT:__ Permite la comunicación en tiempo real entre el sistema y los sensores a través del protocolo MQTT.
* __🌍 Diseño responsivo:__ Adaptado para ser visualizado en distintos dispositivos (PC, tablets, móviles).
* __🌱 Gestión de cultivos:__ Selección del tipo de cultivo (Tomate, Pepino, Pimiento, Cannabis) para optimizar los parámetros del riego.
* __📊 Panel de monitoreo:__ Muestra datos en tiempo real como:
  * 🌡️ __Temperatura:__ Monitoreo de la temperatura actual en grados Celsius.
  * 💧 __Humedad:__ Nivel de humedad del ambiente dentro del invernadero.
  * ☀️ __Tiempo de exposición al sol:__ Tiempo que las plantas han estado expuestas a la luz solar.
  * 🌬️ __Niveles de CO2:__ Concentración de dióxido de carbono.
* Botones interactivos:
  * Encender y Apagar el sistema de riego.
  * Aumentar niveles de CO2 para mejorar el crecimiento de las plantas.
  * Cerrar el sistema en caso de condiciones desfavorables.
* __⏰ Historial:__ Botón para mostrar el historial de lecturas (en desarrollo).

## 🔧 Qué construí

El sistema actual está compuesto por los siguientes elementos:

* Interfaz Web: <br>
Basado en HTML5, CSS3 (incluyendo Bulma para un diseño moderno) y JavaScript.
La interfaz incluye botones para controlar el sistema y visualizar métricas relevantes.
Imágenes representativas (granja-inteligente.png, planta.png) para un diseño visual más atractivo.

* Conexión con MQTT:<br>
Utiliza la librería mqtt para conectar y suscribirse a un broker MQTT, permitiendo recibir datos en tiempo real.
Escucha el tema (topic) # para recibir mensajes de cualquier sensor conectado.

## 💻 Tecnologías utilizadas
* __HTML5 y CSS3:__ Estructura y estilos de la página.
* __JavaScript:__ Lógica de interacción con el usuario y conexión con el backend.
* __Bulma CSS Framework:__ Para un diseño moderno y responsivo.
* __Node.js y MQTT:__ Comunicación en tiempo real con sensores a través del protocolo MQTT.
