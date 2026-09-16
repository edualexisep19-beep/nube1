# Capítulo 1 — Qué hace realmente un inspector QA/QC

---

Son las cuatro y media de la tarde. La grúa está esperando, el capataz lleva veinte minutos mirándote y te dice lo mismo que te va a decir mil veces en tu carrera:

> —Jefe, ¿me firma? Es solo una junta.

Y ahí está el trabajo completo, resumido en una frase.

Porque la pregunta real no es si la junta está buena. La pregunta real es: **¿contra qué documento la estás evaluando, con qué criterio de aceptación, y qué pasa dentro de cinco años cuando alguien abra el dossier y vea tu firma ahí?**

Este capítulo trata de eso: de entender exactamente qué eres, qué no eres, y qué significa tu firma. Si esto te queda claro, el resto del libro es técnica. Si no te queda claro, la técnica no te va a salvar.

---

## 1.1 QA y QC no son lo mismo (y casi nadie lo explica bien)

En obra vas a escuchar "calidad" como si fuera una sola cosa. Son dos.

**QA — Aseguramiento de la Calidad.** Es el **sistema**. Se ocupa de que existan procedimientos, de que la gente esté calificada, de que los equipos estén calibrados, de que el proceso esté definido *antes* de que alguien encienda una máquina. QA trabaja sobre el **proceso** y su objetivo es **prevenir**.

**QC — Control de la Calidad.** Es la **verificación**. Mide, inspecciona, ensaya y compara el producto real contra lo que pedía el documento. QC trabaja sobre el **producto** y su objetivo es **detectar**.

La forma más simple de recordarlo:

> **QA escribe la receta y revisa que la cocina esté apta. QC prueba el plato antes de que salga.**

En la práctica, en obra mediana, tú haces las dos cosas y el cargo se llama "inspector QA/QC". Pero tienes que saber en cuál de los dos sombreros estás parado en cada momento, porque las preguntas son distintas:

| | QA pregunta | QC pregunta |
|---|---|---|
| Soldador | ¿Está calificado para este procedimiento? | ¿Esta soldadura que hizo cumple? |
| Equipo | ¿Está calibrado y vigente? | ¿Qué me está midiendo ahora? |
| Procedimiento | ¿Existe, está aprobado y es el vigente? | ¿Se está siguiendo tal como dice? |
| Pintura | ¿El aplicador está capacitado? ¿Hay hoja técnica? | ¿Cuánto espesor tiene esta mano? |

**Por qué importa:** cuando algo sale mal, la pregunta del cliente nunca es solo "¿por qué pasó?". Es "¿por qué el sistema permitió que pasara?". Esa segunda pregunta es QA. Y si tú solo miraste el producto, no tienes respuesta.

---

## 1.2 Para quién trabajas cambia todo

Dos inspectores pueden estar mirando la misma junta y tener obligaciones distintas. Depende de quién les paga.

- **Inspector del contratista (o subcontratista).** Trabajas para el que ejecuta. Tu función es que el trabajo salga conforme **antes** de que lo vea el cliente. Eres el filtro propio. Si el cliente encuentra un defecto que tú no encontraste, el problema es tuyo.
- **Inspector del cliente (o de la EPC / gerencia de proyecto).** Verificas lo que entrega el contratista. Tú **aceptas o rechazas** en nombre de quien paga la obra. Tienes más autoridad y más exposición.
- **Inspector de tercera parte.** Trabajas para un organismo independiente contratado para certificar. Tu valor es la **imparcialidad**: no le debes nada a ninguna de las dos partes. Firmas lo que viste, y punto.

Antes de tu primer turno, ten claro en cuál estás. Determina a quién le reportas, qué puedes detener, y quién revisa tu trabajo.

**Regla que no falla:** tu autoridad real es la que dice el **contrato y el plan de calidad del proyecto**, no la que crees tener. Pídelo y léelo.

---

## 1.3 Qué NO es tu trabajo

Esto es tan importante como lo anterior, porque el inspector nuevo tiende a invadir terreno ajeno y a perder credibilidad.

- **No eres producción.** No decides cómo se ejecuta ni cómo se repara. Dices si cumple o no cumple. El *cómo* lo resuelve el contratista con su procedimiento.
- **No eres diseño.** Si la especificación pide algo que te parece mal, no lo cambias por tu cuenta. Lo levantas como consulta técnica al que diseñó.
- **No eres el que hace los END.** Los ensayos no destructivos los ejecuta personal certificado para eso. Tú los **solicitas, presencias y evalúas el informe**. (Cap. 7.)
- **No eres HSE.** Si ves una condición insegura la reportas de inmediato —eso es obligación de cualquier persona en obra—, pero la seguridad tiene su propia estructura y sus propios inspectores.
- **No eres la policía.** El inspector que anda buscando culpables se queda solo y sin información. El que anda buscando **conformidad** consigue que le avisen antes de cometer el error. Es una diferencia de actitud que se nota en el primer mes.

---

## 1.4 Tu firma: lo único que realmente vendes

Un inspector no vende horas. Vende **firmas confiables**.

Cuando firmas un protocolo, un registro o una liberación, estás declarando tres cosas al mismo tiempo:

1. Que **lo verificaste personalmente**, no que te lo contaron.
2. Que lo comparaste contra un **documento identificable** (norma, especificación, procedimiento, plano y su revisión).
3. Que **cumple** ese criterio.

Ese papel se va al dossier de calidad y ahí se queda. Diez, quince, veinte años. Si esa línea falla, se abre el dossier. Y lo primero que aparece es tu nombre.

Por eso, tres reglas duras:

