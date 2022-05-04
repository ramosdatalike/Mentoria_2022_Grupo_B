# Mentoria_2022_Grupo_B
Mentoria 2022 Grupo B: Analisis de indicadores y noticias financieras Diplomatura en ciencia de datos UNC
#### El primer dataset consiste en
 - List item
 - Ticker
 - Titulo de noticia
 - Contenido de Noticia
 - Fecha de noticia
 
#### El segundo dataset consiste en
 - Ticker
 - 200 Indicadores financieros
 - Año
- Class (Fue una buena inversión si o no ese año para ese ticker)

## Analisis y Visualizacion
Exploraremos los datos importando los CSV en una notebook
Se proponen algunas ideas para comenzar:
- Se recomienda reducir ambos datasets para que los archivos csv tengan un tamaño entre 10MB y 50MB. Estos archivos se deben subir al repositorio, luego se podran leer directamente este. De esta manera nos podemos dar una buena idea para hacer el trabajo, cuando el codigo este terminado lo corremos con el dataset completo para ver el resultado final. 

#### Dataset financial_data.csv:
- Explorar indicadores, para identificar límites, distribución, extraer medidas de tendencia central, medidas de dispersión, outliers y valores NaN(Nulos).

A continuacion se sugiere una pre-seleccion de indicadores con los que pueden trabajar:
 'Revenue'
 'Revenue Growth'
 'Cost of Revenue'
 'Gross Profit'
 'Net Income'
 'EPS'
 'Dividend per Share'
 'EBITDA Margin'
 'EBITDA'
 'priceToSalesRatio'
 'priceEarningsRatio'
 'priceToFreeCashFlowsRatio'
 'priceEarningsToGrowthRatio'
 'priceSalesRatio'
 'dividendYield'
 'enterpriseValueMultiple'
 'returnOnAssets'
 'returnOnEquity'
 'debtRatio'
 'debtEquityRatio'
 'PE ratio'
 'EV to Sales'
 'Enterprise Value over EBITDA'
 'Graham Net-Net'
 'EPS Growth'

Pueden seleccionar algunos de estos para contestar los siguientes puntos. 

- Visualizar las distribuciones de estos
- Que son estos indicadores? como se calculan?
- Graficar cantidad de registros agrupados por año
- Graficar cantidad de registros agrupados por sector
- Distribución de PRICE VAR
- Distribución de PRICE VAR agrupados por año y por sector

- Crear Matriz de correlación entre indicadores incluyendo PRICE VAR
- Realizar scatterplots de pares de indicadores para ver su correlacion
- ¿Que podemos observar en las distribuciones y los graficos realizados? 


#### Del Dataset news_dataset.csv:
- Listar providers, cuales conocemos? cuales son los mas grandes?

- Graficar la cantidad de noticias por provider
- Graficar la cantidad de noticias por año
- Graficar la cantidad de noticias por ticker
- Graficar la cantidad de noticias por ticker y por año
- Graficar frecuencia de las palabras
link de utilidad: https://programminghistorian.org/es/lecciones/contar-frecuencias

Opcional: 
- Generar un histograma de palabras 
	- de cada empresa, 
	- de cada proveedor 
	- de cada año
- Generar nube de palabras
	- de cada empresa, 
	- de cada proveedor 
	- de cada año
