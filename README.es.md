# Android Sensor and Location Tracker

> **Idioma**: 🇪🇸 Español | [🇺🇸 English](README.md)

![Demostración de la Aplicación](image.png)

## Descripción General

Esta aplicación de Android está diseñada para recopilar y almacenar datos de múltiples sensores del dispositivo, incluyendo acelerómetro, giroscopio, sensor de gravedad y sensor de campo magnético. Además, rastrea la ubicación del dispositivo en tiempo real utilizando GPS. Todos los datos recopilados se almacenan en archivos en el dispositivo para su posterior análisis.

Este proyecto de investigación fue realizado con el apoyo de la **[Operadora Distrital de Transporte - La Rolita](https://www.odt.gov.co)**, el operador de transporte distrital de Bogotá, Colombia. La Rolita facilitó el acceso a su flota de buses, permitiendo la instalación de dispositivos de recolección de datos en sus vehículos durante un período de dos meses para obtener datos reales de transporte.

## Características

- **Recopilación de datos multi-sensor**: Acelerómetro, giroscopio, sensor de gravedad y campo magnético
- **Rastreo de ubicación GPS en tiempo real** con actualizaciones continuas
- **Almacenamiento persistente de datos** en archivos locales para análisis posterior
- **Servicio en segundo plano** utilizando servicio en primer plano para asegurar la recopilación continua de datos
- **Fusión de sensores Android** para detección precisa de movimiento

## Colaboración

<table>
  <tr>
    <td align="center">
      <strong>Organización Asociada</strong><br>
      <a href="https://www.odt.gov.co" target="_blank">
        <strong>Operadora Distrital de Transporte (ODT)</strong>
      </a><br>
      <em>La Rolita - Operadora de Transporte Distrital de Bogotá</em><br>
      <br>
      La Rolita apoyó este proyecto de investigación proporcionando acceso a su flota de buses.<br>
      Los dispositivos con esta aplicación fueron instalados en sus buses durante dos meses,<br>
      permitiendo la recopilación de datos reales de transporte para analizar la dinámica vehicular,<br>
      patrones de rutas y mejorar la eficiencia y seguridad del transporte en Bogotá.
    </td>
  </tr>
</table>

## Requisitos

- **Android 6.0 (API nivel 23) o superior**
- **Permisos**: Acceso a ubicación y almacenamiento del dispositivo
- **Dispositivo con GPS** y sensores de movimiento (acelerómetro, giroscopio)
- **Google Play Services** (para servicios de ubicación)

## Tecnologías Utilizadas

- **Kotlin** - Lenguaje de programación principal
- **Android Location Services** - Rastreo GPS
- **Android Sensor Framework** - Recopilación de datos de sensores de movimiento
- **Foreground Service** - Recopilación de datos en segundo plano
- **File I/O** - Persistencia de datos

## Uso

1. **Iniciar la aplicación** en tu dispositivo Android
2. **Conceder permisos** para acceso a ubicación y almacenamiento
3. **Iniciar recopilación de datos** - la app comenzará a rastrear sensores y GPS
4. **Los datos se guardan automáticamente** en el almacenamiento del dispositivo
5. **Exportar archivos de datos** para análisis cuando sea necesario

## Recopilación de Datos

La aplicación recopila los siguientes tipos de datos:

### Datos de Sensores
- **Acelerómetro**: Aceleración lineal (m/s²)
- **Giroscopio**: Velocidad rotacional (rad/s)
- **Sensor de Gravedad**: Fuerza de gravedad (m/s²)
- **Campo Magnético**: Intensidad del campo magnético (μT)

### Datos de Ubicación
- **Latitud y Longitud**: Coordenadas GPS
- **Altitud**: Altura sobre el nivel del mar (metros)
- **Velocidad**: Velocidad de movimiento actual (m/s)
- **Precisión**: Precisión del GPS (metros)
- **Marca de tiempo**: Hora de recopilación de datos

## Contexto de Investigación

Esta aplicación fue desarrollada como parte de un proyecto de investigación de tesis. Con el apoyo de La Rolita (Operadora Distrital de Transporte de Bogotá), se instalaron dispositivos con esta aplicación en buses públicos durante dos meses para recopilar datos del mundo real. Los datos recopilados se utilizaron para analizar:

- Patrones de movimiento vehicular y dinámicas
- Características de las rutas y condiciones viales
- Patrones de aceleración y frenado
- Precisión del rastreo GPS en entornos urbanos
- Mejoras en seguridad del transporte
- Comportamiento real de sensores en vehículos de transporte público

## Repositorio Original

Este proyecto está basado en el repositorio de investigación original:

**🔗 Fuente Original**: [https://github.com/CoKeFish/android-sensor-data-logger.git](https://github.com/CoKeFish/android-sensor-data-logger.git)

---

<div align="center">
  <p><strong>Investigación apoyada por</strong></p>
  <p><a href="https://www.odt.gov.co"><strong>Operadora Distrital de Transporte - La Rolita</strong></a></p>
  <p><em>Bogotá, Colombia</em></p>
</div>
