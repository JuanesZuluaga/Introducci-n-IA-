# Ficha de análisis

## 1. Nombre del Space

**Nombre:** Nemotron-Labs-Audex

**Enlace:** https://huggingface.co/spaces/nvidia/Nemotron-Labs-Audex

---

## 2. ¿Qué hace el agente?

Este agente toma voz y la decodifica transformándola en texto. A su vez, también tiene otras funciones como tomar texto y leerlo, generar un audio con el texto transcrito o traducir un audio previamente cargado.

---

## 3. Análisis PEAS

### Performance
**¿Qué significa que el agente haga bien su trabajo?**

- Confiabilidad en la transcripción.
- Tiempo de respuesta.
- Uso de tokens.

### Environment
**¿Con qué interactúa el agente?**

- Personas.
- Voces.
- Textos.

### Actuators
**¿Qué acciones produce?**

- Transcribe.
- Traduce.
- Genera audio.

### Sensors
**¿Qué información recibe como entrada?**

- Audios.
- Texto.

---

## 4. Clasificación del entorno

Complete la siguiente tabla y justifique brevemente cada respuesta.

| Propiedad | Clasificación | Justificación |
|-----------|---------------|---------------|
| Observable | Parcial | Solo percibe la información en los momentos en que se ejecuta la aplicación para recibir o escuchar la entrada. |
| Determinista | No | Puede presentarse aleatoriedad debido al ruido ambiental o a una mala pronunciación, afectando la respuesta. |
| Episódico | Sí | Cada tarea es independiente y las respuestas no se almacenan para alterar futuras ejecuciones. |
| Estático | Sí | El entorno no sufre cambios durante el proceso de ejecución. |
| Discreto | No | El trabajo consiste en procesar ondas de audio continuas, las cuales no pueden dividirse en componentes fijos o claramente definidos. |
| Conocido | Sí | Sigue un conjunto de reglas lingüísticas previamente definidas. |

---

## 5. ¿Qué tipo de programa de agente creen que es?

### Agente basado en objetivos

El agente está diseñado para cumplir objetivos específicos, como convertir un audio **A** en una transcripción **B**, o traducir un audio **A** para producir una respuesta **B** en otro idioma.

---

# Reto adicional

## 1. Totalmente observable, determinista y episódico

**Nombre:** Tic-Tac-Toe

**Enlace:** https://huggingface.co/spaces/anakin87/LFM2-2.6B-mr-tictactoe

- **Observable:** El agente puede ver en todo momento el estado completo del tablero y los movimientos del jugador.
- **Determinista:** No existen factores aleatorios; todas las acciones dependen de reglas lógicas.
- **Episódico:** Cada partida tiene reglas fijas y el resultado de una partida no modifica las siguientes.

---

## 2. Parcialmente observable, estocástico y secuencial

*Pendiente por completar.*
