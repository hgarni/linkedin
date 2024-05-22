<center> 
<img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="Logo Linkedin" width="100" height="100">

# Profile Scraping in Linkedin

Extract information about a specific profile into Linkedin web

## Objetivo
Realizar Scraping en la página web de la red social Linkedin https://www.linkedin.com/ para poder automatizar el proceso de extracción de información sobre   perfiles de personas que debe arrojar una búsqueda laboral deseada. Por ejemplo "Cientifico de Datos".

<img src="https://i.ibb.co/k9M0B6n/Whats-App-Image-2024-05-15-at-23-03-09.jpg" alt="LogoLinkedin" width="80" height="30" border="0" />
es una red social profesional orientada a facilitar el establecimiento de contactos laborales y empresariales. Permite a sus usuarios crear perfiles que destacan sus habilidades, experiencia laboral, educación y logros. Estos perfiles actúan como un currículum digital.

La solución propuesta busca economizar los gastos relacionados a la suscripción de las siguientes herramientas:

<img src="https://i.ibb.co/89mm7y8/0-precios.jpg" alt="0-precios" border="0" />

## Tipos de aplicaciones 
Linkedin cuenta con distintos tipos de aplicaciones que permiten manipular la interacción con la pagina de la red social y poder manipular fácilmente dicha información. Para realizar el pedido de ellas se interactúa a través de su página para desarrolladores en el siguiente link:

https://developer.linkedin.com/

A los fines de poder acceder a la información de búsqueda de personal con específicos perfiles que deseamos obtener, en nuestro caso solicitamos permisos a las 2 siguientes aplicaciones:

API de portabilidad de datos de los miembros.

<img src="https://i.ibb.co/M1BMXsY/api-member.jpg" alt="api-member" border="0" />

API de portabilidad de datos de paginas.

<img src="https://i.ibb.co/8M74Qvp/api-page.jpg" alt="api-page" border="0" />


Estas solicitudes relacionadas con la gestión de productos para desarrolladores se someten a un proceso de revisión y aprobación y atraviesan las siguientes 3 etapas.

### Etapas de la solicitud

<img src="https://i.ibb.co/rwgYhc1/estado.jpg" alt="estado" border="0" />

En nuestro caso hemos atravesado dichas etapas en 2 oportunidades utilizando 2 cuentas de usuarios de Linkedin tanto del tipo “no paga” e incluso de tipo “paga” suponiendo que obtendríamos un resultado favorable.


### Tipos de rechazos
Existen diversos motivos por los cuales los pedidos de accesos a las aplicaciones pueden ser rechazados. 

<img src="https://i.ibb.co/nDHQbDr/mensaje.jpg" alt="mensaje" border="0" />

En nuestro caso intentamos con 2 cuentas diferentes y fuimos rechazados por “Política de privacidad no válida”.
Continuamos con la apelación de la misma y realizamos modificaciones en las respectivas páginas web en donde incorporamos las mencionadas políticas de privacidad en cuestión.  Al momento no hemos tenido respuesta satisfactoria despues de más de 3 semanas.
Por esto hemos decidido intentar realizar scraping sobre la página sin utilizar las API.

