Comandos :

-> Compilar : 
tsc
-> Asignar Variables para test : 

$env:INPUT_UrlChecked=''
$env:INPUT_ApiToken=''
$env:INPUT_Nombre=''
$env:INPUT_IdStatusPage=''


-> Ejecutar : 

node index.js

-> publicacion (generar el archivo para publicar)

tfx extension create --manifest-globs vss-extension.json