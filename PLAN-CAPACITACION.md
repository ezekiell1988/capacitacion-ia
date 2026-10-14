# Plan de trabajo — Capacitación "IA en acción"

> **Creá tu primera página web hablando con la inteligencia artificial**
> Sin saber programar: la IA escribe el código, vos das las instrucciones.

---

## 1. Participantes

Grupo pequeño y de confianza: **3 personas no programadoras y no técnicas** que quieren hacer sus propias páginas web.

| Participante | Computadora | Desde dónde | Notas |
|---|---|---|---|
| **Jesús** | Windows | Su casa | Amigo de toda la vida |
| **Ileana** | Windows | Su casa | Prima de Jesús |
| **Karen** | Mac | El otro cuarto | Si algo se traba, puedo ir a ayudarla en persona |
| **Ezequiel (instructor)** | Mac | — | Comparto pantalla y doy las demos |

Lo que esto implica para el diseño de la sesión:

| Situación | Decisión |
|---|---|
| Nunca usaron una terminal | **No escriben comandos**: todo se maneja hablando con la IA (el MCP hace el trabajo técnico). |
| No conocen VS Code | Se usa solo lo mínimo: abrir la carpeta, el panel de la IA y ver los archivos. |
| La instalación es la mayor barrera | **Sesión previa de instalación en la que la IA instala todo**, una por persona. |
| No les interesa la sintaxis | No se explica código. Se explica **qué pedir, cómo pedirlo y cómo revisar** el resultado. |
| Soy el único que ayuda | Con 3 personas alcanza: **rondas de pantalla** donde cada uno muestra lo suyo, y el proyecto base listo para no perder tiempo. |
| Dos Windows y yo en Mac | **Lo más riesgoso es Windows**: hay que probarlo antes (ver sección 11). |
| Es un grupo de confianza | Sesión relajada, sin formalidades; se puede ir al ritmo del grupo. |

Enfoque: **70 % práctica, 30 % explicación**. MCP y Skills se explican con analogías. **Cada uno crea su propio control remoto (MCP) pidiéndoselo a la IA**, con una receta que ya viene en el kit; no escriben código.

---

## 2. Objetivo

Que cada participante salga con **su propia página web** (de su negocio o proyecto), funcionando en su computadora, **abierta desde su celular** por Internet, y sabiendo cómo seguir mejorándola solo, pidiéndoselo a la IA.

Mensaje central:

> "No necesitás saber programar para crear una página web. Necesitás saber explicar lo que querés y revisar lo que la IA te entrega."

Al final, el participante debería poder decir:

> "Hice la página de mi negocio, la vi en mi celular y sé cómo pedirle cambios a la IA."

---

## 3. Herramientas (lo que ve el participante vs. lo que hay por debajo)

| Lo que ve el participante | Qué es en realidad | Se explica como |
|---|---|---|
| El chat de la IA dentro de VS Code | Codex conectado a ChatGPT | "Tu asistente, que además puede tocar los archivos de tu proyecto." |
| La carpeta del proyecto | Proyecto Next.js + Tailwind (ya creado) | "La carpeta donde vive tu página." |
| `AGENTS.md` | Reglas permanentes del proyecto | "Las instrucciones que la IA lee siempre antes de trabajar." |
| Skills | Procedimientos guardados | "Recetas: le enseñás una vez cómo hacer algo y la reutiliza." |
| MCP `local-project-manager` | Servidor MCP que opera el proyecto | "El control remoto: botones que la IA puede apretar por vos." |
| La URL `trycloudflare.com` | Cloudflare Quick Tunnel | "Un puente temporal de tu computadora a Internet." |

**¿Por qué Next.js si son principiantes?** Ellos no lo ven ni lo tocan; la IA lo maneja. Se elige porque deja la puerta abierta para crecer (formularios, usuarios, tienda) sin cambiar de tecnología. Para el participante, "es la base de tu página".

**Fuera de alcance:** explicar código, React, TypeScript, terminal, bases de datos, despliegue permanente.

---

## 4. La analogía que guía toda la sesión

```
            VOS (el dueño de la obra)
                     |
                     |  le explicás qué querés
                     v
          LA IA (el maestro de obras)
                     |
         +-----------+-----------+
         |                       |
         v                       v
   RECETAS (Skills)      CONTROL REMOTO (MCP)
   "así se hace una      "encender, apagar,
    buena página"         publicar, revisar"
         |                       |
         +-----------+-----------+
                     |
                     v
              TU PÁGINA WEB
                     |
                     v
         PUENTE A INTERNET (túnel)
                     |
                     v
              TU CELULAR 📱
```

Regla para recordar:

> **Vos decidís. La IA trabaja. Las recetas le dicen cómo. El control remoto le permite actuar.**

---

## 5. Modalidad: videollamada de WhatsApp

Todo (la instalación y la capacitación) es **por videollamada de WhatsApp** en un grupo con los cuatro (Ezequiel, Jesús, Ileana y Karen). Jesús e Ileana desde sus casas, Karen desde el otro cuarto.

### Qué necesita cada participante

