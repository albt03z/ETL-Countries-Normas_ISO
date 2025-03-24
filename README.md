# ETL-Countries-Normas_ISO
# API Geográfica ISO

Esto proyecto cuyo objetivo es ofrecer información geográfica detallada y estandarizada de países, regiones y ciudades. La API se alimenta de datos provenientes de fuentes públicas como Geonames y RestCountries, y está diseñada siguiendo las normas ISO para países y divisiones administrativas.

## Características

- **Información Geográfica Completa:**  
  Datos de países, regiones y ciudades, incluyendo:
  - Datos básicos (códigos ISO, nombres oficiales en inglés y español, etc.)
  - Información adicional (capital, banderas, código telefónico, divisa, idiomas)
- **Proceso ETL Robusto:**  
  Un pipeline ETL implementado en Google Colab se encarga de:
  - Extraer datos de Geonames y RestCountries.
  - Transformar y enriquecer la información (traducción de nombres, generación de URLs de banderas, incorporación de datos de divisas e idiomas).
  - Cargar los datos en archivos CSV, listos para ser importados en la base de datos.


## Tecnologías Utilizada

- **ETL y Procesamiento de Datos:**  
  - Pandas
  - Requests
  - BeautifulSoup4
  - Deep-translator

- **Datos de Fuentes Públicas:**  
  - Geonames
  - RestCountries

## Instalación y Configuración

1. **Clonar el Repositorio:**
   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   cd tu_repositorio
