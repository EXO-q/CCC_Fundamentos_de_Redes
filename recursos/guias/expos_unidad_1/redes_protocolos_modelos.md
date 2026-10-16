# 12. Concepto de protocolo

- Define qué es un protocolo de comunicación y explica por qué es necesario para que dos dispositivos puedan intercambiar información correctamente.
- Utiliza un ejemplo cotidiano, como una conversación, para ilustrar la necesidad de establecer reglas comunes antes de presentar su aplicación en las redes informáticas.
- Incluye ejemplos de protocolos conocidos (como HTTP, TCP e IP) e indica, de forma simplificada, qué función cumple cada uno.
- Explica brevemente las principales características que permiten establecer una comunicación ordenada y confiable entre dispositivos.

# 13. Características de los protocolos

*Desarrolla las siguientes características:*

- Formato del mensaje
- Reglas de intercambio
- Sincronización
- Direccionamiento
- Detección de errores
- Control de flujo
- Seguridad

*Por cada característica:*

- Define en qué consiste y su razón.
- Menciona un protocolo que cumpla esa característica.

Por último, aclara que no todos los protocolos implementan estas características de la misma manera ni necesitan encargarse de todas ellas.

# 14. Estandarización de redes

- Inicia explicando qué es la estandarización y por qué es necesaria, especialmente para la existencia de Internet.
- Explica la existencia de las entidades de estandarización.

*Desarrolla las siguientes organizaciones de estándares:*

- **ISO** (International Organization for Standardization)
- **ITU** (International Telecommunication Union)
- **IEEE** (Institute of Electrical and Electronics Engineers)
- **IETF** (Internet Engineering Task Force)
- **ICANN** (Internet Corporation for Assigned Names and Numbers)
- **IANA** (Internet Assigned Numbers Authority)

*Por cada entidad:*

- Define su rol para el desarrollo de las redes.
- Si aplica, menciona los aportes más relevantes que ha realizado y su función.

Concluye diferenciando a las organizaciones que desarrollan estándares técnicos de aquellas que coordinan identificadores y recursos necesarios para el funcionamiento de Internet.

# 15. Encapsulamiento

- Define qué es el encapsulamiento y explica cómo cada capa de una arquitectura de red añade información de control a los datos para permitir su transmisión.
- Utiliza un diagrama que muestre cómo los datos atraviesan las capas del emisor y cómo se procesan en orden inverso en el receptor.
- *Explica las partes que pueden formar una unidad de datos encapsulada:*
	- Cabecera (header)
	- Carga útil (payload)
	- Tráiler (trailer)
- Define _overhead_ como la información adicional necesaria para gestionar la comunicación, que ocupa recursos de transmisión sin formar parte de los datos útiles de la aplicación. Incluye un ejemplo.
- Introduce el concepto de *Protocol Data Unit (PDU)* y ejemplifícalo.

# 16. Modelo OSI

- Explica qué es el modelo OSI y cuál es su propósito como modelo de referencia.
- Presenta sus siete capas en orden, desde la capa física hasta la de aplicación, indicando para cada una:
	- su nombre
	- su función principal
	- un ejemplo de tecnología, protocolo o mecanismo relacionado
- Explica cómo se distribuyen las responsabilidades entre las capas y cómo cada una proporciona servicios a la capa superior.
- Utiliza un esquema vertical para representar las siete capas y facilitar su memorización. Evita profundizar en protocolos específicos.

# 17. Modelo TCP/IP

- Define qué es el modelo TCP/IP y explica su relación con la arquitectura de protocolos utilizada en Internet.
- Presenta sus cuatro capas e indica para cada una:
	- su nombre
	- su función principal
	- un ejemplo de protocolo relacionado
- Representa el modelo mediante un esquema vertical y explica cómo colaboran sus capas para permitir que una aplicación intercambie información con otra a través de una red.

# 18. Relación entre modelos y protocolos

- Explica la diferencia entre un modelo de referencia, como OSI, y una arquitectura de protocolos, como TCP/IP.
- Relaciona las capas de ambos modelos mediante un esquema comparativo. Explica que la correspondencia es aproximada y que no existe una equivalencia exacta entre todas las capas.
- Selecciona un ejemplo de comunicación, como abrir una página web, e identifica los protocolos que intervienen en las distintas capas para ambos modelos.
- Utiliza ese ejemplo para mostrar cómo colaboran los protocolos y cómo el encapsulamiento permite que cada capa añada la información necesaria.
- Responde por qué se utiliza TCP/IP para las redes informáticas y no el modelo OSI.

# 19. Tipos de encapsulamiento

- Explica cómo cambia la denominación de la unidad de datos a medida que atraviesa las capas de los modelos de red.
- Describe las siguientes unidades e indica a qué capa del modelo TCP/IP se asocian cada una de ellas:
	- **Datos:** información gestionada por los protocolos de aplicación
	- **Segmento:** Es la unidad de datos propia de TCP en la capa de transporte. Si se utiliza UDP, se denomina normalmente _datagrama_.
	- **Paquete:** unidad de datos de la capa de Internet
	- **Trama:** unidad de datos de la capa de enlace
- Explica, con un diagrama, cómo los datos se encapsulan desde los datos de aplicación hasta la trama según el modelo TCP/IP.
- Luego, presenta cómo el receptor desencapsula el mensaje recibido realizando el proceso inverso.
