# Practica crear contenedores con yml y proyeto de springboot
## Informe de dos contenedores y proyecto con sprigboot
## 2. Tiempo 
 50 minutos
## 3. Fundamentos:

 ### 3.1 Docker
 Docker es una plataforma para poder virtualizar y empaquetar aplicaciones con dependencias en contenedores, que a diferencia de las máquinas virtuales comparten el mismo núcleo del sistema.

 - Imagen -
 Una imagen es un conjunto de instrucciones que describe cómo se debe configurar el contenedor.
 ### 3.2 Springboot
Es un framework que se basa en spring el cual está destinado para simplificar el proceso de configuración y despliegue de aplicaciones de java mediante el uso de dependencias.
 ### 3.3 YAML
 Yaml es un formto o estandar que se puede utilizar para poder hacer una configuración más rapida con código que puede ser más facil de leer o interpretar por otras personas.
## 4. Conocimientos previos.
   
Para realizar esta practica debemos tener conocimientos es:
1. Conocimientos de Docker.
2. Docker descargado.
3. Uso de la Terminal.
4. Navegador Web.
5. Acceso a Internet.
6. Comprensión de Puertos.
7. Conocimiento de Documentación de Docker.
8. Conocimientos de yml

## 5. Objetivos a alcanzar
   
- Dentro de la practica se tiene contemplado entender como se despliega un entorno dentro de docker con una base de datos postgres y un proyecto de springboot, conectandolo correctamente. 
## 6. Equipo necesario:
  
- Computador.
- Navegador web.
- Docker instalado.
- Proyecto de springboot

## 7. Material de apoyo.
   
- Documentacion de docker.
- Guia de asignatura.
- Imágnes de docker.
- Proyecto creado
  
## 8. Procedimiento

 ### 8.1 Creación de contendores y red
 Dentro de esta práctica vamos a comenzar levantando los contenedores y la red que ya los tenemos creados con el achivo yml, recordando que uno de los contenedores es de postgres, para la base de datos y otro de pgadmin que la va a consumir.
    ![](/backend/picture1)
 ### 8.2 Creación de artefacto jar
 Una vez con los contenedores en ejecución y verificada la conexión correcta de la base de datos 
     ![](/backend/picture6)
 vamos a crear el artefacto .jar, este artefacto nos va a servir para poder contener en un archivo comprimido todos los archivos necesarios para la ejecución del proyecto de springboot que tenemos.
    ![](/backend/picture4)
 ### 8.3 Creación de imagen con springboot
 Ahora con el archivo jar que contiene los documentos del proyecto vamos a colocarlo dentro de una imagen de docke para poder tener una mejor ejecución del proyecto.
 ### 8.4 Creación del ultimo contenedor
 Para poder tener nuestro proyecto de springboot en un entorno aislado vamos a tener que crear un nuevo contenedor que va a tener dentro la imagen que creamos con el arhivo .jar del proyecto completo.
    ![](/backend/picture5)
    ![](/backend/picture7)
## 9. Resultados esperados:
 Siguiendo todos los pasos vamos alograr comprender como podemos conseguir tener una aplicación o proyecto despringboot en un entorno aislado que vamos a poder manejar de una mejor manera tanto en su despliegue como en su mantenimiento.
