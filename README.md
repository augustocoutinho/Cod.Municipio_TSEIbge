# Shapefile dos Municípios (TSE e Ibge)
Shapefile unificando os ids dos municípios presentes nas bases do ``TSE`` e ``IBGE``.

Utilizei a base disponibilizada pelo <a href = "https://github.com/betafcc/Municipios-Brasileiros-TSE">``betafcc/Municipios-Brasileiros-TSE``</a>. A malha utilizada foi a publicada pelo <a href="https://geoftp.ibge.gov.br/organizacao_do_territorio/malhas_territoriais/malhas_municipais/municipio_2021/Brasil/BR/BR_Municipios_2021.zip">``IBGE``</a>, de 2021.

<br/>

A tabela tratada segue com a seguinte estrutura de variáveis: ``cod_mun | municipio | sigla_uf | area_km2 | geometry``

### head(10):

| cod_mun ``<chr>`` | municipio ``<chr>``  | sigla_uf ``<chr>`` | area_km2 ``<dbl>`` | geometry ``<S3: sfc_MULTIPOLYGON>`` |
|---------------|:------------------------:|:--------------:|:--------------:|:-------------------------------:|
|1100015	      | Alta Floresta D'Oeste	   |  RO            |	7067.127	     |  <S3: sfc_MULTIPOLYGON>         |
|1100023	      |	Ariquemes	               |  RO            |	4426.571	     |  <S3: sfc_MULTIPOLYGON>         |
|1100031	      |	Cabixi	                 |  RO            |	1314.352	     |  <S3: sfc_MULTIPOLYGON>         |
|1100049	      |	Cacoal	                 |  RO            |	3793.000	     |	<S3: sfc_MULTIPOLYGON>         |
|1100056	      |	Cerejeiras	             |  RO            |	2783.300	     |	<S3: sfc_MULTIPOLYGON>         |
|1100064	      |	Colorado do Oeste        |	RO            |	1451.060	     |	<S3: sfc_MULTIPOLYGON>         |
|1100072	      |	Corumbiara               |	RO            |	3060.321	     |	<S3: sfc_MULTIPOLYGON>         |
|1100080	      |	Costa Marques            |	RO            |	4987.177	     |	<S3: sfc_MULTIPOLYGON>         |
|1100098	      |	Espigão D'Oeste          |	RO            |	4518.038	     |	<S3: sfc_MULTIPOLYGON>         |
|1100106	      |	Guajará-Mirim            |	RO            |	24856.877	     |	<S3: sfc_MULTIPOLYGON>         |
