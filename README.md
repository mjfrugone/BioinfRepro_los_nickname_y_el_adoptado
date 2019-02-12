# Readme
## BioinfRepro_grupo3
Este repositorio contiene el resultados del ejercicio 3 del equipo "Los nickname y el adoptado", Grupo 3.

### Integrantes del equipo:

* María José Frugone Wielandt 
* Brett Oliver Butler
* Kyle James Shaney

## Programas Útiles
### Beast
Beast corresponde a un conjunto de programas que utilizan secuencias para determinar relaciones filogenéticas, y estimar las fechas de divergencia entre linajes utilizando calibraciones de fósiles o métodos de reloj. Es útil para inferir procesos divergencia entre poblaciones o especies. El archivo de entrada es en formato Nexus, el cual se usa con el programa Beauti, donde se setean los parámetros de la filogenia y se genera un archivo de extensión .xml, el cual es utlizado por Beast para realizar los análisis.
### [Liga para Beast](http://beast2.org/)

### Adegenet
Adegenet es un paquete de R software, el cual permite inferir clusters genéticos sin basarse en modelos. 
Este paquete puede utlizar como formato de entrada archivos structure (.str), los cuales son convertidos en objetos de clase "genind" o "genlight" para realizar los análisis. Las funciones principales de este paquete son, **find.clusters** que propone el número óptimo de clusters basado en BIC, y el **dapc** que es un análisis similar a un PCA. dapc provee variables sinteticas a partir de las variables originales, pero que se diferencian de un PCA ya que en dapc, las variables son contruidas buscando maximizar la varianza entre grupos.
### [Liga para Adegenet](https://cran.r-project.org/web/packages/adegenet/index.html)