> **No firmes lo que no viste.** Ni por confianza, ni por apuro, ni porque "siempre sale bien".
>
> **No firmes en blanco, ni retroactivo, ni un formato incompleto.** Un registro sin fecha, sin revisión de plano o sin identificación de la junta no vale nada, y a la vez te compromete todo.
>
> **No firmes bajo presión.** La presión de terreno es real y es constante. Pero el que te apura hoy no va a estar en la reunión el día que se investigue la falla.

Y su contraparte, igual de importante: **firma rápido lo que sí cumple**. El inspector que retiene liberaciones sin motivo genera más daño que uno permisivo, y termina siendo ignorado. Tu credibilidad se construye igual en los dos sentidos: rechazas lo que no cumple, y liberas sin demora lo que cumple.

---

## 1.5 Las tres preguntas antes de aceptar cualquier inspección

Grábate estas tres. Te van a sacar del 90% de los problemas:

**1. ¿Contra qué documento lo inspecciono?**
Nombre, número y **revisión**. Un plano revisión B y uno revisión C son dos obras distintas. (Cap. 2.)

**2. ¿Cuál es el criterio de aceptación, y quién lo definió?**
"Se ve bien" no es un criterio. El criterio sale del código y de la especificación del proyecto. Si no lo tienes por escrito, no tienes inspección: tienes una opinión.

**3. ¿Tengo el equipo adecuado y calibrado?**
Galgas, medidor de espesores, termómetro, luxómetro, lo que corresponda. Con certificado vigente. Un instrumento sin calibración vigente invalida la medición y, con ella, tu firma.

Si alguna de las tres no tiene respuesta, **no se inspecciona todavía**. No es obstruccionismo: es lo que te permite defender el registro después.

---

## 1.6 La cadena documental: de dónde sale tu autoridad

Todo lo que puedes exigir viene de una cadena. Entenderla te cambia la forma de discutir en terreno, porque dejas de decir "yo pienso" y empiezas a decir "lo pide este documento".

```
CONTRATO
   └── ESPECIFICACIÓN TÉCNICA DEL PROYECTO   (lo que el cliente exige)
          └── NORMA / CÓDIGO APLICABLE        (el estándar de referencia)
                 └── PROCEDIMIENTOS           (cómo lo va a hacer el contratista)
                        └── ITP               (qué se inspecciona y en qué punto)
                               └── REGISTRO   (la evidencia de que se hizo)  ← tu firma
```

Léela de arriba hacia abajo: cada nivel obedece al de arriba.

Dos consecuencias prácticas:

- **La especificación del proyecto puede ser más exigente que la norma, nunca menos.** Si la spec pide más, manda la spec.
- **Si algo no está en ningún nivel de esa cadena, no lo puedes exigir.** Y si crees que debería estar, el camino es una consulta técnica formal, no una discusión en el andamio.

---

## 1.7 Cuando algo no cumple, la decisión no es tuya

Este punto confunde a todo el mundo al principio.

Tú **detectas y documentas** el incumplimiento. Lo que se hace después —reparar, rechazar, aceptar como está— **no lo decides tú**.

- **Reparar / rehacer**: lo ejecuta el contratista con un procedimiento de reparación aprobado. Tú verificas que la reparación cumpla.
- **Aceptar aunque se desvíe de lo especificado**: eso es una **concesión o desviación**, y la autoriza **quien es dueño del requisito** (el cliente, o el área de diseño). Jamás el inspector, jamás el capataz, jamás "de palabra".

Tu aporte al proceso es que el hecho quede **registrado con evidencia**, para que quien decide lo haga con información real. (Todo el mecanismo está en el Cap. 9.)

Decirlo en terreno es simple y desactiva casi cualquier discusión:

> —Yo no puedo aceptarlo así. Lo dejo registrado con la foto y la medición, y lo resuelve el cliente. Si lo autoriza, seguimos.

---

## 1.8 Los cinco errores del inspector nuevo

Los vas a ver todos. Ojalá en otros.

1. **Inspeccionar de memoria.** Llevas seis meses viendo lo mismo y dejas de abrir el plano. El día que cambió la revisión, liberaste mal cincuenta juntas.
2. **Confiar en lo verbal.** "Ya lo revisó el otro turno." Si no está escrito y firmado, no ocurrió.
3. **Pelear en vez de documentar.** Discutir a gritos no cambia un criterio. Un registro con foto, medición y referencia al documento, sí.
4. **Llenar el papeleo al final del día.** Lo que no anotaste en el momento, lo inventaste. Y se nota.
5. **Aceptar el "después te lo mando".** El certificado del material, la calificación del soldador, la calibración del equipo: **antes**, no después. Si dejas pasar el trabajo esperando el papel, ese papel nunca llega.

---

## Checklist del capítulo 1

Antes de tu primer turno en un proyecto nuevo, responde por escrito:

- [ ] ¿Para quién trabajo: contratista, cliente o tercera parte?
- [ ] ¿A quién le reporto y quién revisa mis registros?
- [ ] ¿Qué tengo autoridad para detener, según el plan de calidad del proyecto?
- [ ] ¿Cuál es la especificación técnica del proyecto y en qué revisión está?
- [ ] ¿Qué código o norma aplica, y en qué edición?
- [ ] ¿Tengo acceso al ITP y sé cuáles son mis puntos de control?
- [ ] ¿Qué equipos de medición necesito y están calibrados y vigentes?
- [ ] ¿Qué formatos de registro debo usar y dónde se guardan?
- [ ] ¿Quién autoriza una concesión o desviación en este proyecto?

Si no puedes responder alguna, esa es tu primera tarea. No la soldadura.

---

**En el capítulo 2** entramos a los documentos uno por uno: qué te tienen que entregar antes de inspeccionar, qué revisas en cada uno, y cómo detectar en dos minutos que te están pasando un papel vencido.
