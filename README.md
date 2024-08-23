Google Caso Práctico - Cyclistic
RenyV
2024-08-20
Caso práctico: ¿Cómo lograr el éxito rápido de un negocio de bicicletas compartidas?

Introducción
Bienvenido al caso práctico del análisis de bicicletas compartidas Cyclistic. En este caso práctico, realizarás muchas tareas del mundo real, típicas de un analista de datos júnior. Trabajarás para una empresa ficticia llamada Cyclistic y conocerás a diferentes personajes y miembros del equipo. Para responder a las preguntas clave de la empresa, seguirás los pasos del proceso de análisis de datos: preguntar, preparar, procesar, analizar, compartir y actuar. En este proceso, las tablas del mapa de ruta de caso práctico, incluidas las preguntas orientativas y las tareas clave, te ayudarán a mantenerte en el camino correcto.

Escenario
Eres un analista de datos júnior que trabaja en el equipo de analistas de marketing de Cyclistic, una empresa de bicicletas compartidas de Chicago. La directora de marketing cree que el éxito futuro de la empresa depende de maximizar la cantidad de membresías anuales. Por lo tanto, tu equipo quiere entender qué diferencias existen en el uso de las bicicletas Cyclistic entre los ciclistas ocasionales y los miembros anuales. A través de estos conocimientos, tu equipo diseñará una nueva estrategia de marketing para convertir a los ciclistas ocasionales en miembros anuales. Sin embargo, antes de eso, los ejecutivos de Cyclistic deben aprobar tus recomendaciones; por eso, debes respaldar tu propuesta con una visión convincente de los datos y visualizaciones profesionales de los mismos.

Personajes y equipos
●     Cyclistic: Un programa de bicicletas compartidas que incluye 5,800 bicicletas y 600 estaciones. Cyclistic se destaca por ofrecer también bicicletas reclinadas, triciclos manuales y bicicletas de carga que ofrecen un uso más inclusivo de las bicicletas compartidas para las personas con discapacidad y los ciclistas que no pueden utilizar una bicicleta estándar de dos ruedas. La mayoría de los ciclistas eligen las bicicletas tradicionales, alrededor de un 8% de los ciclistas usan las opciones asistidas. Los usuarios de Cyclistic son más propensos a utilizar la bicicleta para recreación, pero alrededor del 30% la utiliza para ir al trabajo cada día.

●     Lily Moreno: La directora de marketing y tu gerente. Moreno es responsable del desarrollo de campañas e iniciativas para promover el programa de bicicletas compartidas. Las campañas pueden incluir correo electrónico, redes sociales y otros canales.

●     Equipo de análisis computacional de datos de marketing de Cyclistic: Un equipo de analistas de datos que se encargan de recopilar, analizar e informar datos que ayudan a conducir la estrategia de marketing de Cyclistic. Te incorporaste a este equipo hace seis meses y te has dedicado no solo a conocer la misión y las metas de negocios de Cyclistic, sino también a ver cómo puedes ayudar a Cyclistic a lograrlo, desde tu posición de analista de datos júnior.

●     Equipo ejecutivo de Cyclistic: El equipo ejecutivo, sumamente detallista, decidirá si aprueba el programa de marketing recomendado.

Acerca de la empresa
En 2016, Cyclistic lanzó una exitosa oferta de bicicletas compartidas. Desde entonces, el programa creció hasta alcanzar una flota de 5,824 bicicletas georreferenciadas y bloqueadas en una red de 692 estaciones en toda Chicago. Las bicicletas se pueden desbloquear desde una estación y devolverse en cualquier otra estación del sistema en cualquier momento.

Hasta ahora, la estrategia de marketing de Cyclistic se basaba en la construcción de un reconocimiento de marca general y en atraer a amplios segmentos de consumidores. Uno de los enfoques que ayudó a hacer esto posible fue la flexibilidad de sus planes de precios: pases de un solo viaje, pases de un día completo y membresías anuales. A los clientes que compran pases de un solo viaje o pases de un día completo se los llama ciclistas ocasionales. Los clientes que compran membresías anuales se llaman miembros de Cyclistic.

Los analistas financieros de Cyclistic llegaron a la conclusión de que los miembros anuales son mucho más rentables que los ciclistas ocasionales. Aunque la flexibilidad de precios ayuda a Cyclistic a atraer más clientes, Moreno cree que maximizar el número de miembros anuales será clave para el crecimiento futuro. En lugar de crear una campaña de marketing que apunte a todos los clientes nuevos, Moreno cree que hay muchas posibilidades de convertir a los ciclistas ocasionales en miembros. Ella señala que los ciclistas ocasionales ya conocen el programa de Cyclistic y han elegido a Cyclistic para sus necesidades de movilidad.

Moreno estableció una meta clara: Diseñar estrategias de marketing orientadas a convertir a los ciclistas ocasionales en miembros anuales. Sin embargo, para hacer eso, el equipo de analistas de marketing necesita entender mejor cómo difieren los miembros anuales y los ciclistas ocasionales, por qué los ciclistas ocasionales comprarían una membresía y cómo los medios digitales podrían afectar sus tácticas de marketing. Moreno y su equipo están interesados en analizar los datos históricos de viajes en bicicleta de Cyclistic para identificar tendencias.

Pasos a seguir
En este proayecto utilizaremos las seis etapas de analisis de datos:

●     Preguntar: En esta etapa se identifican las preguntas claves junto a los interesados.

●     Preparar: Reunir los datos, identificar como esta organizada y se determina la credibilidad de los datos.

●     Procesar: Se elige la herramienta de limpieza de los datos, se revisa por errores y se documentan todos los cambios realizados.

●     Analizar: Se organiza y se da formato a los datos, se realizan los calculos y se identifican las relaciones y tendencias.

●     Compartir: Usando los principios de pensamiento de diseño y la narracion basada en datos, se presentan los hallazgos con visualizaciones efectivas, asegurandose de responder la tarea empresarial.

●     Actuar: Se comparte la conclusion final y las recomendaciones.

ETAPA 01
Preguntar
Objetivo: Identificar los tipos de membresia y analizarlos para descubrir tendencias del uso del servicio para preparar una estrategia publicitaria que permita convertir a usuarios casuales en miembros anuales.

Intaeresados: Lily moreno quien es la directora de marketing y gerente, ademas de el equipo ejecutivo quienes deciden si aprueba el programa de marketing recomendado.

ETAPA 02
Preparar
Para este proyecto, usaremos los datos publicos del historial de viajes proporcionados por Motivate International Inc. Bajo esta licencia de libre uso, es la data completa de todos los viajes que realizaron los usuarios de esta empresa de bicicletas durante el periodo 08-2024 al 07-2024 y aunque no cuentan con vinculaciones de pagos ni forma de identificar clientes con nombre real, lo que impide confirmar si un mismo cliente realizo más de un viaje en un solo día, son apropiados, además respetan la privacidad de los usuarios de la empresa y permiten responder las preguntas de este caso practico bajo el nombre ficticio Cyclistic.

Los datos Incluyen

Id del viaje, duración, ubicación inicial, ubicación final y tipo de miembro que realizo el viaje

Todo separado por mes

ETAPA 03 y 04
Procesar y analizar
Debido a la gran cantidad de datos en esta base decidi no utilizar excel ya que puede ser inestable y algo lento al manejar demasiados datos. podria haber utilizado SQL para la limpieza y el analisis de los datos pero me incline por la version de escritorio de Rstudio debido a que queria hacerlo todo en un solo lugar sin necesidad de estar cambiando de herramientas

por lo que empezaremos preparando nuestro entorno de trabajo

Instalando las librerias necesarias de ser necesario
install.packages("tidyverse")
Nota: En la version de escritorio esto solo se hace una vez, ya que los paquetes quedan instalados y disponibles para todos los futuros proyectos y solo debemos cargarlos para utilizarlos.

