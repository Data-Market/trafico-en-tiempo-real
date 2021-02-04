# Tráfico en Tiempo Real

![trafico-en-tiempo-real-banner](https://datamarket.es/static/core/img/banners/trafico-en-tiempo-real-banner.png)

Datos de tráfico en Madrid y Barcelona. Este dataset se puede adquirir en [Data Market](https://datamarket.es/#trafico-en-tiempo-real-dataset), plataforma de referencia de datos externos en España. Puede consultar nuestro catálogo de datos en la siguiente url: [datamarket.es](https://datamarket.es/)

A continuación se muestran las columnas de las que consta el dataset en el formato __nombre_columna__: __ejemplo_columna__, donde ejemplo_columna representa posibles valores que se pueden encontrar en dicha columna.

| nombre     | tipo     | descripción                                                                                                 | ejemplo                                             |
|------------|----------|-------------------------------------------------------------------------------------------------------------|-----------------------------------------------------|
| date       | datetime | Fecha y hora del momento en el cual se que se obtuvieron los datos de densidad viaria.                      | 15-01-2021 13:35:08                                 |
| city       | str      | Lugar donde se ha registrado el dato de intensidad de tráfico.                                              | Madrid                                              |
| poi_id     | int      | Código de identificación del punto de medida de la densidad de tráfico.                                     | 3409                                                |
| poi_name   | str      | Nombre del punto de medida de la densidad de tráfico.                                                       | SEPULVEDA Ø118 N-S (CEBREROS-CJAL. FCO. J. JIMENEZ) |
| poi_lat    | geo      | Coordenada geográfica de latitud correspondiente a un punto de medida de densidad de tráfico.               | 40.401447                                           |
| poi_lon   | geo      | Coordenada geográfica de longitud correspondiente a un punto de medida de densidad de tráfico.              | -3.7541516712546996                                 |
| intensity  | int      | Intensidad de número de vehículos por hora.                                                                 | 144                                                 |
| occupation | int      | Porcentaje de ocupación del punto de control por los vehículos.                                             | 1                                                   |
| load       | int      | Parámetro de carga del vial en función de la intensidad, ocupación y características de la infraestructura. | 6                                                   |
