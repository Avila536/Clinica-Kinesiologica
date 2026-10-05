# Clinica-Kinesiologica
pequeños códigos, para acelerar procesos de atención y actualización en una clinica enfocada en el movimiento

1. Buscador Local (Ruta de Escritorio)
Script optimizado para operar escaneando directorios locales del sistema operativo (diseñado para trabajar en conjunto con Google Drive para Escritorio).

Funcionamiento: Utiliza librerías nativas de Python para recorrer los directorios locales, buscar coincidencias exactas o parciales de texto en los nombres de los archivos y ejecutarlos directamente.

Ventaja principal: Permite a los profesionales seguir utilizando el software nativo de Microsoft Excel. Esto asegura que las validaciones de datos, listas desplegables, protección de celdas y formatos visuales estrictos de la ficha clínica funcionen al 100% sin desconfigurarse.

Caso de uso: Ideal para clínicas donde el trabajo simultáneo sobre un mismo paciente es raro y se prioriza la interfaz clásica de Excel.

2. Buscador en la Nube (API de Google Drive)
Script avanzado de conexión remota que interactúa directamente con los servidores de Google mediante autenticación OAuth 2.0.

Funcionamiento: Implementa google-api-python-client para consultar la base de datos en la nube. Valida credenciales (credentials.json), busca archivos con formato de hoja de cálculo y extrae el enlace web directo para abrir la ficha en el navegador.

Ventaja principal: Habilita la colaboración en tiempo real. Al abrir las fichas directamente en Google Sheets a través de la web, múltiples socios o profesionales pueden editar el mismo registro del paciente de forma simultánea sin generar conflictos de guardado o archivos duplicados.

Caso de uso: Ideal para entornos de trabajo dinámicos donde se requiere acceso multiplataforma sin depender de instalaciones locales pesadas.