| Dispositivo | Para qué |
|---|---|
| **Computadora con WhatsApp Desktop** | Entrar a la llamada y **compartir la pantalla**. Desde el celular no se puede mostrar la pantalla de la computadora. |
| **Celular** | Abrir el enlace público de su página y ver las de los demás. |
| Audífonos (recomendado) | Evitar eco. **Karen sobre todo**: al estar en el otro cuarto, sin audífonos se acopla el sonido entre las dos Mac. |

### Cómo se trabaja en la llamada

- **Yo comparto mi VS Code** con letra grande (zoom de VS Code al 150 % o más) y una sola ventana a la vista.
- Cada uno tiene **VS Code y la llamada lado a lado**, o alterna entre ellas. Se practica en la sesión de instalación.
- **Solo uno comparte pantalla a la vez.** Para ver a alguien: dejo de compartir y le pido que comparta.
- **Rondas de pantalla:** al final de cada bloque práctico, cada uno comparte 2 minutos y muestra cómo va. Con 3 personas son unos 6–8 minutos. Sirve para revisar y también para que se inspiren con lo de los otros.
- **Si alguien se traba:** lo dice en la llamada o escribe en el grupo. Los otros dos siguen con pedidos de mejora mientras lo ayudo.
- **Si es Karen:** puedo ir al otro cuarto y ayudarla en persona mientras Jesús e Ileana siguen.
- Los prompts, la plantilla de pedido y los pedidos sugeridos van **fijados en el grupo**, listos para copiar y pegar.

### Privacidad al compartir pantalla

- Antes de compartir: **cerrar correo, banca, chats personales** y activar "No molestar".
- Si la computadora pide la contraseña (instalaciones en Mac), **dejar de compartir** antes de escribirla; nunca decirla en voz alta.

### Permiso de compartir pantalla en Mac (Karen)

macOS bloquea el uso compartido hasta que se da permiso: **Configuración del Sistema → Privacidad y seguridad → Grabación de pantalla → activar WhatsApp**, y reiniciar WhatsApp. **Se deja listo en la instalación de Karen.** En Windows no hace falta.

### Respaldo

- **Enlace de llamada de WhatsApp** fijado en el grupo. Si alguien se cae, vuelve con el mismo enlace.
- Si alguien no puede compartir pantalla: mostrarla con la cámara del celular.
- WhatsApp no graba llamadas. Si quiero grabarla (para que la repasen después), lo hago desde mi Mac con QuickTime u OBS, **avisándoles antes**.

---

## 6. Antes de la capacitación (clave para este público)

### Sesión de instalación con IA (60 min, días antes)

Por **videollamada de WhatsApp**, **una persona a la vez**. **La propia IA (Codex) instala lo que falta**, en Windows y en macOS. Además de preparar las computadoras, es la primera experiencia del curso: *"Le pedí a la IA que preparara mi computadora y lo hizo."*

#### Orden recomendado

| Turno | Quién | Por qué |
|---|---|---|
| 1 | **Karen** (Mac) | Puedo estar a su lado si algo falla. Es la primera prueba real de la Skill en una Mac que no es la mía. |
| 2 | **Jesús** (Windows) | Primera instalación en Windows. Jesús tiene la confianza para aguantar si algo sale mal y hay que corregir la Skill. |
| 3 | **Ileana** (Windows) | Con lo aprendido de Jesús ya corregido. Si quiere, Jesús puede acompañarla en la llamada. |

Conviene dejar **al menos un día** entre Jesús e Ileana para corregir la Skill si hace falta.

#### Qué instala la persona y qué instala la IA

| Paso | Quién | Qué |
|---|---|---|
| 0 | Participante (antes del turno) | Instalar **WhatsApp Desktop** en la computadora y entrar a la llamada desde ahí |
| 0b | Karen (Mac, con ayuda) | Dar permiso de **Grabación de pantalla** a WhatsApp y comprobar que puede compartir |
| 1 | Participante (guía con capturas) | Instalar **VS Code** desde code.visualstudio.com |
| 2 | Participante | Instalar la extensión **Codex** e iniciar sesión con su cuenta de ChatGPT |
| 3 | Participante | Descargar y descomprimir el **kit de instalación** (ZIP), y abrir esa carpeta en VS Code |
| 4 | **IA** | Detectar el sistema operativo y revisar qué ya está instalado |
| 5 | **IA** | Instalar **Node.js LTS**, **cloudflared** y **Git** (opcional) |
| 6 | **IA** | Instalar las dependencias del proyecto base (`npm install`) |
| 7 | **IA** | Comprobar que Codex ve las recetas del kit (incluida la de crear el control remoto, que se usa en la Sesión 1) |
| 8 | **IA** | Prueba final: encender la página (`npm run dev`), confirmar que responde y apagarla |
| 9 | **IA** | Entregar un resumen: ✅ listo / ❌ falta, en lenguaje simple |

Los primeros pasos sí los hace la persona: la IA no puede trabajar hasta que VS Code, Codex y la sesión de ChatGPT estén listos.

#### El kit de instalación

Es el mismo proyecto base (sección 10). Lleva una Skill `preparar-computadora` y un `AGENTS.md` que le indica a la IA qué hacer al abrir la carpeta por primera vez. El participante solo escribe:

