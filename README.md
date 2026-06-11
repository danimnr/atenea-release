<div align="center">
  <img src="icon.png" width="128" alt="Atenea">
  
  # Atenea
  
  **Tu tiempo, bajo control**
  
  Calendario personal de tareas para escritorio Linux. Completamente local, sin cuentas, sin internet, sin telemetría.
  
  ![Debian](https://img.shields.io/badge/Debian-12+-red?style=flat-square&logo=debian)
  ![GNOME](https://img.shields.io/badge/GNOME-compatible-blue?style=flat-square&logo=gnome)
  ![License](https://img.shields.io/badge/License-GPL--3.0-purple?style=flat-square)
  ![Open Source](https://img.shields.io/badge/Código-Abierto-green?style=flat-square)

</div>

## Características

- 📆 Calendario mensual visual
- ✅ Crear, editar y eliminar tareas
- ⏰ Hora y prioridad por tarea
- 📋 Próximas tareas y pendientes anteriores
- 🎨 Color de acento personalizable
- ✦ Efecto cristal opcional
- ⌨ Atajos de teclado
- 📥 Importar/exportar calendarios (.ics)
- 🔒 100% local — tus datos no salen de tu ordenador
- 🌙 Tema claro y oscuro

## Instalación

Descarga el archivo `.deb` desde [Releases](https://github.com/danimnr/atenea-release/releases) y ejecuta:

```bash
cd ~/Descargas
sudo apt install ./atenea_1.0.6_amd64.deb
```

## Requisitos

- Debian 12 / Ubuntu 22.04 o posterior
- Escritorio GNOME

## Desinstalar

```bash
sudo apt remove atenea
```

Para eliminar también todos los datos:

```bash
rm -rf ~/.local/share/atenea ~/.config/atenea ~/.cache/atenea
```

## Privacidad y datos

Atenea **no se conecta a internet**, no crea cuentas y no envía ningún dato a ningún servidor.

Todos los datos se almacenan localmente en tu ordenador:

| Tipo | Ruta |
|------|------|
| Base de datos (tareas) | `~/.local/share/atenea/atenea.db` |
| Configuración | `~/.config/atenea/settings.json` |
| Logs | `~/.cache/atenea/atenea.log` |

La base de datos es un archivo SQLite estándar que puedes abrir, inspeccionar o eliminar en cualquier momento.

## Verificación de integridad

Para verificar que el archivo descargado no ha sido modificado:

```bash
sha256sum atenea_1.0.6_amd64.deb
```

El hash SHA-256 oficial de `v1.0.6` es:
dc5fd064502c9ced9ac44c6c7b1a1c578e61ea3eb6c841a654de406cc8ce548a

## Código fuente

El código fuente completo está disponible en:
**https://github.com/danimnr/atenea**

## Autor

Desarrollado por **danidev_mnr**
- GitHub: [github.com/danimnr](https://github.com/danimnr)
- ☕ [Ko-fi](https://ko-fi.com/danidev_mnr)
