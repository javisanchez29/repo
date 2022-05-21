# repo

1. ¿Cómo ve los archivos cambiados dentro de cada confirmación del registro de git?
R/ para mostrar registros de confirmacion se utiliza el comando git log --raw.

2. ¿Cómo ve el contenido de lo que cambió dentro de cada archivo del registro de git?
R/ el comando git log --follow -p para ver el historial de archivos completo.
Y para un solo archivo git log --[nombre archivo].

3. ¿A qué se refiere HEAD en el contexto de git? (No debe confundirse con el "HEAD<<<<" que se observa dentro del conflicto de fusión)
R/se refiere en el que se a posicionadp el repositorio en la actualidad sin importar la rama.
