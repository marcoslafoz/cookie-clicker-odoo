# Cookie clicker

Cookie clicker es un juego incremental basado en crear galletas.
Inicialmente, el usuario hace clic en una galleta grande en la pantalla y
gana una sola galleta por clic. Luego pueden gastar las galletas obtenidas
en la compra de activos como "cursores" y otros "edificios" que producen
galletas automáticamente. 

## Instalacion

## Uso
Esta maquina virtual ya esta preparada para desarrollo. Levanta odoo usando docker compose.
Para ello, abre una terminal y usa:
```bash
cd /home/me/odoo
docker-compose up
```
Accede en chrome a http://localhost:8069/ para usar odoo.
Abre pycharm (si no esta ya abierto) y haz un cambio. Este sera reflejado automaticamente dado que el modo desarrollador ya esta habilitado.
Si algun cambio no aparece, puedes forzar el refresco de la cache, clickando la extension "Clear cache" ya añadida a chrome.

Git mostrara los cambios de cada fichero en la pestaña "Local changes"
para simplificar el desarollo.
Realiza cambios pequeños y cuando este seguro de que funcionan haz un commit
para guardar el estado. Puedes volver a un estado anterior 
haciendo un rollback de codigo recientemente cambiado (no commit aun)
o un checkout de un commit anterior. Puedes buscar algun tutorial breve
de git para ayudarte. En la pestaña de log tienes los commit anteriores.

Puedes empezar con el clicker_systray_item

Happy codding!