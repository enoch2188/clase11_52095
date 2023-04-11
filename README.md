Primero debemos descargar git para luego instalarlo en nuestra pc.
recordar tildas la opcion de :"git bash here" y seleccionar la opcion de use cisual stufio as a git degault editor.
Podemos abrir el git bash o una consola o una terminal desde vs.
para abrir la termina desde vsc tenemos que abrir el root en el IDE, luego tocamos sobre el boton "terminal" y luego tocamos sobre el select que esta al lado del "+" y seleccionamos la opcion "git bash". Al tocarlo, se nos abre el bash en la terminal.
Paso seguido necesitamos configurar nuestro usuario por unica vez con los siguientes comandos:
got config --global user.name "nombreUsuario"
git config --global user.mail emailsuyo@gmail.com
Luego de esto podemos corroborar si la configuracion quedo impactada con los siguientes comandos:
git config user.name
git config user.email
------------------------------
Luego de tener todo configurado e instalado necesito pararme sobre mi root y decirle: "che root, vamos a trabajar con git" (Como hago esto?)
Para hacer esto necesitamos estar posicionado sobre mi root y usar el comando (por primera y unica vez):
git init
Luego de ejecutar el git init ya estamos parados sobre el estado"working directory" que es donde generamos todas las lineas de codigo
Cuando completo mi tarea, paso todo lo trabajado del "working directory" -> "staging area" Como hago esto? Para hacerlo necesitamos el comando: 
git add . (comando por lote)
git add nombreArchivo (manual archivo o directorio)
Luego de pasar todo el "STAGING AREA" instantaneamente pasamos todo el "repository" con el comando:
git commit -m "comentario breve y descriptivo de lo que se estuvo trabajando"
Al terminar de commitear, se nos genera una version nueva y nos posiciona en el "working directory" automaticamente.
Como controlo los estados de mis archivos/directorios? con el siguiente comando:
git status
git log --oneline: para ver los commit
git log : para ver directamente a que hora lo hizo y quien lo hizo