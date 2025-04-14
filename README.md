# Web-Scraping

El web scraping, también conocido como extracción de datos web, es una técnica automatizada utilizada para recopilar información de sitios web. Consiste en extraer datos de páginas web, ya sea de manera manual o, más comúnmente, mediante programas informáticos, para luego procesar y analizar esos datos. 

El proceso de web scraping generalmente implica enviar solicitudes HTTP a un sitio web y luego analizar el HTML o XML resultante para extraer la información deseada. Puede ser utilizado para recopilar datos como precios de productos, información de noticias, reseñas de productos, datos meteorológicos y mucho más.

### Web crawling

El web crawling, también conocido como rastreo web o spidering, es el proceso de navegar automáticamente por la World Wide Web y recopilar información sobre sitios web. Estos crawlers siguen enlaces de una página a otra, indexando el contenido de los sitios web que visitan.

El objetivo principal del web crawling es recopilar datos para construir índices de búsqueda utilizados por motores de búsqueda como Google, Bing y otros. Estos índices permiten a los motores de búsqueda ofrecer resultados rápidos y relevantes cuando los usuarios realizan consultas.

El proceso de web crawling implica enviar solicitudes HTTP a las páginas web, recuperar el contenido HTML de esas páginas y luego analizar ese contenido para extraer información relevante. Los crawlers también siguen enlaces dentro de las páginas para descubrir nuevas páginas y ampliar su alcance.

Es importante destacar que el web crawling se realiza de manera automatizada y a gran escala para gestionar el vasto y dinámico contenido de la web. Además, los web crawlers deben seguir las reglas establecidas por los sitios web a través del archivo robots.txt para respetar las políticas de exclusión de rastreo y evitar sobrecargar los servidores de un sitio específico.

# API

Interfaz de Programación de Aplicaciones (API), es un conjunto de reglas y protocolos que permite a una aplicación o servicio comunicarse con otro. En términos simples, una API define la forma en que los componentes de software deben interactuar.

Las API actúan como intermediarios que permiten que diferentes aplicaciones se comuniquen entre sí. Proporcionan un conjunto de funciones, métodos y reglas que permiten a los desarrolladores acceder a ciertas características o datos de una aplicación, servicio o plataforma, sin necesidad de conocer los detalles internos de su implementación. Esto facilita la integración de servicios y la construcción de aplicaciones más complejas a partir de componentes existentes.

Hay varios tipos de API, pero las dos categorías principales son:

- **APIs web (Web APIs):** Estas son APIs que se acceden a través de Internet mediante protocolos como HTTP. Las API web son comunes en el desarrollo de aplicaciones web y móviles. Pueden devolver datos en formatos como JSON (JavaScript Object Notation) o XML (eXtensible Markup Language).

- **APIs de bibliotecas o SDK (Software Development Kit):** Estas son APIs que se proporcionan como parte de una biblioteca o conjunto de herramientas de desarrollo. Los desarrolladores pueden utilizar estas APIs para acceder a funciones específicas o servicios sin tener que escribir todo el código desde cero.

# API vs Web scraping

API y web scraping son enfoques diferentes para obtener datos de la web, y cada uno tiene sus propias características y casos de uso específicos. Las diferencias clave son:

### Acceso a datos:

- **API:** Proporciona un acceso estructurado a datos a través de interfaces predefinidas. Los datos se entregan generalmente en un formato específico, como JSON o XML, facilitando su manipulación.
- **Web scraping:** Involucra extraer datos directamente del HTML de las páginas web. Los datos extraídos pueden requerir un procesamiento adicional para estructurarse de manera útil.

### Integración y automatización:

- **API:** Diseñada para facilitar la integración entre aplicaciones y servicios. Permite la automatización de procesos y la transferencia de datos de manera eficiente.
- **Web scraping:** Puede ser más manual y propenso a cambios en la estructura de la página web. La automatización puede ser más complicada y menos confiable en comparación con el uso de APIs.

### Legalidad y ética:

- **API:** Se utiliza de acuerdo con los términos de servicio proporcionados por el proveedor de la API. Generalmente, el acceso a través de una API es legal y ético, siempre y cuando se respeten las restricciones y políticas establecidas.
- **Web scraping:** Puede estar sujeto a restricciones legales y éticas, ya que algunos sitios web prohíben explícitamente la extracción automatizada de datos en sus términos de servicio.

### Estructura y mantenimiento:

- **API:** Ofrece una interfaz más estable y estructurada. Cambios en la estructura de los datos o en la API se comunican a los desarrolladores de manera controlada.
- **Web scraping:** Puede volverse frágil si hay cambios en la estructura de la página web, ya que depende directamente de la presentación HTML de la página.

### Desempeño:

- **API:** Suele ser más eficiente y rápida, ya que se diseñó para entregar datos de manera optimizada.
- **Web scraping:** Puede ser más lento y demandante de recursos, ya que implica descargar y analizar el contenido completo de las páginas web.

