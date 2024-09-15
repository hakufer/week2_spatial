# Week2_spatial

Link: https://hakufer.github.io/week2_spatial/

Este proyecto forma parte del CHALLENGE 1, donde se visualizan datos espaciales del país seleccionado: China. El objetivo es combinar tres capas de datos espaciales en un solo mapa:

Puntos: Aeropuertos
Líneas: Ríos
Polígonos: Divisiones administrativas (provincias)

## Diccionario de Datos

### Aeropuertos
| Variable            | Descripción                                                       |
|---------------------|-------------------------------------------------------------------|
| **id**              | Identificador único del aeropuerto.                               |
| **ident**           | Código de identificación del aeropuerto (código ICAO).            |
| **type**            | Tipo de aeropuerto (e.g., "large_airport", "medium_airport").     |
| **name**            | Nombre del aeropuerto.                                            |
| **latitude_deg**    | Latitud en grados.                                                |
| **longitude_deg**   | Longitud en grados.                                               |
| **elevation_ft**    | Elevación del aeropuerto en pies.                                 |
| **continent**       | Código del continente.                                            |
| **country_name**    | Nombre del país.                                                  |
| **iso_country**     | Código ISO del país.                                              |
| **region_name**     | Nombre de la región donde se encuentra el aeropuerto.             |
| **iso_region**      | Código ISO de la región.                                          |
| **local_region**    | Región local.                                                     |
| **municipality**    | Municipio donde se encuentra el aeropuerto.                       |
| **scheduled_service** | Indica si el aeropuerto ofrece servicio programado (1 para sí, 0 para no). |
| **gps_code**        | Código GPS del aeropuerto.                                        |
| **iata_code**       | Código IATA del aeropuerto.                                       |
| **local_code**      | Código local del aeropuerto.                                      |
| **home_link**       | Enlace a la página web del aeropuerto.                            |
| **wikipedia_link**  | Enlace a la página de Wikipedia del aeropuerto.                   |
| **keywords**        | Palabras clave asociadas con el aeropuerto.                       |
| **score**           | Puntaje del aeropuerto.                                           |
| **last_updated**    | Fecha de la última actualización.                                 |