> Prepará mi computadora para la capacitación.

#### Skill `preparar-computadora` (resumen)

```markdown
# Preparar computadora

## Cómo hablar con el usuario
- El usuario no es técnico. Explicá cada paso en una frase simple antes de hacerlo.
- Si el sistema pide la contraseña de la computadora o permiso de administrador,
  avisá antes y explicá por qué ("para instalar programas, tu computadora pide permiso").
- Nunca pidas que escriba comandos; vos los ejecutás.

## Pasos
1. Detectar el sistema operativo (Windows o macOS) y la arquitectura.
2. Revisar qué ya está instalado: node -v, npm -v, cloudflared --version, git --version.
3. Instalar solo lo que falte:
   - Windows: winget (Node.js LTS, Cloudflare.cloudflared, Git.Git).
   - macOS: Homebrew si no está; luego brew install node cloudflared git.
     Si Homebrew no se puede instalar, usar los instaladores oficiales (.pkg).
4. Si el programa recién instalado no aparece, pedir que cierren y abran VS Code
   y continuar desde el paso 2.
5. npm install dentro del proyecto.
6. Comprobar que Codex ve las recetas de la carpeta .agents/skills.
7. Prueba: encender la página con npm run dev, comprobar que responde en localhost:3000 y apagarla.
8. Resumen final con ✅ / ❌ por cada elemento y qué hacer si algo falló.

## Reglas
- No instalar nada fuera de la lista.
- No cambiar configuraciones del sistema que no sean necesarias.
- No borrar archivos.
```

#### Diferencias por sistema operativo

| Tema | Windows | macOS |
|---|---|---|
| Instalador de programas | `winget` (ya viene en Windows 10/11 recientes) | Homebrew (hay que instalarlo; tarda varios minutos) |
| Permisos | Ventana de "¿Permitir cambios?" (UAC): hacer clic en **Sí** | Pide la **contraseña de la Mac** en la terminal; no se ven los caracteres al escribirla (avisarlo) |
| Herramientas extra | — | Homebrew puede pedir instalar las *Command Line Tools* de Xcode (ventana emergente, aceptar) |
| Después de instalar | A veces hay que **reiniciar VS Code** para que reconozca Node | Normalmente no hace falta |

#### Momentos para enseñar (aprovechar la sesión)

- **Permisos:** la IA pide permiso para ejecutar algo; leer qué es antes de aceptar. Se ve en la práctica la regla de seguridad n.º 1.
- **La IA verifica:** muestra que revisó cada instalación y no da por hecho que funcionó.
- **Cuando algo falla:** si una instalación falla, la IA explica el problema y prueba otro camino.

#### Plan B

- Si la IA no logra instalar algo, la guía trae los **instaladores oficiales con capturas** para hacerlo a mano.
- Comparten pantalla y los guío. Con Karen, en persona.
- Preguntar antes a Jesús e Ileana: **¿la computadora es personal o del trabajo?** Si es del trabajo, puede que no tengan permisos de administrador ni puedan instalar programas.

### Material que se envía antes

- Guía corta con **capturas paso a paso** (Windows y macOS) para lo único manual: instalar WhatsApp Desktop, instalar VS Code, agregar Codex, iniciar sesión y abrir el kit de instalación.
- Preguntar por WhatsApp a Jesús e Ileana: **versión de Windows** (10 u 11) y si la computadora es **personal o del trabajo**.
- Pedirle a cada uno que piense: **nombre del negocio o proyecto, qué ofrece, 3 servicios/productos, colores que les gustan, datos de contacto**. Si pueden, que traigan un logo o fotos.
- Video corto (2–3 min) de lo que van a lograr.

---

## 7. Plan por sesiones de 1 hora

La capacitación se divide en **sesiones de 1 hora** por videollamada. Antes va la instalación (sección 6), una por persona.

| Sesión | Tema | Al terminar tienen |
|---|---|---|
| 0 | Instalación con IA (individual) | Computadora lista y página base encendida una vez |
| **1** | **Landing sencilla + crear el control remoto + túnel** | Página propia, MCP que la enciende/apaga/reinicia y la publica en Internet |
| 2 | Pedir bien: la página de su negocio, reglas (`AGENTS.md`) y recetas (Skills) | Página con su contenido y su estilo |
| 3 | Formulario de contacto + cuando algo falla (nuevos botones al control remoto) | Página que recibe mensajes; saben pedir diagnósticos |
| 4 | Dirección fija: cuenta de Cloudflare y dominio | Enlace que no cambia cada vez (si se decide comprar dominio) |

> Cada sesión arranca con 5 minutos de "encendé todo" y termina con 5 minutos de "apagá todo". Así practican el control remoto en cada sesión.

### Sesión 1 — Mi primera página, mi control remoto y mi puente (60 min)

**Objetivo:** que cada uno tenga una landing sencilla, **cree con la IA su propio MCP** para manejarla y la publique con un túnel.

