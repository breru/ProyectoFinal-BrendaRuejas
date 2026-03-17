# **Proyecto de Testing QA - TikTok Lite**



###### **Integrante: Brenda Ruejas**







### Objetivo



El presente proyecto está destinado a la aplicación de los conocimientos de testing manual de software a los fines de evaluar el funcionamiento de la aplicación TikTok Lite para dispositivos móviles con SO Android.

Para ello se diseñaron casos de prueba funcionales que han sido ejecutados para validar el comportamiento del sistema y a partir de allí detectar los posibles defectos y documentar los resultados obtenidos durante el proceso.

Es por esto que el proyecto incluye los respectivos casos de prueba, como también su correspondiente ejecución y las evidencias de cada caso. Además cuenta con el reporte de bugs, elaboración de informes a partir de lo observado, junto con las pruebas de API utilizando herramientas de testing.



### Alcance



Los casos de prueba se enfocaron en validar las funcionalidades principales del sistema, desde la perspectiva del usuario final. Dichas funcionalidades incluyen: 

* Pruebas funcionales sobre la aplicación
* Validación de flujos principales como registro, login, perfil, navegación
* Ejecución de un total de 37 casos de prueba
* Identificación y documentación de bugs
* Pruebas de API en Fake Store API y utilización de Postman
* Validación de respuestas HTTP y de estructura JSON



### Entorno de prueba



Los casos de prueba han sido ejecutado bajo las siguientes condiciones:



* DISPOSITIVO: teléfono móvil Samsung Galaxy A56 5G
* SO: Android 16
* CONECTIVIDAD: Conexión a red wifi privada
* APLICACIÓN: TikTok Lite (versión pública en Google Playstore)
* TIPOS DE PRUEBAS: funcionales manuales
* HERRAMIENTAS:

  * Postman (API testing)
  * Excel (matriz de casos de prueba)
  * Git y GitHub



### Resultados 



En total se ejecutaron 37 casos de prueba, de los cuales:



 	- PASS: 33

 	- FAIL: 4

 	- BLOCKED: 0



### Bugs identificados



1. Mensaje de validación incompleto para el campo Nombre de usuario
2. Inconsistencia visual entre Modo claro / Modo oscuro (no reproducible)
3. Pérdida de estado de la aplicación al volver desde segundo plano
4. Falla en la aplicación de políticas de la empresa en la restricción de cambio de nombre de usuario y de perfil



### Testing de APIs



Se registraron 11 casos de prueba sobre los endpoints de Fake Store API:

* Métodos: GET, POST, PUT, DELETE
* Casos positivos y negativos
* Validación de estructura JSON



Resultado: status PASS para todas las pruebas considerando el comportamiento esperado de una API pública simulada para su testeo



### Conclusiones



De acuerdo con los resultados obtenidos y su posterior análisis, la aplicación logra cumplir con un funcionamiento estable en la mayoría de los escenarios evaluados con cada caso de prueba. Los defectos identificados son considerados de severidad media y baja, pero que no afectan a su uso principal, aunque impactan en la experiencia del usuario. Se considera que la aplicación puede ser utilizada, aunque se recomienda su revisión y mejora de los bugs encontrados para que la experiencia de usuario sea más óptima y así mejorar la calidad del producto.





### Observaciones

* Buen comportamiento general en sus funcionalidades
* Los bugs no afectan su uso

