# SantiagoRome.github.io
<link rel='stylesheet' href='/css/github.css'>
<h1>USO DE GIT/GITHUB CON VSCODE</h1>
<h2>VSCODE X GIT</h2>
<p>Primero creamos una carpeta en la que guardaremos los archivos y usamos el comando git init, para
    iniciar git en la carpeta</p>

<img src="/img/crearCarpeta.png">


<p>Tras crear la carpeta, nos iremos a la pestaña de source control y le daremos a la opción de open
    folder y seleccionamos la carpeta que creamos anteriormente</p>

<img src="/img/vscodeSinGitHub.png">


<p>
    Creamos un archivo de prueba como por ejemplo “hola.txt” y escribimos algo en el, tras escribir
cualquier cosa, git lo guardara como un cambio y te mostrara lo que había antes y después de
realizar los cambios
</p>

<img src="/img/commitGit.png">


<p>
    Añadimos el archivo a los cambios que queremos guardar y escribimos un mensaje en el recuadro
encima del botón de commit, tras esto le damos al botón, en caso de no haber escrito un mensaje en
el recuadro, saldrá un archivo en pantalla en el cual podrás escribir el mensaje, es importante
escribir el mensaje ya que si no, no se realizara el commit.
</p>

<img src="/img/mensajeCommit.png">


<p>
    Tambien podemos, modificar el archivo y descartar los cambios, pulsando en el botón al lado
izquierdo del “+”, lo cual eliminara todos los cambios realizados y se quedara con la parte izquierda
de lo enseñado, el archivo antes de ser modificado, esto puede ser muy útil para volver a un estado
anterior a realizar cambios en un fichero y recuperar el archivo en caso de error.
</p>

<img src="/img/descartarCommit.png">

<img src="/img/comparacionVersiones.png">

<h2>
VSCODE X GITHUB
</h2>

<p>
    Para usar GitHub, crearemos un repositorio y le daremos al botón Clone Repository en vez de Open
folder, tras esto saldrá un recuadro que pedira escribir la url del repositorio, en vez de escribir la url,
podrás darle click justo debajo suya y enlazara tu cuenta de github con vscode
</p>

<img src="/img/vscodeConectarGitHub.png">


<p>
    Tras esto nos saldrán todos los repositorios asociados a la cuenta con la que iniciamos sesion, le
damos click, crearemos una carpeta en la que guardar los archivos y se sincronizara y descargara
todos los ficheros del repositorio.
</p>

<img src="/img/vscodeRepositorio.png">

<img src="/img/CarpetaGitHubClonada.png">


<p>
    Para comprobar su funcionamiento modificaremos un archivo cualquiera y procederemos a realizar
los mismos pasos que sin GitHub, escribimos un mensaje y le damos a commit.
</p>

<img src="/img/GithubCambiarArchivo.png">


<p>
    Tras esto saldrá un nuevo botón, esta vez pondrá sincronizar y podremos usarlo para subir los
archivos modificados a GitHub, tras esto saldrá un mensaje abajo a la derecha que nos preguntara si
queremos realizar git fetch periódicamente, le damos a permitir.
</p>

<img src="/img/sincronizar.png">

<img src="/img/gitfetch.png">


<p>
Y con esto VSCODE realizara git fetch periódicamente, descargándose los archivos que no sean
iguales a los de la carpeta local.
</p>
