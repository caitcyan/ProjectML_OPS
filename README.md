```fix
 ⚡⚡ Bienvenidos a mi primer proyecto individual ⚡⚡
```
Autora: <span style="color: violet;"> Na</span><span style="color: green;">ta</span><span style="color: cyan;">lia</span> Gomez

Video explicativo: [Video](https://drive.google.com/drive/u/2/folders/11aZIv_wl6Z9jhXrXGiamTD5zXxDBgfaR)


Este proyecto consistió en limpiar, analizar brevemente y realizar un modelo de recomendación con un dataset de películas y series. 

Requisitos:
- Python 3.10.6 
- Microsoft Build tools 2014 o superior.
  
- Datos:
      https://drive.google.com/drive/folders/1b49OVFJpjPPA1noRBBi1hSmMThXmNzxn
    - Carpeta Data, con los cuatro csv de nuestros cuatro proveedores(netflix,amazon,disney,hulu).
    - Subcarpeta ratings, con los 8 archivos csv.
- Librerías: Pandas, Numpy, Space, Streamlit. # pip install

La carpeta del proyecto está estructurada de la siguiente manera:
> ProjectML_OPS
 - Data
 - ProjectML_OPS_ML
 - ProjectML_OPS_API
 - ETL.ipynb
 - EDA.ipynb

Dentro de ProjectML_OPS_ML tenemos la carpeta Streamlit, donde se encuentra la interfaz gráfica del sistema.

 - EDA_ML.ipynb
 - Streamlit

Dentro de Streamlit
- recommendations_movies.py
- background.gif
- overview.png
- upload_to_drive.py
- config.toml
- data.csv
- new_data.csv
- data_aux.csv

<span style="color: cyan;">Indicaciones para la ejecución del proyecto</span>

- Crear las carpetas necesarias.
- Ejecutar el notebook ETL.ipynb de la carpeta principal.
- Ejecutar el notebook EDA.ipynb de la carpeta principal.
- Deployar la API mediante Space, empleando la carpeta ProjectML_OPS_API.
- Ejecutar el notebook EDA_ML.ipynb, de la carpeta ProjectML_OPS_ML.
- Ejecutar la streamlitapp desde la carpeta Streamlit, preferemente en el archivo recommendations_movie.py. Usa el comando streamlit. 
- Eso es todo!

✨IMPORTANTE✨: el archivo upload_to_drive.py es para subir mis datasets a Deta Drive.

- Sobre el modelo de ML:

Usé un filtro colaborativo, con el que se comparan los valores de ratings de distintos usuarios.Usé el Singular Value Decomposition para realizar las operaciones matemáticas.

![alt text](https://www.statdeveloper.com/wp-content/uploads/2020/03/colaborativo-1.png)

```fix
Overview de la API
```
- Para saber cómo funciona la API dirigirse al readme.md ubicado en la carpeta ProjectML_OPS_API.
- https://deta.space/discovery/@caitcyan/my_api/exp-AYCh
```fix
Overview de StreamlitApp
```
- La indicación consistió en crear un sistema de recomendación para saber si recomendar una pelicula o no a un usuario. 
  
 - Usé Streamlit para realizar la interfaz de la aplicación. 

 - Consideraciones:
 - Colocar el usuario Id en la caja de texto.
 - Elegir la película de la lista desplegable.
 - El sistema te indicará si te recomienda o no la película.

![alt text](./ProjectML_OPS_ML/Streamlit/overview.png "Over view")

 - Eso es todo. Cualquier feedback es bienvenido. ✨✨✨
