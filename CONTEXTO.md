# Contexto del espacio

## Qué es
Espacio compartido entre líderes LDLA. Aquí se guarda la memoria de trabajo del
área de Setting: perfiles de cada setter, lecturas de llamadas, compromisos y
seguimiento.

## Quién lidera este espacio
**Brian — Líder de Setting.**

Objetivo declarado:

> Tener un equipo comprometido que facture, para una empresa que elige creer y
> apostar por mí como líder y como persona.

Lo que esto implica para el trabajo de este espacio:
- El foco no es solo técnica de setting: es **compromiso + facturación**.
- Cada setter se trabaja desde su aspiración personal, no solo desde su número.
- Brian responde ante la empresa: todo lo que se registre debe poder traducirse
  en decisiones (formar, reforzar, promover o soltar).

## Cómo se trabaja
1. Brian aporta llamadas grabadas / transcripciones de los setters.
2. Por cada llamada se genera o actualiza la ficha del setter en `setters/`.
3. Cada cierto número de llamadas se actualiza la lectura de equipo en
   `equipo/lectura-de-equipo.md` (patrones comunes, riesgos, palancas).
4. Las acciones que salen de cada llamada se cargan **por día** en el tablero de
   tareas (`tareas/`, ver [`tareas/README.md`](tareas/README.md)), donde Braian
   las marca a medida que las resuelve.
5. Todo queda versionado para poder mirar la evolución en el tiempo.

## Estructura
- `setters/` — una ficha por setter (`setters/nombre.md`).
- `setters/_PLANTILLA-SETTER.md` — plantilla base de cada ficha.
- `equipo/lectura-de-equipo.md` — visión transversal del equipo.
- `tareas/` — tablero de tareas por día (HTML publicado + registro de lo cargado).

## Personas del entorno (mencionadas en las llamadas)
- **Braian** — Líder de Setting. Conduce las entrevistas 1:1.
- **Marco** — referencia operativa del equipo; valida las iniciativas de Braian.
- **Vika** — da clases/formación; Kelly se descarga con ella cuando se satura.
- **Brenda** — setter; citada por Kelly como el estándar correcto en el manejo de bandejas.
- **Tobías** — setter; amigo de Yaris, se apoyan mutuamente.

## Estado del relevamiento
**Equipo de setting bajo Braian: 5 personas** (Yumico queda fuera: setea para la
socia de Vika, no reporta a esta estructura).

- ✅ **Entrevistados y analizados (3):** Yaris, Rosario, Kelly — llamadas del 29/09/2026.
- ⏸️ **Diferidos por decisión de Braian (30/09/2026):**
  - **Brenda** — está en el estado objetivo, sin fricción. *Nota: es el caso de
    mayor valor pendiente, porque es el único modelo replicable que hay.*
  - **Tobías** — menos de una semana. Sugerido entrevistarlo a los 30 días.
- 🚫 **Fuera de alcance:** Yumico.

La lectura de equipo en `equipo/lectura-de-equipo.md` está calculada sobre 3 de 5
y **no va a cambiar hasta que entre Brenda**. Los patrones actuales describen lo
que falla; falta el contraste con lo que funciona.

### Pendientes abiertos
1. Sacar del CRM los números de los tres analizados (conversaciones, agendas,
   show rate). Sin esto no se puede confirmar ni descartar la queja de Yaris
   sobre calidad de leads.
2. Escalar a Marco / la empresa el esquema de compensación de Kelly.
3. Publicar la regla de bandejas (estándar: la práctica de Brenda).
4. Devolver respuesta a las propuestas de los tres.
5. Registrar los primeros 30 días de Tobías mientras ocurren — es el único test
   en vivo de la debilidad de onboarding que señaló Kelly.

## Setters con ficha
| Setter | Antigüedad | Estado | Riesgo de fuga | Ficha |
|---|---|---|---|---|
| Yaris | a confirmar | ✅ analizado | 🔴 Alto (1-2 meses) | [`setters/yaris.md`](setters/yaris.md) |
| Rosario Sulla | reciente | ✅ analizado | 🟢 Bajo | [`setters/rosario.md`](setters/rosario.md) |
| Kelly Chaverra | +1 año (la más experimentada) | ✅ analizado | 🟡 Bajo, pero sin aviso previo | [`setters/kelly.md`](setters/kelly.md) |
| Brenda | mucha experiencia | ⏸️ diferido — **estado objetivo del equipo** | 🟢 Bajo | [`setters/brenda.md`](setters/brenda.md) |
| Tobías | < 1 semana | ⏸️ diferido | sin datos | [`setters/tobias.md`](setters/tobias.md) |
| Yumico | — | 🚫 fuera de alcance (setea para la socia de Vika) | — | [`setters/yumico.md`](setters/yumico.md) |
