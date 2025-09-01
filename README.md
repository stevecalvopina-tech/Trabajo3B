# Trabajo3B
Trabajo 3 con otra base de datos
# Data set sobre  "Cybersecurity Incidents & Data Breaches 2024" Incidentes de #ciberseguridad y filtraciones de datos en 2024
# Este conjunto de datos captura 25 incidentes importantes de ciberseguridad y filtraciones de datos reportados en 2024 en múltiples industrias y países. Cada registro proporciona información detallada sobre el tipo de ataque, el vector de entrada, los datos comprometidos, las pérdidas financieras, los tiempos de recuperación, las multas regulatorias y el impacto en las acciones y los clientes.

# Además de los detalles del incidente, el conjunto de datos incluye información sobre la postura de seguridad de la organización afectada, como el estado de los parches, la adopción de MFA, la capacitación en seguridad, la presencia de CISO y la asignación presupuestaria, lo que lo convierte en un recurso valioso para analizar factores de riesgo, tendencias y correlaciones en ciberseguridad.

# Se procede hacer exploracion de los datos que presenta el dataset, entre los maás importantes tenemos:
# 1. Industry -Industria: Que se refiere a que tipo de industria es ejm Tecnología, Finaciero etc.
# 2. Country - País.
# 3. Attack_Type- Tipo de Ataque: tipos de ataque que hicieron
# 4. Attack_Vector: Como hicieron el ataque
# 5. Records_Compromised: Total de datos comprometidos
# 6. Recovery_Time_Days : Numero de días en recuperación
# 7. Financial_Impact_Million_USD : Impacto que dejo el ataque en cuestión monetaria
# 8. Security_Budget_Million_USD : Inversión en seguridad
# 9. Employee_Count : Numero de empleados
# 9. Response_Time_Hours : tiempo en horas para respoder el incidente
# 10. Customer_Churn_Percent : Perdida de clientes
# En este análisis se escoge estos campos debido que existe una relación entre ellos, debido que para una organización o empresa lo más primordial son sus clientes, y sus empleados, y con esto la inversión que han implementado para mantener a día sus empresas.
# Para esto se elima columnas o datos que no son relevantes para un análisis de datos, y así para una toma de decisiones a futuro
# Se hace un analisis exploratorio de industrias atacadas por país en donde se observa que el país de Estados Unidos, es el país con mas ataques en el año 2024 en sus diferentes industrias con 8 industrias atacadas entre ellas Tecnología, Financiera, Hospitalarias, entre otras.
# observamos que existe un correlación entre Impacto de dinero de perdida, registros comprometidos, el número de empleados, y el tiempo de respuestas para solventar el incidente, en donde Financial_Impact_Million_USD - Impacto de dinero perdido esta correlacionado con los datos comprometidos y en tiempo de respuesta.
# En una empresa cuando existe un ataque cibernético, lo más crítco es los datos que se comprometieron, y el tiempo de respuesta, debido que a la fuga de datos de sus clientes, pueden perder clientes, y así sus finazas pueden decaer, sin clientes las empresas no surge, no genrean ingresos, y sin ingresos, pueden exister despidos de empleados, y la quiebra de dicha empresa.
# También existe correlación entre entre el dinero que uso para el rescate, con los registros comprometidos, el tiempo que duro en recuperase,  y el número de empleados, en donde la correlación mas relevante es Ransom_Amount_USD con Recovery_Time_Days, el monto que se uso para rescatar la información con el núemro de días que se demoro para la recuperación del incidente, y es debido que son datos sencibles de clientes, y a veces los ciberdelincuentes pieden cantidad de dinero  depositados en cuentas de otros paises donde no piden  declaraciones de impuestos o declaraciones de donde vienen los fondos, actualmente existe casos que los ciberdelincuntes pden rescate mediantes el uso de criptomonedas para el rescate, y esto para no perder la credibilidad de sus clientes que confían en dichas empresas, al otorgar información personal
#  Como conclusión una empresa debe ytener un equipo de Tic´s - Tecnología que se enfoque o se dedique a la infraestructura, en donde puede estar el departamento de Ciberseguridad, el cual estará  encargado de la seguridad de la información de la empresa y así mediantes difrentes técnicas de seguridad proteger los dominios que posee dicha empresa, mediante firewalls, monitoreo diario de anomalias en la red, ingresos no autorizados a sus diferentes servidores.