| Min | Actividad | Detalle |
|---|---|---|
| 0–5 | Bienvenida | Ezequiel muestra en 2 minutos el resultado final: pide un cambio, la página se actualiza sola, la publica y manda el enlace al grupo. |
| 5–20 | **Landing sencilla** | Con la plantilla de pedido (bloque 4) cada uno crea su página: nombre, frase, 3 tarjetas y contacto. La IA la enciende con `npm run dev` para verla. Ronda rápida de pantallas. |
| 20–40 | **Crear el control remoto (MCP)** | Cada uno pega el pedido de creación (abajo). La IA usa la receta del kit, crea el MCP, lo registra en Codex y pide recargar VS Code. |
| 40–48 | **Probar el control remoto** | "Apagá mi página" → "Encendé mi página" → pedir un cambio y ver que **se refresca sola** → "Reiniciá mi página" → "¿Está encendida?" |
| 48–57 | **Túnel** | "Publicala temporalmente" → enlace `trycloudflare.com` → al grupo → los cuatro abren las páginas en el celular → "Apagá el puente" y ven que el enlace deja de funcionar. |
| 57–60 | Cierre | "Apagá todo." Qué vamos a hacer en la Sesión 2. |

**Pedido para crear el control remoto** (fijado en el grupo):

```
Usá la receta para crear un control remoto (MCP) para mi página.

Quiero estos botones:
- Encender mi página
- Apagar mi página
- Reiniciar mi página
- Ver si está encendida y en qué dirección
- Encender el puente a Internet (Cloudflare) y darme el enlace
- Apagar el puente
- Ver si el puente está encendido y cuál es el enlace

Reglas:
- Respondé siempre en español simple.
- Solo manejá los programas que vos mismo encendiste.
- Pedime permiso antes de publicar mi página en Internet.
- Cuando termines, registralo y decime qué tengo que hacer para empezar a usarlo.
```

**¿"Refrescar" necesita un botón?** No. Next.js actualiza la página sola cada vez que la IA cambia algo (Fast Refresh). Se incluye **"Reiniciar"** solo para cuando algo se traba o cambia la configuración. En la demo, se muestra que el cambio aparece **sin tocar nada**.

**Riesgo de tiempo:** crear y registrar el MCP es lo más delicado (sobre todo en Windows). Plan B: el kit trae un **control remoto ya hecho** en una carpeta de respaldo. Si a alguien no le sale en 15 minutos, se le pide a la IA *"Usá el control remoto de respaldo"* y sigue con el grupo. En la Sesión 2 se puede volver a intentar.

> Antes de la Sesión 1, Ezequiel prueba el pedido completo en su Mac y en un Windows, y mide cuánto tarda la IA en crear el MCP.

### ¿Se necesita un dominio o cuenta de Cloudflare?

**Para la Sesión 1, no.** El túnel rápido (*Quick Tunnel*) no pide **cuenta ni dominio**: `cloudflared` genera un enlace gratis y aleatorio tipo `https://palabras-al-azar.trycloudflare.com`.

| | Túnel rápido (Sesión 1) | Túnel con nombre (Sesión 4) |
|---|---|---|
| Cuenta de Cloudflare | ❌ No | ✅ Sí |
| Dominio | ❌ No | ✅ Sí, agregado a Cloudflare |
| Enlace | Aleatorio, **cambia cada vez** que se enciende | Fijo, ej. `jesus.midominio.com` |
| Costo | Gratis | Túnel gratis; el dominio se paga (un `.com` ronda los US$10–12 al año) |
| Uso | Pruebas y demos | Mostrar la página siempre con la misma dirección |

**Conclusión:** crear la cuenta de Cloudflare en la Sesión 1 no aporta nada; sin dominio, el túnel con nombre no sirve. Se deja para la Sesión 4, con estas opciones:

- **Opción A — Un dominio de Ezequiel, un subdominio por persona** (`jesus.`, `ileana.`, `karen.`): Ezequiel crea los túneles en su cuenta y le da a cada uno su **token del túnel**. Ellos no necesitan cuenta ni pagar nada. El token es un secreto: se guarda fuera del proyecto, nunca en el chat ni en el grupo.
- **Opción B — Cada uno con su cuenta y su propio dominio:** tiene sentido para quien quiera la página de su negocio con nombre propio. Requiere tarjeta para comprar el dominio.

Ojo: aun con dominio, el túnel solo funciona **mientras la computadora está encendida y el puente activo**. Para que la página esté siempre en línea hace falta publicarla en un hosting (nivel siguiente).

### Sesión 2 — La página de mi negocio (60 min)

Bloques 4, 5 y 6 del banco de contenido: pedir bien vs. pedir mal, construir la página con su contenido, `AGENTS.md` con una regla propia y una receta (Skill). Ronda de pantallas al final.

### Sesión 3 — Mi página recibe mensajes y sé arreglarla (60 min)

- Bloque 7: formulario de contacto.
- **Agregar botones nuevos al control remoto** pidiéndoselo a la IA: "ver los errores", "revisar qué pasa", "mostrame los mensajes que llegaron". Así ven que el MCP crece con lo que necesitan.
- Bloque 9: cuando algo falla.
- Bloque 10: seguridad básica.

### Sesión 4 — Una dirección fija (60 min)

