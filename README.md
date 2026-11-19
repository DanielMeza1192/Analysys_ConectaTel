# Analysys_ConectaTel
Proyecto para analizar los datos sobre el tipo de uso, tipo de plan y tipo de cliente, de una base de datos de usuarios de planes telefónicos
Objetivo: Encontrar patrones de uso, con base a tipos de cliente, tipos de planes telefónicos, con base a los hallazgos tomar decisiones de negocio, bien sea crear un nuevo tipo de plan, o una campaña de descuentos para fomentar el incremento de uso en diferentes tipos de clientes.

Se utilizan los siguientes datasets para el analisis:
- plans.csv: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
- users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.
- usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).

El desarrollo del proyecto comprende las siguientes etapas:
- Carga de Datosets
- Importe de las librerías clave de Python: Pandas, Numpy, Seaborn y Matplotlib
- Visualización rápida de datos, forma preliminar de los datasets crudos, exploración de las bases de datos
- Verificación de valores nulos o faltanes
- Verificación de columnas, o variables problema
- Normalización de formatos de las columnas (Si aplica), es decir pasar de formato objeto, a tipo numérico, pasar datos a tipo fecha
- Hallazgo o detección de sentinels, corrección de los mismos
- Resumen estadístico por usuario, agregando tipo de plan, cantidad de mensajes, cantidad de llamadas, cantidad de minutos en las llamadas
- Visualización de las distribuciones de las edades de los usuarios, las cantidades de mensajes, llamadas y minutos de las llamadas y sus respectivos outliers
- Segmentación de los datos por grupo de edad y tipo de uso
- Conclusiones del proyecto

Archivo `.ipynb`
Abrir el archivo **`.ipynb`** en GitHub o visual estudio
Descargar los datasets, ubicarlos en una carpeta local, y reproducir el archivo desde visualstudio, actualizando la ruta en donde se guarden los datasets
Haz clic en  **Open in Colab**

Abrir Analysis_ConnectaTel.ipynb
Ejecutar celdas en orden 
El notbook carga automaticamente los datasets desde un enlace publico
