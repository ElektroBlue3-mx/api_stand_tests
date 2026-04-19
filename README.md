# Pruebas para el parámetro firstName al crear un/a usuario/a en []
- Necesitas tener instalados los paquetes pytest y request para ejecutar las pruebas.
- Ejecuta todas las pruebas con el comando pytest.

Comandos principales de Git:

Verifica en qué rama estás trabajando:
git branch

Si necesitas cambiar de rama:
git checkout nombre-de-la-rama

Agrega los cambios al área de preparación (staging):
git add .
(El punto agrega todos los archivos modificados; también puedes especificar archivos individuales.)

Crea un commit con un mensaje descriptivo:
git commit -m "Mensaje claro sobre los cambios"

Sube la rama al repositorio remoto en GitHub:
git push origin nombre-de-la-rama

Casos comunes

Si es la primera vez que subes esa rama:
git push -u origin nombre-de-la-rama
El -u establece el seguimiento entre tu rama local y la remota, para que después solo uses git push.

Si quieres subir directamente a la rama principal (main/master):
git checkout main
git merge nombre-de-la-rama
git push origin main