Cargamos las librerias a utilizar
library(tidyverse)
Almacenamos los datos de los archivos .csv en vectores para su uso en R
data01 <- read.csv("202308data.csv")
data02 <- read.csv("202309data.csv")
data03 <- read.csv("202310data.csv")
data04 <- read.csv("202311data.csv")
data05 <- read.csv("202312data.csv")
data06 <- read.csv("202401data.csv")
data07 <- read.csv("202402data.csv")
data08 <- read.csv("202403data.csv")
data09 <- read.csv("202404data.csv")
data10 <- read.csv("202405data.csv")
data11 <- read.csv("202406data.csv")
data12 <- read.csv("202407data.csv")
Nota: Los archivos descargados fueron renombrados para mejor legibilidad y fueron ubicados en el directorio principal del proyecto para evitar problemas de ruta en los archivos.

Ahora verificamos que la estructura de todos los vectores sean iguales.
glimpse(data01)
## Rows: 771,693
## Columns: 13
## $ ride_id            <chr> "903C30C2D810A53B", "F2FB18A98E110A2B", "D0DEC7C94E…
## $ rideable_type      <chr> "electric_bike", "electric_bike", "electric_bike", …
## $ started_at         <chr> "2023-08-19 15:41:53", "2023-08-18 15:30:18", "2023…
## $ ended_at           <chr> "2023-08-19 15:53:36", "2023-08-18 15:45:25", "2023…
## $ start_station_name <chr> "LaSalle St & Illinois St", "Clark St & Randolph St…
## $ start_station_id   <chr> "13430", "TA1305000030", "TA1305000030", "KA1504000…
## $ end_station_name   <chr> "Clark St & Elm St", "", "", "", "", "", "", "", ""…
## $ end_station_id     <chr> "TA1307000039", "", "", "", "", "", "", "", "", "",…
## $ start_lat          <dbl> 41.89072, 41.88451, 41.88498, 41.90310, 41.88555, 4…
## $ start_lng          <dbl> -87.63148, -87.63155, -87.63079, -87.63467, -87.632…
## $ end_lat            <dbl> 41.90297, 41.93000, 41.91000, 41.90000, 41.89000, 4…
## $ end_lng            <dbl> -87.63128, -87.64000, -87.63000, -87.62000, -87.680…
## $ member_casual      <chr> "member", "member", "member", "member", "member", "…
glimpse(data02)
## Rows: 666,371
## Columns: 13
## $ ride_id            <chr> "011C1903BF4E2E28", "87DB80E048A1BF9F", "7C2EB7AF66…
## $ rideable_type      <chr> "classic_bike", "classic_bike", "electric_bike", "c…
## $ started_at         <chr> "2023-09-23 00:27:50", "2023-09-02 09:26:43", "2023…
## $ ended_at           <chr> "2023-09-23 00:33:27", "2023-09-02 09:38:19", "2023…
## $ start_station_name <chr> "Halsted St & Wrightwood Ave", "Clark St & Drummond…
## $ start_station_id   <chr> "TA1309000061", "TA1307000142", "SL-010", "TA130700…
## $ end_station_name   <chr> "Sheffield Ave & Wellington Ave", "Racine Ave & Ful…
## $ end_station_id     <chr> "TA1307000052", "TA1306000026", "13304", "TA1308000…
## $ start_lat          <dbl> 41.92914, 41.93125, 41.87506, 41.93125, 41.92914, 4…
## $ start_lng          <dbl> -87.64908, -87.64434, -87.63314, -87.64434, -87.649…
## $ end_lat            <dbl> 41.93625, 41.92557, 41.86127, 41.93974, 41.92557, 4…
## $ end_lng            <dbl> -87.65266, -87.65842, -87.65663, -87.65887, -87.658…
## $ member_casual      <chr> "member", "member", "member", "member", "member", "…
glimpse(data03)
## Rows: 537,113
## Columns: 13
## $ ride_id            <chr> "4449097279F8BBE7", "9CF060543CA7B439", "667F21F4D6…
## $ rideable_type      <chr> "classic_bike", "electric_bike", "electric_bike", "…
## $ started_at         <chr> "2023-10-08 10:36:26", "2023-10-11 17:23:59", "2023…
## $ ended_at           <chr> "2023-10-08 10:49:19", "2023-10-11 17:36:08", "2023…
## $ start_station_name <chr> "Orleans St & Chestnut St (NEXT Apts)", "Desplaines…
## $ start_station_id   <chr> "620", "TA1306000003", "620", "TA1306000003", "TA13…
## $ end_station_name   <chr> "Sheffield Ave & Webster Ave", "Sheffield Ave & Web…
## $ end_station_id     <chr> "TA1309000033", "TA1309000033", "TA1307000111", "TA…
## $ start_lat          <dbl> 41.89820, 41.88864, 41.89807, 41.88872, 41.88872, 4…
## $ start_lng          <dbl> -87.63754, -87.64441, -87.63751, -87.64445, -87.644…
## $ end_lat            <dbl> 41.92154, 41.92154, 41.88584, 41.88584, 41.88584, 4…
## $ end_lng            <dbl> -87.65382, -87.65382, -87.63550, -87.63550, -87.635…
## $ member_casual      <chr> "member", "member", "member", "member", "member", "…
glimpse(data04)
## Rows: 362,518
## Columns: 13
## $ ride_id            <chr> "4EAD8F1AD547356B", "6322270563BF5470", "B37BDE091E…
## $ rideable_type      <chr> "electric_bike", "electric_bike", "electric_bike", …
## $ started_at         <chr> "2023-11-30 21:50:05", "2023-11-03 09:44:02", "2023…
## $ ended_at           <chr> "2023-11-30 22:13:27", "2023-11-03 10:17:15", "2023…
## $ start_station_name <chr> "Millennium Park", "Broadway & Sheridan Rd", "State…
## $ start_station_id   <chr> "13008", "13323", "TA1307000061", "TA1308000001", "…
## $ end_station_name   <chr> "Pine Grove Ave & Waveland Ave", "Broadway & Sherid…
## $ end_station_id     <chr> "TA1307000150", "13323", "TA1307000061", "TA1308000…
## $ start_lat          <dbl> 41.88110, 41.95287, 41.89753, 41.92628, 41.92628, 4…
## $ start_lng          <dbl> -87.62408, -87.65003, -87.62869, -87.63083, -87.630…
## $ end_lat            <dbl> 41.94947, 41.95283, 41.89745, 41.92628, 41.92628, 4…
## $ end_lng            <dbl> -87.64645, -87.64999, -87.62872, -87.63083, -87.630…
## $ member_casual      <chr> "member", "member", "member", "member", "member", "…
glimpse(data05)
## Rows: 224,073
## Columns: 13
## $ ride_id            <chr> "C9BD54F578F57246", "CDBD92F067FA620E", "ABC0858E52…
## $ rideable_type      <chr> "electric_bike", "electric_bike", "electric_bike", …
## $ started_at         <chr> "2023-12-02 18:44:01", "2023-12-02 18:48:19", "2023…
## $ ended_at           <chr> "2023-12-02 18:47:51", "2023-12-02 18:54:48", "2023…
## $ start_station_name <chr> "", "", "", "", "", "", "", "", "", "", "", "", "",…
## $ start_station_id   <chr> "", "", "", "", "", "", "", "", "", "", "", "", "",…
## $ end_station_name   <chr> "", "", "", "", "", "", "", "", "", "", "", "", "",…
## $ end_station_id     <chr> "", "", "", "", "", "", "", "", "", "", "", "", "",…
## $ start_lat          <dbl> 41.92, 41.92, 41.89, 41.95, 41.92, 41.91, 41.99, 42…
## $ start_lng          <dbl> -87.66, -87.66, -87.62, -87.65, -87.64, -87.63, -87…
## $ end_lat            <dbl> 41.92, 41.89, 41.90, 41.94, 41.93, 41.88, 42.00, 41…
## $ end_lng            <dbl> -87.66, -87.64, -87.64, -87.65, -87.64, -87.65, -87…
## $ member_casual      <chr> "member", "member", "member", "member", "member", "…
glimpse(data06)
## Rows: 144,873
## Columns: 13
## $ ride_id            <chr> "C1D650626C8C899A", "EECD38BDB25BFCB0", "F4A9CE7806…
## $ rideable_type      <chr> "electric_bike", "electric_bike", "electric_bike", …
## $ started_at         <chr> "2024-01-12 15:30:27", "2024-01-08 15:45:46", "2024…
## $ ended_at           <chr> "2024-01-12 15:37:59", "2024-01-08 15:52:59", "2024…
## $ start_station_name <chr> "Wells St & Elm St", "Wells St & Elm St", "Wells St…
## $ start_station_id   <chr> "KA1504000135", "KA1504000135", "KA1504000135", "TA…
## $ end_station_name   <chr> "Kingsbury St & Kinzie St", "Kingsbury St & Kinzie …
## $ end_station_id     <chr> "KA1503000043", "KA1503000043", "KA1503000043", "13…
## $ start_lat          <dbl> 41.90327, 41.90294, 41.90295, 41.88430, 41.94880, 4…
## $ start_lng          <dbl> -87.63474, -87.63444, -87.63447, -87.63396, -87.675…
## $ end_lat            <dbl> 41.88918, 41.88918, 41.88918, 41.92182, 41.88918, 4…
## $ end_lng            <dbl> -87.63851, -87.63851, -87.63851, -87.64414, -87.638…
## $ member_casual      <chr> "member", "member", "member", "member", "member", "…
glimpse(data07)
## Rows: 223,164
## Columns: 13
## $ ride_id            <chr> "FCB05EB1758F85E8", "7FB986AD5D3DE9D6", "40CA13E15B…
## $ rideable_type      <chr> "classic_bike", "classic_bike", "electric_bike", "c…
## $ started_at         <chr> "2024-02-03 14:14:18", "2024-02-05 21:10:06", "2024…
## $ ended_at           <chr> "2024-02-03 14:21:00", "2024-02-05 21:15:44", "2024…
## $ start_station_name <chr> "Clark St & Newport St", "Michigan Ave & Washington…
## $ start_station_id   <chr> "632", "13001", "TA1309000029", "13235", "KA1503000…
## $ end_station_name   <chr> "Southport Ave & Waveland Ave", "Wabash Ave & Grand…
## $ end_station_id     <chr> "13235", "TA1307000117", "13243", "13229", "KA15030…
## $ start_lat          <dbl> 41.94454, 41.88398, 41.91760, 41.94815, 41.83078, 4…
## $ start_lng          <dbl> -87.65468, -87.62468, -87.68250, -87.66394, -87.632…
## $ end_lat            <dbl> 41.94815, 41.89147, 41.91262, 41.93948, 41.83846, 4…
## $ end_lng            <dbl> -87.66394, -87.62676, -87.68139, -87.66375, -87.635…
## $ member_casual      <chr> "member", "member", "member", "member", "casual", "…
glimpse(data08)
## Rows: 301,687
## Columns: 13
## $ ride_id            <chr> "64FBE3BAED5F29E6", "9991629435C5E20E", "E5C9FECD5B…
## $ rideable_type      <chr> "electric_bike", "electric_bike", "electric_bike", …
## $ started_at         <chr> "2024-03-05 18:33:11", "2024-03-06 17:15:14", "2024…
## $ ended_at           <chr> "2024-03-05 18:51:48", "2024-03-06 17:16:04", "2024…
## $ start_station_name <chr> "", "", "", "", "", "", "", "", "", "", "", "", "",…
## $ start_station_id   <chr> "", "", "", "", "", "", "", "", "", "", "", "", "",…
## $ end_station_name   <chr> "", "", "", "", "", "", "", "", "", "", "", "", "",…
## $ end_station_id     <chr> "", "", "", "", "", "", "", "", "", "", "", "", "",…
## $ start_lat          <dbl> 41.94, 41.91, 41.91, 41.90, 41.93, 41.93, 41.94, 41…
## $ start_lng          <dbl> -87.65, -87.64, -87.64, -87.63, -87.70, -87.70, -87…
## $ end_lat            <dbl> 41.96, 41.91, 41.92, 41.89, 41.93, 41.95, 41.95, 41…
## $ end_lng            <dbl> -87.65, -87.64, -87.64, -87.63, -87.72, -87.68, -87…
## $ member_casual      <chr> "member", "member", "member", "member", "member", "…
glimpse(data09)
## Rows: 415,025
## Columns: 13
## $ ride_id            <chr> "743252713F32516B", "BE90D33D2240C614", "D47BBDDE7C…
## $ rideable_type      <chr> "classic_bike", "electric_bike", "classic_bike", "c…
## $ started_at         <chr> "2024-04-22 19:08:21", "2024-04-11 06:19:24", "2024…
## $ ended_at           <chr> "2024-04-22 19:12:56", "2024-04-11 06:22:21", "2024…
## $ start_station_name <chr> "Aberdeen St & Jackson Blvd", "Aberdeen St & Jackso…
## $ start_station_id   <chr> "13157", "13157", "TA1307000107", "13157", "TA13070…
## $ end_station_name   <chr> "Desplaines St & Jackson Blvd", "Desplaines St & Ja…
## $ end_station_id     <chr> "15539", "15539", "13249", "15539", "TA1308000029",…
## $ start_lat          <dbl> 41.87773, 41.87772, 41.96167, 41.87773, 41.96161, 4…
## $ start_lng          <dbl> -87.65479, -87.65496, -87.65464, -87.65479, -87.654…
## $ end_lat            <dbl> 41.87812, 41.87812, 41.95606, 41.87812, 41.88683, 4…
## $ end_lng            <dbl> -87.64395, -87.64395, -87.66884, -87.64395, -87.622…
## $ member_casual      <chr> "member", "member", "member", "member", "member", "…
glimpse(data10)
## Rows: 609,493
## Columns: 13
## $ ride_id            <chr> "7D9F0CE9EC2A1297", "02EC47687411416F", "101370FB2D…
## $ rideable_type      <chr> "classic_bike", "classic_bike", "classic_bike", "el…
## $ started_at         <chr> "2024-05-25 15:52:42", "2024-05-14 15:11:51", "2024…
## $ ended_at           <chr> "2024-05-25 16:11:50", "2024-05-14 15:22:00", "2024…
## $ start_station_name <chr> "Streeter Dr & Grand Ave", "Sheridan Rd & Greenleaf…
## $ start_station_id   <chr> "13022", "KA1504000159", "13022", "13022", "KA15040…
## $ end_station_name   <chr> "Clark St & Elm St", "Sheridan Rd & Loyola Ave", "W…
## $ end_station_id     <chr> "TA1307000039", "RP-009", "TA1309000010", "TA130700…
## $ start_lat          <dbl> 41.89228, 42.01059, 41.89228, 41.89227, 41.90349, 4…
## $ start_lng          <dbl> -87.61204, -87.66241, -87.61204, -87.61195, -87.643…
## $ end_lat            <dbl> 41.90297, 42.00104, 41.87077, 41.93625, 41.90297, 4…
## $ end_lng            <dbl> -87.63128, -87.66120, -87.62573, -87.65266, -87.631…
## $ member_casual      <chr> "casual", "casual", "member", "member", "casual", "…
glimpse(data11)
## Rows: 710,721
## Columns: 13
## $ ride_id            <chr> "CDE6023BE6B11D2F", "462B48CD292B6A18", "9CFB6A858D…
## $ rideable_type      <chr> "electric_bike", "electric_bike", "electric_bike", …
## $ started_at         <chr> "2024-06-11 17:20:06.289", "2024-06-11 17:19:21.567…
## $ ended_at           <chr> "2024-06-11 17:21:39.464", "2024-06-11 17:19:36.377…
## $ start_station_name <chr> "", "", "", "", "", "", "", "", "", "", "", "", "",…
## $ start_station_id   <chr> "", "", "", "", "", "", "", "", "", "", "", "", "",…
## $ end_station_name   <chr> "", "", "", "", "", "", "", "", "", "", "", "", "",…
## $ end_station_id     <chr> "", "", "", "", "", "", "", "", "", "", "", "", "",…
## $ start_lat          <dbl> 41.89, 41.89, 41.93, 41.88, 41.94, 41.94, 41.94, 41…
## $ start_lng          <dbl> -87.65, -87.65, -87.65, -87.64, -87.64, -87.64, -87…
## $ end_lat            <dbl> 41.89000, 41.89000, 41.94000, 41.88000, 41.94000, 4…
## $ end_lng            <dbl> -87.65000, -87.65000, -87.65000, -87.64000, -87.640…
## $ member_casual      <chr> "casual", "casual", "casual", "casual", "casual", "…
glimpse(data12)
## Rows: 748,962
## Columns: 13
## $ ride_id            <chr> "2658E319B13141F9", "B2176315168A47CE", "C2A9D33DF7…
## $ rideable_type      <chr> "electric_bike", "electric_bike", "electric_bike", …
## $ started_at         <chr> "2024-07-11 08:15:14.784", "2024-07-11 15:45:07.851…
## $ ended_at           <chr> "2024-07-11 08:17:56.335", "2024-07-11 16:06:04.243…
## $ start_station_name <chr> "", "", "", "", "", "", "", "", "California Ave & M…
## $ start_station_id   <chr> "", "", "", "", "", "", "", "", "13084", "", "", ""…
## $ end_station_name   <chr> "", "", "", "", "", "", "", "", "California Ave & M…
## $ end_station_id     <chr> "", "", "", "", "", "", "", "", "13084", "", "", ""…
## $ start_lat          <dbl> 41.80000, 41.79000, 41.79000, 41.88000, 41.95000, 4…
## $ start_lng          <dbl> -87.59000, -87.60000, -87.59000, -87.64000, -87.640…
## $ end_lat            <dbl> 41.79000, 41.80000, 41.79000, 41.90000, 41.91000, 4…
## $ end_lng            <dbl> -87.59000, -87.59000, -87.60000, -87.67000, -87.620…
## $ member_casual      <chr> "casual", "casual", "casual", "casual", "casual", "…
Con esto ya podemos ver como estan conformados los datos y nos encontramos que las variables started_at y ended_at que estan en tipo caracter y deben convertirse a fecha para poder analizar correctamente la información pero antes vamos a unir todos los vectores en un solo conjunto de datos

