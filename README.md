# Datasets de Tráfico en Tiempo Real

<a href="https://datamarket.es">
  <img src="https://datamarket.es/static/core/img/banners/trafico-en-tiempo-real-banner.png">
</a>

## Descripción

Datos sobre el __tráfico en Madrid y Barcelona__. 

Las características de este dataset son las siguientes:

* __Frecuencia de actualización__: en tiempo real
* __Volumen estimado__: 1.5 millones de registros cada día
* __Histórico__: desde 2013

El dataset completo se puede adquirir en [DataMarket](https://datamarket.es/#trafico-en-tiempo-real-dataset), plataforma de referencia de datos externos en España. 

Este repositorio contiene los siguientes recursos:

* La documentación completa del dataset.
* Una muestra representativa del mismo disponible para su evaluación y uso gratuito.

## Muestra

La muestra se encuentra disponible para descarga en el siguiente [link](https://github.com/Data-Market/trafico-en-tiempo-real/blob/main/trafico-en-tiempo-real-sample.csv).

## Documentación

A continuación se muestran las columnas de las que consta el dataset junto con su descripción.

| nombre | tipo | descripción | ejemplo |
|--------|------|-------------|---------|
| city | str | Lugar donde se ha registrado el dato de intensidad de tráfico. | Madrid |
| date | datetime | Fecha y hora del momento en el cual se que se obtuvieron los datos de densidad viaria. | 15-01-2021 13:35:08 |
| day | int | Día en el que obtuvieron los datos de densidad viaria. | 15 |
| hour | int | Hora en el que se registraron los datos de densidad viaria. | 13 |
| intensity | int | Número de vehículos por hora. | 144 |
| load | int | Parámetro de carga del vial en función de la intensidad, ocupación y características de la infraestructura. | 6 |
| month | int | Mes en el que obtuvieron los datos de densidad viaria. | 1 |
| occupation | int | Porcentaje de ocupación del punto de control (POI). | 1 |
| poi_id | int | Código de identificación del punto de medida de la densidad de tráfico. | 3409 |
| poi_lat | geo | Coordenada geográfica de latitud correspondiente a un punto de medida de densidad de tráfico. | 40.401447 |
| poi_lon | geo | Coordenada geográfica de longitud correspondiente a un punto de medida de densidad de tráfico. | -3.7541516712546996 |
| poi_name | str | Nombre del punto de medida de la densidad de tráfico. | SEPULVEDA Ø118 N-S (CEBREROS-CJAL. FCO. J. JIMENEZ) |
| year | int | Año del momento en el cual se obtuvieron los datos de densidad viaria. | 2021 |