- **Opción A elegida y lista** (2026-10-13). Túneles creados en la cuenta de Ezequiel, zona `ezekl.com`:

  | Participante | Dirección fija | Túnel |
  |---|---|---|
  | Jesús | `https://jesus.ezekl.com` | `capacitacion-jesus` |
  | Ileana | `https://ileana.ezekl.com` | `capacitacion-ileana` |
  | Karen | `https://karen.ezekl.com` | `capacitacion-karen` (probado de punta a punta ✅) |

  Los tokens están en `~/.local-secrets/capacitacion-tunnels.json` (permisos 600, fuera del repo). Cada token se entrega **en privado a su dueño**, nunca en el grupo, y en su computadora se guarda en `.local-secrets/` del proyecto (ignorado por git).
- Cada uno le pide a la IA *"Agregá a mi control remoto el puente con mi dirección fija"*. El control remoto corre el túnel así, con el token en variable de entorno y no en la línea de comandos:

  ```
  TUNNEL_TOKEN=<token> cloudflared tunnel --no-autoupdate run --url http://localhost:3000
  ```

- Para revocar el acceso de alguien: `cloudflared tunnel delete capacitacion-<nombre>` y borrar su CNAME.
- Opción B: crear cuenta de Cloudflare, comprar/agregar el dominio y crear el túnel con nombre, todo guiado por la IA.
- Cierre: los cuatro abren las páginas con sus direcciones fijas.

---

## 8. Banco de contenido por bloque

Contenido de referencia para armar cada sesión. La agenda real está en la sección 7.

### Bloque 1 — Bienvenida (15 min)

- Mostrar en vivo, en 3 minutos, el ciclo completo: pedir una página, encenderla, publicarla y mandar el enlace al grupo y que Jesús, Ileana y Karen la abran en su celular mientras siguen en la llamada.
- Explicar la evolución en lenguaje simple:

| Antes | Ahora |
|---|---|
| Le preguntabas a ChatGPT y copiabas la respuesta. | Le pedís a la IA y ella misma crea y cambia los archivos. |
| Necesitabas un programador para ver tu página en Internet. | Le decís "publicala" y te da un enlace. |

- Presentar la analogía de la obra (sección 4).

### Bloque 2 — Conocer el espacio de trabajo (15 min)

Solo tres cosas:

1. **La carpeta del proyecto** (panel izquierdo): "aquí vive tu página; no hace falta tocar nada".
2. **El chat de la IA**: dónde se escribe y cómo se ve cuando la IA está trabajando.
3. **Los permisos**: la IA a veces pide permiso para hacer algo. Leer lo que pide antes de aceptar.

Primer mensaje: *"Hola, explicame en palabras simples qué hay en esta carpeta."*

### Bloque 3 — Encender la página (15 min)

Los participantes escriben:

> Encendé mi página y decime dónde la puedo ver.

La IA usa el MCP y responde con `http://localhost:3000`. Se explica:

- **localhost** = "tu página, pero solo en tu computadora".
- La página se actualiza sola cuando la IA hace cambios: no hace falta apagar y encender.

### Bloque 4 — Cómo pedirle cosas a la IA (20 min)

Comparar en vivo:

❌ Pedido vago:
```
Hacé una página bonita.
```

✅ Pedido claro (plantilla para copiar y completar):
```
Quiero la página de mi negocio.

Mi negocio se llama: [nombre]
Nos dedicamos a: [qué hacen]
Ofrecemos: [servicio 1], [servicio 2], [servicio 3]
Colores que me gustan: [colores]
Estilo: [moderno / elegante / divertido / sencillo]
Contacto: [teléfono, correo, WhatsApp, dirección]

La página debe verse bien en celular.
Antes de hacer cambios, contame en pocas palabras qué vas a hacer.
Cuando termines, revisá que todo funcione.
```

Cuatro consejos para recordar:

1. **Contale el contexto**: quién sos, para quién es la página.
2. **Sé específico**: colores, textos, secciones.
3. **Pedí un cambio a la vez** cuando estés corrigiendo.
4. **Pedile que revise su trabajo**: la IA no solo debe crear, también debe verificar.

Ejercicio: cambiar el título de la página base por el nombre de su negocio.

### Bloque 5 — Construir la página de su negocio (40 min)

Con la plantilla del bloque 4, cada participante crea su página. Contenido mínimo:

- Encabezado con el nombre y menú.
- Sección principal con frase llamativa y botón (ej.: "Escribinos por WhatsApp").
- Tres tarjetas con servicios o productos.
- Sección "Sobre nosotros".
- Datos de contacto.

Luego, ronda de mejoras con pedidos sugeridos (mensaje fijado en el grupo de WhatsApp):

- "Cambiá los colores a tonos más cálidos."
- "Agregá una sección de preguntas frecuentes con 4 preguntas."
- "Agregá un botón flotante de WhatsApp con mi número."
- "Hacé que el título sea más grande y llamativo."
- "Mostrame cómo se vería en un celular y arreglá lo que no se vea bien."
- "Usá la imagen `logo.png` que está en la carpeta como logo."

> Al final, **ronda de pantallas**: cada uno muestra su página 2 minutos y los otros dan una idea. Quien termina antes, sigue con mejoras libres.

