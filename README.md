# Telecommunications-Data-Analysis

## Introducción

Este proyecto se realizó simulando ser un Data Analyst de una consultora y tiene como finalidad la elaboración de un análisis de datos solicitado por una empresa prestadora de servicios de telecomunicaciones que permita reconocer el comportamiento de este sector a nivel nacional y orientar a ésta en brindar una buena calidad de sus servicios, identificar oportunidades de crecimiento y poder plantear soluciones personalizadas a sus posibles clientes.


## Contexto

La industria de las telecomunicaciones ha jugado un papel vital en nuestra sociedad, facilitando la información a escala internacional y permitiendo la comunicación continua. La transferencia de datos y comunicación se realiza en su mayoría a través de internet, líneas telefónicas fijas, telefonía móvil, y en casi cualquier lugar del mundo.

A pesar que Argentina está a la vanguardia en el desarrollo de las telecomunicaciones (teniendo para el 2020 un total de 62,12 millones de conexiones) existen sectores del país donde el acceso a internet es limitado, precario o simplemente no existe.

Por todo ello, este proyecto tiene como objetivo realizar un análisis integral del sector de telecomunicaciones a nivel nacional para la empresa prestadora de servicios. El enfoque principal es proporcionar información clave para mejorar la calidad de los servicios, identificar oportunidades de crecimiento y plantear soluciones personalizadas a los clientes.

## Desarrollo

1. `Datos`

    Para este proyecto se trabajó con la base de datos proporcionado por [ENACOM](https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/) y se utilizó tablas como **Penetración por hogares nacional de Internet fijo**, **Accesos a banda ancha y banda angosta**, **Acceso a Internet fijo por tecnología**, **Velocidades medias de bajada de Internet fijo** y **Localidades con conectividad a internet**.

2. `Análisis`

    El análisis se llevó a cabo a través de un notebook utilizando herramientas de análisis estadístico y visualización de datos para realizar un análisis exploratorio de cada uno de los datasets destacando los siguientes puntos:

    - **Penetración de internet fijo**

        Los resultados del análisis mostraron que la penetración de Internet fijo varío significativamente a lo largo de los años, además de poseer una gran variabilidad en la cantidad promedio de acceso entre las diferentes provincias.

        ![p-i-f](https://raw.githubusercontent.com/PedroLiLL/Telecommunications-Data-Analysis/main/assets/descarga.png)

        ![acceso-por-provincia](..\PROJECT\Telecommunications-Data-Analysis\assets\descarga (1).png)

    - **Acceso a banda ancha y banda angosta**

        Los datos evidenciaron que la mayoría de las provincias tienen un número muy bajo de conexiones de Dial up, con un promedio cercano a cero y una mayor acogida de banda ancha fija.

        ![acceso-BAba]()

    - **Acceso a Internet fijo por tecnología**

        Se observó una tendencia hacia el uso de tecnologías de acceso a Internet de alta velocidad como la Fibra Óptica y el Cablemodem; mientras que, por un lado el ADSL está disminuyendo en términos de cantidad de accesos, por otro lado la tecnología inalámbrica (Wireless) ha mantenido un nivel constante de accesos a lo largo de los años, lo que sugiere que su uso se ha mantenido estable. Además, los datos muestran que la Fibra Óptica y el Cablemodem representan más del 75% del total de accesos a Internet fijo en Argentina para el año 2022.

        ![evolucion-acceso-internet]()

        ![evolucion-acceso-internet-zoom]()

    - **Velocidad Media de bajada de Internet fijo**

        La velocidad media de bajada ha superado los 70 Mbps en el en 2022, lo que sugiere que se han producido mejoras significativas en la calidad de la conexión a Internet en los últimos años. Si embargo, los datos estadísticos arrojaron que existe una enorme brecha digital por provincias.

        ![promedio-minimo-velocidades]()

3. `KPIs`