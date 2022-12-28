# NodeRed-Dashboard-y-MQTT
Instalación de nodos, instalación de nodos Mosquitto 

## Instalar Node.js

Node Red es un servidor programado en javascript por lo que sigue el formato de JSON, ocupamos  instalar Node.js en la maquina virtual siguiendo las instrucciones a continuación:
 
+ Instalar el instalador **curl**

        sudo apt install curl

![Imagen repositorio nodesource]()
+ Ingresar al repositorio de nodesource/distributions(https://github.com/nodesource/distributions/blob/master/README.md).
+ Seguir la ruta: Debian and Ubuntu based distributions (deb)-> Node.js LTS (v16.x)
+ Usar los comandos:

        curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
        sudo apt-get install -y nodejs
  
+  Instalar el gestor de paquetes de NodeJS.
     
        apt-get install -y build-essential

+ Instalar NodeRed
	https://nodered.org/
	https://nodered.org/docs/getting-started/local
      
        sudo npm install -g --unsafe -perm node-red
	
+ Comprobar la version de nodeRed
	
        node-red --version
    
    ![Imagen pagina Node-red]()
    
## Iniciar Node-Red.

Es un servicio que se ejecuta en segundo plano (servicio daemon) y se requiere una ventana terminal para ejecutarlo, por lo que se tiene que dejar abierta esa ventana terminal.

![Imagen inicio Node-red]()
![Imagen inicio Node-red2]()

## Node-Red MQTT 
Dentro de los nodos estandar se encuentra el nodo de MQTT in

![Imagen Node-red mqtt]()

### Manejo de nodos extra.
Los nodos estandar cubren apenas lo basico y para mas funcionalidades se ocua instalar más nodos, desde el **Manage Pallete** se pueden buscar nuevos nodos para aplicaciones especificas.

![Imagen Node-red mqtt]()
