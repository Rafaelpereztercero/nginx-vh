#VIRTUAL HOSTS EN NGINX


### 1 Conexion ssh
Para conectarnos a la maquina, es sencillo, seguimos el siguiente ejemplo <code> ssh user@ip <code/>
 ![image](https://user-images.githubusercontent.com/91564342/173431548-2da861b6-e2aa-4928-bd30-38dcfedd3dfc.png)

### 2 Instalar Nginx

Para la instalación, ejecutaremos el siguiente comando <code> apt-get install nginx <code/>

  ![image](https://user-images.githubusercontent.com/91564342/173431574-cb9051c2-6fef-4eb6-afea-77aac4d5c8b6.png)
  ![image](https://user-images.githubusercontent.com/91564342/173431879-75cda860-256a-4d51-94a8-c177d9542c9d.png)

  ### 3 Crear los sites
  
  Para la creacion de los sites, simplemente nos dirigmos al directorio de sites-available y copiamos el default cambiandole el nombre de la siguiente forma
  
![image](https://user-images.githubusercontent.com/91564342/173431918-6e4841f6-a44d-4188-a6f6-74553c0b82de.png)
  
  Despues adaptamso los archivos creados con sus rutas y direcciones ccorrespondientes
  
  ![image](https://user-images.githubusercontent.com/91564342/173432046-6d0309a8-0565-4143-bd54-d10c46361df5.png)
![image](https://user-images.githubusercontent.com/91564342/173432064-100fa737-f152-4bc1-91b8-c8bfe1997f5f.png)

  
  ### 4 Crear directorios
  
  Para hacer referencia a los directorios indicados anteriormente, hemos de crearlos tal y como vemos a continuacion
  
  ![image](https://user-images.githubusercontent.com/91564342/173432212-4ba43783-8aa6-475c-90a4-b793ee0f281c.png)

  Una vez creados, les asignamos el contenido
  
  ![image](https://user-images.githubusercontent.com/91564342/173432271-c1d23fc8-c87a-48ea-9af2-9d062d852baf.png)
![image](https://user-images.githubusercontent.com/91564342/173432300-da04d7b2-5f55-48bd-a562-b5dc41e16eff.png)

 
  
  Reiniciamos el servicio <code>nginx -t <code/>
 
  ![image](https://user-images.githubusercontent.com/91564342/173432383-e7625744-26a8-4cb3-9470-4d654fba566c.png)

  
  ## LISTO, YA PODEMOS COMPROBAR QUE TODO FUNCIONA!
  
  ![image](https://user-images.githubusercontent.com/91564342/173432516-f6ef910a-9397-4ffc-adf0-b46eef37fe65.png)
 
![image](https://user-images.githubusercontent.com/91564342/173432538-703604f1-9aef-4063-8706-db8bef152a15.png)
 

  Todo el contenidoo html ha sido extraído de https://onehtmlpagechallenge.com/
  
  
  
