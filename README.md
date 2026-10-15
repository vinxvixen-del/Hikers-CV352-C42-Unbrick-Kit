# 🛠️ Hikers CV352-C42 / CV352-A42 Smart TV Unbrick & Recovery Kit

Kit de rescate, respaldo y unbrick oficial para la tarjeta base **CV352-C42** / **CV352-A42** utilizada en Smart TVs Hikers y otros dispositivos con procesador **HiSilicon Hi3751V352E** (Titan OS / Android TV).

---

## 🔍 Descripción del Problema (Bootloop Fix)
Si tu pantalla Hikers se queda congelada en el logotipo de inicio (bootloop), no pasa del menú de carga o perdiste el lanzador principal del sistema, este kit contiene las particiones limpias y la aplicación de interfaz extraídas directamente mediante acceso Root y depuración ADB desde un equipo funcional para restaurar el sistema.

## 📦 Contenido del Kit de Rescate
* TitanLauncher.apk (~71 MB): Lanzador de aplicaciones original y APK de interfaz de sistema Titan OS.
* boot.img (40 MB): Partición del kernel de arranque para placas CV352.
* recovery.img (40 MB): Partición de recuperación del sistema.

## ⚙️ Especificaciones Técnicas Soportadas
* Modelo de Tarjeta Principal (Mainboard): CV352-C42 / CV352-A42
* SoC / Procesador: HiSilicon Hi3751V352E
* Marca de Pantalla Compatible: Hikers / Pantallas genéricas chasis CV352
* Método de recuperación: ADB Shell / Actualización por USB

---

## 🚀 Instrucciones de Instalación Rápida vía ADB
1. Conecta tu Smart TV a la red local y habilita la conexión de depuración:
   adb connect <IP_DE_LA_TV>

2. Instala el lanzador de respaldo para romper el bucle de arranque:
   adb install -r TitanLauncher.apk

3. Reinicia el dispositivo:
   adb reboot

---

## ☕ Apoyo al Proyecto / Donaciones
Si este kit te ayudó a revivir tu Smart TV y te ahorró el costo de reemplazar la tarjeta lógica, considera dejar una donación voluntaria para apoyar la preservación y el mantenimiento de firmwares libres:

* 💳 PayPal / Donaciones: [https://paypal.me/](https://paypal.me/)
