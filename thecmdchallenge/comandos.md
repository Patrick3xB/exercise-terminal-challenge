# Comandos usados en el Terminal Challenge

Este archivo contiene un resumen de los comandos que utilicé durante el reto de la terminal para practicar el uso basico de la linea de comandos (bash) en GitHub Codespaces.



- Navegacion entre carpetas

bash
pwd                                 # Mostrar la ruta donde estoy
ls                                  # Ver los archivos y carpetas
cd direccion o nombre carpeta       # Entrar en una carpeta
cd ..                               # Salir de la carpeta (ir hacia atrás)




-Archivos y carpetas

bash
mkdir nombre             # Crear una carpeta nueva
touch archivo.txt        # Crear un archivo nuevo
cat archivo.txt          # Ver lo que hay dentro de un archivo
rm archivo.txt           # Borrar un archivo
rm -r carpeta            # Borrar una carpeta con todo dentro




-Mover y copiar archivos

bash
mv archivo.txt otra-carpeta/          # Mover archivo a otra carpeta
cp archivo.txt copia.txt              # Copiar un archivo con otro nombre
cp archivo.txt otra-carpeta/copia.txt # Copiar archivo a otra carpeta




-Buscar archivos

bash
find . -name "nombre.txt"      # Buscar un archivo por nombre exacto
find . -iname "*parte*"        # Buscar aunque no sepas el nombre completo




- Editar archivos con `vi`

bash
vi archivo.txt   # Abrir archivo con vi (cuidado, me comi un loop y me costo entender como funcionar vi)
# Dentro de vi:
i                # Empiezo a escribir
(Esc)            # Salgo de escribir
:wq              # Guardo y salgo
:qa!             # Salgo sin guardar si algo falla




- Git

bash
git status             # Ver cambios
git add .              # Añadir todos los cambios
git commit -m "mensaje" # Guardar los cambios con un mensaje
git push origin master # Subir todo a GitHub




Repositorio final:  
🔗 https://github.com/Patrick3xB/exercise-terminal-challenge

Ejecutado en Codespaces, reto completado con éxito.
