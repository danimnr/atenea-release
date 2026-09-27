<div align="center">
  <img src="icon.png" width="128" alt="Atenea">

  # Atenea

  **Tu tiempo, bajo control**

  Calendario y gestor de tareas personal para Windows, Linux y Android. Local por defecto, con sincronización opcional con tu cuenta de Google.

  ![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-blue?style=flat-square&logo=windows)
  ![Linux](https://img.shields.io/badge/Linux-deb%20%7C%20rpm%20%7C%20AppImage-orange?style=flat-square&logo=linux)
  ![Android](https://img.shields.io/badge/Android-Google%20Play-green?style=flat-square&logo=android)

</div>

## Descargar

👉 **[Última versión](https://github.com/danimnr/atenea-release/releases/latest)** · también desde **[atenea.sbs](https://atenea.sbs)**

| Sistema | Archivo |
|---|---|
| Windows 10/11 (64 bits) | `Atenea_x.y.z_x64-setup.exe` |
| Debian, Ubuntu, Linux Mint… | `Atenea_x.y.z_amd64.deb` |
| Fedora, openSUSE… | `Atenea-x.y.z-1.x86_64.rpm` |
| Cualquier distribución Linux | `Atenea_x.y.z_amd64.AppImage` |
| Android | [Google Play](https://play.google.com/store/apps/details?id=com.danidev.atenea_mobile) |

## Características

- 🗓️ Vistas Día, Semana, Mes y Año (estilo Google Calendar), además de la vista clásica
- ✅ Tareas con hora de inicio y de fin, prioridad y descripción
- ☁️ Sincronización con tu cuenta de Google entre escritorio, web y móvil — o uso 100 % local sin cuenta
- 📥 Importar y exportar calendarios `.ics`
- 🎨 Tema claro, oscuro o del sistema y colores personalizables
- ⌨️ Atajos de teclado

## Instalación

**Windows:** ejecuta el instalador. Si aparece *"Windows protegió su PC"*, pulsa **Más información → Ejecutar de todas formas** (el instalador aún no está firmado con un certificado de pago).

**Linux (.deb):**
```bash
sudo apt install ./Atenea_x.y.z_amd64.deb
```
Requisitos: Debian 12, Ubuntu 22.04, Linux Mint 21 o posteriores.

**Linux (.AppImage):** `chmod +x Atenea_x.y.z_amd64.AppImage` y ábrelo.

## Verificación de integridad

Cada release incluye la huella SHA-256 de sus archivos en las notas. Para comprobar una descarga:

```bash
sha256sum Atenea_x.y.z_amd64.deb      # Linux
Get-FileHash .\Atenea_x.y.z_x64-setup.exe   # Windows (PowerShell)
```

## Versión antigua para GNOME

La versión para escritorio GNOME (Python + GTK4, hasta la 1.0.6) queda retirada y sin soporte: la nueva versión de Linux la sustituye y, al instalar su `.deb`, se actualiza encima.

## Autor

Desarrollado por **danidev_mnr** (D.A.S. Interactive Software)
- GitHub: [github.com/danimnr](https://github.com/danimnr)
- ☕ [Ko-fi](https://ko-fi.com/danidev_mnr)
