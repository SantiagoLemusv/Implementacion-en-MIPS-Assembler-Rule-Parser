# Implementacion-en-MIPS-Assembler-Rule-Parser
Proyecto de Semestre Arquitectura y Organización del Computador - 3799 // PUJ - 2023. Autoria de Christian Xavier, Santiago Lemus y Miguel Marquez.
//
En esta investigación que realizamos, se proporciona una visión general del concepto de un parser (analizador). Un parser es un programa que procesa información basada en reglas específicas y genera una estructura de datos ordenada y estructurada. El parser tiene diferentes usos en campos de Tecnología, en el campo de la seguridad de la información, los analizadores se utilizan para analizar registros y buscar actividad maliciosa.

Para ejecutar un análisis adecuado, un parser requiere un archivo de texto a analizar y un conjunto de reglas para correlacionar la información. También se menciona la importancia de ordenar los datos de manera cronológica y asegurarse de que estén libres de duplicados. El parser busca posibles amenazas según las reglas definidas y genera alarmas en caso de detectar irregularidades.

En el caso proyecto, se reciben dos archivos: "data." y "Parsing_Rules.config". El archivo "data." contiene registros de logs con campos de IP, Username y Date en formato Epoch, mientras que "Parsing_Rules.config" contiene las reglas que generarán las alarmas. Los datos se almacenan en dos tablas separadas: Logs (IP, Username, Date) y Alerts (IP, Username).

El proyecto ordena la tabla de Logs por fecha, eliminar duplicados en la tabla de Alerts, ejecutar las reglas de pareo para generar alarmas, generar un archivo de registro de alarmas, y realizar búsquedas por IP o usuario y generar un informe.

En resumen, en este proyecto desarrollamos un parser en lenguaje de ensamblador MIPS que realiza las tareas para analizar registros de logs y generar alarmas y reportes según las reglas especificadas.

