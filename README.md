# TP4 de Programación Multimedial 4

|                        |                                 |
| ---------------------- | ------------------------------- |
| Integrantes por grupo: | 2                               |
| Se aprueba con         | 6                               |
| Fecha de entrega       | Miércoles 19 de junio, 23:59 hs |
| Fecha de re-entrega    | Miércoles 26 de junio, 23:59 hs |

## Metodología

### Objetivos

- Interpretar los requerimientos de la app que les tocó.
- Crear un proyecto de frontend desde cero.
- Usar una API desde el frontend.
- Deployarla a algún servicio de hosting serverless.

### Comentarios Adicionales

Quiero darles la mayor libertad posible para que lo resuelvan como quieran. Incluso pueden no usar lo que vimos en clase. Aplica también para NextJS por si quieren usar otro framework. 

Lo que les pido es que:

- Estén hechos en TypeScript.
- Todos los tipos de datos sean estáticos (o sea, que no haya ningún `any`).
- Expliquen en el oral por qué les pareció mejor opción que lo que vimos en clase.

Si hay algo que no entienden, aprovechen que conocen a los que hicieron el relevamiento de requerimientos en el TP2 y a los que hicieron la API en el TP3. Yo les permito ir a preguntarles todo lo que necesiten.

Recuerden que, por lo general, la solución más simple es la mejor.

----

## Entrega

### Fecha

Agreguen una `tag` en el repositorio que se llame `tp4`. Ese commit es el que voy a corregir.

Por favor, mándenme un mail a <me@diegofreijo.com> cuando lo tengan listo.

### Código

Todo lo van a resolver en un repositorio de GitHub. Puede que lo más conveniente sea que sea un repo nuevo, no se forqueen el del TP3, así mantenemos las partes separadas. Lo que puede estar bueno que se copien a su repo es:

- La documentación, tanto del TP2 como el TP3. Pueden dejar cada una en distintos archivos.
- El modelo que usó el TP3, así trabajan con los mismos tipos de datos que manda y recibe express desde el lado de ellos.

Todo el resto del proyecto, si lo hacen en NextJS, pueden crearlo desde cero como mostré en clase o copiar el machete.

### Reporte

No es importante el reporte en este TP. Lo único que estaría bueno sería que en el `README.md` pongan una screenshot de la portada de su aplicación o algo así que la haga fácil de identificar.

### Entrega

Para la entrega les voy a estar mandando horarios para que cada pareja se conecte y tengamos la devolución por Google Meet o Teams.

No tenemos margen de tiempo porque se nos acaba el cuatrimestre. Así que si no entregan, igual nos conectamos para que me muestren lo que hicieron así los guío y los dejo encaminados para la re-entrega.

### Exposición

El día de re-entrega va a ser la exposición, donde también está invitado el coordinador de la carrera y capaz más gente de la facultad.

Van a tener 15 minutos para mostrar todo lo que hicieron en este TP. Pueden hacer slides como hicieron para el TP2 y TP3. Lo que se me ocurre que estaría bueno explicar ahí sería:

Más importante que la documentación, en un proyecto frontend, es la demo en vivo. Asegúrense de haber hecho las paces con los dioses de la demo previamente! Esto incluye:

- Recuerden traer cargador para la laptop.
- Asegúrense de que tienen puerto HDMI en la laptop.
- Asegúrense de que les anda internet.
- Cinco minutos antes de exponer, asegúrense de que la app no se rompió en el deploy (sí, esas cosas pasan).
    - Igual tengan el frontend listo para exponer en su máquina, por si el deploy decide dejar de andar a la mitad de su charla.
- Asegúrense de tener datos de prueba razonables así es fácil de entender el uso de la app.

### Mini-exposición de TP2 y TP3

Va a venir gente que no estuvo en los TPs anteriores. Además, me gustaría que hagamos un cierre de las aplicaciones, donde las 3 parejas que trabajaron en cada una puedan ver cómo fue madurando su idea.

Por lo tanto, para cada app que pase a exponer y antes de los del TP4, les voy a dar 2 minutos a los del TP2 y otros 2 minutos a los del TP3 para que expongan un resumen de lo que les tocó y lo que hicieron. Si quieren proyectar algo, les recomiendo que lo hablen con los del TP4 así no están cambiando de laptop cada 2 minutos. Pero lo dejo libre de hacerlo como gusten.

----

## Requerimientos

Los puntos que voy a evaluar son:

- Buen relevo de requerimientos: acá es donde hay más chances de que tengan errores. Probablemente por haber ignorado algún requerimiento. Así que revisen bien el enunciado para asegurarse de que no pasaron nada por alto.
- Deploy: que sea en alguna plataforma serverless, como Vercel o Netlify, y que el deploy se haga automáticamente desde git.
- Errores: aparte de que no haya bugs en la app, me gustaría que ninguna página tire errores en consola. Lo que sí les permito es que dejen los `console.log` de debug como el mensaje que llegó desde la API, etc.
- UX: no me voy a poner exquisito con la UX, pero les pido que tengan consideraciones básicas. Esto incluye:
    - Comunicar de buena manera los errores inesperados al usuario.
    - Validar los datos del usuario y explicarle qué hizo mal.
    - Confirmación de acciones importantes, como haber agregado una nueva entidad.
- UI: esto es programación, así que no los voy a juzgar por el diseño. Estoy seguro de que van a hacer uno más lindo que el que hice en clase 😄 Lo que sí voy a evaluar es que:
    - El diseño sea responsive. Apunten a que se pueda usar en PC y en celular. Estaría bueno que muestren esto en la demo!
    - Ningún elemento visual esté roto.
 