Unimos Vectores en solo
DatosViajes <- bind_rows(data01,data02,data03,data04,data05,data06,data07,data08,data09,data10,data11,data12)
totaldatosiniciales <- dim(DatosViajes)
cat("Cantidad de filas del conjunto de datos:", totaldatosiniciales[1], "\n")
## Cantidad de filas del conjunto de datos: 5715693
cat("Cantidad de variables del conjunto de datos:", totaldatosiniciales[2], "\n") 
## Cantidad de variables del conjunto de datos: 13
lo que nos deja un conjunto de datos de 13 variables y 5.715.693 filas

colnames(DatosViajes)
##  [1] "ride_id"            "rideable_type"      "started_at"        
##  [4] "ended_at"           "start_station_name" "start_station_id"  
##  [7] "end_station_name"   "end_station_id"     "start_lat"         
## [10] "start_lng"          "end_lat"            "end_lng"           
## [13] "member_casual"
Renombre de columnas y datos al español para legibilidad del caso
# Cambiar nombres de columnas
DatosViajes <- DatosViajes %>%
  rename(
    id_viaje = ride_id,
    tipo_bicicleta = rideable_type,
    inicio_viaje = started_at,
    fin_viaje = ended_at,
    estacion_inicial = start_station_name,
    estacion_inicial_id = start_station_id,
    estacion_final = end_station_name,
    estacion_final_id = end_station_id,
    lat_inicial = start_lat,
    long_inicial = start_lng,
    lat_final = end_lat,
    long_final = end_lng,
    tipo_usuario = member_casual
  )
