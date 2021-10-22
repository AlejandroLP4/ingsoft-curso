# XML
El XML __(siglas en ingles eXtensible Markup Lenguage)__  comenzo a desarrollarse a fines de 1996 a instancias del World Wide Web Consortium con la intención de crear un estandar en el lenguaje de marcas que permitiera integrar la simplicidad que ofrece el HTML y las posibilidades de expresión del GML, proviene de un lenguaje inventado por IBM en los años 70´s, que surgió por necesidad que tenía la empresa de almacenar grandes cantidades de información y compartirlas en otros SO y plataformas.

Su objetivo es facilitar la representación, almacenamiento y tansmisión de información varia por parte de aplicaciones informáticas, computadoras y medios de comunicación digital en general.

XML no es un lenguaje en particular sino sirve de marco para definir lenguajes para diferentes necesidades. Algunos ejemplos son XHTML, XSLT, SOAP.

<img src="https://blog.gosocket.net/wp-content/uploads/2015/03/Collection-of-XML-documents.png" alt="">

__¿Que es XML?__

XML es el acrónimo de Extensible Markup Language, es decir, es un lenguaje de marcado que define un conjunto de reglas para la codificacón de documentos.
El lenguaje de marcado es un conjunto de códigos que se pueden aplicar en el análisis de datos o la lectura de textos creados por computadoras o personas. El lenguaje XML proporciona una plataforma para definir elementos para crear un formato y generar un lenguaje personalizados.

<img src="https://tecnologia-facil.com/wp-content/uploads/2019/10/que-es-xml-1.jpg" alt="">

__Caracteristicas__

+ Permite la creación de etiquetas propias y permite asignar atributos a las etiquetas.
+ En un documento XML la estructura y el diseño estan completamente separados.
+ XML se almacena en formato texto (no binario) lo cual hace que los documentos sean directamente entendibles.
+ Cada documento incluye metadatos sobre si mismo, lo cual facilita la tarea de los motores de búsquedas en la web, ya que devolverán respuestas más adecuadas y precisas.
+ Permite la exportabilidad a otros formatos de publicación de datos.
+ XML es un estándar abierto no sujeto a ningun tipo de licencia.
+ XML permite la internacionalización, es decir puede trabajar con cualquier conjunto de caracteres, entre ellos el juego de caracteres UNICODE.
+ XML itiliza reglas de generación concretas y, por tanto, los documentos son fácilmente entendibles. 
+ XML permite compartir información entre sistemas o fuentes de datos heterogéneas, por ejemplo, paginas web, distintas bases de date, entre otras.

<img src="https://www.danysoft.com/wp-content/uploads/2018/08/XML-WEB-1-1500x430.jpg" alt="">

__Principales usos:__

__*XML aplicado a los sitios web*__

Permite separar el contenido de la presentación y que los mismos datos se puedan mostrar varias fromas distintas sin demasiado esfuerzo.

__*XML para la comunicación entre aplicaciones*__

Representación de los datos muy simple y fácil de transmitir por la red.

__*Aplicaciones heredadas*__

Acceso a datos de aplicaciones que ya no están en uso o incompatibles por diferencias entre versiones.

<img src="https://desarrolloweb.com/storage/tag_images/actual/l0Y74ZmHXhjCyoaFWL9edPW6tT07tqyyvoiLmyPU.png" alt="">

__Ventajas y desventajas de XML__

La creación de bases de datos en lenguaje XML tiene diversas ventajas y desventajas:

__*Ventajas*__

Las principales ventajas de las bases de datos XML son:

+ Son fáciles de leer.
+ Los documentos XML son sencillos de procesar.
+ Es un lenguaje que tiene una gran compatibilidad con SGML.
+ El lenguaje XML es sencillo de estructurar con lo que se pueden diferenciar fácilmente las distintas partes de un documento.
+ Se pueden importar y exportar a otras aplicaciones, programas y formatos.
+ Para los que no dominan del todo el XML, exixten analizadores que permiten corregir errores de sintexis, como XML Copy Editor.
+ Los documentos se pueden actualizar simplemente añadiendo nuevas etiquetas.

__*Desventajas*__

Por su parte, tambien es necesario hacer mención a algunas de las desventajas de las bases de datos XML:

+ Son más lentas y requieren que los datos estén comprimidos para funcionar más rápidamente.
+ Las búsquedas son más lentas que en una base de datos relacional, ya que se deben organizar a travéz de texto y etiquetas.
+ Existe cierta limitación en cuanto a los gestores de base de datos pueden utilizar lenguaje XML.
+ Las bases de datos con documentos XML no están preparadas para el almacenamiento de información a largo plazo.
+ Pueden existir problemas para garantizar la seguridad de los datos. Por ejemplo, no se pueden configurar para definir quién puede actualizar, añadir o eliminar la imformación de la base de datos.

