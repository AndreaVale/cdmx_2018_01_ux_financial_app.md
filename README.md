# Tus Finanzas App   :moneybag:

## Introducción    :yen:

México es un país con una insípida cultura del ahorro. Desafortunadamente para la generación Millenial (1982 a 2000 aproximadamente) la poca previsión del futuro acarreará un gran problema de niveles nacionales dentro de varios años.

Afortunadamente, según un estudio hecho por la firma de inversión Finx, esto está empezando a cambiar lentamente, pues las mexicanas y mexicanos están empezando a ahorrar a partir de los 25 años. Aunque este dato es alentador; aún hace falta un largo camino para que los mexicanos tengamos una buena cultura financiera y del ahorro.

La aplicación Fintech será de utilidad para ayudar a esta generación a ahorrar mediante la técnica SMART, en la cual busca fijar metas pequeñas y alcanzables, para esto se necesitan objetivos Específicos, Medibles, Alcanzables, Realistas en un corto Tiempo.

Para llegar a hacer esta implementación se hará en varias etapas. En este momento nos enfocaremos en la primera parte.

## Problema :money_with_wings:
A pesar de que en México se han hecho avances en la cuestión de bancarización, todavía alrededor del 56% de la ciudadanía no tiene una cuenta bancaria, según la Encuesta Nacional de Inclusión Financiera (ENIF) hecha por el Instituto Nacional de Estadística y Geografía (INEGI) y la Comisión Nacional Bancaria y de Valores (CNBV).

En esa misma encuesta se hace referencia a que la ciudadanía prefiere hacer sus ahorros de manera informal ya sea por tandas o guardando el dinero “debajo del colchón”.

Una de las explicaciones del problema es que los ingresos que reciben no son los suficientes como para ser candidatos para una cuenta bancaria.

Por otro lado, la fuerza laboral entrante es la generación Millenial, debido a la crisis que el país lleva arrastrando desde hace varios años, los salarios de esta generación en promedio se encuentran en los $6,117, según el Reporte de Información Laboral de la Subsecretaría de Empleo y Productividad Laboral. Como mencionamos anteriormente, una de las razones por las que una persona económicamente activa no está bancarizada es justo por tener un sueldo bajo que no cumple con las especificaciones para hacerse con una cuenta bancaria.

Mientras tanto, la data proporcionada nos muestra un alto porcentaje de gente que está entrando a la Landing Page por medio de celulares Samsung J7 y J2, ambos pertenecientes a la gama media baja de dicha compañía. Dado que nuestra app está enfocada a dispositivos IOS, es totalmente entendible que haya un alto bounce rate en nuestra Landing Page.

También nos encontramos con problemas en temas de usabilidad, pues en las primeras pruebas hechas la mayoría de los testeados concluyeron que les era muy difícil leer y ubicar dónde era que tenían que hacer click para poner los datos que se les pedía.

Otro problema fue el flujo que en cierta parte del proceso era imposible volver al menú principal, igualmente se detectó un problema en el login pues ciertos datos estaban de más o eran difíciles de conseguir para el usuario.

## Hipótesis   :credit_card:

- Para Fintech nuestro producto resolverá a las y los clientes el problema del bounce rate en la Landing Page, dándoles una app dirigida para Android.

- Para Fintech nuestro producto resolverá a las y los clientes el problema de no hacer login, dándoles una opción de hacer una contraseña por medio de su voz.

- Para Fintech nuestro producto resolverá a lxs clientes el problema de contar con escaner de huella digital en sus celulares, dándoles una opción de token individual.

## Técnicas utilizadas    :books:
Las técnicas utilizadas para este proyecto son las siguientes:

### Pruebas de usabilidad

Para acercarnos a los problemas que tenía arrastrando la app de Tus Finanzas hicimos testeo con 5 personas, de esos testeos rescatamos lo siguiente:

- Los usuarios no pueden regresar a la pantalla de navegación

