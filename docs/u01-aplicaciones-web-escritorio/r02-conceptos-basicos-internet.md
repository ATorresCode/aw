# R2: Conexiones, nube y navegación por Internet

La diferencia entre Internet y la Web, el modelo cliente-servidor, los navegadores y la evolución de la Web se explican en [R1: Internet, la Web y sus aplicaciones](r01-internet-y-web.md). En esta página nos centramos en las formas de conectarse, los servicios en la nube y algunos conceptos prácticos para navegar.

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; margin: 1.5rem 0;">
  <iframe src="https://www.youtube.com/embed/jKA5hz3dV-g?start=88" title="Video introductorio sobre Internet y conectividad" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
</div>

## 1. Cómo nos conectamos a Internet

El **proveedor de servicios de Internet** (ISP, por sus siglas en inglés) conecta el hogar, el centro educativo o la empresa a Internet. La tecnología disponible, la cobertura y las condiciones del plan dependen de la ubicación y del proveedor.

### Tecnologías de acceso

- **Acceso telefónico (*dial-up*):** utilizaba la línea telefónica fija y era una conexión lenta. Mientras se usaba, no permitía utilizar esa línea para llamadas al mismo tiempo. Está obsoleta y se incluye aquí como referencia histórica.
- **DSL (Digital Subscriber Line):** ofrece banda ancha a través de la línea telefónica y permite usar Internet y el teléfono simultáneamente. En muchas zonas ha sido sustituida por fibra.
- **Cable coaxial:** ofrece banda ancha a través de una red de cable. Las prestaciones pueden variar según la tecnología y la zona.
- **Fibra óptica:** transmite datos mediante señales luminosas por cables de fibra. Suele ofrecer conexiones rápidas y estables; su disponibilidad depende del despliegue de la red.
- **Red móvil (4G y 5G):** proporciona acceso inalámbrico a través de antenas del operador. La cobertura, la congestión de la red, el dispositivo y el plan contratado influyen en la velocidad y los datos disponibles.
- **Internet por satélite:** puede ofrecer conexión en lugares donde no llegan redes terrestres. La latencia y las condiciones del servicio dependen de la tecnología y del proveedor. Por ejemplo, Starlink utiliza satélites de órbita baja para reducir la latencia y mejorar la velocidad.

### Velocidad y calidad de la conexión

Los planes suelen expresar la velocidad en **Mbps** (megabits por segundo), a menudo con valores distintos para las descargas y las subidas. Un megabyte (MB) contiene ocho megabits (Mb), por lo que Mbps y MB/s no son la misma unidad.

La velocidad anunciada no siempre coincide con la que se obtiene: puede variar por la cobertura, la congestión, el equipo y la conexión entre el dispositivo y el router. La **latencia**, medida normalmente en milisegundos (ms), indica cuánto tarda en responder la conexión y es especialmente importante en videollamadas, juegos en línea y otras comunicaciones en tiempo real.

