# 🛠️ Firmware para TV Hikers Smart Android (CV352-C42 / CV352-A42) - Unbrick & Recovery Kit

Kit de rescate, respaldo y unbrick oficial de firmware para Smart TV **Hikers Smart Android** y otras pantallas compatibles con la tarjeta base / chasis **CV352-C42** / **CV352-A42** y procesador **HiSilicon Hi3751V352E** (Titan OS / Android TV).

---

## 🔍 Descripción del Problema y Solución (Bootloop Fix)
Si tu televisor Hikers Smart Android se queda congelado en el logotipo de inicio (bootloop), no pasa de la pantalla de carga o perdió el lanzador principal del sistema, este kit incluye el firmware limpio de rescate, las particiones de arranque (`boot.img`, `recovery.img`) y la interfaz original (`TitanLauncher.apk`) extraídas de un equipo funcional mediante ADB/Root.

## 📦 Contenido del Kit de Rescate
* **TitanLauncher.apk** (~71 MB): Lanzador original y APK de interfaz de usuario de Titan OS / Android TV.
* **boot.img** (40 MB): Partición del kernel de arranque del firmware para placas CV352-C42 / CV352-A42.
* **recovery.img** (40 MB): Partición de recuperación del sistema.

## ⚙️ Especificaciones Técnicas Soportadas
* **Producto / Dispositivo:** Smart TV Hikers Smart Android
* **Tarjeta Principal (Mainboard):** CV352-C42 / CV352-A42
* **Procesador / SoC:** HiSilicon Hi3751V352E
* **Método de recuperación:** ADB Shell / Actualización e instalación por USB

---

## 🚀 Instrucciones Rápidas de Instalación vía ADB
1. Conecta la Smart TV a la red local e inicia sesión de depuración:
   adb connect <IP_DE_LA_TV>

2. Instala el lanzador de respaldo para romper el bucle de arranque:
   adb install -r TitanLauncher.apk

3. Reinicia el dispositivo:
   adb reboot

---

## ☕ Apoyo al Proyecto / Donaciones Voluntarias
Si este kit de firmware te ayudó a revivir tu Smart TV y te ahorró el costo de reemplazo de tarjeta, considera dejar una contribución voluntaria para el mantenimiento de firmwares y herramientas libres:

* 🌍 **PayPal (Internacional / Tarjeta):** [https://paypal.me/VicenteCastillo885](https://paypal.me/VicenteCastillo885)
* 🇲🇽 **Mercado Pago / Transferencia SPEI (México):** Puedes solicitar los datos directos o realizar transferencia directa a nuestra cuenta de respaldo.