- Los usuarios consideran que la parte de “gastos” puede estar incluida en la de “movimientos”

- La ilustración del login puede ser más genérica.

- El login pide datos que el usuario no tiene a la mano.

- A los usuarios les cuesta leer las pantallas.

- A los usuarios les gusta la parte de movimientos, pero consideran que el color en rojo es muy agresivo.

- A los usuarios les gusta la parte de ahorros, pero les gustaría una pequeña explicación de cómo funciona.

## Benchmark

## Entrevistas

Las entrevistas fueron realizadas a gente que por varias razones no tienen una app bancaria, pero que la necesitan. Con estas entrevistas y con data del ENIF hecha por el Instituto Nacional de Estadística y Geografía, el Estudio sobre ahorro realizado por Finx se produjo la User Persona.

### User Persona
```
![user persona](img/userpersonaok1.jpg)
```
### Journey Map

![Journey Map](img/TrueJourneyMap.jpg)

Junto con las pruebas de usabilidad se realizó un Journey Map de la app para focalizar los problemas de flujo.

## Diagrama de Flujo :chart_with_downwards_trend:

En primera instancia de arregló el flujo con un diagrama de flujo completo.
![Diagrama de flujo](src/images/TusFinanzasApp.jpeg)
## Valor agregado    :bulb:
Para hacer resaltar Tus Finanzas App de todas las demás apps bancarias existentes, haremos que la parte de ahorro se llame “Ahorro S.M.A.R.T.”, inspirándonos en las metas SMART usadas para los negocios.

La nomenclatura hace referencia a “S” de específico, “M” de medible, “A” de alcanzable, “R” realista, y “T” en poco tiempo. Basándonos en estos 5 conceptos guiaremos a los clientes a ahorrar de una manera inteligente y así crecer con ellos y en un futuro se pueda invertir en la bolsa de valores para hacer ahorros de un carácter más serio.
### Anexos


### Guía de entrevistas
Guía de preguntas para la User Persona:

¿Cuál es tu nombre?

¿Qué edad tienes?

¿Cuál es tu estado civil?

¿A qué te dedicas?

(Si trabaja) ¿desde qué edad empezaste a trabajar?

(Si trabaja) ¿Cuánto llevas en tu trabajo actual?

(Si no trabaja) Gracias por tu tiempo. Vete alv porque no nos sirves :P

¿Tienes una cuenta bancaria?

¿Con qué banco o bancos tienes tus cuentas?

¿Desde cuándo tienes tu(s) cuenta(s)?

¿Usas la app de tu banco?

¿Desde cuándo la tienes?

¿Desde qué dispositivos la usas?

¿Con qué frecuencia la usas?

¿Cuáles son las funciones que más usas?

¿Qué te gusta de tu app bancaria?

¿qué le cambiarías?

¿qué es lo que no te gusta?

¿Has tenido algún problema con tu app bancaria?

¿cuál fue el problema?

¿Usas alguna app de ahorro, independiente de la app del banco?

¿cuál?

¿Por qué la usas?

Usar la técnica de los por qué’s

(Andy)

La primera vez que usaste tu app bancaria ¿Utilizaste la opción de huella digital para registrarte en tu app bancaria? ¿o fue de otra manera?

(Steph)

Enumerar del 1 (mayor uso) al 5(menor uso) las veces que usas las funciones de tu app bancaria
### Audios e imágenes
[https://drive.google.com/open?id=1l94l2xshJ4fuqzPMrJDnjESk5YsD1mbE]
**Fuentes**

Arenas, Edgar. (2017). En México ahorran más los hombres y cada vez empiezan más jóvenes. _Rankia_. [https://bit.ly/2D7dB5l](https://bit.ly/2D7dB5l)

Barboza, César. (2016). No tiene cuenta bancaria 56% de población en México. _Milenio._ [https://bit.ly/2OB8dsN](https://bit.ly/2OB8dsN)

