# airline-revenue-research
EDA

Task: research airline revenue by flight destinations, types of flights, seasonality of sales

Data source: https://raw.githubusercontent.com/jpatokal/openflights/master/data/airports.dat <br>
column_names = ['Airport Name', 'Location', 'Country', 'IATA_Code', 'ICAO_Code', 'Latitude', 'Longitude', 'Altitude', 'Timezone', 'DST', 'Timezone Region', 'Type', 'Source'] <br>

The dataset contains information about the sale of airline tickets. Each line is a unique purchase. <br>

ISSUE_DATE:	дата покупки <br>
FLIGHT_DATE_LOC:	дата совершения перелета <br>
PAX_TYPE:	тип пассажиров <br>
REVENUE_AMOUNT:	сумма (значения скорректированы, но пропорции сохранены) <br>
ORIG_CITY_CODE:	город отправления <br>
DEST_CITY_CODE:	город назначения <br>
ROUTE_FLIGHT_TYPE:	тип перелета <br>
FFP_FLAG:	наличие программы лояльности <br>
SALE_TYPE:	способ покупки <br>

Расшифровка значений в полях: <br>
PAX_TYPE	<br>
AD - ADULT <br>
CHD -	CHILD <br>
INF -	UNDEFINED <br>

ROUTE_FLIGHT_TYPE	<br>
ВВЛ -	Внутренние Воздушные Линии <br>
МВЛ -	Международные Воздушные Линии
