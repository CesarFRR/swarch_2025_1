# Arquitectura de Software Grupo 1 2025-1  
## Laboratorio 2 - c&c  
### César Fabián Rincón Robayo
Correo: [crinconro@unal.edu.co](mailto:crinconro@unal.edu.co)  
GitHub: [CesarFRR](https://github.com/CesarFRR)  
<div style="text-align: center;">  
    <img src="https://lucid.app/publicSegments/view/a60431d0-970e-41b2-b452-e02ba568eec6/image.png" alt="Representación gráfica de la estructura del sistema">  
</div>  


## Las 5 propiedades del sistema

## Externamente visible



## 1. Portabilidad: 
El sistema es portable gracias al uso de Docker, el cual empaqueta el software junto con todas sus dependencias en contenedores, logrando que se pueda ejecutar en cualquier lugar que pueda tener docker.

## 2. Escalabilidad (gracias a sus capas)
A pesar de su sencillez al utilizar la arquitectura monolito, dentro de esta la distribución de carpetas mediante componentes (`controllers`, `models`, `services`, `repositories`) permite una escalabilidad marcable para futuros avances o incrementos en el producto de software.

## 3. Modularidad: 
Al tener esa distribución de carpetas, y a su vez, al estar dockerizado, obtenemos un buen grado de modularidad que nos permite realizar cambios o actualizaciones en componentes específicos del software sin afectar negativamente todo e sistema en sí.

## 4. Seguridad:
El sistema garantiza un nivel adecuado de seguridad gracias al uso de Docker, que aísla el entorno de ejecución del software, evitando conflictos y reduciendo riesgos de acceso no autorizado al sistema operativo anfitrión. Además, el uso de SQLAlchemy como ORM permite prevenir ataques de inyección SQL al manejar las consultas de manera segura y estructurada.


### Externamente visibles:
## 5. Mostrar calificaciones
El sistema permite ver con facilidad todas las calificaciones de los estudiantes con su respectiva asignatura, es una visualización directa y sencilla
 

