PRIMER RETO

1.- ¿Qué es un control de versiones?

Es un sistema que registra modificaciones o cambios en un conjunto de archivos a lo largo del tiempo de un determinado proyecto, guardando sus versiones anteriores a la que podemos acudir en caso la última versión del proyecto (software) no funcione. En Git tenemos dos comandos principales parar visualizar el historial de modificaciones del proyecto:

    git commit -m “mensaje” // confirma y guardar los cambios al directorio .git además se agrega un mensaje que identifique los cambios realizados.

    git log // muestra el histórico de confirmaciones realizados de todas las modificaciones hechas en el proyecto.

2.- ¿Cuáles son los problemas al no usar un control de versiones?

-Dificultad trabajar de manera colaborativa y al mismo tiempo con otras personas.

-Inconvenientes para resolver conflicto y no tener una copia de seguridad del       proyecto con riesgo a perderlo.

-Dificultad y desorden para versionar los archivos del proyecto.

3.- ¿Cuáles son los beneficios?

-Permite que varios desarrolladores trabajen al mismo tiempo y en paralelo en un proyecto con un acceso compartido, así como identificar qué usuario y cuándo ha realizado cada modificación.

-Cada desarrollador cuenta con una copia local de todo el proyecto y de los cambios generados, lo que le permite trabajar de forma individual y a su propio ritmo, en cualquier momento y lugar.

-Esta característica hace posible que los desarrolladores puedan trabajar en diferentes ramas de un proyecto, pero sin modificar en el código base principal, facilitando así que puedan probar nuevas funcionalidades sin miedo a cometer equivocaciones, ya que siempre pueden dar marcha atrás y volver a versiones anteriores.

-Permite comparar, fusionar o restaurar versiones de una aplicación y contar con una copia del código fuente para volver atrás ante cualquier imprevisto.

-Lo utilizan empresas tecnológicas de referencia como Google, Facebook o Nefflix para controlar las versiones de código fuente sus proyectos.

4.- ¿Qué tipos de control de versiones existen?

-Sistemas de Control de Versiones Locales:
Los sistemas de control de versiones locales en vez de mantener las versiones como archivos independientes, los almacenaban en una base de datos. Cuando era necesario revisar una versión anterior del proyecto se usaba el sistema de control de versiones en vez de acceder directamente al archivo, de esta manera en cualquier momento solo se tenía una copia del proyecto, eliminando la posibilidad de confundir o eliminar versiones.

-Sistemas de Control de Versiones Centralizados:
Para facilitar la colaboración de múltiples desarrolladores en un solo proyecto los sistemas de control de versiones evolucionaron: en vez de almacenar los cambios y versiones en el disco duro de los desarrolladores, estos se almacenaban en un servidor.

-Sistemas de Control de Versiones Distribuidos:
La siguiente generación de sistemas de control de versiones se alejó de la idea de un solo repositorio centralizado y optó por darle a cada desarrollador una copia local de todo el proyecto, de esta manera se construyó una red distribuida de repositorios, en la que cada desarrollador podía trabajar de manera aislada, pero teniendo un mecanismo de resolución de conflictos mucho más elegante que un su versión anterior.
