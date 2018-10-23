# Wallpaper_dinamico

## Dependencias:

- Feh
- Modulos Python os, time, subprocess

## Configuración:

- Búsque en `Cambio_de_wallpapers.py` la línea: `wall = '/home/jorge/Imágenes/Wallpapers/'` y reemplace el `path` por el de su preferencia.
- Si usa xinit para inicio de sesión, sugiero que inicie el script con permisos de ejecución `chmod +x  Cambio_de_wallpapers.py` en el `.xinitrc` en su home, si no... utilice las preferencias de su sistema para inicio de programas con el sistema.
- Puede modificar el retardo de cambio de fondo en la instrucción `time.sleep()` en segundos.