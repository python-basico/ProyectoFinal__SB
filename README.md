# Proyecto Final, Segundo Bimestre - PYTHON BÁSICO

- **Vencimiento: Miércoles, 27 de julio**
- **Calificación: .../10 (Auto califique su trabajo)**

## Objetivos de aprendizaje
- Aplicar nuevas habilidades a un problema del mundo real
- Sintetizar las técnicas aprendidas

## Herramientas
- git
- github
- python
- poetry
- pandas
- numpy
- click



## Organización de carpetas

Archivos generados automáticamente por poetry

```
poetry-demo
├── pyproject.toml              
├── README.md                   # Documentación del proyecto    
├── poetry_demo
│   └── __init__.py
└── tests
    ├── __init__.py
    └── test_poetry_demo.py
```


## Flujo de Trabajo
1. Clona este repositorio en tu máquina local    
2. Edite los archivos que sean necesarios y complete todas las tareas semanales que se señalan en los entregables.
3. Confirme sus cambios y envíelos a github. 


## Entregables
- **Semana 2 (15 jun.):** 
  - Definición de problema. Debe ser un problema relacionado con su área de estudio y que se pueda dividir en módulos, analice algún problema que lo este desarrollando de forma manual y que pueda ser automatizado. Es importante que en el problema se realice operaciones numéricas con vectores, matrices. 
 
- **Semana 3 (22 jun.):** 
  - Lista de funcionalidades del problema a automatizar.
  - Implementación de funciones (30%)
  - Funcionamiento de aplicación por consola (empleando un menú).
   
- **Semana 6 (13 jul.):**  
  - Implementación de funciones en módulos (60%).
  - Creación de paquete empleando poetry en carpeta de proyecto. 
  - Funcionamiento de aplicación por consola empleando click
  - **\*** Publicación de paquete en [test.pypi.org](https://test.pypi.org/)
  
- **Semana 8 (27 jul.):**  
  - Implementación de funciones en módulos (100%).
  - Generación de gráficas
  - **\*** Almacenamiento de gráficas empleando el método savefig de matplotlib.  
  - Pruebas de funcionamiento del programa.
  - Documentación del proyecto: actualizar el contenido de README.md empleando el archivo plantilla_doc.md.
  - Publicación de paquete en [pypi](https://pypi.org/)

\* Opcional.

## Instrucciones

El proyecto final pretende ser un proyecto independiente que utilice las habilidades que ha aprendido en esta clase, así como las cosas que ha aprendido por su cuenta, para crear un programa de Interfaz de línea de comandos (CLI) que logre una o más tareas relevantes para resolver un problema del mundo real relacionadas con su **área de estudio**. A diferencia de otras actividades en las que se proporciono el problema, ahora es su turno de plantear un problema que desee automatizar. 

Específicamente, deberá utilizar técnicas de programación modular (uso de funciones), crear un paquete de la solución y publicarlo en pypi. 

Revisar los siguientes vídeos de referencia:
- [Creación de paquete con poetry](https://youtu.be/ZOSWdktsKf0?list=PLwkJQeEWueTsRrnrFJo3oRf89oYx--7PJ&t=3072)
- [Gestión de paquetes con poetry](https://youtu.be/4g9zXWzCLX0?t=682)
- [Poetry: "dependency management and packaging made easy"](https://youtu.be/QX_Nhu1zhlg?t=670) 
- [Creación de una aplicación CLI](https://www.youtube.com/watch?v=nNfgWhCqk4w&list=PL6cBnnS2SIgoSRRXYuvN6czVek-resNyl&ab_channel=Feregrino%E2%80%93ThatC%23guy)


### Criterios de revisión

La especificación del problema describe una lista de requisitos sobre la funcionalidad y el enfoque requerido. La calificación se basa en cuántos de los requisitos se satisfacen con la solución dada.

Para obtener el máximo crédito por el proyecto final, deberá:

1. Entregar una propuesta de proyecto antes del jueves 16 de junio. La descripción de la propuesta solo necesita ser de un párrafo. Debe describir en palabras lo que hará su proyecto final. Revisaré su propuesta lo antes posible y se le informara si es aceptable. Coloque la descripción de su propuesta en un archivo de texto llamado proposal.txt(o proposal.md si lo prefiere, markdown) y súbalo a través de github.

2. En su proyecto deberá utilizar programación modular (uso de funciones), paquetes (poetry), la librería numpy y matplolib. 

    En el caso de necesitar leer algún archivo de texto o CSV puede utilizar los métodos loadtxt, loadcsv de numpy ([revisar vídeo](https://www.youtube.com/watch?v=uGgKGuZqHuE)). Si son archivos de excel será más fácil utilizando la [librería pandas](https://www.quora.com/How-do-I-extract-data-from-Excel-into-NumPy).


3. Documente y comente su código, utilice nombres de variables y funciones representativos. Dado que este es su proyecto y no un ejercicio ordinario, es posible que no sepamos lo que está tratando de hacer. La documentación nos permitirá comprender mejor sus intenciones. Agregue comentarios a sus códigos para informarnos sus intenciones, si no se distinguen fácilmente de los comandos de código específicos. El uso de nombres representativos en variables y funciones ayudará a sólo dejar comentarios en las partes importantes y no en todo el código.   

4. Presente su proyecto a la clase el miércoles 27 de julio. Deberá tener claro lo que hizo y mostrar comprensión de su proyecto. No debe preparar una presentación formal (es decir, NO hacer un powerpoint). Simplemente describa oralmente lo que hizo para su proyecto y brinde una descripción general rápida de su (s) código (s) y los resultados obtenidos. Planee que su presentación tome solo 4 a 5 minutos. 

5. También debe entregar los archivos de datos necesarios para ejecutar sus códigos o proporcionar un enlace web donde se puedan descargar si pesa más de 100 MB. 

6. Actualizar el contenido de README.md empleando el archivo plantilla_README.md  


### Ejemplos de ideas de proyectos

- Aplicación para estimar el costo de construcción de una casa. 
- Aplicación para Funcionalidad de espacios (matriz de relaciones)
- Aplicación para procesar datos de sensores. 
- Procesar datos desde un repositorio público. 