<img src="https://ideasenlinea.com/wp-content/uploads/2021/04/abrir-archivos-xml-2.jpg" alt="">

__Fuentes de consulta de XML:__

+ https://lm-xml-apuntes.readthedocs.io/apuntes/10_introduccion_xml.html.
+ https://www.ecured.cu/XML#Historia
+ https://rockcontent.com/es/blog/que-es-xml/
+ https://ayudaleyprotecciondatos.es/bases-de-datos/xml/

# JSON
A principios de la década de los 90's surgió el problema de que las maquinas pudieran entenderse entre si. Entonces utilizaban diferentes sistemas operativos y sus programas estaban escritos en diferentes lenguajes de programación. Una de las creaciones fue crear el éstandar XML.

Sin embargo, XML presentaba problemas sobre todo cuando se trataba de trabajar con gran volumen de datos, su procesamiento se volvia lento. Surgieron entonces intentos para definir dormatos que fueran más ligeros y rapidos para el intercambio de información. Uno de ellos fue __JSON__, promovido y popularizado a principios de los 2000 por __Douglas Crockford__, un programador conocido como el __*gurú*__ de JavaScript.

Desde entonces JSON se caracteriza por reducir el tamaño de los archivos y el volumen de datos que es necesario transmitir.

<img src= "https://png.pngtree.com/png-vector/20190330/ourlarge/pngtree-json-file-document-icon-png-image_897441.jpg" alt="">

__¿Que es JSON?__

JSON (JavaScript Object Notation) es un formato de texto pensado para el intercambio de datos. Su sintaxis está basada originalmente en la sintaxis de JavaScript, pero realmente es independiente de cualquier lenguaje de programación.

<img src= "https://store-images.s-microsoft.com/image/apps.54295.14007053301936083.39ffa2e2-e36c-4fd9-8bc6-c12766a7ce38.192d8dd4-5fdc-4c9e-a0d7-599ea2b89c42" alt="">

__Caracteristicas__

+ JSON es solo un formato de datos.
+ Requiere usar comillas dobles para las cadenas y los nombres de propiedades. Las comillas simples no son válidas.
+ Una coma o dos puntos mal hubicados pueden producir que un archivo JSON no funcione.
+ Puede tomar la forma de cualquier tipo de datos que sea válido para ser incluido en un JSON, no solo arreglos u objetos. Asi, por ejemplo, una cadena o número único podrían ser objeros JSON válidos.
+ A diferencia del código JavaScript, en el que las propiedades del objeto pueden no estar entre comillas, en JSON solo las cadenas entre comillas pueden ser utilizadas como propiedades.

<img src="https://miracomosehace.com/wp-content/uploads/mch/representacion-grafica-archivo-json_14157.jpg" alt="">

__Principales usos:__

JSON es un formato de texto completamente independiente de lenguaje, pero se utiliza convenciones que son ampliamenye conocidos por los programadores, entre ellos:

+ C
+ C++
* C#
* Java
* JavaScript
* Perl
* Python
* Entre otros

<img src="https://estradawebgroup.com/ImagesUpload/json-to-c.png" alt="">

__Ventajas y desventajas de JSON__

__*Ventajas*__

Unas de las ventajas de JSON son:

+ Es autodescriptivo y fácil de entender.
+ Su sencillez le ha permitido posicionarse como alternativa a XML.
+ Es más rápido en cualquier navegador.
+ Es más fácil de leer que XML.
+ Es más ligero (bytes) en las transmisiones.
+ Se parsea más rapido.
+ Velocidad de procesamiento alta.
+ Puede ser entendido de forma nativa por los analizadores de JavaScript.

__*Desventaja*__

Una de las desventajas de JSON son:

+ Algunos desarrolladores encuentran su escueta notación algo confusa.
+ No cuenta con una caracteristica que posee XML: extensibilidad.
+ No soporta grandes cargas, solo datos comunes.
+ Para la seguridad requiere de mecanismos externos como expresiones regulares.

<img src="https://desarrolloweb.com/storage/tag_images/actual/bZFSnglVmxfBmRRLl70XSVNPJjd5Be3s2qHVsfYl.png" alt="">


__Ejemplo de XML y JSON__

<img src="https://duenaslerin.com/pmdm/imgs/json-vs-xml.png" alt="">


__Fuentes de consulta de JSON:__

+ https://www.mclibre.org/consultar/informatica/lecciones/formato-json.html
+ https://www.nextu.com/blog/que-es-json/
+ https://cambiodigital-ol.com/2019/10/json-que-es-como-usarlo-y-con-que-herramientas/
