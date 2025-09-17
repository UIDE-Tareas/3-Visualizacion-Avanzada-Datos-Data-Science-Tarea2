# 3-Visualizacion-Avanzada-Datos-Data-Science-Tarea2
3-Visualizacion-Avanzada-Datos-Data-Science-Tarea2



### Conjunto de Datos de Crímenes en Chicago - Diccionario de Datos

Actualizado: **16/Septiembre/2025**    
Proporcionado por: **Departamento de Policía de Chicago - Illinois**    
Uri: **[Crimes - 2017](https://data.cityofchicago.org/Public-Safety/Crimes-2017/d62x-nvdr/about_data)**

| Column Name            | Description                                                                                                                                                            | API Field Name       | Data Type            |
|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------|----------------------|
| ID                     | Identificador único para el registro.                                                                                                                                  | id                   | Number               |
| Case Number            | Número RD del Departamento de Policía de Chicago (Records Division Number), único para el incidente.                                                                    | case_number          | Text                 |
| Date                   | Fecha en que ocurrió el incidente (a veces es una estimación).                                                                                                          | date                 | Floating Timestamp   |
| Block                  | Dirección parcialmente redactada donde ocurrió el incidente, ubicada en el mismo bloque que la dirección real.                                                          | block                | Text                 |
| IUCR                   | Código de Reporte Uniforme de Crímenes de Illinois (Illinois Uniform Crime Reporting). Relacionado con el Tipo Primario y la Descripción. [Ver IUCR codes](https://data.cityofchicago.org/d/c7ck-438e) | iucr                 | Text                 |
| Primary Type           | Descripción primaria del código IUCR.                                                                                                                                   | primary_type         | Text                 |
| Description            | Descripción secundaria del código IUCR, una subcategoría de la descripción primaria.                                                                                    | description          | Text                 |
| Location Description   | Descripción del lugar donde ocurrió el incidente.                                                                                                                       | location_description | Text                 |
| Arrest                 | Indica si se realizó un arresto.                                                                                                                                        | arrest               | Checkbox             |
| Domestic               | Indica si el incidente estuvo relacionado con violencia doméstica (según la Ley de Violencia Doméstica de Illinois).                                                    | domestic             | Checkbox             |
| Beat                   | Indica el “beat” donde ocurrió el incidente. Un beat es el área geográfica policial más pequeña, con un patrullero asignado. Tres a cinco beats conforman un sector.    | beat                 | Text                 |
| District               | Indica el distrito policial donde ocurrió el incidente. [Ver distritos](https://data.cityofchicago.org/d/fthy-xz3r)                                                     | district             | Text                 |
| Ward                   | El “ward” (distrito del Concejo Municipal) donde ocurrió el incidente. [Ver wards](https://data.cityofchicago.org/d/sp34-6z76)                                          | ward                 | Number               |
| Community Area         | Indica el área comunitaria donde ocurrió el incidente. Chicago tiene 77 áreas comunitarias. [Ver community areas](https://data.cityofchicago.org/d/cauq-8yn6)           | community_area       | Text                 |
| FBI Code               | Clasificación del crimen según el Sistema Nacional de Reportes Basados en Incidentes del FBI (NIBRS).                                                                   | fbi_code             | Text                 |
| X Coordinate           | Coordenada X en proyección State Plane Illinois East NAD 1983. Desplazada de la ubicación real por redacción parcial, pero en el mismo bloque.                          | x_coordinate         | Number               |
| Y Coordinate           | Coordenada Y en proyección State Plane Illinois East NAD 1983. Desplazada de la ubicación real por redacción parcial, pero en el mismo bloque.                          | y_coordinate         | Number               |
| Year                   | Año en que ocurrió el incidente.                                                                                                                                        | year                 | Number               |
| Updated On             | Fecha y hora en que se actualizó el registro por última vez.                                                                                                            | updated_on           | Floating Timestamp   |
| Latitude               | Latitud de la ubicación del incidente. Desplazada de la ubicación real por redacción parcial, pero en el mismo bloque.                                                   | latitude             | Number               |
| Longitude              | Longitud de la ubicación del incidente. Desplazada de la ubicación real por redacción parcial, pero en el mismo bloque.                                                  | longitude            | Number               |
| Location               | Ubicación del incidente en formato apto para creación de mapas y operaciones geográficas. Desplazada de la ubicación real por redacción parcial, pero en el mismo bloque. | location             | Point                |
