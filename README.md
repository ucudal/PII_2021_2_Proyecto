# Universidad Católica del Uruguay
<img src="https://ucu.edu.uy/sites/all/themes/univer/logo.png">

## Facultad de Ingeniería y Tecnologías
### Programación II

## Proyecto 2021 - Segundo Semestre - Mapeo de Emprendedores - [Economía Circular](https://es.wikipedia.org/wiki/Econom%C3%ADa_circular).

El trabajo consiste en desarrollar un [chatbot](https://es.wikipedia.org/wiki/Bot_conversacional) que permitirá conectar organizaciones (o empresas) con emprendedores.

## Introducción
Un chatbot (o bot conversacional) es «un programa que simula mantener una conversación con una persona al proveer respuestas automáticas a entradas hechas por el usuario.»<sup>1</sup>

Existen gran variedad de chatbots actualmente y varios _sabores_. Hay chatbots que simplemente responden a comandos pre-establecidos, y otros que integran algoritmos de [inteligencia artificial](https://es.wikipedia.org/wiki/Inteligencia_artificial) para procesar los mensajes de los usuarios e [interpretar lo que se está diciendo](https://es.wikipedia.org/wiki/Procesamiento_de_lenguajes_naturales).

Los chatbots son especialmente útiles para asistir a las personas en tareas o consultas sin necesidad de la interacción humana del otro lado. Algunos ejemplos de esto son:

- ayudar a resolver un problema cuando pido comida y no llega
- hacer trámites con bancos, por ejemplo, notificación por Whatsapp que salgo de viaje
- [asistencia al público actualmente durante la pandemia del COVID-19](https://www.gub.uy/ministerio-salud-publica/coronavirus)
- hacer de asistente, por ejemplo, para agendar reuniones entre personas
- oficiar de agente de viajes, para encontrar vuelos, estadías, etc.
- buscar multimedia (GIFs, videos, música, etc.)
- y mucho más.

Algunas de las aplicaciones más conocidas que abren sus puertas al desarrollo de chatbots (tienen [APIs](https://es.wikipedia.org/wiki/Interfaz_de_programaci%C3%B3n_de_aplicaciones)) son: Telegram, Messenger, Whatsapp, Slack, Discord, entre otras.

## La propuesta (TBD)

**GONZALO: ¿NO HABRÍA QUE DEFINIR ACÁ QUE ESTAS SON LAS HISTORIAS DE USUARIO? OTRA COSA, ¿HABLAMOS DE "PLATAFORMA"?**

Como administrador, quiero poder invitar empresas a la plataforma, para que de esa forma puedan realizar ofertas de materiales reciclables o residuos.

Como empresa, quiero publicar una oferta de materiales reciclables o residuos, para que de esa forma los emprendedores que lo necesiten puedan reutilizarlos.

Como empresa, quiero clasificar los materiales o residuos, indicar su cantidad y unidad, el valor (en $ o U$S) de los mismos y el lugar donde se ubican, para que de esa forma los emprendedores tengan información de materiales o residuos disponibles.

Como empresa, quiero indicar las habilitaciones que requiere un emprendedor, para que de esa forma pueda recibir o retirar los materiales o residuos.

Como empresa, quiero indicar un conjunto de palabras claves asociadas a la publicación de los materiales, para que de esa forma sea más fácil de encontrarlos en las búsquedas que hacen los emprendedores.

Como emprendedor, quiero registrarme en la platarforma indicando nombre, ubicación, rubro, habilitaciones y especializaciones, para que de esa forma pueda ver las ofertas de materiales o residuos. **GONZALO: ¿PORQUÉ PARA LAS EMPRESAS NO PEDIMOS DATOS SIMILARES?**

Como emprendedor, quiero poder buscar materiales ofrecidos por empresas mediante palabras clave, categorías, o por zona, para de esa forma obtener insumos para mi emprendimiento.

Como emprendedor, quiero saber qué materiales se generan constantemente, para de esa forma planificar que insumos tengo disponibles.

Como emprendedor, quiero saber cuándo un material o residuo se genera puntualmente, para de esa forma determinar oportunidades de desarrollar nuevos productos.

Como empresa, quiero saber todos los materiales o residuos entregados en un período de tiempo, para de esa forma tener un seguimiento de su reutilización.

Como emprendedor, quiero saber cuántos materiales o residuos consumí en un período de tiempo, para de esa forma tener un control de mis insumos.

### Persistencia de la información
Cómo ya te habrás dado cuenta, nuestro chatbot necesitará guardar la información de empresas, emprendedores, materiales, etc. Para esto te brindaremos una interface que te permitirá realizar persistencia de datos (guardar y recuperar) y luego una implemnentación utilizando archivos. Tengan presente, que a los profes les gusta guardar información en bases de datos, así que si cambiamos la implementación de la interface, el chatbot debería seguir funcionando sin cambios.

## Roadmap y Entregables
| Instancia | Fecha | Entregables |
| --- | --- | --- |
| Kick-off | 6 de Setiembre |
| Primer Entrega | 29 de Setiembre | Entrega de tarjetas CRC/Diagrama de Clases.<sup>1</sup>
| Segunda Entrega | 3 de Noviembre | Entrega de [User Stories](https://es.wikipedia.org/wiki/Historias_de_usuario) implementadas. **GONZALO, A VER QUÉ TE PARECE LO SIGUIENTE** Las historias de usuario deberán ser implementadas mediante casos de prueba.
| Entrega Final | 1 de Diciembre<sup>2</sup>|

<sup>1</sup> Cada equipo designará qué integrante del equipo desarrollará cada clase. La distribución debe contemplar número de clases y responsabilidades. Se evaluará que cada integrante trabaje en una rama independiente y que se integren los cambios mediante pull requests.

<sup>2</sup> _Las entregas serán hasta las 23:59 del día indicado._ **GONZALO: LA HORA NO DEBERÍA SER DIFERENTE PARA LA MAÑANA Y PARA LA NOCHE?**
