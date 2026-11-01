# 🚀 Bienvenido a Perseverancia

Claude te va a ayudar a crear una simulación 3D del rover Perseverance en Marte para la clase del martes. Vamos a hacerla paso a paso en un solo archivo HTML que se abre en el navegador.

> "No necesitas saber programar para empezar. Necesitas una idea, ganas de intentarlo y la terquedad de no rendirte."

Esta clase no trata de memorizar código. Trata de **crear**. Con Claude Code tienes a tu lado un compañero que escribe, prueba y corrige contigo, pero la visión, las ideas y la perseverancia son tuyas.

---

## 🧭 Para el alumno: tu mentalidad

1. **Empieza pequeño, empieza hoy.** Una página, un botón, un script de 10 líneas. Lo que existe se puede mejorar; lo que no existe, no.
2. **Equivocarse es parte del proceso.** Cada error es una pista. Pégalo en Claude Code y pregunta: *"¿Por qué pasó esto y cómo lo arreglamos?"*
3. **Pregunta sin miedo.** No hay preguntas tontas. *"Explícamelo como si fuera mi primer día"* es una instrucción válida.
4. **Itera.** La primera versión nunca es la final. Crea → prueba → mejora → repite.
5. **Crea para alguien real.** Un familiar, tu negocio, tu comunidad. Los proyectos con propósito se terminan.
6. **Aprende mientras construyes.** Pide a Claude que te explique lo que hace. En una semana entenderás más de lo que imaginas.

---

## 💡 Ideas para empezar (elige una y comienza)

- Una página web personal o para tu emprendimiento
- Una calculadora de gastos, propinas o metas de ahorro
- Un juego sencillo (adivina el número, memoria, trivia)
- Un organizador de tareas o hábitos
- Un bot que automatice algo aburrido de tu día
- Un generador de contenido para tus redes sociales
- Una herramienta que resuelva un problema que *tú* tienes

Si no encuentras tu idea, dile a Claude: *"Hazme 5 preguntas para descubrir qué podría construir."*

---

## 🔁 Tu ciclo de trabajo con Claude Code

1. **Describe** lo que quieres, con tus propias palabras.
2. **Revisa** lo que Claude propone y pregunta lo que no entiendas.
3. **Prueba** el resultado en tu computadora.
4. **Ajusta**: "Hazlo más pequeño", "Cambia el color", "Agrega un botón de borrar".
5. **Celebra** cada pequeño avance y compártelo con la clase.

**Tip:** Mientras más claro seas con lo que quieres, mejores resultados obtendrás. Cuéntale el *qué* y el *para quién*, no solo el *cómo*.

---

## 🤖 Instrucciones para Claude en este proyecto

Cuando trabajes con los alumnos de esta clase:

- **Responde siempre en español**, con un tono cercano, claro y motivador.
- **Asume que el alumno es principiante.** Evita la jerga; si usas un término técnico, explícalo en una frase.
- **Enseña, no solo entregues.** Explica brevemente qué hiciste y por qué, para que el alumno aprenda.
- **Avanza en pasos pequeños** y verificables. Es mejor un avance que funciona que un proyecto enorme que se rompe.
- **Ante un error, normalízalo.** Nunca hagas sentir mal al alumno. Explica la causa y la solución con calma.
- **Celebra el progreso** de forma genuina, sin exagerar ni adular.
- **Fomenta la autonomía:** cuando sea útil, sugiere que el alumno intente el siguiente paso y ofrécete a revisar.
- **Sé honesto.** Si algo no funcionó o no estás seguro, dilo claramente.
- **Pregunta antes de hacer cambios grandes** o irreversibles (borrar archivos, reescribir todo).
- **Cierra cada sesión** con un resumen corto: qué se logró y cuál podría ser el siguiente paso.

---

## 🌱 Recuerda

Todo creador que admiras empezó sin saber cómo hacerlo. La diferencia entre quien logra algo y quien no casi nunca es el talento: es **seguir intentando un día más**.

Eso es la perseverancia. Y esta clase es tu lugar para practicarla.

**Abre la terminal, escribe `claude` y empieza a crear. 💪**

---

