# objetos_js

## Principal use de location
El principal uso de la "location" (ubicación) en programación depende del contexto en el que se esté utilizando. En muchos casos, "location" se refiere a la ubicación física o geográfica de un objeto, dispositivo o usuario, y su uso principal es en aplicaciones que requieren servicios de localización, como aplicaciones de mapas, aplicaciones de navegación, aplicaciones de entrega de comida a domicilio, redes sociales con funciones de geolocalización, entre otros.

En términos de programación, "location" puede hacer referencia a variables o propiedades que almacenan información sobre la ubicación actual de un objeto o entidad en el espacio físico o virtual. Estas ubicaciones pueden ser representadas de diversas formas, como coordenadas geográficas (latitud y longitud), direcciones, nombres de lugares, entre otros.

Además, en el contexto web, "location" se utiliza para acceder y manipular la URL (Uniform Resource Locator) de una página web, lo que permite redireccionar o cambiar la ubicación actual del navegador web.

## PROPIEDADES
En programación, la "location" puede referirse a diferentes cosas dependiendo del contexto. Si estás hablando específicamente sobre el objeto "location" en el contexto de navegación web en JavaScript, por ejemplo, las principales propiedades que puedes encontrar son:

1. **location.href**: Esta propiedad devuelve la URL completa de la página actual, incluyendo el protocolo (http:// o https://), el dominio, el puerto (si se especifica) y la ruta.

2. **location.protocol**: Devuelve el protocolo de comunicación utilizado (http: o https:).

3. **location.hostname**: Devuelve el nombre de host del servidor web donde está alojada la página actual.

4. **location.port**: Devuelve el número de puerto del servidor web donde está alojada la página actual.

5. **location.pathname**: Devuelve la ruta de acceso y el nombre del archivo de la URL de la página actual.

6. **location.search**: Devuelve la cadena de consulta de la URL de la página actual, incluyendo el signo de interrogación (?).

7. **location.hash**: Devuelve el fragmento identificador (hash) de la URL de la página actual, incluyendo el signo de almohadilla (#).

## METODOS
-  Assign(url): Este método carga el documento ubicado en la URL especificada en el navegador. Es similar a hacer clic en un enlace.
```Javascrip
location.assign("https://www.ejemplo.com");
```

- reload(forcedReload): Este método recarga la página actual. Si se le pasa true como argumento (forcedReload), fuerza una recarga desde el servidor, ignorando la caché.

```Javascrip
location.reload();
```
- replace(url): Este método carga un nuevo documento, reemplazando la entrada actual en el historial del navegador. Esto significa que el usuario no puede regresar a la página anterior utilizando el botón de atrás del navegador.

```Javascrip
location.replace("https://www.ejemplo.com");
```
- toString(): Este método devuelve la URL de la página actual como una cadena de caracteres.

```Javascrip
var currentURL = location.toString();
```