DatosViajes <- DatosViajes %>%
  mutate(tipo_usuario = case_when(
    tipo_usuario == "member" ~ "miembro",
    TRUE ~ tipo_usuario  # Mantener el valor original si no coincide
  ))
DatosViajes <- DatosViajes %>%
  mutate(tipo_bicicleta = case_when(
    tipo_bicicleta == "electric_bike" ~ "bici_electrica",
    tipo_bicicleta == "classic_bike" ~ "bici_clasica",
    tipo_bicicleta == "docked_bike" ~ "bici_compartida",
    TRUE ~ tipo_bicicleta  # Mantener el valor original si no coincide
  ))
Verificamos valores nulos
nulos_y_espacios_df <- DatosViajes %>%
  summarise_all(~ sum(is.na(.) | str_trim(.) == "")) %>%
  pivot_longer(cols = everything(), names_to = "Variables", values_to = "Nulos_o_Espacios")
print(nulos_y_espacios_df)
## # A tibble: 13 × 2
##    Variables           Nulos_o_Espacios
##    <chr>                          <int>
##  1 id_viaje                           0
##  2 tipo_bicicleta                     0
##  3 inicio_viaje                       0
##  4 fin_viaje                          0
##  5 estacion_inicial              947025
##  6 estacion_inicial_id           947025
##  7 estacion_final                989476
##  8 estacion_final_id             989476
##  9 lat_inicial                        0
## 10 long_inicial                       0
## 11 lat_final                       7756
## 12 long_final                      7756
## 13 tipo_usuario                       0
str_trim(.) elimina los espacios en blanco al inicio y al final de cada cadena.

str_trim(.) == "" verifica si, después de eliminar los espacios, la cadena es vacía.

is.na(.) | str_trim(.) == "" verifica si el valor es NA o si es una cadena de caracteres que consiste únicamente en espacios en blanco.

summarise_all(~ sum(...)) cuenta cuántos valores en cada columna cumplen cualquiera de las dos condiciones.

pivot_longer() organiza el resultado en un formato largo con una columna Columna que contiene los nombres de las columnas de DatosViajes y otra columna Nulos_o_Espacios que contiene el número de valores nulos o que son solo espacios.

Ahora podemos ver que hay muchos valores que solo contienen espacios o nulos tanto en nombres de estaciones como en latitudes y longitudes, pero a mi criterio esto no afecta el analisis final ya que aun conservamos la duracion de los viajes, los id unicos por viaje y el tipo de miembro, y si bien la representacion de los viajes geograficamente se vera ligeramente impedida no es algo que pueda afectar nuestro analisis por lo que vamos a conservar los datos.

Verificar que las variables no tengan datos equivocados o duplicados
Solo existen dos tipos de miembros y tres tipos de bicicletas disponibles. Ademas cada viaje debe ser unico y para esto vemos si tenemos duplicados en la variable ride_id

cat("Tipos de miembros:",unique(DatosViajes$tipo_usuario), "\n")
## Tipos de miembros: miembro casual
cat("Tipos de bicicletas:",unique(DatosViajes$tipo_bicicleta), "\n")
## Tipos de bicicletas: bici_electrica bici_clasica bici_compartida
n_duplicados <- sum(duplicated(DatosViajes$id_viaje))
cat("Número de duplicados:", n_duplicados, "\n")
## Número de duplicados: 211
duplicated() devuelve un vector lógico que indica si un elemento en la es duplicado (TRUE) o no (FALSE).

sum() cuenta el número de valores TRUE en ese vector, que corresponde al número de elementos duplicados.

Como podemos apreciar no existen valores inconsistentes en las variables pero tenemos valores duplicados en la columna de ride_id la cual solo deberia contener valores unicos asi que vamos a analizar por que esta sucediendo esto.

Duplicados <- DatosViajes %>% filter(duplicated(id_viaje)) #extraemos lo valores a otra tabla
glimpse(Duplicados)
## Rows: 211
## Columns: 13
## $ id_viaje            <chr> "3B5CE4D8B3EE6ED8", "60B4DDFF369931B2", "1D8856396…
## $ tipo_bicicleta      <chr> "bici_electrica", "bici_electrica", "bici_electric…
## $ inicio_viaje        <chr> "2024-05-31 23:50:04.153", "2024-05-31 23:51:07.39…
## $ fin_viaje           <chr> "2024-06-01 00:06:08.273", "2024-06-01 00:25:37.45…
## $ estacion_inicial    <chr> "", "", "California Ave & Milwaukee Ave", "Austin …
## $ estacion_inicial_id <chr> "", "", "13084", "16918", "TA1309000061", "639", "…
## $ estacion_final      <chr> "", "", "", "Austin Blvd & Madison St", "Orleans S…
## $ estacion_final_id   <chr> "", "", "", "16918", "620", "13059", "13050", "TA1…
## $ lat_inicial         <dbl> 41.98000, 41.88000, 41.92271, 41.88028, 41.92921, …
## $ long_inicial        <dbl> -87.67000, -87.65000, -87.69715, -87.77445, -87.64…
## $ lat_final           <dbl> 41.98000, 41.97000, 41.93000, 41.88028, 41.89820, …
## $ long_final          <dbl> -87.67000, -87.68000, -87.72000, -87.77445, -87.63…
## $ tipo_usuario        <chr> "casual", "casual", "casual", "casual", "miembro",…
Viendo los datos tenemos una hipotesis de por que sucede esto.
Los datos iniciales estaban divididos por mes y estos viajes tienen fecha de inicio el 31 de mayo y finalizan el 01 de junio por lo que esta podria ser la razon de estar duplicados asi que vamos a confirmar esta hipotesis buscando y contando los datos de nuestro nuevo conjunto duplicados en la data separada por mes.