### Bloque 6 — Instrucciones permanentes y recetas (15 min)

**`AGENTS.md` = "las reglas de la casa".** Ya viene en el proyecto base, escrito en español simple:

```markdown
# Reglas de este proyecto

- Esta es la página web de un negocio pequeño.
- Siempre debe verse bien en celular.
- Usá textos claros y amables, sin palabras técnicas.
- No agregues cosas que no te pedí.
- Antes de cambiar algo grande, explicame qué vas a hacer.
- Cuando termines, revisá que la página funcione y no tenga errores.
```

Ejercicio: cada uno agrega **una regla propia** (ej.: "Usá siempre un tono formal", "Mis colores son azul marino y dorado") y pide un cambio para ver que la IA la respeta.

**Skills = "recetas".** Se muestra (no se construye) una receta ya incluida, por ejemplo `nueva-seccion`, y se usa:

> Usá la receta para agregar una sección de testimonios.

Mensaje: una Skill es solo un documento con instrucciones; **cualquiera puede escribir una**, no hace falta programar. Quien quiera, puede pedirle a la IA: *"Creá una receta para agregar secciones con el mismo estilo de mi página."*

### Bloque 7 — Formulario de contacto que funciona (20 min)

Pedido:

> Agregá un formulario de contacto con nombre, correo y mensaje. Cuando alguien lo envíe, que muestre "¡Gracias, te contactaremos pronto!" y que el mensaje quede guardado para que yo lo pueda ver.

Se explica en una frase: *"tu página ahora no solo muestra cosas, también recibe información; eso es lo que se llama backend"*. Los participantes envían un mensaje de prueba y le piden a la IA: *"Mostrame los mensajes que llegaron."*

> Nota para el instructor: la IA crea un endpoint en `src/app/api/contacto/route.ts` que guarda en un archivo local de la carpeta del proyecto. Sin base de datos ni envío de correos en este nivel.

### Bloque 8 — Publicar y verla en el celular (20 min)

Pedido:

> Quiero ver mi página en el celular. Publicala temporalmente.

La IA pide autorización (explicar por qué es importante), abre el túnel y devuelve un enlace tipo `https://algo-aleatorio.trycloudflare.com`.

- Abrirlo en el celular. Mandarlo al grupo para que los otros dos la vean desde sus casas: así comprueban que **de verdad está en Internet**, no solo en su computadora.
- Explicar: **es temporal**. Mientras la computadora y el puente estén encendidos, funciona; al apagarlos, el enlace deja de existir.
- Para tener una dirección fija hace falta una cuenta de Cloudflare y un dominio (Sesión 4). Para que esté siempre en línea, aunque la computadora esté apagada, hace falta un hosting (nivel siguiente).

### Bloque 9 — Cuando algo falla (15 min)

Yo rompo algo a propósito en mi proyecto, compartiendo pantalla (por ejemplo, apago la página o meto un error), y luego cada uno pega un pedido preparado que "rompe" su propia página. Después practican:

> Mi página no funciona. Revisá qué pasa y arreglalo.

La IA usa el MCP para diagnosticar, mirar los errores y corregir. Mensaje: **no hace falta entender el error; hace falta saber pedir que lo revise y comprobar que quedó bien.**

Otros pedidos útiles:

- "Deshacé el último cambio, no me gustó."
- "¿Qué cambiaste en la última respuesta? Explicámelo simple."
- "La página se ve rara en el celular, revisala."

### Bloque 10 — Seguridad básica y cierre (10 min)

Cinco reglas en lenguaje simple:

1. **Leé antes de aceptar** cuando la IA pide permiso para hacer algo.
2. **No pongas contraseñas ni datos privados** en la página ni en el chat.
3. **El enlace público lo ve cualquiera** que lo tenga: no publiques nada privado.
4. **Apagá el puente** cuando termines de mostrar la página.
5. **La IA puede equivocarse**: revisá siempre el resultado en el navegador y en el celular.

**Cierre:** cada uno manda su enlace al grupo, los cuatro abren las páginas de los demás desde el celular y, al final, cada uno escribe:

> Apagá el puente y la página.

Los enlaces dejan de funcionar en vivo: queda clarísimo qué hizo el "control remoto".

---

## 9. El control remoto (MCP) `local-project-manager`

Cada participante lo **crea en la Sesión 1** con la receta de MCP del kit (basada en la Skill de Ezequiel para MCP locales: Node.js, `stdio`) y le agrega botones en la Sesión 3. Los participantes solo hablan; la IA traduce a herramientas. Tabla para el instructor:

**Sesión 1:** `project_start`, `project_stop`, `project_restart`, `project_status`, `tunnel_start`, `tunnel_stop`, `tunnel_status`.
**Sesión 3:** `project_health`, `project_logs`, `project_diagnose`, `project_install`, ver mensajes.


