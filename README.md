# consulta_warehouse
Consulta para obtener mes con mayor  diferencia entre (ingresos y egresos) comparados mes a mes

DESCRIPCION : Consulta para obtener el mes con mayor diferencia entre (ingresos y egresos) comparados mes a mes del warehouse de la tienda de nuestra base de datos

SOFTWARE: MYSQL WorkBench 8.0

PROCESO: Este código SQL en MySQL es una consulta que busca calcular el ingreso de dos años diferentes (2019 y 2020) para cada mes. La consulta utiliza varias subconsultas anidadas y varios join para combinar los resultados de diferentes tablas. En primer lugar, se separan los ingresos de 2019 y 2020 en subconsultas, cada una de las cuales calcula el ingreso total para un año en particular sumando las ventas, restando las compras y los gastos. Luego, se combinan los resultados de las dos subconsultas utilizando un join interno basado en el mes. Finalmente, se ordenan los resultados en orden descendente según el ingreso total.
         
RESULTADO: El resultado fue una fila con el valor para el mes "4" y Dif_mesAMes = 1744266.320 que en resumidas cuentas nos indica que los ingresos fueron mayores para la doferencia de Abril 2020 menos Abril 2019
