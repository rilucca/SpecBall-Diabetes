# 🩸 SpecBall-Diabetes (Beta)

Este proyecto transforma la **SpecBall S2 (ESP32-S3)** en un monitor dedicado de glucosa en tiempo real. 
Basado en el hardware de **Xiaozhi/RealDeco**, pero optimizado exclusivamente para **T1D (Diabetes Tipo 1)**.

### 🚀 Funcionalidades (En desarrollo)
- **Monitoreo Directo:** Conexión a Nightscout (SGV, IOB, COB).
- **Interfaz Circular:** Visualización en pantalla GC9A01 con arcos de color.
- **Alertas Sonoras:** Alarma por I2S (Speaker) configurables para bajas/altas.
- **LED Status:** Anillo LED para alertas visuales inmediatas.

### 🛠️ Configuración actual
- **Hardware:** ESP32-S3-2.1 (Spotpear/SpecDevice).
- **Firmware:** ESPHome + Custom C++ Component (`nightscout.h`).

### 📂 Estructura
- `xiaozhi.yaml`: Configuración de hardware (Speaker, Display, LED).
- `nightscout.h`: Lógica de conexión y parsing de datos CGM.

# ota_password: "YOUR_OTA_PASSWORD_HERE"
