# Android Sensor and Location Tracker

> **Language**: [🇪🇸 Español](README.es.md) | 🇺🇸 English

![Application Demo](image.png)

## Overview

This Android application is designed to collect and store data from multiple device sensors including accelerometer, gyroscope, gravity sensor, and magnetic field sensor. Additionally, it tracks the device's real-time location using GPS. All collected data is stored in files on the device for subsequent analysis.

This research project was conducted with the support of **[Operadora Distrital de Transporte - La Rolita](https://www.odt.gov.co)**, the District Transport Operator of Bogotá, Colombia. La Rolita provided access to their bus fleet, allowing the installation of data collection devices on their vehicles for a two-month period to gather real-world transportation data.

## Features

- **Multi-sensor data collection**: Accelerometer, gyroscope, gravity sensor, and magnetic field
- **Real-time GPS location tracking** with continuous updates
- **Persistent data storage** in local files for later analysis
- **Background service** using foreground service to ensure continuous data collection
- **Android sensor fusion** for accurate motion detection

## Collaboration

<table>
  <tr>
    <td align="center">
      <strong>Partner Organization</strong><br>
      <a href="https://www.odt.gov.co" target="_blank">
        <strong>Operadora Distrital de Transporte (ODT)</strong>
      </a><br>
      <em>La Rolita - Bogotá's District Transport Operator</em><br>
      <br>
      La Rolita supported this research project by providing access to their bus fleet.<br>
      Devices running this application were installed on their buses for a two-month period,<br>
      enabling the collection of real-world transportation data to analyze vehicle dynamics,<br>
      route patterns, and improve transportation efficiency and safety in Bogotá.
    </td>
  </tr>
</table>

## Requirements

- **Android 6.0 (API level 23) or higher**
- **Permissions**: Location and device storage access
- **Device with GPS** and motion sensors (accelerometer, gyroscope)
- **Google Play Services** (for location services)

## Usage

1. **Launch the application** on your Android device
2. **Grant permissions** for location and storage access
3. **Start data collection** - the app will begin tracking sensors and GPS
4. **Data is automatically saved** to device storage
5. **Export data files** for analysis when needed

## Data Collection

The application collects the following data types:

### Sensor Data
- **Accelerometer**: Linear acceleration (m/s²)
- **Gyroscope**: Rotational velocity (rad/s)
- **Gravity Sensor**: Gravity force (m/s²)
- **Magnetic Field**: Magnetic field strength (μT)

### Location Data
- **Latitude & Longitude**: GPS coordinates
- **Altitude**: Height above sea level (meters)
- **Speed**: Current movement speed (m/s)
- **Accuracy**: GPS accuracy (meters)
- **Timestamp**: Time of data collection

## Research Context

This application was developed as part of a thesis research project. With the support of La Rolita (Bogotá's District Transport Operator), devices running this application were installed on public buses for two months to collect real-world data. The collected data was used to analyze:

- Vehicle movement patterns and dynamics
- Route characteristics and road conditions
- Acceleration and braking patterns
- GPS tracking accuracy in urban environments
- Transportation safety improvements
- Real-world sensor behavior in public transport vehicles

## Original Repository

This project is based on the original research repository:

**🔗 Original Source**: [https://github.com/CoKeFish/android-sensor-data-logger.git](https://github.com/CoKeFish/android-sensor-data-logger.git)

---

<div align="center">
  <p><strong>Research supported by</strong></p>
  <p><a href="https://www.odt.gov.co"><strong>Operadora Distrital de Transporte - La Rolita</strong></a></p>
  <p><em>Bogotá, Colombia</em></p>
</div>