Algunos buscadores, como Google, ofrecen servicios de prueba de velocidad que permiten comprobar la conexión y la latencia. También existen servicios independientes, como [Speedtest](https://www.speedtest.net/).

### Hardware de red doméstica

- **Módem:** establece la comunicación con el tipo de red del proveedor, por ejemplo una red de cable o DSL.
- **ONT:** en una instalación de fibra, el terminal de red óptica convierte la señal de la fibra para que pueda utilizarla el equipo de la red doméstica. Según la instalación, puede estar integrado con el router.
- **Router:** conecta los dispositivos de la red local y dirige el tráfico entre esta e Internet. El módem o la ONT y el router pueden estar en equipos separados o en un único dispositivo.
- **Punto de acceso Wi-Fi:** permite conectar dispositivos a la red local sin cable. **Wi-Fi es la conexión inalámbrica entre dispositivos y el router; no es en sí el servicio de Internet.**

## 2. La nube y las aplicaciones web

### Qué significa «la nube»

La **nube** (*cloud*) hace referencia a servicios y recursos disponibles a través de Internet. Cuando un archivo se guarda en la nube, se almacena en servidores remotos en lugar de depender únicamente del disco duro del dispositivo.

Algunos usos habituales son:

- **Almacenamiento de archivos:** guardar documentos, fotografías y otros datos para acceder a ellos desde distintos dispositivos. Algunos ejemplos son Google Drive y Dropbox.
- **Compartición de archivos:** facilitar que varias personas accedan a los mismos archivos.
- **Copias de seguridad:** mantener una copia remota que permita recuperar los datos si el dispositivo se pierde, se daña o deja de funcionar.

### Aplicaciones web

Una **aplicación web** permite realizar tareas desde un navegador y puede guardar o procesar información en servidores remotos. No es sinónimo de «nube»: hay servicios en la nube que no son aplicaciones web y algunas aplicaciones web ofrecen funciones que continúan disponibles sin conexión.

Las aplicaciones web no suelen requerir una instalación tradicional, aunque algunas pueden ofrecerse como aplicaciones web progresivas (PWA) e instalarse para facilitar el acceso. Antes de elegir una aplicación, resulta útil comprobar si funciona en los dispositivos previstos, qué puede hacer sin conexión y cómo almacena y protege los datos. Para ver cómo se organiza técnicamente una aplicación web, consulta [R1](r01-internet-y-web.md).

## 3. Navegadores, enlaces y búsquedas

### Hiperenlaces

Un **hiperenlace** (o enlace) lleva a otra página, documento o recurso. Antes de abrir un enlace, se puede comprobar la dirección de destino —por ejemplo, mediante la vista previa del navegador— y revisar el dominio, sobre todo si conduce a una página de inicio de sesión o solicita datos personales.

### Navegadores web

Un **navegador web** es la aplicación que utilizamos para abrir sitios y páginas web. Algunos ejemplos son Chrome, Firefox, Edge y Safari. Desde el navegador se pueden escribir direcciones URL, seguir enlaces, guardar marcadores y abrir varias páginas en pestañas.

### Motores de búsqueda

Un **motor de búsqueda** es un servicio web que ayuda a localizar páginas e información. Se utiliza desde un navegador, escribiendo una consulta en la página del buscador o en la barra de búsqueda del navegador. Por ejemplo, Chrome es un navegador y Google es un motor de búsqueda: son herramientas distintas, aunque algunos navegadores integran un buscador para facilitar las consultas.

Para afinar una búsqueda, se pueden probar estas técnicas:

- Añadir palabras concretas sobre el tema, el lugar o la fecha.
- Usar comillas para buscar una expresión exacta: `"seguridad en Internet"`.
- Anteponer un signo menos para excluir un término: `jaguar -coche`.
- Limitar los resultados a un sitio o dominio con `site:`: `becas site:educacion.gob.es`.

Los resultados pueden incluir publicidad y no son necesariamente una clasificación de las fuentes más fiables. Antes de dar una información por válida, comprueba quién la publica, la fecha, las fuentes que cita y si otras fuentes fiables la corroboran.

## 4. Direcciones URL

Una **URL** (*Uniform Resource Locator*, o localizador uniforme de recursos) es la dirección que identifica dónde encontrar un recurso. Por ejemplo:

```text
https://www.ejemplo.com:443/carpeta/pagina.html?tema=web#resultados
```

- **Esquema:** `https` indica cómo se solicita el recurso. HTTP es el protocolo de la Web; HTTPS añade cifrado a la comunicación y permite verificar el sitio mediante certificados. **HTTPS protege la conexión, pero no demuestra por sí solo que el sitio sea legítimo o fiable.**
- **Nombre de dominio:** `www.ejemplo.com` identifica el servidor mediante un nombre fácil de leer. El DNS ayuda a localizar la dirección IP asociada al dominio. En el ejemplo, `www` es un subdominio y `.com` es el dominio de nivel superior.
- **Puerto (opcional):** `:443` señala el puerto de conexión para HTTPS, mientras que el puerto estándar para HTTP es 80. Los puertos estándar de HTTP y HTTPS suelen omitirse en la barra de direcciones.
- **Ruta:** `/carpeta/pagina.html` identifica un recurso dentro del sitio.
- **Parámetros (opcionales):** comienzan con `?` y transmiten datos adicionales, por ejemplo `tema=web`. Puede haber varios, separados por `&`.
- **Fragmento (opcional):** comienza con `#` y apunta a una sección del recurso, como `resultados`. Normalmente permite saltar a esa sección sin solicitar otra página al servidor.

## 5. Para ampliar

- [GCFGlobal: tutoriales de Internet](https://edu.gcfglobal.org/)
- [Almacenamiento en la nube](https://www.youtube.com/watch?v=4OO77HFcCUs&t=1s)
- [Navegadores web](https://www.youtube.com/watch?v=FxirRVJWUTs)
- [Motores de búsqueda](https://www.youtube.com/watch?v=7RlB1CJovTs)