en_mayo <- sum(Duplicados$id_viaje %in% data10$ride_id) #siendo data10 la carga de datos del 2024-05
en_junio <- sum(Duplicados$id_viaje %in% data11$ride_id) #siendo data10 la carga de datos del 2024-06
# Imprimir los resultados
cat("Número de duplicados encontrados anteriormente:", n_duplicados, "\n")
## Número de duplicados encontrados anteriormente: 211
cat("Conteo de duplicados en mayo:", en_mayo, "\n")
## Conteo de duplicados en mayo: 211
cat("Conteo de duplicados en junio:", en_junio, "\n")
## Conteo de duplicados en junio: 211
Como vemos confirmamos que los id de esos viajes se encuentran tanto en mayo como en junio por lo que ahora podemos eliminar los duplicados conociendo cual fue su causa. y volvemos a verificar que se realizo correctamente

DatosViajes <- DatosViajes %>% distinct(id_viaje, .keep_all = TRUE) #conserva solo los datos unicos
n_duplicados2 <- sum(duplicated(DatosViajes$id_viaje))
cat("Actualización de duplicados:", n_duplicados2, "\n")
## Actualización de duplicados: 0
distinct() es una funcion del dplyr que selecciona los datos unicos de un conjunto

Limpieza de entorno de trabajo
Ademas podemos eliminar algunos de los conjuntos temporales para limpiar un poco nuestro entorno de trabajo

remove(data01,data02,data03,data04,data05,data06,data07,data08,data09,data10,data11,data12,Duplicados,en_junio,en_mayo,n_duplicados2) 
Calculamos la duración de los viajes usando las variables started_at y ended_at
Pero antes debido a que estan como tipo character no se pueden realizar operaciones con estas columnas por lo que vamos a convertirlas a fechas con horas usando el comando ymd_hms() de la libreria lubridate()

DatosViajes$inicio_viaje <- ymd_hms(DatosViajes$inicio_viaje)
DatosViajes$fin_viaje <- ymd_hms(DatosViajes$fin_viaje)
ymd_hms() es una función de lubridate que convierte una cadena de caracteres en un objeto de fecha y hora.

ahora si calculamos la duración de los viajes y verificamos la estructura de nuestros datos

#para evitar que los valores sean mostrados como notacion cientifica usamos el siguiente comando y asi mantener una mejor legibilidad
options(scipen=999)
DatosViajes$duracion_viaje <- round(as.numeric(difftime(DatosViajes$fin_viaje, DatosViajes$inicio_viaje, units = "mins")),2)
tibble(DatosViajes$id_viaje,DatosViajes$duracion_viaje)
DatosViajes$id_viaje
<chr>
DatosViajes$duracion_viaje
<dbl>
903C30C2D810A53B	11.72
F2FB18A98E110A2B	15.12
D0DEC7C94E4663DA	12.48
E0DDDC5F84747ED9	9.45
7797A4874BA260CA	20.90
DF4DE734EBC4DF66	27.58
EE60FB066E69AFAC	12.40
A115DA6AA13DE5EF	6.60
86DBB19374245893	10.05
2905CBC8B8EE392C	5.95
...
1-10 of 10,000 rows
difftime() calcula la diferencia entre dos fechas y horas.

El argumento units = "mins" especifica que quieres la diferencia en minutos.

round(valor,2) redondea el valor especificado a 2 decimales o cualquier otra cantidad especificada

as.numeric da formato como numero

Tambien podemos extraer los valores de la fecha por separado para nuestro analisis posterior, como solo nos interesa el inicio del viaje esa sera la fecha que usaremos de referencia para la creacion de los datos

DatosViajes$fecha <- as.Date(DatosViajes$inicio_viaje)
DatosViajes$mes <- format(as.Date(DatosViajes$fecha),"%B") 
DatosViajes$dia <- format(as.Date(DatosViajes$fecha), "%d")
DatosViajes$ano <- format(as.Date(DatosViajes$fecha), "%Y")
DatosViajes$diaDeLaSemana <- weekdays(DatosViajes$fecha)
DatosViajes$hora <- format(DatosViajes$inicio_viaje, "%H")
DatosViajes <- DatosViajes %>%
  arrange(inicio_viaje)
tibble(DatosViajes$id_viaje,DatosViajes$fecha,DatosViajes$mes,DatosViajes$dia,DatosViajes$ano,DatosViajes$diaDeLaSemana)
DatosViajes$id_viaje
<chr>
DatosViajes$fecha
<date>
DatosViajes$mes
<chr>
DatosViajes$dia
<chr>
DatosViajes$ano
<chr>
E1212DA176FD5BAF	2023-08-01	August	01	2023	
4F9E4987AC3DF9D1	2023-08-01	August	01	2023	
27441012AD09BF4C	2023-08-01	August	01	2023	
608E6D41D97C3D3A	2023-08-01	August	01	2023	
8A79B716BCB53DE8	2023-08-01	August	01	2023	
781FAAE046AA028A	2023-08-01	August	01	2023	
C8C5EC66D2FE7BEE	2023-08-01	August	01	2023	
47CBE532DF4D64C8	2023-08-01	August	01	2023	
299738C65CE2119E	2023-08-01	August	01	2023	
9099226E4C7622CC	2023-08-01	August	01	2023	
...
1-10 of 10,000 rows | 1-5 of 6 columns
as.Date() da formato como fecha

format(valor,criterio) dependiendo del criterio separa una parte del dato ingresado.

weekdays regresa el dia de la semana en texto segun una fecha

Renombrar dias y meses
DatosViajes <- DatosViajes %>%
  mutate(mes = case_when(
    mes == "January" ~ "Enero",
    mes == "February" ~ "Febrero",
    mes == "March" ~ "Marzo",
    mes == "April" ~ "Abril",
    mes == "May" ~ "Mayo",
    mes == "June" ~ "Junio",
    mes == "July" ~ "Julio",
    mes == "August" ~ "Agosto",
    mes == "September" ~ "Septiembre",
    mes == "October" ~ "Octubre",
    mes == "November" ~ "Noviembre",
    mes == "December" ~ "Diciembre",
    TRUE ~ mes  # Mantener el valor original si no coincide
  ))

DatosViajes <- DatosViajes %>%
  mutate(diaDeLaSemana = case_when(
    diaDeLaSemana == "Sunday" ~ "Domingo",
    diaDeLaSemana == "Monday" ~ "Lunes",
    diaDeLaSemana == "Tuesday" ~ "Martes",
    diaDeLaSemana == "Wednesday" ~ "Miercoles",
    diaDeLaSemana == "Thursday" ~ "Jueves",
    diaDeLaSemana == "Friday" ~ "Viernes",
    diaDeLaSemana == "Saturday" ~ "Sabado",
        TRUE ~ diaDeLaSemana  # Mantener el valor original si no coincide
  ))
mutate() crea, modifica o elimina datos

case_when condicional, solo actua cuando se cumple la condicion.

Duraciones de viajes iguales o menores a cero
Ahora que tenemos la duración vamos a confirmar que todas las duraciones sean superiones a cero

conteocero <- sum(DatosViajes$duracion_viaje <= 0)
cat("Conteo de duraciones menores o iguales a cero:", conteocero, "\n")
## Conteo de duraciones menores o iguales a cero: 1545
Existen casos por lo que vamos a verificar esto.