| El participante dice | Tools del MCP que se usan |
|---|---|
| "Encendé mi página" | `project_status` → `project_start` → `project_health` |
| "Apagá mi página" | `tunnel_stop` (si está activo) → `project_stop` |
| "Publicala / quiero verla en el celular" | `project_health` → (autorización) → `tunnel_start` |
| "Apagá el puente" | `tunnel_stop` |
| "¿Está encendida? ¿Cuál es mi enlace?" | `project_status`, `tunnel_status` |
| "No funciona, revisá qué pasa" | `project_diagnose` → `project_logs` → corrección → `project_health` |
| "Reiniciá la página" | `project_restart` (solo si la IA lo considera necesario) |
| "Instalá lo que falte" | `project_install` |
| "Mostrame los mensajes que llegaron" | lectura del archivo de mensajes del proyecto |

> **¿Hace falta reiniciar Next.js?** Normalmente no: se actualiza solo con cada cambio. Solo se reinicia ante cambios de configuración, de dependencias o si se cuelga. `project_restart` existe para esos casos y el participante no necesita saberlo.

### Requisitos del MCP pensando en este público

- **Respuestas en lenguaje simple** (ej.: "✅ Tu página está encendida. Miralá en http://localhost:3000"), no salidas técnicas crudas.
- **Errores traducidos**: en vez de `EADDRINUSE`, "Ya hay algo usando ese espacio; voy a revisarlo".
- Nada de tools genéricas tipo "ejecutar cualquier comando"; solo operaciones específicas y permitidas.
- Controla **solo los procesos que él inició** (PID / grupo de procesos); nunca `killall node`.
- Evita duplicados y recuerda su estado si se reinicia.
- Limitado a la carpeta del proyecto.
- `tunnel_start` siempre requiere confirmación del usuario.
- Configurable por archivo para reutilizarlo en otros proyectos:

```json
{
  "project": {
    "name": "mi-pagina",
    "type": "nextjs",
    "port": 3000,
    "commands": { "start": "npm run dev", "build": "npm run build" }
  },
  "tunnel": { "provider": "cloudflare", "enabled": true }
}
```

### Skill `project-operator` (incluida en el proyecto base)

Le enseña a la IA cómo usar el control remoto con este público:

```markdown
# Operador del proyecto

## Cómo hablar con el usuario
- El usuario no es técnico. Respondé en español simple, sin jerga.
- Nunca le pidas que escriba comandos en la terminal.
- Si algo falla, explicá qué pasó en una frase y qué vas a hacer.

## Reglas
1. Antes de encender la página, revisá si ya está encendida.
2. No enciendas la página dos veces.
3. Antes de publicar, comprobá que la página funciona.
4. Pedí autorización antes de publicar la página en Internet.
5. Al apagar, apagá primero el puente y después la página.
6. Si hay un error, revisá los registros antes de responder.
7. No hagas nada fuera de la carpeta del proyecto.

## Flujos
- Encender: project_status → project_start → project_health → informar enlace local
- Publicar: project_health → tunnel_status → (autorización) → tunnel_start → informar enlace público
- Algo falla: project_diagnose → project_logs → corregir → project_health → explicar
- Apagar: tunnel_stop → project_stop → confirmar
```

---

## 10. Proyecto base que se entrega

```
mi-pagina/
├── AGENTS.md                    ← reglas de la casa (español simple)
├── .agents/
│   └── skills/
│       ├── preparar-computadora/ ← la IA instala lo necesario
│       │   └── SKILL.md
│       ├── crear-control-remoto/ ← receta para crear el MCP (Sesión 1)
│       │   └── SKILL.md
│       ├── project-operator/    ← cómo usar el control remoto
│       │   └── SKILL.md
│       └── nueva-seccion/       ← receta de ejemplo
│           └── SKILL.md
├── respaldo/
│   └── control-remoto/          ← MCP ya hecho (plan B de la Sesión 1)
├── public/                      ← aquí ponen su logo y fotos
├── src/
│   └── app/
│       ├── layout.tsx
│       └── page.tsx             ← página de bienvenida simple
├── package.json
└── tsconfig.json
```

- Es también el **kit de instalación**: se entrega sin `node_modules`; la IA los instala en la sesión previa.
- El MCP **no** viene instalado: lo crea cada uno en la Sesión 1. La receta `crear-control-remoto` es una versión simplificada de la Skill de MCP de Ezequiel e incluye lo que esa Skill necesita (runtime compartido y `package.json`) para que funcione en una computadora limpia.
- Página inicial con un mensaje tipo "¡Hola! Esta es tu página. Pedile a la IA que la transforme."

> Verificar antes de la sesión la ruta exacta donde Codex descubre Skills del proyecto y dónde lee la configuración de MCP.

---

## 11. Preparación del instructor (checklist)

**MCP `local-project-manager`**

- [ ] Escribir la receta `crear-control-remoto` a partir de mi Skill de MCP local (Node.js, `stdio`), simplificada para este público.
- [ ] Probar el pedido de creación de la Sesión 1 en Mac y en Windows; medir el tiempo (meta: menos de 15 min).
- [ ] Dejar el control remoto de respaldo en `respaldo/control-remoto/`.
- [ ] Mensajes de respuesta y de error en español simple.
- [ ] Probar encender, apagar, reiniciar, publicar y diagnosticar en mi Mac **y en Windows** (lo más importante: Jesús e Ileana usan Windows).
- [ ] Probar que apagar no deja procesos huérfanos ni toca procesos ajenos.
- [ ] Probar recuperación si el MCP se reinicia.
- [ ] Instrucciones dentro de la Skill `preparar-computadora` para que la IA lo registre en Codex.