En resumen, mientras que las APIs proporcionan un acceso estructurado y más confiable a datos en línea, el web scraping puede ser una solución cuando no hay una API disponible o para obtener datos específicos de una página web. Sin embargo, es crucial respetar los términos de servicio y las leyes aplicables al realizar web scraping.

# Conceptos básico sobre la web


- **URL (Uniform Resource Locator):** Una URL es la dirección única que se utiliza para localizar un recurso en la web. 

- **Protocolo HTTP/HTTPS:** Hypertext Transfer Protocol (HTTP) y su versión segura HTTPS (Hypertext Transfer Protocol Secure) son protocolos de comunicación utilizados para la transmisión de información en la web. HTTPS cifra la comunicación para mayor seguridad.

- **Servidor web:** Un servidor web es un software que responde a las solicitudes de los navegadores, entregando páginas web al cliente. Algunos servidores web populares son Apache, Nginx e IIS.

- **Dominio:** Un dominio es una identificación alfanumérica única asociada con una dirección IP en internet. Los dominios son utilizados en las URL para identificar sitios web. Por ejemplo, "ejemplo.com" es un dominio.

### HTTP status codes

Son indicadores numéricos que se devuelven en las respuestas de las solicitudes HTTP para proporcionar información sobre el estado de la solicitud al cliente. Los códigos más comunes son:

**1xx (Respuestas informativas):**

- 100 Continue: La solicitud ha sido recibida y el servidor espera que el cliente continúe con la solicitud.

**2xx (Respuestas satisfactorias):**

- 200 OK: La solicitud ha sido exitosa. El significado exacto puede depender del método de solicitud utilizado.

- 201 Created: La solicitud ha sido exitosa y ha resultado en la creación de un nuevo recurso.

- 204 No Content: La solicitud ha sido exitosa, pero no hay contenido para enviar en la respuesta.

**3xx (Redirecciones):**

- 301 Moved Permanently: La página solicitada ha sido trasladada permanentemente a otra ubicación.

- 302 Found (o 303 See Other): La página solicitada ha sido trasladada temporalmente a otra ubicación.

**4xx (Errores del cliente):**

- 400 Bad Request: La solicitud no pudo ser entendida o contiene parámetros inválidos.

- 401 Unauthorized: La autenticación es necesaria y ha fallado o no se ha proporcionado.

- 403 Forbidden: El servidor entendió la solicitud, pero se niega a autorizarla.

- 404 Not Found: El recurso solicitado no se encuentra en el servidor.

**5xx (Errores del servidor):**

- 500 Internal Server Error: Un error genérico del servidor. Indica que algo salió mal en el servidor.

- 501 Not Implemented: El servidor no puede cumplir con la solicitud. Este código se genera cuando el servidor no reconoce el método de solicitud.

- 503 Service Unavailable: El servidor no está listo para manejar la solicitud. Comúnmente se utiliza cuando el servidor está en mantenimiento o sobrecargado.

# Document Object Model (DOM)

Es una representación jerárquica de la estructura de un documento HTML o XML. El DOM es esencial en la programación web, ya que proporciona una interfaz estructurada y orientada a objetos que permite a los programas y scripts manipular la estructura, el estilo y el contenido de un documento web de manera dinámica. En otras palabras, el DOM actúa como una interfaz de programación que permite a los desarrolladores interactuar y manipular los elementos de una página web utilizando lenguajes de programación como JavaScript.

Algunas características clave del DOM son:

Árbol de nodos: La estructura del DOM se organiza como un árbol de nodos, donde cada elemento HTML en la página es representado por un nodo en el árbol.

Nodos: Cada parte de un documento HTML (como elementos, atributos, texto) es un nodo en el DOM. Los nodos pueden tener relaciones padre-hijo, hermano-hermano, etc.

Manipulación dinámica: Los desarrolladores pueden utilizar el DOM para agregar, eliminar o modificar elementos y atributos en una página web después de que la página ha cargado. Esto permite la creación de aplicaciones web interactivas y dinámicas.

Interactividad: Eventos como clics de ratón, teclas presionadas o cambios en el contenido pueden desencadenar acciones que modifican el DOM. Esto permite respuestas interactivas a las acciones del usuario.

En resumen, el DOM es una interfaz que permite a los desarrolladores web acceder y manipular la estructura y contenido de una página web. Es fundamental en la programación web moderna y es utilizado extensamente para crear aplicaciones interactivas y dinámicas.


<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/DOM-model.svg/1200px-DOM-model.svg.png" width=50%>

# Flujo de trabajo

- Pedimos la información de la página al servidor (HTTP request)

- Parseamos el HTML (u otro formato) que recibamos

- Procesamos la información y la guardamos


### Web Scraping con Python y BeautifulSoup

Beautiful Soup es una biblioteca de Python que facilita el web scraping al proporcionar herramientas para extraer información de páginas HTML o XML. 

Crea un árbol de análisis a partir del código fuente de la página.

<image src="https://miro.medium.com/v2/resize:fit:1400/0*ETFzXPCNHkPpqNv_.png" width=50%>

<image src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/DOM-model.svg/1200px-DOM-model.svg.png" width=50%>
