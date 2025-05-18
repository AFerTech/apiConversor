# Conversor de Monedas en Java (API ExchangeRate-API)

Este proyecto es una aplicación Java de consola que permite:

- Muestra todas las monedas disponibles con su código y país
- Convertir una moneda a otra usando una cantidad específica
- Interactuar con la API ExchangeRate-API realizando peticiones GET según lo solicitado por el usaurio en consola
- Muestra los resultados en formato JSON usando la librería Gson

## 📦 Estructura del Proyecto

- Main.java — Interfaz de usuario por consola con opciones para mostrar monedas, convertir moneda y salir de consola
- CurrencyService.java — Lógica de negocio
- ApiClient.java — Cliente HTTP para consumir la API
- ConversionResponse.java — Modelo para conversión de moneda
- ExchangeRateResponse.java — Modelo para lista de monedas
