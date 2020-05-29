#Scrip elavorado para realizar el respaldo del servicio rsylog y archivos de configuracion.

#Instrucciones..
Descarga el repositorio y ejecuta el scrip con permisos de root.

#Pasos a seguir.
1.- git clone https://github.com/juanpageek90/respaldo_syslog.git
2.- cd respaldo_syslog/
3.- chmod +x respaldo_syslog.sh
4.- ./respaldo_syslog

#Funcionalidades.
Paso 1.- El scrip realiza el respaldo de la db correspondiente.
Paso 2.- El scrip realiza el respaldo de los archivos de configuracion de rsyslog (Archivos de configuracion y panel de administracion web)
Paso 3.- El scrip mueve los archivos de configuracion y la db a una carpeta con la fecha actual y posteriormente pasa a comprimirla para una mayor administracion. 
Paso 4.- El scrip envia el respaldo a un servidor remoto por medio de ftp o scp. (Falta por definir)
