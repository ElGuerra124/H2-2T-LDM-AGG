Este proyecto trata de la representacion de los datos de un archivo json en nuestro sitio html para mostrar los datos de los pedidos de nuestra empresa durante 2021 y 2022

Te incluyo los siguientes:

# Proyecto de Gestión de Pedidos

## Descripción

Este proyecto es una aplicación web sencilla que muestra información de pedidos, clientes y ventas a partir de un archivo JSON. Los datos se cargan dinámicamente y se presentan en tablas HTML.

## Estructura del Proyecto

- `index.html`: Contiene la estructura HTML de la página.
- `H2-2T-AGG.js`: Archivo JavaScript que maneja la carga y visualización de datos desde el archivo JSON.
- `H2-2T-AGG.json`: Archivo JSON que contiene los datos de pedidos, clientes y ventas.
- `stiles.css`: Archivo CSS para el diseño de la página.

## Instrucciones de Uso

1. Clonar el repositorio o descargar los archivos.
2. Abrir `index.html` en un navegador web.
3. La aplicación cargará automáticamente los datos del archivo `H2-2T-AGG.json` y los mostrará en las tablas correspondientes.

## Posibles Errores y Mejoras

### Errores

1. **Fetch no funciona correctamente**: Hay un error tipográfico en la llamada a `fetch`. La respuesta no está siendo convertida a JSON correctamente.
    ```javascript
    fetch('H2-2T-AGG.json')
        .then(Response => response.json) // Error aquí
    ```
    Debería ser:
    ```javascript
    fetch('H2-2T-AGG.json')
        .then(response => response.json())
    ```

### Colaboración

Si deseas colaborar en este proyecto, puedes hacerlo de las siguientes maneras:

1. Reportando errores en el código.
2. Proponiendo mejoras o nuevas características.
3. Contribuyendo con código a través de pull requests.

Para más detalles, por favor abre un issue o un pull request en el repositorio del proyecto.

### Licencia

Este proyecto está licenciado bajo la Licencia MIT. Licencia MIT

Por la presente se concede permiso, libre de cargos, a cualquier persona que obtenga una copia
de este software y archivos de documentación asociados (el "Software"), para utilizar el Software sin restricción,
incluyendo sin limitación los derechos para usar, copiar, modificar, fusionar, publicar, distribuir, sublicenciar,
y/o vender copias del Software, y para permitir a las personas a quienes se les proporcione el Software a hacer lo mismo,
sujeto a las siguientes condiciones:

El aviso de derechos de autor anterior y este aviso de permiso se deberán incluir en todas las copias o partes sustanciales del Software.

EL SOFTWARE SE PROPORCIONA "TAL CUAL", SIN GARANTÍA DE NINGÚN TIPO, EXPRESA O IMPLÍCITA, INCLUYENDO PERO NO LIMITADO A GARANTÍAS DE
COMERCIABILIDAD, IDONEIDAD PARA UN PROPÓSITO PARTICULAR Y NO INFRACCIÓN. EN NINGÚN CASO LOS AUTORES O TITULARES DEL DERECHO DE AUTOR
SERÁN RESPONSABLES POR NINGUNA RECLAMACIÓN, DAÑO O OTRA RESPONSABILIDAD, YA SEA EN UNA ACCIÓN DE CONTRATO, AGRAVIO O DE OTRO MODO,
QUE SURJA DE, FUERA O EN CONEXIÓN CON EL SOFTWARE O EL USO U OTROS TRATOS EN EL SOFTWARE.


### Autor

Este proyecto fue desarrollado por **Alberto Guerra**, estudiante de 1ro de ASIR - CampusFp.

