# Primera entrega // Proyecto en proceso
## 1. Base de datos
- Registros diarios climáticos en Islas Galápagos <br>
Link a la base: 
<a href="https://drive.google.com/drive/folders/1oZDfXZPnu-UuAa1T_SG9Qa7yRF8EMy75?usp=sharing">Base</a>



Integrantes del proyecto: Consiglio Gerardo, Burko Ivan, D'onofrio Gianluca.
<hr>

## 2. Temática elegida

<img src="https://media.a24.com/p/98cb7616c3563e3b8c0f87a058335f7f/adjuntos/296/imagenes/008/118/0008118776/1200x675/smart/donde-quedan-las-islas-galapagos.jpeg">

La temática a tratar será la evolución de las condiciones climáticas en el archipiélago desde 1964 hasta la actualidad. Teniendo en cuenta que el archipiélago Galápagos es un lugar único para la investigación climática ya que están en una posición geográfica donde convergen varias corrientes marinas del Pacífico que poseen diferentes características (corriente de Sur Ecuatorial, Subecuatorial o Corriente de Cromwell, Humboldt y Panamá).
Queremos analizar, en base a los datos provistos por la fundación “Charles Darwin”, si encontramos variaciones considerables interanuales y tratar de identificar si guardan relación con el cambio climático. 

<hr>

## 3. Diagrama entidad - relación <br>
<i> Diagrama entidad-relación de las tablas seleccionadas. </i> <br>
 Link al diagrama : <a href='https://drive.google.com/file/d/11sMcyxh5iNHtrlKof_97Amztoqxr6aU_/view?usp=sharing'> Diagrama </a> <br>
 Link en miro : <a href='https://miro.com/app/board/uXjVO6ADgHM=/'> Diagrama </a>

<img src='https://raw.githubusercontent.com/geracons/galapagoscoder/main/Entity%20Relationship%20Diagram%20(3).jpg'>

<hr>

## 4. Características de la base: <br>
### 4.1 Listado de tablas y definición de claves.
<i> Listado de tablas, con definición de clave primaria y/o clave foránea, según corresponda.
 </i>

    Tablas:
    - Islas 
        Claves:  PK 'ID_isla'
    - Estación
        Claves: PK 'ID_estacion'
    - Clima
        Claves: FK 'ID_estacion', FK 'ID_isla'
    
 
<hr>



### 4.2 Listado de columnas por tablas y tipos de datos
<i> Listado de columnas por tablas, con definiciones de tipos de datos.  </i> <br>

    Columnas por tabla:
    - Islas:
        ID_isla 
        nombre_isla
        pos_geografica
        habitantes_cantidad
        dimension_m2
        
    - Estación
        ID_estacion
        nombre_estacion
        investigadores

    - Clima
        ID_estacion
        ID_isla
        observation_date
        min_air_temp
        max_air_temp
        mean_air_temp
        sea_temp
        humidity
        precipitation
        sunshine_hours
        clouds
 
