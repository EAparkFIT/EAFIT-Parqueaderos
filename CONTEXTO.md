# Contexto del proyecto: \[Parqueaderos EAFIT\]

> **Qué es este archivo.** Es la memoria del proyecto para la IA. Cada vez que abras una sesión nueva con la IA, pégalo o adjúntalo y pídele que resuma lo que entendió antes de hacer cualquier cosa. La IA no recuerda lo de ayer; este archivo sí.

> **Cómo llenarlo.**

> - Escríbelo entre todo el equipo. La IA puede ayudarte a ordenarlo, pero el contenido sale de ustedes y de su investigación.  
> - Reemplaza todo lo que está entre \[corchetes\].  
> - Borra estos bloques de instrucciones (las líneas que empiezan con `>`) cuando termines.  
> - Sé breve y concreto. Una IA lee mejor un texto corto y claro que uno largo.  
> - **No incluyas** nombres, correos, grabaciones ni datos identificables de los participantes de tu investigación. Usa códigos (P1, P2).  
> - Nunca escribas aquí contraseñas ni llaves de acceso.  
> - Actualiza solo la sección "Estado actual" al cerrar cada sesión. Las demás secciones cambian únicamente si cambia una decisión del equipo.

---

## 1\. Propósito

> Qué es el sitio y qué debe lograr, en 2 o 3 frases. Si no puedes explicarlo en tres frases, aún falta claridad (vuelve a la Fase 0).

\[Portal para obtención de información de parqueaderos y ejecución de pagos de los mismos\]

## 2\. Usuarios y tareas principales

> Una línea por tipo de usuario: quién es y qué necesita hacer en el sitio. Salen de tu investigación, no de suposiciones.

- **\[Estudiantes\]:** necesita \[Información de disponibilidad para diferentes vehículos, procesos de pago tanto digital mediante conexión PSE a banco de preferencia y físico a través de locaciones específicas en el campus, recarga de carnet, registro de placa con verificación por código enviado al correo institucional,, vinculación con cuenta y usuario de la universidad\].  
- **\[Profesores\]:** necesita \[Información de disponibilidad para diferentes vehículos, procesos de pago tanto digital mediante conexión PSE a banco de preferencia y físico a través de locaciones específicas en el campus, recarga de carnet, registro de placa con verificación por código enviado al correo institucional,, vinculación con cuenta y usuario de la universidad\].  
- **\[Visitante\]:** necesita \[Proceso de pago con el ticket que se entrega al ingresar en la universidad, registro de ticket, oferta de pago digital mediante conexión PSE a banco de preferencia, información o rutas de la ubicación de las zonas para pago físico\].

## 3\. Evidencia clave de la investigación

> Los hallazgos más importantes del ciclo Lean UX y la decisión que implican para el sitio. Esta tabla es la que le permite a la IA (y a tu docente) ver por qué el sitio es como es. Cada decisión de diseño debería poder rastrearse hasta una fila de aquí.

| Hallazgo (sin datos personales) | Estado (validada, refutada, inconclusa) | Decisión para el sitio |
| :---- | :---- | :---- |
| \[La experiencia del servicio de parqueadero actual es poco satisfactoria, debido al proceso de pago físico\] | \[Experiencia con los puntos de pago físicos del parqueadero ha sido regular, debido a fallas del sistema, problemas en los datáfonos y dificultades para realizar pagos con tarjeta, además de ser un proceso poco claro para los nuevos usuarios debido a la falta de información\] | \[Volver el proceso de pago físico fácil, accesible y positivo, dando la informacion de como realizar el pago de manera eficiente, crear un nuevo portal para el sistema, evitar fallos constantes, \] |
| \[Para poder hacer la experiencia de parqueadero más agradable, este debe de ser similar a otros procesos de pagos en otras plataformas\] | \[Lo que hace que la experiencia de parquear sea placentera, es que tengan una similitud con otros sistemas, buen funcionamiento de los puntos de pago, con alternativas mediante Flypass y Pago automatizado, además de no tener tiempo limitado para retirar el vehículo\] | \[Al crear el nuevo portal o sistema de pago y de información, este de ofrecer varias opciones, no solo de pago físico, que sea similar a otros sistemas y tener un buen intervalo de tiempo de permanencia del vehículo\] |
| \[Las personas pueden trasladar la experiencia de usar otros portales de otros locales o establecimientos para poder entender la nueva propuesta\] | \[Nunca han utilizado aplicaciones o páginas web para pago de parqueaderos, pero si han pagado mediante códigos QR o aplicaciones bancaria como Bancolombia, además de poder realizar consultas mediante la placa\] | \[La propuesta debe de implementar una función que utilice un QR para que los usuarios puedan pagar de manera familiar y cómoda, además de incluir una función para poder registrar y tener un historial de pagos con la placa del vehículo particular\] |

