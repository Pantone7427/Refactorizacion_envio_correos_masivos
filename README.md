Sistema de Automatización y Refactorización de Soportes de Pago
Desarrollado por: Maria Melisa Serna
Tecnología: Google Apps Script (JavaScript)

Descripción
Este proyecto nació como una iniciativa académica para la optimización de procesos administrativos. El sistema automatiza el envío masivo de soportes de pago, transformando una tarea manual de varias horas en un proceso de pocos minutos con alta precisión.

La lógica fue refactorizada para cumplir con estándares profesionales de modularidad, eficiencia en el consumo de cuotas de Google y seguridad de la información.

Características Técnicas
Agrupación de Datos (Data Grouping): Implementa lógica para consolidar múltiples registros bajo un mismo NIT, enviando un único correo con todos los adjuntos correspondientes.

Arquitectura Modular: Separación clara entre la lógica de negocio, los ayudantes de utilidad (helpers) y la construcción dinámica del cuerpo del correo (HTML/CSS).

Resiliencia de Estructura: El script utiliza mapeo de encabezados (indexOf), permitiendo que la base de datos sea flexible y no se rompa si se insertan o mueven columnas.

Reportes Automáticos: Generación de una hoja de reporte tras cada ejecución con el estado detallado (Enviado, Error, Sin Archivo, etc.).

Optimización con IA
Para la etapa de refactorización, se utilizaron herramientas de Inteligencia Artificial aplicadas a:

Limpieza de strings mediante Expresiones Regulares (Regex) para normalizar nombres y direcciones.

Diseño visual del cuerpo del correo para garantizar una experiencia de usuario profesional.

Instalación y Uso
Cargar el código en el editor de Google Apps Script vinculado a la hoja de cálculo.

Configurar la constante ID_CARPETA con el ID de la carpeta de Google Drive donde residen los PDFs.

Ejecutar el menú personalizado 📧 El Castillo que aparecerá en la barra superior.

Licencia
Este código es de uso privado y propiedad intelectual de la autora. Su implementación en entornos de producción debe ser coordinada con el área de desarrollo.
