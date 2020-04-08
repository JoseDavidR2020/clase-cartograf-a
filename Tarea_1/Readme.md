# Tarea 1


## ESTADO DE CALIDAD DEL AIRE EN BOGOTÁ PARA EL AÑO 2020

Mapa web con el estado de calidad del aire para Bogotá, según los datos diarios de PM2.5 reportados por la red de monitoreo de calidad del aire (RMCA) de la secretaria distrital de ambiente(SDA).


## 1. ¿Cuál es el problema a tratar?

Identificar la distribución del material particulado PM2.5 para la zona urbana de la ciudad de Bogotá y así definir los riesgos a la salud humana de las zonas más contaminadas. 


## 2. ¿Por qué los datos geográficos ayudan a resolverlo?

Porque los mapas permiten identificar gráficamente la distribución del material particulado. Asimismo, con el mapa puedo conocer los sitios más afectados y adoptar medidas según los lineamientos de la normatividad vigente (Resolución 2254 del 01 noviembre de 2017).


## 3. Descripción de la solución propuesta

El MAPA DE CALIDAD DEL AIRE permite representar la distribución de los valores monitoreados en las 13 estaciones de calidad del aire, con que cuenta la RMCA para Bogotá. La normatividad ambiental cita un código de colores de acuerdo a los valores obtenidos, tal como se muestra a continuación.

### Por qué establecer la calidad del aire con el PM2.5

Este contaminante es uno de los más nocivos para la salud humana, ya que está asociado a enfermedades cardiacas y pulmonares, además de cáncer.

### Valor

A continuación, se muestra un cuadro que define los puntos de corte para los valores del contaminante y se asocia un código de colores atribuido a una serie de efectos sobre la salud humana:

| PM2.5 (μg/m3)|  Color  |      Categoría      |                            Efectos                           |
|     :---:    |  :---:  |        :---:        |                             :---                             |
|    0 - 12    |  Verde  |        Buena        |La contaminación supone un riesgo bajo para la salud          |
|    13 - 37   | Amarillo|      Aceptable      |Posibles síntomas respiratorios en poblacion sensible         |
|    38 - 55   | Naranja |     Dañina a GS     |Grupos poblaciones sensibles pueden presentar efectos en salud|
|   56 - 150   |  Rojo   |  Dañina a la salud  |Todos los individuos pueden experimentar efectos en salud     |
|  151 - 250   | Purpura |Muy Dañina a la salud|Estado de alerta que significa en todos efecto grave en salud |
|  251 - 500   |  Verde  |      Peligrosa      |Advertencia sanitaria. Efectos adversos graves en la salud    |


## 4. Listado detallado de las fuentes de datos seleccionadas

### Localidades de Bogotá
**Proveedor:** Plataforma distrital de Datos Abiertos
**Descripción del conjunto de datos:** El mapa abarca las 20 localidades del distrito capital con un atributo de área por localidad
**Descripción de atributos:** El mapa contiene las áreas de las localidades con su respectivo nombre. 
**Enlace para descarga:** https://datosabiertos.bogota.gov.co/dataset/localidad-bogota-d-c
