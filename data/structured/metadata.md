 • Fuente de los Datos: API
 • Fecha de Recogida: 19/10/2024
 • Formato de los Datos: JSON 
 • Licencia de Uso: Licencias bajo las cuales se encuentran los datos (si aplica).
 • Descripción de las Variables o Atributos: 
    
En vivienda.csv:
1. propertyCode (Código de la Propiedad): Identificador único asignado a cada propiedad en Idealista. Tipo de Datos: Numérico (Entero).

2. url (Enlace):Dirección web específica donde se encuentra la página detallada de la propiedad en Idealista. Tipo de Datos: Cadena de texto (String).

3. address (Dirección):Ubicación física de la propiedad, incluyendo calle y número. Tipo de Datos: Cadena de texto (String).

4. size (Tamaño):Superficie total de la propiedad en metros cuadrados. Tipo de Datos: Numérico (Flotante).

5. floor (Piso):Nivel del edificio en el que se encuentra la propiedad. Puede estar vacío si la propiedad no está en un edificio de varios pisos. Tipo de Datos: Numérico (Entero) o vacío.

6. province (Provincia):Provincia en la que está ubicada la propiedad. Tipo de Datos: Cadena de texto (String).

7. municipality (Municipio):Municipio o ciudad específica donde se encuentra la propiedad. Tipo de Datos: Cadena de texto (String).

8. district (Distrito/Barrio):Distrito, barrio o zona específica dentro del municipio donde está situada la propiedad. Tipo de Datos: Cadena de texto (String).

9. price (Precio):Precio de venta de la propiedad en euros. Tipo de Datos: Numérico (Flotante).

10. rooms (Habitaciones):Número total de habitaciones en la propiedad. Tipo de Datos: Numérico (Entero).

11. hasLift (Tiene Ascensor):Indica si el edificio dispone de ascensor. Tipo de Datos: Booleano (True o False).

12. hasParking (Tiene Aparcamiento):Indica si la propiedad incluye un espacio de aparcamiento. Tipo de Datos: Booleano (True o False) o vacío si no se especifica.

13. hasTerrace (Tiene Terraza):Indica si la propiedad dispone de una terraza. Tipo de Datos: Booleano (True o False).

14. hasSwimmingPool (Tiene Piscina):Indica si la propiedad cuenta con una piscina. Tipo de Datos: Booleano (True o False).

15. hasAirConditioning (Tiene Aire Acondicionado):Indica si la propiedad está equipada con aire acondicionado. Tipo de Datos: Booleano (True o False).

16. hasGarden (Tiene Jardín): Indica si la propiedad dispone de un jardín. Tipo de Datos: Booleano (True o False).

17. bathrooms (Baños) Número total de baños en la propiedad. Tipo de Datos: Numérico (Entero).


En location.csv:
1. propertyCode (Código de la Propiedad): Identificador único asignado a cada propiedad en Idealista.  Tipo de Datos: Numérico (Entero).

2. latitude (Latitud): Coordenada geográfica que indica la posición norte-sur. Tipo de Datos: Numérico (Flotante).

3. longitude (Longitud)
Descripción: Coordenada geográfica que indica la posición este-oeste. Tipo de Datos: Numérico (Flotante).
