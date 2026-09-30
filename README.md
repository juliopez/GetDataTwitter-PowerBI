# GetDataTwitter-PowerBI

Material docente complementario al video **“GetTwitter with PowerBI / Analizando Twitter con PowerBI”**, publicado en 2021. El repositorio conserva el script de Power Query (lenguaje M) utilizado en la demostración para consultar datos de Twitter desde Power BI.

## Video asociado

▶️ **YouTube:** https://youtu.be/usaaMRB9Hho

## Contenido del repositorio

- `GetDataTwitterconPowerBI`: script de Power Query utilizado en el video.

El script muestra el flujo empleado en la demostración original:

1. Construcción de la autenticación a partir de Consumer Key y Consumer Secret.
2. Obtención de un token de acceso mediante OAuth 2.0.
3. Consulta de tweets utilizando la API REST de Twitter.
4. Conversión de la respuesta JSON a una tabla para su análisis en Power BI.

El código utiliza una variable `Busqueda` definida desde Power BI para establecer el término de consulta.

## Uso docente

Este repositorio fue creado para que estudiantes y personas que siguieran el video pudieran disponer del código utilizado durante la demostración y reproducir el procedimiento en su propio entorno.

> **Importante:** el archivo no contiene credenciales reales. Los valores `<Aqui-pegar-ConsumerKey>` y `<Aqui-pegar-ConsumerSecret>` son marcadores que deben sustituirse por las credenciales correspondientes.

## Vigencia tecnológica

Este material corresponde al ecosistema de **Twitter y su API en 2021**. Desde entonces Twitter pasó a denominarse **X** y sus API, mecanismos de acceso, endpoints, planes y condiciones de uso han cambiado.

Por esta razón, el script se conserva **como material docente e histórico asociado al video original** y no debe interpretarse como una implementación actual de la API de X. Puede requerir modificaciones sustanciales para funcionar con servicios actuales.

## Fuente del script

El archivo original incluye como referencia:

- Chris Koester, *Get Data from Twitter API with Power Query*: http://chris.koester.io/index.php/2015/07/16/get-data-from-twitter-api-with-power-query/

## Autor

**Dr. Julio López-Núñez**  
Material docente sobre Business Intelligence, Power BI y analítica de datos.
