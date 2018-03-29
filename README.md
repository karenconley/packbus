# Packbus

Packbus es una app móvil para comprar paquetes de pasajes en buses interurbanos al mejor precio. Además no necesitas imprimir tu pasaje: descarga el código QR, muéstralo al subir al bus y listo.

![proyecto-header-packbus](https://user-images.githubusercontent.com/32284471/38099023-ea95ed16-334f-11e8-96ca-b733d0b137a9.jpg)

## Desarrollado para [Laboratoria](http://laboratoria.la)

# I. El reto

El reto que se nos planteó se titulaba "Nueva experiencia en empresas de buses". La situación era la siguiente: nos ha contactado Catalina una emprendedora viajera con una idea de negocio. Durante sus últimas vacaciones Catalina estuvo viajando por todo latinoamérica. Durante estos viajes Catalina tuvo que tomar muchos buses de todo tipo para llegar a ver los paisajes más lindos del continente. Durante sus viajes Catalina se dio cuenta que existen aún muchas oportunidades para mejorar la experiencia de todos los usuarios de este tipo de transporte: horarios, embarques, desembarques, compra de tickets en los terminales, compra de tickets online, cancelaciones, cambios de pasajes, etc. Adicionalmente, Catalina se dio cuenta que todas las plataformas de venta de tickets de bus tienen cosas por mejorar en Chile, Perú y México.

Luego de vivir todo esto, Catalina está pensando en emprender en este sector. Para ello ha contratado a tu squad para que la ayude a investigar más sobre los usuarios de este tipo de transportes y para que definan y prueben un MVP.

Con tu asesoría, ella podrá sustentar su idea de negocio a un grupo de inversión y así obtener el financiamiento necesario para emprender su negocio y mejorar la experiencia en este rubro.

# II. Research

## Entrevistas y encuestas

Nuestro squad, conformado por 6 integrantes, se dividió las tareas. Un grupo fue a terreno a los terminales de buses a consultar directamente a los usuarios que viajan.

![Terminal](assets/img/fotos-terminales.jpg)

Las preguntas que debían responder eran las siguientes:

1. ¿Cuál es tu principal motivo para viajar?

2. ¿Estás satisfecho con los horarios y frecuencias de salidas de buses? ¿Hay alguna diferencia de precio entre un horario y otro?

3. Al momento de comprar un pasaje, ¿con cuál de estas opciones realizas la compra?: Internet, ventanilla, máquina auto servicio, cupones, otro (especifique cuál)

4. ¿Cuál es el benefecio de comprar un pasaje con la opción que consideraste? ¿Y la principal dificultad?

5. ¿Alguna vez tuviste que devolver o cambiar un pasaje? Si la respuesta es sí... ¿cómo fue el proceso de devolución o cambio?

**Accesibilidad al servicio**

6. ¿Has tenido dificultad antes de iniciar el viaje? (retraso, problema técnico de la máquina, cambio de horario...)

7. En caso de haber sufrido alguna dificultad, ¿qué experiencia tienes con la respuesta por parte de la línea de bus para solucionar tu problema?

**Información en los vehículos**

8. ¿Su línea de bus cumple con informarte acerca de algún incidente sucedido con la máquina? (retraso, problema técnico de la máquina, cambio de horario...)

9. En caso de responder no, ¿consideras que es importante que se informe de cualquier incoveniente?

**Atención al cliente**

10. Considerando alguna dificultad que hayas experimentado al momento de viajar, ¿cómo ha sido la atención al cliente? ¿Te entregan respuestas eficientes en el caso de que existan inconvenientes con el servicio ofertado?

**Confort del servicio**

11. En relación precio/calidad ¿El costo del servicio ofertado cumple con tus espectativas de comodidad, eficiencia y limpieza del vehículo?

Las principales conclusiones a las que llegamos fue que el motivo principal del viaje son las vacaciones, probablemente influenciado por la época, ya que este trabajo se realizó en enero. Y el segundo motivo era laboral.
Con respecto a horarios la mayor parte de los usuarios se siente satisfecho, no así el resto del porcentaje de usuarios declara un servicio regular y finalmente malo.

Se registra una diferencia en alza de precios durante el fin de semana con mayor flujo de pasajeros.

En cuanto a la modalidad de compra sigue repuntando por muy poca diferencia la compra tradicional de ventanilla, debido a una asesoría directa y elecciones personalizadas. Sin embargo, una cantidad no menor de usuarios prefiere el canal online. Justifican la comodidad de hacerlo desde sus hogares, mejores precios con descuentos, ahorro de tiempo y evitar largas filas. Un pequeño porcentaje prefiere la compra a bordo en casos puntuales, de emergencia o imprevisto, a pesar de no poder elegir asiento. Se muestran satisfechos embarcando con rapidez en el horario que se encuentre.

Otro tema a considerar es el cambio o devolución del pasaje, donde el usuario dice no haber tenido mayores problemas por un cambio, pero en devolución se manifiesta descontento, ya que el reembolso solo alcanza el 85% del total pasaje y en algunos casos no se entrega devolución.

La siguiente pregunta evidencia el mayor descontento por parte de los usuarios: "En caso de haber sufrido alguna dificultad, ¿qué experiencia tiene con la respuesta por parte de la línea de bus para solucionar el problema?", algunas de las respuestas fueron:
- “Nunca resuelven nada. Toca aguantar”.
- “Pésima, no hay solución real, uno se debe acomodar a lo que sucede”.
- “Ninguna respuesta”.

Seguido de esta mala evaluación el usuario enfrenta situaciones de incidentes como retrasos, dificultades técnicas, cambio de horario, cambio de destino, poca o nada de información, todo ocurre en completo desconocimiento por parte de los encargados. Considerando que para el usuario la información es lo más importante y que es un derecho por el servicio prestado, declaran como deficiente la atención al cliente en este ámbito.

En relación al servicio ofertado versus la realidad se especifica que no cumple con las expectativas, precios muy elevados por un bus muchas veces desaseados, pagar menos significa un bus aún más incómodo y de menor calidad.

 ![Encuestas](assets/img/encuestas.jpg)

## Observaciones

Mientras encuestabamos a las personas en los terminales de buses, también pudimos observar ciertas situaciones y comportamientos del lugar:

#### Terminal Pajaritos (viernes 19 de enero, de 19 a 19:30 hrs aprox.)

1. El terminal pajaritos es un lugar de embarque a destinos cercanos (de una a dos horas de viaje aproximadamente).

2. Los equipajes en general son más pequeños (mochilas y maletas pequeñas), por lo que da a entender que son viajes de fin de semana, no muy extensos.

3. Pocas familias, habían viajeros frecuentes (gente que viaja a trabajar diariamente) y grupos de jóvenes.

4. Existe venta de talonarios de pasajes, para gente que viaja frecuentemente, el talonario pequeño consta de 10 tickets (5 idas, 5 vueltas) y también de 20 tickets (10 idas y 10 vueltas), vienen en blanco y se pueden confirmar en ventanilla.

5. Tienen diversos medios de pago, efectivo, débito y tarjetas. También se puede comprar online y retirar en ventanilla con el código de venta. No existen máquinas de autoservicio.

6. Las líneas de buses existentes en este terminal son Turbus, Condor, Romani, Pullman Bus y Casablanca. También hay un servicio de transporte al aeropuerto.

#### Terminal Alameda 

1. Cuenta con servicios de viajes a todo destino incluyendo internacional.

2. Máquinas de auto-servicio de compra de pasajes: nos topamos con un usuario/pasajera que necesitaba comprar un pasaje pero al intentarlo con la máquina no resolvió como utilizarla y molesta no tuvo más opción que dirigirse a la ventanilla para realizar la compra presencial.

3. Con respecto a la compra de pasajes, usuarios nos comentan que no están muy conformes, dado que no existe una tarifa fija referente al precio y que varía desvergonzadamente dependiendo del día que se compra e incluso dependiendo de la hora. En general pudimos constatar que hay un valor casi estándar dependiendo del destino pero este se respeta solo si compra con días de anticipación. Pero al final se mostraban resignados debido a que tenían que viajar igual.

4. Muchos usuarios de 40 años hacia arriba aprox. no están muy familiarizados con las compras en otras plataformas por lo que prefieren la compra en ventanilla.

5. Al haber algunos problemas de retraso, o de que el bus no llegó, o se fue antes del horario establecido, (ya que no tienen como informarse en caso de algún incidente), los usuarios toman la precaución de estar mucho tiempo antes para evitar inconvenientes. A pesar de esto, tampoco existen espacios cómodos para la espera.

Preguntamos en varias ventanillas a los vendedores con respecto a los pasajes y la información recopilada fue:
1. Se recomienda comprar los pasajes en ventanilla con 3 a 4 días de anticipación por la alta demanda.
2. Algunos no tienen el servicio de venta online y una de las líneas que si lo tiene, nos comentó que la página estaba caída por lo que no es recomendable. También si se compra por alguna plataforma online suben su valor.
3. Precio cambia por horarios y si es que se pudiera comprar el mismo día también sube su precio. El precio también cambia por horario de salida del bus.
4. Si decides comprar con anticipación te hacen un pequeño descuento.
5. Se cobra extra en caso de que lleves equipaje de más (como cajas, bultos, etc.). En algunas líneas nos contestaron que dependía de la tripulación si es que aceptaban.

Considerando todo lo que pudimos apreciar y observar, pudimos concluir lo siguiente:
 
1. En TERMINAL DE BUSES ESTACIÓN CENTRAL existen muchas líneas de buses pequeñas, que no tienen servicio online ni otros medios de pago que no sean efectivo, por lo que los clientes deben, primero, ir a cotizar y buscar su pasaje para luego ir nuevamente el día que deben viajar, lo que considera un gasto de dinero y tiempo.

2. Existen líneas de buses pequeñas que si tenían venta online, pero no con página propia, sino que asociados a https://www.pasajeschile.cl , lo que implica un costo mayor en el precio final del pasaje, dando a entender que los gastos asociados los traspasan al usuario.

3. Existe más transparencia cuando los valores de los pasajes están publicados en algún tipo de plataforma online, ya que se democratiza la información y se saben los valores de antemano, en cambio, al ir y cotizar, los precios varían mucho entre un horario y otro sin ningún tipo de explicación, pero se obtienen más ofertas y rebajas.

## Entrevista a experto

Alejandro Donoso, Ejecutivo de atención al cliente y Back Office de Tur Bus entre el año 2015 y 2017, respondió algunas preguntas relacionadas con reclamos de los clientes de la empresa de transportes en donde se desempeñó. Él estuvo encargado de reclamos presenciales y vía web, de responder a los clientes, contactarlos y entregarles la información necesaria a su demanda.  

**¿Qué reclamos son los que más se repiten entre los clientes? **

Existen 3 reclamos habituales que son atrasos de buses, suspensión de servicio y cambio de servicio. 

Los atrasos de buses es cuando éstos no salen en su horario programado, y el período de tiempo puede ir de 5 minutos a 2 horas. 

Suspensión de servicio es cuando se cancela la salida de un bus que ya estaba programado. Esto ocurre cuando no se completaba la venta de los asientos. Por ejemplo, un bus con capacidad para 64 personas pero solo se logran vender 50 asientos. En estos casos la empresa cancela la salida de la máquina y a los pasajeros los cambian de bus de manera arbitraria. 

Y el cambio de servicio es cuando un pasajero que compró un tipo de asiento lo cambian a otro inferior. Por ejemplo, una persona que pagó por un pasaje en “salón cama” y lo cambian a “semi-cama” o “clásico”. Esto puede ocurrir por algún error en la venta como pasajes duplicados o por cambio de bus. 

Otros reclamos habituales son por mala atención de parte del personal a bordo, por malos olores de los baños, y por insectos al interior del bus.  En cuanto a esto último, la falta de higiene se debe a que muchos buses al terminar un recorrido comienzan otro de inmediato, por esto no los alcanzan a limpiar ni a ventilar. Hay asientos sucios, manchados y que se desarman. En el último tiempo han sido frecuentes los reclamos por presencia de bichos en los baños, pasillos, ventanas y asientos, como cucarachas, chinches, pulgas y garrapatas.  

**¿Qué vías tienen los clientes para comunicar esto a la empresa? **

Existen tres vías de reclamo: personal, donde deben completar un formulario de reclamo ; vía web, a través del portal donde hay disponible un formulario y un correo electrónico ; o dirigirse a entidades fiscalizadoras como el Sernac y Subsecretaría de Transportes  

**¿De qué manera la empresa responde a sus clientes?**
 
La manera de compensar al consumidor del servicio es por un sistema de puntos (pesos) “Tur Club”, que se acumulan a la cuenta del pasajero. Con esos puntos pueden comprar pasajes dentro de la misma compañía.  La empresa jamás va a devolver dinero, a menos que exista alguna acción penal que obligue a la empresa.  

Los pasajeros reclaman ante esta situación y la empresa solo responde que pueden hacer denuncia judicial a las entidades correspondientes, pero eso significa que el cliente tendrá que contratar un abogado y estar un largo tiempo en esos trámites, y que por el monto que se está exigiendo muchas veces no vale la pena (considerando los altos costos de una asesoría legal). 

A Tur Bus estos reclamos los hace más fuertes, les conviene que los buses se atrasen o que les den un asiento equivocado porque a la hora de responder, hacen que el dinero y el pasaje permanezca con ellos; el sistema de puntos que tienen hace eso, el objetivo de ese método es que el pasajero no pueda recibir de vuelta su dinero y que deba consumir otro viaje en el futuro con ellos. Fuerza a sus clientes y los retiene.  

**¿Qué tipo de sanciones o multas ha recibido la empresa de parte de entidades externas?**

En el período que él estuvo en la empresa jamás escuchó de alguna sanción importante.  

En febrero del año pasado hubo un accidente en una ruta hacia Mendoza, donde murieron 19 pasajeros, producto del exceso de velocidad del conductor. En un principio el Ministerio les iba a cancelar la licencia para rutas fuera de Chile, es decir, que Tur Bus solo hiciera recorridos dentro del territorio nacional, pero finalmente no quedó en nada, siguen operando tal cual.  

Las sanciones de tipo monetaria ocurren solamente cuando hay accidentes y se ha llevado una denuncia vía judicial, especialmente en caso de muerte. Es la justicia la que exige a la empresa indemnizar al pasajero, de lo contrario Tur Bus por cuenta propia no lo haría.  

**¿La empresa ha hecho algún cambio por cuenta propia de sus políticas internas? **

El único cambio que realizaron fue tras el accidente ocurrido en la Autopista del Sol el año 2010 donde hubo 20 muertos. Tiempo después de ese hecho, Tur Bus determinó cancelar la ruta a San Antonio, debido a que los buses eran apedreados por la gente en la carretera. 

## Benchmarking

Para tomar el pulso del negocio, fue necesario realizar un análisis de la competencia del sector. Con esto se pretendía realizar una búsqueda de información e indicadores, que suministren datos para la realización de las estrategias adecuadas, que puedan dar una ventaja competitiva a este emprendimiento.

Investigamos la página web, app, redes sociales de 10 empresas de buses, identificando las herramientas que tienen a disposición de sus clientes.

![Benchmarking](assets/img/Benchmark-Ahumada.png)
![Benchmarking](assets/img/Benchmark-Ciktur-Elite.png)
![Benchmarking](assets/img/Benchmark-Condor.png)
![Benchmarking](assets/img/Benchmark-Eme.png)
![Benchmarking](assets/img/Benchmark-Jac.png)
![Benchmarking](assets/img/Benchmark-Linea-Azul.png)
![Benchmarking](assets/img/Benchmark-Nilahue.png)
![Benchmarking](assets/img/Benchmark-Pullman.png)
![Benchmarking](assets/img/Benchmark-Pullman-del-Sur.png)
![Benchmarking](assets/img/Benchmark-Turbus.png)

En la tabla a continuación resumimos lo descubierto, concluyendo que la mayoría de las empresas tienen web, permiten la compra online y poseen redes sociales, pero más de la mitad está al debe con una app y con call center.

![Benchmarking](assets/img/Benchmark.png)

# III. Definiendo el problema

## Diagrama de Afinidad

Luego de recopilar todas las problemáticas, inquietudes y necesidades de los usuarios, partimos por hacer un **diagrama de afinidad** para clasificarlos por temática.

![Afinidad](assets/img/afinidad-1.jpeg)
![Afinidad](assets/img/afinidad-2.jpeg)
![Afinidad](assets/img/afinidad-3.jpeg)
![Afinidad](assets/img/afinidad-4.jpeg)

## Problem Statement

Planteamos algunas de las necesidades específicas que hemos descubierto y nos enfocamos en ellas para encontrar una posible solución.

¿Qué necesita | ¿Por qué? | What if...?
--------------|-----------|-------------
Precios bajos | Porque viaja recurrentemente y necesita ahorrar | Qué pasaría si... hacemos precio por cantidad de boletos comprados?
Imprimir su pasaje | Para subir al bus y no tiene donde imprimir | Qué  pasaría si... creamos boletos digitales y presenta solo el celular?
Saber de los atrasos e información del viaje | Porque está en su derecho y las compañías no comunican nada | Qué pasaría si... ofrecemos notificaciones con información?

## User Person

Creamos varios User Person con diferentes cosas que los caracterizan, como el cliente informado, el cliente frecuente y el exigente.

Finalmente nos quedamos con Leandro, el pasajero trabajador y frecuente, como nuestro User principal.

![User](assets/img/User-Leandro-trabajador.pdf)
![User](assets/img/User-Andrea-exigente.pdf)
![User](assets/img/User-Sandra-informada.pdf)

## Storytelling y Customer Journey Map