menoscero <- DatosViajes %>% filter(DatosViajes$duracion_viaje <= 0)
tibble(menoscero$id_viaje,menoscero$inicio_viaje,menoscero$fin_viaje,menoscero$duracion_viaje)
menoscero$id_viaje
<chr>
menoscero$inicio_viaje
<dttm>
menoscero$fin_viaje
<dttm>
menoscero$duracion_viaje
<dbl>
682DECAD48CF1025	2023-08-01 08:07:27.000	2023-08-01 08:07:27.000	0.00
BC98D582B6099319	2023-08-01 08:32:03.000	2023-08-01 08:32:03.000	0.00
83E696587B612CA5	2023-08-01 16:26:15.000	2023-08-01 16:26:15.000	0.00
6D389E0C7E908903	2023-08-01 17:53:42.000	2023-08-01 17:53:42.000	0.00
8ACB1040FBDA50E6	2023-08-01 20:26:10.000	2023-08-01 20:26:10.000	0.00
D4EF0A818612867B	2023-08-01 20:28:34.000	2023-08-01 20:28:34.000	0.00
AD4B65B064F84F78	2023-08-01 21:23:10.000	2023-08-01 21:20:17.000	-2.88
A106F6C802A7DD4A	2023-08-01 21:29:30.000	2023-08-01 21:24:54.000	-4.60
08DF79E869E504F1	2023-08-02 09:33:30.000	2023-08-02 09:33:30.000	0.00
0AB81B55174ACB4A	2023-08-02 16:36:34.000	2023-08-02 16:36:34.000	0.00
...
1-10 of 1,545 rows
La función filter() de dplyr selecciona solo las filas que cumplen con la condición especificada.

Vemos como efectivamente los tiempos de llegada son iguales o inferiores a los de partida. en algunos casos por pocos segundos, en otros por multiples minutos, y aunque los datos de longitud y latitud muestran cambios no podemos consultar para verificar si existe un error, en este caso simplemente vamos a eliminarlos y aprovechar de eliminar nuestra tabla temporal

DatosViajes <- DatosViajes %>% filter(duracion_viaje > 0)
remove(menoscero)
Viajes de más de 24 horas
Tambien podemos verificar los viajes superiores a 24 horas

viajes_largos <- DatosViajes %>%
    filter(duracion_viaje > 1440) #el tiempo esta en minutos 1440mins / 60 = 24 horas
ViajesLargos <- nrow(viajes_largos)
cat("Numero de viajes de más de 24 horas:",ViajesLargos, "\n")
## Numero de viajes de más de 24 horas: 7958
glimpse(viajes_largos)
## Rows: 7,958
## Columns: 20
## $ id_viaje            <chr> "A4AC38FA8E20177B", "660A642D881977C1", "69F875950…
## $ tipo_bicicleta      <chr> "bici_clasica", "bici_clasica", "bici_clasica", "b…
## $ inicio_viaje        <dttm> 2023-08-01 00:29:59, 2023-08-01 00:40:37, 2023-08…
## $ fin_viaje           <dttm> 2023-08-02 01:29:50, 2023-08-02 01:40:30, 2023-08…
## $ estacion_inicial    <chr> "Michigan Ave & 8th St", "Michigan Ave & 8th St", …
## $ estacion_inicial_id <chr> "623", "623", "KA1504000114", "E014", "KA150400017…
## $ estacion_final      <chr> "", "", "", "", "", "", "", "", "", "", "", "", ""…
## $ estacion_final_id   <chr> "", "", "", "", "", "", "", "", "", "", "", "", ""…
## $ lat_inicial         <dbl> 41.87277, 41.87277, 41.89547, 42.06485, 42.00797, …
## $ long_inicial        <dbl> -87.62398, -87.62398, -87.70613, -87.71530, -87.66…
## $ lat_final           <dbl> NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA…
## $ long_final          <dbl> NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA…
## $ tipo_usuario        <chr> "casual", "casual", "casual", "casual", "casual", …
## $ duracion_viaje      <dbl> 1499.85, 1499.88, 1499.63, 1499.65, 1499.65, 1499.…
## $ fecha               <date> 2023-08-01, 2023-08-01, 2023-08-01, 2023-08-01, 2…
## $ mes                 <chr> "Agosto", "Agosto", "Agosto", "Agosto", "Agosto", …
## $ dia                 <chr> "01", "01", "01", "01", "01", "01", "01", "01", "0…
## $ ano                 <chr> "2023", "2023", "2023", "2023", "2023", "2023", "2…
## $ diaDeLaSemana       <chr> "Martes", "Martes", "Martes", "Martes", "Martes", …
## $ hora                <chr> "00", "00", "00", "01", "07", "08", "09", "09", "0…
nrow() cuenta el total de filas de un conjunto de datos
Se aprecian muchos NA y vacios en este conjunto de datos por lo que vamos a contarlos

nulos_y_espacioslargos_df <- viajes_largos %>%
    summarise_all(~ sum(is.na(.) | str_trim(.) == "")) %>%
    pivot_longer(cols = everything(), names_to = "Variables", values_to = "Nulos_o_Espacios")
print(nulos_y_espacioslargos_df)
## # A tibble: 20 × 2
##    Variables           Nulos_o_Espacios
##    <chr>                          <int>
##  1 id_viaje                           0
##  2 tipo_bicicleta                     0
##  3 inicio_viaje                       0
##  4 fin_viaje                          0
##  5 estacion_inicial                   0
##  6 estacion_inicial_id                0
##  7 estacion_final                  7804
##  8 estacion_final_id               7804
##  9 lat_inicial                        0
## 10 long_inicial                       0
## 11 lat_final                       7559
## 12 long_final                      7559
## 13 tipo_usuario                       0
## 14 duracion_viaje                     0
## 15 fecha                              0
## 16 mes                                0
## 17 dia                                0
## 18 ano                                0
## 19 diaDeLaSemana                      0
## 20 hora                               0
Anteriormente detectamos 7756 valores nulos en end_lat sobre todo el conjunto de viajes, ahora podemos apreciar que 7559 pertenecen a este segmento de datos, cuando el conjunto de referencia es de 7958 supone una cantidad importante de valores. Esto podria ser resultado de varios factores como la baja de bicicletas por parte de la compañia, hurto, o errores del sistema, aunque igual que anteriormente no tenemos forma de verificarlo en esta instancia por lo que eliminaremos los viajes de mas de 24 horas,
es posible que existan mas casos en segmentos menores como de 12 a 24 horas o menos en algunos casos, pero no son un factor que pueda alterar en gran medida debido al gran volumen de datos disponibles.

DatosViajes <- DatosViajes %>% filter(duracion_viaje <= 1440)
Resumen de viajes
#Comparacion tipo de miembro
DatosViajes %>%
    group_by(tipo_usuario) %>%
    summarise(DuracionPromedio = mean(duracion_viaje), DuracionMaxima = max(duracion_viaje), DuracionMinima = min(duracion_viaje))
tipo_usuario
<chr>
DuracionPromedio
<dbl>
DuracionMaxima
<dbl>
DuracionMinima
<dbl>
casual	21.26364	1439.92	0.01
miembro	12.31283	1439.92	0.01
2 rows
group_by() Agrupa una o mas variables

summarise() hace un resumen de cada grupo en unsa sola columna

mean() calcula el promedio de una cantidad de datos, Suma todos los valores / cantidad de valores

Dado los datos los tiempos promedios de los usuarios casuales son mayores a los miembros.

DatosViajes$diaDeLaSemana <- ordered(DatosViajes$diaDeLaSemana, levels=c("Domingo", "Lunes", "Martes", "Miercoles", "Jueves", "Viernes", "Sabado"))

Viajespordia <- DatosViajes %>%
    group_by(tipo_usuario, diaDeLaSemana) %>%
    summarise(Num_de_viajes = n(), DuracionPromedio = mean(duracion_viaje),.groups = "drop") %>%
    arrange(tipo_usuario, diaDeLaSemana)
