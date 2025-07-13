# -Dashboard-y-Analisis-de-Datos

# Análisis de Ventas y Beneficios de Cafetería

## Descripción del Proyecto

Este proyecto se basa en un conjunto de 3.000 registros de ventas simuladas por ChatGPT correspondientes a cuatro sucursales de una cafetería, en el período comprendido entre enero y los primeros 18 días de abril de 2025. 

El análisis de estos datos permite conocer las preferencias de los clientes respecto a los productos ofrecidos, los métodos de compra más utilizados, los horarios de mayor demanda y otros aspectos clave del negocio. 

El objetivo de este análisis es detectar los factores que más impactan en las ventas y lograr una visión completa del mercado.

## Estructura del Proyecto

El trabajo se compone de un Excel con tres hojas. La primera son los datos en crudo, la segunda las tablas de ventas y beneficios sobre cada columna y la tercera el Dashboard final del proyecto.

## Transformación y Limpieza de Datos

Para asegurar la calidad del análisis, se realizó un proceso de limpieza y transformación de los datos:

Tratamiento de valores nulos:** Se identificaron algunos campos con valores faltantes en la columna "Método de pago" y "Producto". Estos registros fueron eliminados por representar menos del 2% del total y no afectar significativamente el análisis.
  
Formato de fechas:** Las fechas fueron convertidas a formato "fecha completa" para permitir un análisis temporal por mes, día de la semana y horario.

Comprobación de duplicados:** Se realizó una validación para detectar registros duplicados por ID de transacción. Se eliminaron 8 registros repetidos para evitar distorsiones.

Normalización de categorías:** Se estandarizaron nombres de productos y métodos de pago para asegurar coherencia en las agrupaciones (por ejemplo, "Café" y "cafe" se unificaron como "Café").

## Supuestos y Decisiones de Filtrado

- Supuesto de integridad en el rango temporal:
  Se asumió que los datos disponibles (hasta el 18 de abril de 2025) representan fielmente la tendencia estacional inicial del año.

- Agrupación por turno:  
  Para facilitar el análisis horario, se agruparon los horarios en tres franjas:  
  - Mañana (6:00 a 12:00)  
  - Tarde (12:01 a 20:00)  
  - Noche (20:01 a 23:59)

## Interpretación de Insights

Los principales resultados obtenidos y su implicancia para el negocio:

- Producto estrella: Café
  Representa aproximadamente el 50% de las ventas totales, lo que confirma su rol central en el negocio. Su disponibilidad y calidad son clave para la fidelización de clientes.

- Mayor demanda por la mañana:  
  Las ventas se concentran en las primeras horas del día, lo que sugiere que muchos clientes compran productos para el desayuno. Esto abre oportunidades para campañas como "Desayuno Express" o combos matutinos.

- Temporada fuerte: Invierno (enero-abril):
  Enero fue el mes con mayor cantidad de ventas. Si bien los datos solo cubren parte del año, se observa un aumento de consumo en los meses más fríos, lo que permite planificar promociones estacionales.

## Próximos pasos

- Enfocarse en el café, se debe mantener visible, promocionado y siempre disponible. Es fundamental para sostener las ventas.
- Campañas matutinas: Lanzar promociones para el público de la mañana, como combos o descuentos por horario.
- Estrategias estacionales, considerar promociones para el invierno, es la temporada con más ventas.

## Autor

Guido Julían Calvo Sio