4\. Alcance del MVP

> Lo que entra en esta entrega y lo que se deja para después. Así la IA no agrega funciones que no pedimos.

- **Entra:** Proceso de ingreso a la plataforma para estudiantes/maestros/miembros activos de la universidad y otro para visitantes. Ambos deben mostrar un mapa con la ubicación de los parqueaderos, con sus espacios disponibles, entradas y salidas, dar opción de pago físico o digital, el digital permitirá vincular mediante línea PSE la entidad bancaria que el usuario prefiera, el físico mostrará un mapa que muestra los puntos de pago físico más cercanos dependiendo de la entrada o zona en la que se encuentre en la universidad, una vez llevado a cabo y de verificar el pago en cualquiera de los dos medios, se entregará un QR el cual servirá de comprobante para las salidas en los parqueaderos y poder autorizar la salida. Para los estudiantes/maestros/miembros activos de la universidad se dan las opciones de registro de ticket junto con el monto a pagar, registro de placa vehicular con verificación mediante correo académico, historial de pagos realizados con cada placa registrada, apartado de carnet que permite recargarlo de manera similar al pago digital, perfil de usuario vinculado al ya existente en la plataforma universitario con información sobre términos de uso de la app y términos y condiciones de uso de información privada. Para los visitantes debe de aparecer una serie de instrucciones cortas de cómo utilizar el ticket para pagar ya sea de forma digital a través del portal o de los puntos físicos, y el mismo proceso de pago que realizan los estudiantes/maestros/miembros activos de la universidad.\]  
- **No entra por ahora:** \[\]

## 5\. Tecnología y restricciones

> Con qué se construye y dónde se publica. Si algo está prohibido o no se puede usar, dilo aquí.

- Tipo de sitio: \[sitio estático con HTML\]  
- Frameworks o librerías permitidas: \[ninguna\]  
- Dónde se publica: \[Hosting contratado\]  
- Formularios o datos de usuarios: \[Correo electrónico universitario, número de CC. o de identificación, número de placa vehicular, nombre de entidad bancaria.\]  
- Analítica: \[herramienta y eventos definidos en el plan de medición\]

## 6\. Estructura del sitio

> Una fila por página. Copia aquí tu mapa del sitio de la Fase 2\.

| Página | Archivo | Qué hace el usuario aquí (una frase) |
| :---- | :---- | :---- |
| Inicio | index.html | \[Aclara si es Miembro activo de la universidad o un visitante\] |
| Registro/Inicio de sesión Eafitense | bienvenida.html | \[Aclara si es Miembro activo de la universidad o un visitante\] |
| Página principal Eafitense | inicio-eafitense.html | \[Se encuentran las páginas de Parqueadero en vivo, Pagos, Tótems, Placa, Espacios Especiales, Cuenta\] |
| Pagos | pago-inicio.html | \[Ofrece a los usuarios Eafitenses poder pagar con su carnet o con otro medio, ya sea físico o digital, además de poder recargar el propio carnet\] |
| Tótems | mapa-totems.html | \[Ofrece a los usuarios la ubicación de tótems en el mundo real donde se pueden realizar pagos\] |
| &nbsp;Placa | placas-registro.html | \[El usuario verifica la o las placas que están registradas en su cuenta y poder borrar alguna que ya está en ella\] |
| Espacios Especiales | espacios-especiales.html | \[Muestra un mapa similar al de los Tótems y Parqueaderos en vivo\] |
| Cuenta | ajustes.html | \[El usuario puede revisar la información de su cuenta, como correo, historial de pagos, normas de uso y otro tipo de información legal\] |
| Visitantes | visitante-recibir-ticket.html | \[Se le da las instrucciones necesarias al usuario para poder realizar un pago sin necesidad de estar directamente vinculado con la misma\] |
| Bienvenida al visitante | visitante-ticket-ingreso.html | \[Se genera un QR que el usuario utiliza para identificar el recibo del parqueadero, se le muestra un mapa de donde están los Totems para pagar físicamente, y la opción de continuar con el proceso una vez realizado el pago.\] |
|  |  |  |