print(Viajespordia)
## # A tibble: 14 × 4
##    tipo_usuario diaDeLaSemana Num_de_viajes DuracionPromedio
##    <chr>        <ord>                 <int>            <dbl>
##  1 casual       Domingo              339284             24.7
##  2 casual       Lunes                225171             20.6
##  3 casual       Martes               234166             18.5
##  4 casual       Miercoles            265422             18.8
##  5 casual       Jueves               254844             18.5
##  6 casual       Viernes              298956             20.7
##  7 casual       Sabado               413718             24.1
##  8 miembro      Domingo              408322             13.7
##  9 miembro      Lunes                503573             11.7
## 10 miembro      Martes               582812             11.8
## 11 miembro      Miercoles            615591             12.0
## 12 miembro      Jueves               576120             11.8
## 13 miembro      Viernes              517220             12.1
## 14 miembro      Sabado               470780             13.7
ordered() se utiliza para crear un factor ordenado. Un factor ordenado es una variable cuyos niveles tienen un orden especifico
levels=c() se usa para especificar el orden de los niveles
.groups = "drop" es el critero quie se usa para separar los grupos que se hiceron antes, no es estrictamente necesario pero es una buena practica
arrange() se utiliza para ordenar las filas de una data frame segun los valores de una o mas columnas
Tambien podemos apreciar una tendencia a mas cantidad de viajes hacia los fines de semana para usuarios casuales y mayor cantidad de viajes durante la semana para los miembros.
lo cual podria ser explicado que el usuario casual busca un uso mas recreativo mientras que los miembros utilizan el servicio como movilizacion diaria a sus trabajos, de alli tambien la diferencia en tiempos de viaje entre los tipos de usuarios.

DatosViajes$mes <- ordered(DatosViajes$mes, levels=c("Agosto", "Septiembre", "Octubre", "Noviembre","Diciembre","Enero", "Febrero", "Marzo", "Abril", "Mayo", "Junio", "Julio"))

Viajespormes <- DatosViajes %>%
    group_by(tipo_usuario, mes) %>%
    summarise(Num_de_viajes = n(), DuracionPromedio = mean(duracion_viaje),.groups = "drop") %>%
    arrange(tipo_usuario, mes)
print(Viajespormes)
## # A tibble: 24 × 4
##    tipo_usuario mes        Num_de_viajes DuracionPromedio
##    <chr>        <ord>              <int>            <dbl>
##  1 casual       Agosto            310040             21.9
##  2 casual       Septiembre        260819             21.2
##  3 casual       Octubre           176540             19.0
##  4 casual       Noviembre          98072             16.1
##  5 casual       Diciembre          51478             14.7
##  6 casual       Enero              24320             13.7
##  7 casual       Febrero            46931             18.1
##  8 casual       Marzo              82200             19.6
##  9 casual       Abril             131337             21.4
## 10 casual       Mayo              230234             23.4
## # ℹ 14 more rows
Con estos datos podemos apreciar que existen meses una tendencia al uso del servicio en meses mas calidos

ViajesPorHoraUsuario <- DatosViajes %>%
  group_by(hora, tipo_usuario) %>%
  summarise(Num_de_viajes = n(),.groups = "drop") %>%
  arrange(as.numeric(hora), tipo_usuario)  # Ordena las horas numéricamente y por tipo de usuario
con esto tenemos un resumen de los horarios preferidos por cada segmento

Registro de latitudes y longitudes
para uso posterior vamos a almacenar estos valores

NuevoConjunto <- DatosViajes %>%
  select(id_viaje, lat_inicial, lat_final, long_inicial, long_final, tipo_usuario)
#### como no puede haber valores nulos o vacios en las latitudes y longitudes en este conjunto si vamos a eliminar esos valores
NuevoConjunto <- NuevoConjunto %>%
  filter(
    !is.na(lat_inicial) & lat_inicial != "" &
    !is.na(lat_final) & lat_final != "" &
    !is.na(long_inicial) & long_inicial != "" &
    !is.na(long_final) & long_final != ""
  )
Conteo de valores eliminados
totaldatosfinales <-  totaldatosiniciales[1] - n_duplicados - conteocero - ViajesLargos
cat("Iniciamos el analisis con:",totaldatosiniciales[1], "\n")
## Iniciamos el analisis con: 5715693
cat("Eliminamos: ",n_duplicados," datos duplicados \n")
## Eliminamos:  211  datos duplicados
cat("Eliminamos: ",conteocero," viajes con duración igual o menos a cero \n")
## Eliminamos:  1545  viajes con duración igual o menos a cero
cat("Eliminamos: ",ViajesLargos, "Viajes de mas de 24 horas de duración \n")
## Eliminamos:  7958 Viajes de mas de 24 horas de duración
cat("Total de datos para el analisis: ",totaldatosfinales)
## Total de datos para el analisis:  5705979
ETAPA 05
Compartir
Los resultados obtenidos seran representados visualmente en esta etapa.

Iniciamos haciendo referencia al conjunto de datos utilizado el cual se compone por el periodo de 12 meses de actividades de la empresa Ciclystic entre Agosto del 2023 y Julio del 2024

ggplot(DatosViajes, aes(x = mes)) + #crea nuestro plano cartesiano basado en la variable 
  geom_bar(aes(y = after_stat(count)), fill = "skyblue", color = "black") + #define el grafico como barras y cuenta cuantas veces aparece la variable, colorea el relleno y crea un outline
  geom_text( #se encarga de agregar el texto sobre las barras
    aes(label = after_stat(count)), 
    stat = "count", 
    vjust = -0.5,  # Ajusta la posición vertical de las etiquetas
    color = "black",
    size = 3
  ) +
  labs( #crea los tutilos del grafico
    title="Viajes por mes - Cyclistic",
    subtitle = "Periodo Agosto 2023 - Julio 2024",
    x = "Mes",
    y = "Número de Viajes",
    caption = "Base de datos Cyclistic - Empresa Ficticia"
  ) +
  theme_minimal() +
  theme(axis.text.x = element_text(angle = 45, hjust = 1)) #gira la leyenda inferior


El grafico anterior solo considera la totalidad de viajes hechos por mes sin discrimirar entre tipos de usuarios, por lo que podemos apreciar la tendencia de mayor uso del servicio en ciertos meses. esto es posiblemente debido a cambios en las estaciones y la temperatura exterior durante el año.

 ggplot(Viajespormes, aes(x = mes, y = Num_de_viajes, fill = tipo_usuario)) +
  geom_bar(stat = "identity", position = "dodge", color = "black") + # utiliza identity para que ggplot use directamente el valor de numero de viajes
  geom_text(
    aes(label = Num_de_viajes), 
    position = position_dodge2(width = 0.9),  # Ajusta la posición horizontal de las etiquetas
    vjust = 0.4,  # Ajusta la posición vertical de las etiquetas
    hjust = -0.1, # ajusta el texto para estar sobre la barra
    angle = 90,    # Gira el texto a 90 grados para que sea vertical
    color = "black",
    size = 3
  ) +
  labs(
    title = "Viajes por Mes y Tipo de Usuario - Cyclistic",
    subtitle = "Periodo Agosto 2023 - Julio 2024",
    x = "Mes",
    y = "Número de Viajes",
    fill = "Tipo de Usuario",
    caption = "Base de datos Cyclistic - Empresa Ficticia"
  ) +
  theme_minimal() +
  theme(
    axis.text.x = element_text(angle = 45, hjust = 1),  # Mantén las etiquetas del eje x en ángulo
    legend.position = "bottom" #cambia la leyenda para estar debajo de las barras en lugar del lado
  ) +
  scale_fill_manual(values = c(
    "miembro" = "white",
    "casual" = "skyblue"
      )) +  # Reemplaza con los colores y tipos de usuario adecuados
  coord_cartesian(ylim = c(0, max(Viajespormes$Num_de_viajes) * 1.3))  # Extiende el rango del eje y para que no se corte el texto


Aqui podemos apreciar que la mayoria de viajes son realizados por miembros durante todo el año.