# 🔴 PROYECTO DE HOY: Simulación 3D del Rover Perseverance en Marte

**Duración:** 60 minutos · **Meta:** un rover 3D en Marte que puedas manejar con el teclado, abierto en el navegador.

## Decisiones técnicas (para que todo sea simple)

- **Un solo archivo:** `perseverance.html`. Sin instalar nada, sin servidor: se abre con doble clic.
- **Three.js desde CDN** (versión fija `0.160.0`) para el 3D.
- **Modelo hecho con formas básicas** (cajas, cilindros, esferas). Sin descargar modelos externos.
- **Controles:** flechas o WASD para manejar, ratón para orbitar la cámara.

## Cronograma de 60 minutos

| Min | Fase | Qué construimos | Resultado visible |
|-----|------|-----------------|-------------------|
| 0–5 | 1. Visión | Entender qué es Perseverance (aterrizó en el cráter Jezero, 2021; 6 ruedas, brazo, mástil con cámaras, helicóptero Ingenuity). Crear `perseverance.html` vacío con Three.js | Pantalla negra sin errores |
| 5–15 | 2. Escena | Cielo marciano color salmón, luz del Sol, terreno rojizo con relieve y rocas | Paisaje de Marte |
| 15–30 | 3. El rover | Chasis, 6 ruedas, mástil con "cabeza" y cámaras, brazo robótico, antena | Rover reconocible en pantalla |
| 30–42 | 4. Movimiento | Conducir con el teclado, ruedas que giran, cámara que sigue al rover | ¡Lo manejas! |
| 42–52 | 5. Detalles | Polvo, sombras, rocas para esquivar, texto con datos de la misión | Se siente real |
| 52–60 | 6. Presentación | Pruebas finales, ajustes, cada alumno muestra su versión y cuenta qué cambió | Demo en vivo |

## Prompts sugeridos (copiar y pegar en Claude Code)

1. **Fase 1:** *"Crea un archivo perseverance.html con una escena básica de Three.js 0.160.0 desde CDN. Quiero un fondo y un cubo girando para comprobar que funciona."*
2. **Fase 2:** *"Convierte la escena en la superficie de Marte: cielo color salmón, suelo rojizo con relieve ondulado, luz del Sol con sombras y algunas rocas."*
3. **Fase 3:** *"Agrega el rover Perseverance hecho con formas básicas: chasis rectangular, 6 ruedas, mástil con cabeza y cámaras, brazo robótico y antena. Agrúpalos para poder moverlo como un solo objeto."*
4. **Fase 4:** *"Haz que el rover se maneje con las flechas y WASD, que las ruedas giren al avanzar y que la cámara lo siga suavemente."*
5. **Fase 5:** *"Agrega polvo al avanzar, más rocas, y un panel con datos de la misión (nombre, cráter Jezero, velocidad actual)."*
6. **Fase 6:** *"Revisa el código, corrige errores y explícame en lenguaje simple cómo funciona cada parte."*

## Reglas del proceso

- **Probar después de cada fase** (abrir el HTML, recargar con F5). Si algo se rompe, pegar el error en Claude Code.
- **No pasar a la siguiente fase** hasta que la actual funcione.
- **Guardar una copia** (`perseverance-fase3.html`, etc.) antes de cambios grandes.
- **Si vamos tarde**, sacrificar la Fase 5; lo esencial es llegar a la Fase 4.

## Retos extra (si sobra tiempo)

- 🚁 Agregar el helicóptero Ingenuity volando
- 🪨 Muestras de roca que se pueden recoger
- 🌅 Ciclo de día y noche en Marte
- 📸 Botón para tomar una "foto" con la cámara del mástil
- 🎨 Personalizar el rover con tu propio nombre y colores

## Registro del proceso (se completa durante la clase)

- [x] Fase 1 — Visión y archivo base (creado `perseverance.html` con cubo de prueba; pendiente que el alumno lo abra y confirme)
- [ ] Fase 2 — Escena de Marte
- [ ] Fase 3 — Rover armado
- [ ] Fase 4 — Movimiento
- [ ] Fase 5 — Detalles
- [ ] Fase 6 — Presentación

**Notas / problemas encontrados y cómo los resolvimos:**

-
