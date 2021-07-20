# Practica08--Laberinto-VR

**CARRERA:** Computación 

**NOMBRES:** José Quinde		

**ASIGNATURA:** Programación Hipermedial

**NRO. PRÁCTICA:**	8	

**TÍTULO PRÁCTICA:** Desarrollo de una aplicación de realidad virtual usando la herramienta Unity y desplegada en un dispositivo móvil Android.

## OBJETIVOS
•  Experimenta con aplicaciones de realidad virtual.

• Experimenta con aplicaciones de realidad aumentada.

• Distingue la diferencia entre tecnologías de realidad virtual y realidad aumentada.

## ACTIVIDADES DESARROLLADAS
**1)	Crear un repositorio en GitHub con el nombre “Practica08 – Laberinto VR”**

**USUARIO:** JoseQ1996

**Repositorio:** https://github.com/JoseQ1996/Practica08--Laberinto-VR

**Vinculo APK Drive:**
https://drive.google.com/file/d/1Z4xrdNdQFNopv97BehTIdOt-5vWV0mRc/view?usp=sharing

![image](https://user-images.githubusercontent.com/49071271/126377261-1811f9d2-79b1-415a-a812-fa0560147dd8.png)

**2)	Realizar un commit y push por cada requerimiento de los puntos antes descritos.**

![image](https://user-images.githubusercontent.com/49071271/126377317-3327823f-d36a-4ce0-be10-9571be1f244d.png)
 
**3)	Crear la GVR Camera Rig**

![image](https://user-images.githubusercontent.com/49071271/126377403-a1896aba-f7f7-447d-b434-f20486fc2f8a.png)

Se coloco la cámara en la posición inicial para que el jugador pueda visualizar todo el panorama.

**4)	Preparando la escena para la interacción**

Se agrego los eventos necesarios a la cámara para que el usuario interactúe con la escena

![image](https://user-images.githubusercontent.com/49071271/126377486-4df53e9d-6ace-4cf8-82e9-4b637ef517c7.png)
 
**5)	Hacer que los objetos del juego sean interactivos**

Se agrega eventos a los objetos a interactuar en el juego
 
![image](https://user-images.githubusercontent.com/49071271/126377539-97261031-da3c-4dd4-94c2-c179598f0789.png)
![image](https://user-images.githubusercontent.com/49071271/126377591-1c35ba74-c79b-41d3-bc31-296e7bd4d2d5.png)

**6)	Hacer la interfaz de usuario interactiva**

Se realizo el mismo proceso anterior pero ahora al presionar resetea la escena.
	
![image](https://user-images.githubusercontent.com/49071271/126377635-07b4b58e-b0d5-436e-8a64-8548fa1ea869.png)
 
Se modifica el código de Coin para que se pueda hacer interactiva la escena
 
![image](https://user-images.githubusercontent.com/49071271/126377670-17239066-7dda-4b68-958b-0127a7aa2127.png)
![image](https://user-images.githubusercontent.com/49071271/126377681-b8d39949-780c-4d2a-86f6-9e3d972ad656.png)
 
Se debe duplicar el objeto de Coin ya que pide  un mínimo de 5 coins en el juego.

**7)	Programando el comportamiento de la llave (key)**

Se realiza la programación en el script del Key y luego se pone los eventos en el objeto Key para poder interactuar con la llave.

![image](https://user-images.githubusercontent.com/49071271/126377735-7d279696-0bd6-41bc-bc57-53ac2874e4d8.png)
![image](https://user-images.githubusercontent.com/49071271/126377749-2f05f616-9d74-449d-9ee4-4bf3bfadcbe8.png)
  
**8)	Programando el comportamiento de la puerta (door)**

Se realiza el mismo proceso anterior de la llave pero ahora se programa la puerta siguiendo los pasos requeridos.

![image](https://user-images.githubusercontent.com/49071271/126377797-30bdc6c9-352c-4e6f-a39a-d664260e9613.png)
![image](https://user-images.githubusercontent.com/49071271/126377816-5b95bd0f-be90-4682-aaca-d97c2294f72c.png)

**9)	Programando el comportamiento del SignPost**

El mismo proceso anterior se programa el script y luego se agrega el evento.
 
![image](https://user-images.githubusercontent.com/49071271/126377952-4a5da9a3-6037-421a-a225-7ee922dad37f.png)

**10)	Crear la funcionalidad del juego**

Primero se creo el entorno del laberinto con los maze que venían por defecto en el proyecto y también se utilizo las flag y pilares extras.

![image](https://user-images.githubusercontent.com/49071271/126377988-f71848e7-a5f3-4f19-b6e1-2de30309ee24.png)
 
Luego se ingresa los caminos del laberinto en el contorno del juego.
 
![image](https://user-images.githubusercontent.com/49071271/126378012-7a25a381-c53e-4ba0-b933-a90c8c5e7906.png)

Finalmente se agrega los Waypoint para navegar por el laberinto y poder jugar.
 
![image](https://user-images.githubusercontent.com/49071271/126378043-37378cbc-8661-4249-b8df-865975049eb3.png)

Se le agrega los detalles finales como el ambiente y el sonido de ambiente que viene también predeterminados en el proyecto.
 
![image](https://user-images.githubusercontent.com/49071271/126378074-5fcb3b56-8322-4084-aee9-e3c8d951665a.png)

Se cambia las configuraciones del jugador.
 
![image](https://user-images.githubusercontent.com/49071271/126378099-db713ebd-e845-41b4-9201-4e9817b926b7.png)

**11)	Anexo (Pantallazos funcionamiento)**
 
![image](https://user-images.githubusercontent.com/49071271/126378124-7badc59a-0f3e-428d-858c-5d7c468ee78a.png)
![image](https://user-images.githubusercontent.com/49071271/126378145-e145491e-2d7e-477d-9891-2de6cdc2592f.png)
![image](https://user-images.githubusercontent.com/49071271/126378161-c59308cd-19ba-4905-8e60-bc2204b855cc.png)
![image](https://user-images.githubusercontent.com/49071271/126378200-1b89ec72-6b84-4fa5-b683-7c5fd2c81591.png)
 
## CONCLUSIONES:

Como conclusión puedo decir que al finalizar esta practica se aprendió a realizar programación básica para mover objetos en Unity esto nos ayuda para que podamos animar escenas y nos da mas opciones al momento de crear algún proyecto de realidad virtual, se puede decir que el mundo de Unity es extenso y hay muchas herramientas para realizar una escena o juego en esta plataforma para poder exportarlo a un dispositivo Android.

**Nombre de estudiante:** José Quinde

**Firma de estudiante:**

![image](https://user-images.githubusercontent.com/49071271/126378281-51581ff6-82a5-4169-86eb-a28efcf30e8c.png)

  