ggplot(data = Viajespordia, aes(x = diaDeLaSemana, y = Num_de_viajes, fill = tipo_usuario)) +
  geom_bar(stat = "identity", position = "dodge", color = "black") + 
  geom_text(
    aes(label = Num_de_viajes), 
    position = position_dodge(width = 0.9),  # Ajusta la posición horizontal de las etiquetas
    vjust = -0.4,  # Ajusta la posición vertical de las etiquetas
    color = "black",
    size = 2.5
  ) +
  labs(
    title = "Viajes por Día - Cyclistic",
    subtitle = "Por Tipo de Usuario",
    x = "Día de la Semana",
    y = "Número de Viajes",
    fill = "Tipo de Usuario",
    caption = "Base de datos Cyclistic - Empresa Ficticia"
  ) +
  theme_minimal() +
  theme(
    legend.position = "bottom"
  ) +
  scale_fill_manual(values = c(
    "miembro" = "white",
    "casual" = "skyblue"
  )) # Ajusta los colores según tus categorías


Como se ve en el grafico los usuarios casuales realizan mas viajes los fines de semana y los miembros mas viajes durante la semana. Indicando la posibilidad de que los miembros usen principalmente el servicio para llegar a sus trabajos y los casuales lo usan de manera mas recreacional. pero aun necesitamos ver un poco mas a fondo para respaldar esta hipotesis.

ggplot(data = Viajespordia, aes(x = diaDeLaSemana, y = DuracionPromedio, fill = tipo_usuario)) +
  geom_bar(stat = "identity", position = "dodge", color = "black") +  # Crea las barras y las coloca lado a lado
  geom_text(
    aes(label = round(DuracionPromedio, 1)), 
    position = position_dodge(width = 0.9),  # Ajusta la posición horizontal de las etiquetas
    vjust = -0.5,  # Ajusta la posición vertical de las etiquetas
    color = "black",
    size = 2.5
  ) +
  labs(
    title = "Duración Promedio de Viajes por Día - Cyclistic",
    subtitle = "Por Tipo de Usuario",
    x = "Día de la Semana",
    y = "Duración Promedio (minutos)",
    fill = "Tipo de Usuario",
    caption = "Base de datos Cyclistic - Empresa Ficticia"
  ) +
  theme_minimal() +
  theme(
    legend.position = "bottom"
  ) +
  scale_fill_manual(values = c(
    "miembro" = "white",
    "casual" = "skyblue"
  )) +  # Ajusta los colores según tus categorías
   coord_cartesian(ylim = c(0, max(Viajespordia$DuracionPromedio, na.rm = TRUE) * 1.1))  # Extiende el rango del eje y


Como podemos apreciar la duracion de los viajes en promedio es mayor para el usuario causal, lo que sustenta nuestra sobre su uso principalmente recreativo de las bicicletas y mas corto para los miembros quienes usan el servicio usualmente como medio de transporte para sus trabajos, esto tambien explicaria que la cantidad de viajes sean mayores dentro de la categoria de miembros ya que deben utilizar el servicio multiples veces al dia.

# Crear el gráfico de barras con control del ancho y altura
ggplot(data = DatosViajes, aes(x = tipo_bicicleta)) +
  geom_bar(
    aes(y = after_stat(count)), 
    fill = "skyblue", 
    color = "black", 
    width = 0.3  # Ajusta el ancho de las barras; valores menores a 1 las hacen más delgadas
  ) +  
  geom_text(
    aes(label = after_stat(count)), 
    stat = "count", 
    vjust = -0.5,  
    color = "black",
    size = 3
  ) +
  labs(
    title = "Viajes por Tipo de Bicicleta - Cyclistic",
    subtitle = "Periodo Agosto 2023 - Julio 2024",
    x = "Tipo de Bicicleta",
    y = "Número de Viajes",
    caption = "Base de datos Cyclistic - Empresa Ficticia"
  ) +
  theme_minimal() +
  coord_cartesian(ylim = c(0, max(table(DatosViajes$tipo_bicicleta)) * 1.2))   # Ajusta el rango del eje Y basado en los conteos reales


Otra cosa que podemos apreciar es la preferencia por bicicletas clasicas o electricas y poco interes en bicicletas compartidas

# Crear el gráfico filtrando los usuarios casuales directamente
ggplot(data = ViajesPorHoraUsuario %>% filter(tipo_usuario == "casual"), aes(x = hora, y = Num_de_viajes, fill = tipo_usuario)) +
  geom_bar(stat = "identity", position = "dodge", color = "black") +  # Define el gráfico como barras
  geom_text(
    aes(label = Num_de_viajes),
    position = position_dodge(width = 0.9),  # Ajusta la posición horizontal de las etiquetas
    vjust = 0.4,  # Ajusta la posición vertical de las etiquetas
    hjust = -0.1,  # Ajusta el texto para estar sobre la barra
    angle = 90,    # Gira el texto a 90 grados para que sea vertical
    color = "black",
    size = 2.5
  ) +
  labs(
    title = "Viajes por Hora del Día - Cyclistic",
    subtitle = "Usuarios Casuales",
    x = "Hora del Día",
    y = "Número de Viajes",
    fill = "Tipo de Usuario",
    caption = "Base de datos Cyclistic - Empresa Ficticia"
  ) +
  theme_minimal() +
  theme(
    axis.text.x = element_text(angle = 45, hjust = 1),  # Rota las etiquetas del eje X para mejorar la legibilidad
    legend.position = "bottom"  # Coloca la leyenda en la parte inferior
  ) +
  scale_fill_manual(values = c("casual" = "skyblue")) +  # Especifica el color para los usuarios casuales
  coord_cartesian(ylim = c(0, max(ViajesPorHoraUsuario %>% filter(tipo_usuario == "casual") %>% pull(Num_de_viajes)) * 1.2))  # Extiende el rango del eje Y para que no se corte el texto


La tendencia muestra que los usuarios casuales arriendan con mayor frecuencia hacia las horas de la tarde

ggplot(data = ViajesPorHoraUsuario %>% filter(tipo_usuario == "miembro"), aes(x = hora, y = Num_de_viajes, fill = tipo_usuario)) +
  geom_bar(stat = "identity", position = "dodge", color = "black") +  # Define el gráfico como barras
  geom_text(
    aes(label = Num_de_viajes),
    position = position_dodge(width = 0.9),  # Ajusta la posición horizontal de las etiquetas
    vjust = 0.4,  # Ajusta la posición vertical de las etiquetas
    hjust = -0.1,  # Ajusta el texto para estar sobre la barra
    angle = 90,    # Gira el texto a 90 grados para que sea vertical
    color = "black",
    size = 2.5
  ) +
  labs(
    title = "Cantidad de Viajes por Hora del Día - Miembros",
    x = "Hora del Día",
    y = "Número de Viajes",
    fill = "Tipo de Usuario",
    caption = "Base de datos Cyclistic - Empresa Ficticia"
  ) +
  theme_minimal() +
  theme(
    axis.text.x = element_text(angle = 45, hjust = 1),  # Rota las etiquetas del eje X para mejorar la legibilidad
    legend.position = "none"  # Oculta la leyenda ya que solo hay un tipo de usuario
  ) +
  scale_fill_manual(values = c("miembro" = "skyblue")) +  # Especifica el color para los usuarios miembros
  coord_cartesian(ylim = c(0, max(ViajesPorHoraUsuario %>% filter(tipo_usuario == "miembro") %>% pull(Num_de_viajes)) * 1.2))  # Extiende el rango del eje Y para que no se corte el texto


Mientras que al observar a los miembros vemos como las tendencias aumentan en horarios que coinciden con el horario laboral normal de la mayoria de las personas lo que reitera el tipo de uso que da cada usuario al servicio.

ETAPA 06
Actuar
Luego de analizar y establecer algunas de las diferencias entre los tipos de usuario podriamos recomendar algunas estrategias para persuadir a los usuarios casuales a hacer una transicion a miembros

Realizar campañas de marketing sobre todo en epocas de primavera y verano en lugares turisticos y recreacionales populares enre usuarios casuales. para esto se pueden analizar el agrupamiento de las coordenadas de inicio y final de los viajes casuales estableciendo periodos de tiempos especificos para evaluar tendencias y ser mas especificos.

Los usuarios casuales son mas activos en los fines de semana y por tempradas, por lo que una buena opcion seria crear y ofrecer una membresia por temporada o exclusiva de fines de semana.

Tambien podemos apreciar como la duracion de los viajes es mayor para usuarios casuales. Ofrecer descuentos para viajes largos podria ser un incentivo para atraer usuarios casuales a adquirir membresias y tambien motivar a los miembros a realizar viajes mas largos.
