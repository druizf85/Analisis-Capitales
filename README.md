# Análisis Capitales

Para el presente análisis se tomó como principal fuente de información el conjunto de contratos en SECOP II del portal de los datos abiertos del SECOP. Se desarrollaron diferentes procesos de extracción, transformación y carga de los datos en Python y sus diferentes librerías para manipulación de datos. 

Por otro lado, se desea visualizar esta información mediante un tablero de control o Dashboard en Power Bi. Este procedimiento cuenta con información hasta el día 13 de mayo de 2024. Sin embargo, su estructuración facilita que se analice el proceso de manera actualizada, ya que este conjunto de datos abiertos se actualiza de manera diaria.

A su vez, los diferentes documentos relacionados con este proyecto se encuentran publicados en este repositorio para consulta.

Se realizó el siguiente procedimiento en el documento llamado Proyecto Contratación Capitales Colombia.ipynb:

(i) Extracción (Extract): 

• Establecer conexiones seguras y eficientes con estas fuentes de datos, utilizando protocolos de seguridad. 
• Implementar rutinas de extracción automatizadas para garantizar la actualización regular de los datos.

(ii) Transformación (Transform):

• Realizar la limpieza de los datos extranjeros para eliminar valores nulos, datos duplicados, inconsistencias y errores tipográficos que puedan afectar la calidad de las visualizaciones. 
• Aplicar transformaciones y cálculos necesarios para derivar nuevas métricas o indicadores relevantes para el tablero de control. 
• Unificar y estandarizar la estructura de los datos procedentes de diferentes fuentes para facilitar su análisis y visualización. 
• Identificar y tratar valores atípicos o outliers que puedan distorsionar las conclusiones extraídas del análisis de datos.

(iii) Carga (Load):

• Establecer procesos de carga automatizados que transfieran los datos limpios y transformados desde el área de preparación hacia la base de datos del tablero de control. 
• Implementar mecanismos de control de calidad para verificar la integridad y consistencia de los datos cargados, mediante la comparación de conteos de registros y validaciones de integridad referencial si corresponde.

Una vez que se han recopilado y procesado los datos, se procedió a diseñar y configurar el tablero de control:

Se desea mostrar un mapa en el cual se pueda ver la dimensión del valor de los contratos celebrados en el 2024 por ciudad. Además de hacer un resumen de cada uno de estos valores y su participación con respecto al valor total.

![image](https://github.com/druizf85/An-lisis-Capitales/assets/121362745/ecf8d3c0-fbd8-4fd2-9d64-359480185667)

Por otra parte, se desea incorporar diferentes gráficos que puedan mostrar:
(i) La tendencia por cantidades y valores por mes de los contratos en la base de datos.
(ii) La cantidad de contratos por modalidad de contratación y su participación con respecto al total.
(iii) Tendencia mensual de los valores contratados por ciudad y comparativo.
(iv) Uso de la funcionalidad de gráfico mediante las bibliotecas dispuestas en python (matplotlib) para identificar la participación de pymes en los contratos.

![image](https://github.com/druizf85/An-lisis-Capitales/assets/121362745/c99c9fd1-37b9-4e16-a410-54f47c0433e5)

Finalmente, identificar el detalle de los contratos que se filtren en power bi.

Se desea conocer la ciudad, la entidad, numero de contrato, objeto contractual, proveedor, identificador si es pyme el proveedor, valor total del contrato.

![image](https://github.com/druizf85/An-lisis-Capitales/assets/121362745/2c00e36f-a2f3-427c-ae2c-553da8f0ca4b)

