# generaci-n-de-prompts-entrega final

                                                   Proyecto Final  - "Mosaico"

Resumen: Creación de un documento sobre un perfil público de un invitado a canales de streaming, radios, redes sociales y demás programas de entrevistas.


1.- Presentación del problema a abordar

Cada año, millones de canales se crean en diversas plataformas de streaming, reflejando un crecimiento exponencial. En Argentina, estos canales atraen audiencias diarias de hasta 100.000 personas. Karla Agis, líder de Cultura y Tendencias para Canadá y Latinoamérica de YouTube, destaca que en Argentina casi 7 de cada 10 personas consumen videos en YouTube en diversos formatos (largos, shorts, en directo y podcasts). Esta tendencia de consumo de video online “es un claro reflejo de la cultura digital actual”.

El crecimiento continuo de esta tendencia aumenta la demanda de contenido de mayor calidad. Muchos canales realizan entrevistas a figuras públicas, lo que requiere una investigación exhaustiva sobre la vida personal, profesional y los logros de los entrevistados. Los equipos de producción dedican mucho tiempo a esta tarea. En canales de streaming, YouTube y otras plataformas, donde los equipos suelen ser pequeños o incluso de una sola persona, la preparación de un invitado puede ser muy demandante. Este proyecto tiene como objetivo agilizar este proceso, proporcionando una solución integral que facilite el trabajo de producción y reduzca significativamente el tiempo dedicado a la investigación.

El propósito de este proyecto es desarrollar un sistema que genere automáticamente un documento que sirva como perfil de un invitado a programas de radio, podcast y plataformas de streaming. Esto permite acortar los tiempos de búsqueda y agilizar el trabajo de investigación de los productores y generadores de contenido. Dicha herramienta tiene como fin ayudar para aligerar el trabajo de investigación de invitados y brindar un producto completo y sistematizado que sirva de guía en los programas. Utilizaremos la API de OpenAI para GPT-3.5 para generar textos completos y coherentes que formen un perfil de entrevistado.
2.- Desarrollo de la propuesta de solución

2.1. Definición del Contexto

El primer paso en el desarrollo de nuestra solución consiste en la definición del contexto. 
En esta etapa, le pediremos al sistema que recopile datos en base al nombre con perfil público que el usuario introduce sobre la cual desea obtener información. Este nombre actúa como el punto de partida para la recopilación de datos y la generación de contenido relevante. Luego, se le indicará un orden específico para mostrar los datos y un formato amigable al usuario.

2.2 Generación de Texto

Una vez definido el contexto, el sistema utiliza OpenAI GPT-3.5 para procesar la información proporcionada. Este modelo avanzado de procesamiento de lenguaje natural genera un texto completo y coherente que abarca diversas categorías de información sobre la persona en cuestión. Las categorías incluyen:
      •	Información Personal: Datos básicos como nombre completo, fecha de nacimiento, lugar de origen, y otros detalles relevantes.
      •	Información Profesional/Carrera: Un resumen detallado de la trayectoria profesional de la persona, incluyendo puestos ocupados, logros destacados, y contribuciones significativas en su campo.
Los perfiles de LinkedIn, los sitios web corporativos o las publicaciones del sector pueden proporcionar estos datos
      •	Apariciones públicas recientes o menciones en los medios de comunicación: Últimas 3-5 apariciones públicas: Esto incluye conferencias, paneles, entrevistas en medios de comunicación o podcasts en los que el invitado haya aparecido recientemente. Temas clave tratados: Lo más destacado de lo que hablaron en esas apariciones.
    •	Guía de Preguntas Creativas: Basada en la información recopilada, se genera una serie de preguntas creativas diseñadas para fomentar una conversación enriquecedora y profunda sobre la persona.
    
2.3. Evaluación y Mejora

La siguiente fase es la evaluación y mejora del texto generado. En esta etapa, se revisa la calidad del contenido para asegurar que sea preciso, coherente y completo. Se realizan ajustes y mejoras según sea necesario, con el objetivo de expandir y enriquecer la información en cada categoría. Este proceso garantiza que el texto final sea de alta calidad y cumpla con las expectativas del usuario.
2.4. Descarga en Distintos Formatos
Finalmente, una vez que la ficha de la persona con perfil público está completa y revisada, se ofrece la posibilidad de descargar la información en distintos formatos. Los formatos disponibles incluyen PDF, JPG, y otros, permitiendo al usuario elegir el formato que mejor se adapte a sus necesidades. Esta funcionalidad proporciona flexibilidad y conveniencia, facilitando el acceso y uso de la información generada.

2.5 Objetivos
    •	Crear un sistema capaz de generar un perfil completo de una persona con perfil público.
    •	Demostrar la capacidad del sistema para producir contenido de calidad.
    •	Asegurar que el producto generado contenga la información para realizar la entrevista proporcionando los datos personales, logros profesionales, apariciones y dichos públicas como así también una guía de preguntas base personalizada.
    •	Utilizar OpenAI GPT-3.5 para recopilar los datos sobre el/la entrevistado/a y crear el documento mencionado.
    •	Lograr un esquema o formato específico en cada respuesta para brindar un producto completo y estandarizado.
    
2.6. Herramientas y Tecnologías
    •	Python
    •	OpenAI GPT-3.5-turbo API
3. Justificación de la viabilidad del proyecto.

Este sistema es esencial para que los anfitriones puedan acceder instantáneamente a perfiles personalizados y precisos de los huéspedes mediante la automatización de la recopilación de datos de múltiples fuentes. Garantiza información oportuna y estructurada sobre antecedentes personales, carrera profesional y apariciones recientes, todo ello en español. Al ahorrar tiempo y eliminar la investigación manual, mejora la calidad de la entrevista, haciéndola más atractiva y relevante para la audiencia. El hecho de que la herramienta se centre en América Latina añade especificidad regional, atendiendo a los matices culturales y lingüísticos del contenido.

4.- Implementación: En ProyectoFinal.ipynb

5.- Resultados: El resultado arrojado es el esperado dando información requerida junto con la estructura planteada. La información es veraz pero desactualizada por lo que se requiere de API como la de Twitter y Youtube Data API v3 para poder recabar información actualizada.

6.- Conclusiones: En conclusión, el proyecto dió los resultados esperados al probar la API de OpenAI y la utilización de Anaconda. Por otro lado, los puntos a mejorar es la inclusión de otras herramientas como WebScraping para recuperar información que se encuentre en Internet e utlizar otras APIs como la de Twitter y YouTube Data API v3 para dar información más actualizada del entrevistado.

En términos de modelo de negoció, plantearlo como un freemium con un uso limitado de búsquedas semanales y una versión premium sin límites de búsqueda sería lo ideal para este proyecto. El costo de la utilización de las ya mencionadas APIs junto con de tokenización pueden ser amortizados con las cuentas premium con un costo de 5 USD mensuales por cuenta. Para llevar el proyecto a un nivel comercial se requerrirá un desarrollo de una interfaz amigable. 

