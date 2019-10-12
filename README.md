# Dependências
1. Ruby
2. Ruby On Rails
3. Postgres
4. Postgis

# Instalação do Postgis
1. Instale o Postgres 9.4 ou mais recente

`sudo apt-get install postgresql-9.5`

2. Instale o GCC (provavelmente já está instalado)

`sudo apt-get install gcc`

3. Instale Make (provavelmente já está instalado)

`sudo apt-get install make`

4. Instale o Proj4

`sudo apt-get install proj-bin`

5. Instalae o GEOS

`sudo apt-get install libgeos-dev`

6. Instalar LibXML2 (provavelmente já está instalado)

`sudo apt-get install libxml2`

7. Instale o JSON-C

`sudo apt-get install libjson-c-dev`

8. Instale o GDAL

`sudo apt-get install gdal-bin`

9. Instalar PostGIS

`sudo apt-get install postgis`


# dentro do projeto

  `bundle install`

  `rails db:create`

  `rails db:migrate`

  `rails db:seed`

# pra subir o server:

  `rails s`
