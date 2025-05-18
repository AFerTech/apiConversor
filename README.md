# Conversor de Monedas en Java (API ExchangeRate-API)

Este proyecto es una aplicación Java de consola que permite:

- Mostrar todas las monedas disponibles
- Convertir una moneda a otra usando una cantidad específica
- Interactuar con la API ExchangeRate-API
- Mostrar los resultados en formato JSON usando la librería Gson

## 📦 Estructura del Proyecto

- Main.java — Interfaz de usuario por consola
- CurrencyService.java — Lógica de negocio
- ApiClient.java — Cliente HTTP para consumir la API
- ConversionResponse.java — Modelo para conversión de moneda
- ExchangeRateResponse.java — Modelo para lista de monedas

## ✅ Requisitos

- Java 11 o superior
- Librería Gson (descargar gson-2.8.x.jar y agregar al classpath o usar Maven/Gradle)
- Conexión a Internet
- Clave de API válida de ExchangeRate-API

## 🔧 Instrucciones de Uso

1. 🔐 Reemplaza la constante API_KEY en ApiClient.java con tu clave de API:

```java
public static final String API_KEY = "TU_API_KEY";
