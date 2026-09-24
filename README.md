Simulador y Evaluador de Cableado UTP TIA-568

Cátedra: Redes de Datos y Telecomunicaciones

Docente: Profesor Berdun A.

Versión: 1.0 (Autocontenido / Single-File Web App)

📋 Descripción del Proyecto

Este recurso didáctico interactivo simula el proceso de armado (crimpado) de conectores RJ-45 (8P8C) sobre cable de par trenzado UTP, la verificación funcional mediante un tester de red secuencial (Master / Remote) y la evaluación teórico-práctica con emisión de reportes automatizados.

El simulador está diseñado para que los estudiantes comprendan de forma visual y experimental las diferencias entre las normas ANSI/TIA/EIA-568A y ANSI/TIA/EIA-568B, diagnostiquen fallas reales (circuitos abiertos, pares transpuestos, cruces erróneos) y registren sus resultados.

✨ Características Principales

Mesa de Crimpado Interactivo:

Paleta de los 8 conductores normalizados (Blanco/Verde, Verde, Blanco/Naranja, Azul, Blanco/Azul, Naranja, Blanco/Marrón, Marrón).

Inserción y remoción pin por pin en fichas independientes: Extremo A y Extremo B.

Detección automática del estándar configurado y botones de prueba rápida (presets y generador de fallas de par abierto o cruce).

Probador de Red Secuencial (Master / Remote):

Animación de barrido pin a pin (1 al 8 y masa de apantallamiento).

Dos velocidades operativas: Modo S (Lento, 1.2s) y Modo ON (Rápido, 0.4s), además de avance Paso a Paso.

Iluminación semafórica con LEDs virtuales:

🟢 Verde: Continuidad correcta.

🟡 Ámbar: Transposición o cruce de pin.

⚫ Apagado: Circuito abierto o hilo faltante.

Panel de Examen y Cronómetro:

Registro de datos del alumno (Nombre, Curso, División).

Cronómetro de tiempo transcurrido con funciones de pausa y reinicio.

Ponderación automatizada: 60% Práctica de Conectorizado + 40% Examen Teórico.

Cuestionario Técnico Integrado:

5 preguntas técnicas sobre frecuencias, categoría de cable, diafonía (NEXT), distancias de destrenzado y tecnología Auto MDI/MDI-X con devolución formativa inmediata.

Auditoría y Exportación:

Historial de intentos en memoria durante la sesión.

Botón de exportación a archivo .CSV codificado en UTF-8 con BOM para abrir en Microsoft Excel o Google Sheets sin errores de caracteres.

Marca de agua continua de seguridad docente: "Profesor Berdun A.".

🛠️ Tecnologías Empleadas

HTML5 Semántico: Estructura de pestañas y accesibilidad.

CSS3 / Tailwind CSS (CDN): Estilos modernos, diseño responsivo y efectos visuales de LEDs y conductores trenzados con gradientes puros.

JavaScript Vanilla (ES6+): Lógica sin dependencias externas, temporizador, matriz de conexión de pines, motor de testeo y generador de archivos Blob/CSV.

Phosphor Icons: Iconografía técnica ligera.

🚀 Guía de Despliegue y Uso

Al tratarse de una solución de archivo único (single-file), no requiere compilación, servidores Node.js ni bases de datos.

Opción A: Ejecución Local (Offline para Taller o Laboratorio)

Descargá el archivo network_cable_tester_simulator.html.

Guardalo en una carpeta local o distribuilo vía pendrive.

Hacé doble clic sobre el archivo para abrirlo en cualquier navegador web moderno (Google Chrome, Microsoft Edge, Mozilla Firefox o Safari) sin necesidad de conexión a Internet.

Opción B: Alojamiento Gratuito en la Nube (GitHub Pages)

Creá un repositorio público en GitHub.

Renombrá el archivo a index.html y subilo a la rama principal (main).

Dirigite a Settings > Pages.

En Build and deployment > Branch, elegí main y la carpeta / (root), luego hacé clic en Save.

Tu aplicación estará disponible públicamente en:

https://<tu-usuario>.github.io/<nombre-repositorio>/

Opción C: Despliegue Rápido (Netlify Drop)

Colocá el archivo renombrado como index.html dentro de una carpeta vacía.

Ingresá a app.netlify.com/drop.

Arrastrá la carpeta a la ventana del navegador para obtener un enlace público permanente de inmediato.

📖 Metodología Pedagógica Sugerida

Fase 1 - Exposición & Consulta: El estudiante abre la ventana modal "Guía & Rúbrica" para revisar la tabla comparativa de colores y la rúbrica de evaluación analítica.

Fase 2 - Consigna Asignada: El docente define el objetivo (Cable Directo 568A, 568B o Cruzado) y el alumno inicia el cronómetro.

Fase 3 - Verificación en el Probador: El estudiante prueba el comportamiento de los LEDs en el tester virtual para corroborar la correspondencia de señales antes de certificar.

Fase 4 - Examen Conceptual: Se completan las preguntas teóricas para consolidar los criterios de instalación y canalización.

Fase 5 - Entrega: Se genera la planilla .CSV mediante el botón "Descargar Reporte CSV" y se envía al docente a través del aula virtual o correo electrónico institucional.

📄 Licencia y Créditos

Desarrollado con fines educativos y de formación técnico-profesional para la cátedra de cableado estructurado del Profesor Berdun A.

Uso libre para fines académicos no comerciales.
