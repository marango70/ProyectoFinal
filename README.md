# ProyectoFinal
Proyecto Final Henry
# <h1 align="center">**`YELP & GOOGLE MAPS - REVIEWS AND RECOMMENDATIONS`**</h1>


## ​Sprint 2: Puesta en Marcha del Proyecto


## :white_check_mark: ```Data Cruda ```
La fuente de información del proyecto fué proporcionada en Google Drive, los archivos originalmente proporcionado fueron los siguientes: </p>

- 🗂️ Google Maps:</p>
  - **`metadata-sitios`** : La carpeta tiene 11 archivos .json donde se dispone la metadata contiene información del comercio, incluyendo localización, atributos y categorías.</p>
  - **`review-estadosos`** : Los archivos contienen las reviews de los usuarios, uno por cada estado de los EEUU.
- 🗂️ Yelp:</p>
  - **`business`** : Archivo .pkl, que contiene información del comercio, incluyendo localización, atributos y categorías.</p>
  - **`review`** : Archivo .json que contiene las reseñas completas, incluyendo el user_id que escribió el review y el business_id por el cual se escribe la reseña.  </p>
  - **`checkin`** : Archivo .json que contiene los registros en el negocio.</p>
  - **`tips`** : Archivo .json con los Tips (consejos) escritos por el usuario. Los tips son más cortas que las reseñas y tienden a dar sugerencias rápidas.</p>

 

## :white_check_mark: ```Data Lake ```

Se utiliza la plataforma Google Cloud, especificamente Clous Storage para generar los siguientes buckets.
Solo se tomo la información de los estados de Florida (FL), New York (NY), Illinois (IL) y California (CL), para los años de 2016 a 2022. </p>

- 💾 **`Buquet g1_datos_crudos`** : Contiene la data inicial filtrada, previa normalización. </p>
- 💾 **`Buquet g1_datos_limpios`** : Contiene la data normalizada. </p>
- 💾 **`Buquet g1_datos_nuevos`** : Contiene los datos nuevos previa normalización. </p>
- 💾 **`Buquet g1_carga_incremental`** : Contiene los archivos nuevos normalizados para generar las funciones de carga incremental </p>
  
  </p>
(FALTA INCLUIR IMAGEN DE LOS BUCKETS)

## :white_check_mark: ```Data Warehouse```
</p>

(FALTA INCLUIR IMAGEN)
</p>

## :white_check_mark: ```Carga Incremental y Cloud Functions```

</p>
(FALTA INCLUIR IMAGEN)
</p>

## :white_check_mark: ```Relacionamiento de Tablas```

</p>
</p>
(FALTA INCLUIR IMAGEN)
</p>

## :white_check_mark: ```Dashboard Mockup```
  </p>
El dashboard se realizará en 📊 `Power BI` 📊 y tendrá el siguiente esquema:

**1. Página de Inicio:** Presenta el menú principal del Dashboard con sus respectivos links de acceso a cada página. </p>

**2. Resumen:** Presenta la información de los 4 principales KPI's asi: 
  - Valor Actual y % de cumplimiento de la meta 🎯.
  - Valor absoluto del indicador y distancia de este con el valor meta. Grafica de velocimetro 🏎️ .
  - Gráfico de tendencia 📉.

**3. KPI's:** Cada KPI tendrá una página en la cual se representa una grafica de barras con sus valores más recientes y diferentes objetos para contextualizar. Tambien se incluyen indicadores asociados, por ejemplo, para el KPI 2, Indice de oportunidades de Mejora, el cual estám dado por el número de calificaciones entre ⭐ y ⭐⭐ dividido el total de calificaciones, se incluirá tambien el indice para las calificaciones neutras (⭐⭐⭐) y el indice de calificaciones positivas (⭐⭐⭐⭐ y ⭐⭐⭐⭐⭐).

**4. Mercado:** Contiene un contexto general del mercado gastronómico en los 4 estados 🗺️ seleccionados. 
  (FALTA INCLUIR IMAGEN)
  </p>
  </p>
  