**Sesión de instalación con IA**

- [ ] Escribir y probar la Skill `preparar-computadora`.
- [ ] Probarla en un **Windows limpio** antes de la instalación de Jesús: una máquina virtual o una computadora prestada. En una Mac con chip Apple, una VM con Windows 11 ARM sirve como prueba general, aunque no es idéntica a la PC de ellos.
- [ ] Probarla en una **Mac sin Homebrew** (o crear un usuario nuevo en mi Mac) antes de la instalación de Karen.
- [ ] Revisar qué modo de permisos de Codex conviene para que pueda instalar programas (acceso a red y comandos fuera del sandbox) sin quitarle al usuario la confirmación.
- [ ] Confirmar que la extensión Codex funciona bien en Windows nativo o si conviene WSL (para este público, evitar WSL).
- [ ] Medir cuánto tarda en cada sistema (Homebrew + Command Line Tools puede tardar 10–20 min en Mac).

**Proyecto base**

- [ ] Repo/ZIP con el proyecto, `AGENTS.md`, Skills y MCP configurado.
- [ ] Probar el flujo completo desde cero en una máquina limpia.
- [ ] Error "a propósito" preparado para el bloque 9.

**Material para participantes**

- [ ] Guía con capturas para los pasos manuales (VS Code, Codex, iniciar sesión, abrir el kit).
- [ ] PDF (enviado por el grupo y fijado) con: plantilla de pedido, lista de pedidos sugeridos, las 5 reglas de seguridad y un glosario de 10 palabras (página, carpeta, navegador, localhost, enlace, IA, receta/Skill, control remoto/MCP, puente/túnel, formulario).
- [ ] Ejemplos de páginas terminadas para inspirarse.

**Logística**

- [ ] Grupo de WhatsApp con los cuatro: enlace de llamada, prompts y PDF fijados.
- [ ] Mandar antes las reglas de la llamada (audífonos, cómo pedir ayuda, privacidad al compartir).
- [ ] Ensayo con Karen: compartir mi pantalla con VS Code al 150 % y comprobar que se lee bien en su laptop.
- [ ] Plan B si la red de alguien bloquea `trycloudflare.com`: VS Code Port Forwarding.
- [ ] Verificar el plan de ChatGPT que necesita cada uno para usar Codex y su costo; avisarles antes.

---

## 12. Resultado esperado

Al terminar, cada participante habrá:

- ✅ Creado la página web de su negocio o proyecto sin escribir código.
- ✅ Aprendido a pedirle cosas a la IA de forma clara.
- ✅ Usado reglas permanentes (`AGENTS.md`) y una receta (Skill).
- ✅ Encendido, apagado y publicado su página usando solo lenguaje natural.
- ✅ Recibido mensajes a través de un formulario de contacto.
- ✅ Abierto su página desde el celular.
- ✅ Resuelto un problema pidiéndole a la IA que lo revise.
- ✅ Quedado con el proyecto en su computadora para seguir mejorándolo.

---

## 13. Ruta de crecimiento (serie de capacitaciones)

| Nivel | Contenido (para el mismo público) |
|---|---|
| **1 (Sesiones 0–4)** | Mi primera página con IA: crear, mejorar, control remoto, verla en el celular, dirección fija |
| 2 | Publicar mi página en un hosting para que esté siempre en línea |
| 3 | Mi página recibe y organiza información: formularios, citas, catálogo |
| 4 | Mi página con usuarios, panel de administración e IA integrada |

---

## 14. Decisiones pendientes

- [x] ~~Sesión previa o equipos preparados~~ → **Sesión previa de instalación hecha por la IA.**
- [x] ~~Presencial o virtual~~ → **Todo por videollamada de WhatsApp** con pantalla compartida.
- [x] ~~Tamaño del grupo y sistemas~~ → **3 personas**: Jesús e Ileana (Windows), Karen (Mac).
- [ ] Fechas de las tres instalaciones (Karen → Jesús → Ileana) y de la capacitación.
- [ ] Cómo probar Windows antes de la instalación de Jesús (VM o computadora prestada).
- [ ] Versión de Windows de Jesús e Ileana, y si las computadoras son personales.
- [ ] **Cuenta de ChatGPT** de cada uno: plan necesario para Codex y quién lo paga.
- [ ] De qué será la página de cada uno (negocio, proyecto o idea personal).
- [ ] ¿Se graba la sesión para que la repasen?
- [x] ~~Formato~~ → **Sesiones de 1 hora**; la Sesión 1 es landing + crear MCP + túnel rápido.
- [x] ~~Sesión 4: opción A u opción B~~ → **Opción A** con `ezekl.com`: `jesus.`, `ileana.`, `karen.` (túneles y tokens creados).
- [ ] Probar los túneles de Jesús e Ileana desde Windows (el de Karen ya se probó desde la Mac de Ezequiel).