Carpetas del proyecto:

```
[nombre-del-proyecto]/
  CONTEXTO.md
  BITACORA.md
  README.md
  index.html
  ajustes.html
  bienvenida.html
  acceso-eafitense.html
  comprobante-pago.html
  espacios-especiales.html  informacion-pagos.html
  inicio-eafitense.html
  mapa-totems.html
  mis-pagos.html  pago-con-carnet.html  pago-fisico-totem.html
  pago-inicio.html
  pago-pse-banco.html
  pago-pse-datos.html
  pago-sin-carnet.html
  parqueaderos-disponibilidad.html
  perfil.html
  placas-eliminar.html
  placas-registro.html
  recarga-carnet.html
  terminos-condiciones.html
  visitante-recibir-ticket.html
  visitante-ticket-ingreso.html
```

7\. Sistema visual

> Valores exactos, para que la IA no improvise. Todo el estilo vive en `css/estilos.css`.

- Color principal: \[\#004B85\] (acciones principales)  
- Color secundario: \[\#129EE3\] (acciones secundarias)  
- Color de aviso o estado: \[\#FFB903\] (por ejemplo, "Disponible")  
- Fondo: \[\#FFFFFF\] · Texto: \[Sans serif Roboto\]  
- Tipografía de títulos: \[Sans serif Inter\]  
- Tipografía de texto: \[Sans serif Roboto Mono\]  
- Botones, tarjetas y etiquetas: \[Botones principales en forma de cuadrados con bordes redondeados, botones secundarios en más pequeños que los principales con forma de rectángulos con bordes redondeados, botones con opciones desplegables, botones en forma de círculo para acción de salida o de retroceso.\]  
- Página modelo: \[archivo\]  
- Versión actual del CSS: \[ninguno\]

## 8\. Tono de voz y reglas de UX writing

> Salen de tu UX writing de la Entrega 2\.

- Tono: \[Formal, directo, conciso\]  
- Voz: \[Indicativa, comunica errores y esclarece soluciones, expresa nuestra misión: Ayudar a la comunidad Eafitense en sus procesos de parqueadero.\]  
- Frases cortas y verbos de acción en los botones ("Ver cronograma", no "Cronograma").  
- Frases de errores en la parte inferior ("Ingresa tu correo y contraseña", “Recuerda pagar tu parqueadero antes de salir", “Pago exitoso con tu carnet”, “Ingresa la placa de tu vehículo”.).  
- No hay enlaces externos, todos los procesos se hacen en la misma pantalla.

## 9\. Reglas para la IA

> No las borres: son lo que convierte a la IA en copiloto. Puedes agregar las tuyas.

1. Usa los textos exactos que se te entregan. No inventes títulos, datos, cifras ni nombres.  
2. Si falta información, pregúntame antes de escribir.  
3. Un cambio por petición. Antes de escribir código, muéstrame un plan con los archivos que vas a tocar y los supuestos que haces. Espera mi aprobación.  
4. No uses estilos dentro de las páginas ni colores fuera de las variables del CSS.  
5. Marca lo pendiente como "Disponible próximamente".  
6. Dime qué archivos y líneas cambiaste.  
7. No toques lo que está en la sección "No tocar".  
8. Si no puedes verificar algo (por ejemplo, que los enlaces funcionen), dímelo; no afirmes que lo revisaste.

## 10\. No tocar

> Archivos, secciones o decisiones que la IA no debe modificar.

- \[El mapa del Parqueadero, Tótems, Espacios especiales, ni sus sistemas en tiempo real.\]  
- \[Sistema de Registro de Vehículo, ni el de validar Placas.\]  
- \[Generación de comprobante de pagos.\]

## 11\. Estado actual

> Esta es la única sección que se actualiza en cada sesión. Pide a la IA que te proponga la actualización al cerrar, y revísala antes de guardarla.

- **Terminado:** \[lista\]  
- **En curso:** \[lista\]  
- **Siguiente paso:** \[lista\]  
- **Pendiente de decisión del equipo:** \[lista\]  
- **Última actualización:** \[fecha\] por \[nombre\]