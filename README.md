E6Script.ps1

Descripción

E6Script.ps1 es un script en PowerShell diseñado para proporcionar una interfaz interactiva que permite consultar información de fecha y hora, visualizar un calendario y buscar archivos según una fecha específica.

Características

Ver calendario: Muestra un calendario en la terminal.

Consultar fecha y hora: Permite al usuario conocer la fecha y hora actual del sistema.

Buscar archivos por fecha: Permite buscar documentos según su fecha de creación o modificación.

Salir: Finaliza la ejecución del script.

Requisitos

PowerShell 5.1 o superior.

Módulo Seteolvidolahora (asegúrate de que esté disponible en el entorno de ejecución).

Instrucciones de uso

Descarga el archivo E6Script.ps1.

Abre PowerShell y navega hasta la carpeta donde se encuentra el archivo.

Ejecuta el siguiente comando para permitir la ejecución de scripts:

Set-ExecutionPolicy Unrestricted -Scope Process

Ejecuta el script con el siguiente comando:

.\E6Script.ps1

Selecciona una opción en el menú interactivo:

Opción 1: Mostrar calendario.

Opción 2: Ver fecha y hora.

Opción 3: Buscar archivos por fecha.

Opción 4: Salir.

Notas adicionales

Si el módulo Seteolvidolahora no está presente, el script podría no funcionar correctamente. Asegúrate de que esté instalado o disponible en el entorno de ejecución.

Si deseas restringir nuevamente la ejecución de scripts después de utilizar este, puedes restablecer la política de ejecución con:
