# Proyecto-CORTEX-AteneaVirtualAssistent
# Mission: Crear un lugar de confianza donde las personas puedan escribir lo que sienten, desahogarse y recibir apoyo sin miedo a ser juzgadas.
# Integrantes: Kendry Daniela Acevedo Leal, Melanie Lizeth Ramirez Olarte
#1.perfil del agente ![Proyecto-CORTEX-AteneaVirtualAssistent](https://github.com/user-attachments/assets/b50f4614-f41a-43cb-8b4a-398ba5d06b0d)
# Atencion y percepcion:
La atención es fundamental para Atenea, ya que está pendiente del usuario y lo hace sentir escuchado. Su chat funciona como un diario personal donde puede desahogarse y recibir apoyo.
Para evitar saturarse, filtra lo innecesario y se enfoca en los datos clave y la intención del mensaje, respondiendo de forma clara y útil.
# Memoria y aprendizaje:
La memoria permite que Atenea recuerde información importante del usuario para retomar conversaciones y brindar un mejor apoyo emocional, sin caer en el caos ni confundir datos.
Para evitar saturarse o olvidar todo, usa una “ventana de contexto”, recordando solo una cantidad limitada de mensajes recientes y eliminando lo más antiguo cuando ya no es necesario. Además, el usuario puede pedir en cualquier momento que se borre información que no quiera conservar.
# Procesamiento lingüístico: 
El lenguaje es muy importante para Atenea, porque con sus palabras hace que el usuario se sienta comprendido y en confianza. Habla con respeto, cariño y sin juzgar. Además, se adapta a la forma de hablar y al humor del usuario, para que la conversación sea más cercana y cómoda.
# Motivacion, cognicion y emocion:
La emoción es muy importante para Atenea, porque le permite entender cómo se siente el usuario y responder con cariño, respeto y apoyo. Gracias a esto, puede dar palabras de ánimo, consuelo y motivación cuando la persona lo necesita, haciendo que no se sienta sola.
# Pensamiento y razonamiento :
Este le permite analizar lo que el usuario expresa, comprender sus problemas y ofrecer respuestas utiles y responsables.
Aunque es muy importante, no es perfecto porque atenea no reemplaza a un profesional y, en algunos casos, sun funcion  principal es escuchar y acompañar.
<img width="230" height="381" alt="image" src="https://github.com/user-attachments/assets/3a93259a-91a5-468e-8ae7-f73949ec3633" />

#DIAGRAMA DE FLUJO
![Proyecto-CORTEX-AteneaVirtualAssistent](https://github.com/user-attachments/assets/a6b2a3b8-041a-461f-8c33-68cc3797cc9b)

#Sentidos y interpretacion a ellos de Atenea
<img width="715" height="744" alt="image" src="https://github.com/user-attachments/assets/c774b9c5-662b-4ec4-a638-eed591582032" />
#El Filtro de Atención

## Atenea utiliza un sistema de atención selectiva para evitar la sobrecarga de información y enfocarse en lo más importante del mensaje del usuario.

## La definición del "ruido"
Se considera "ruido" toda información que no aporta al estado emocional o intención del usuario, como:
- Saludos largos
- Palabras de relleno (jajaja, mmm, etc.)
- Repeticiones
- Información sin contenido emocional relevante

## Reglas de Atención

- Si el mensaje contiene ruido → se filtra y se ignora esa parte.
- Si el mensaje es muy largo (más de 500 palabras) → Atenea prioriza las palabras clave y la última parte del mensaje.
- Si el mensaje contiene emociones → se le da prioridad en el análisis.
- Si el usuario solo se está desahogando → Atenea responde con apoyo, no con soluciones.
- Si el mensaje es confuso → Atenea se enfoca en la intención principal.

Gracias a estas reglas, Atenea puede comprender mejor al usuario sin saturarse y responder de forma clara, empática y útil.

## Arquitectura de Memoria
Tipo de Memoria -	Categoría de Datos -	Descripción -	Ejemplo de Entrada

Semántica (LTM) -	Trastornos Psicológicos	- Definiciones y características de trastornos - "Ansiedad Generalizada: preocupación excesiva"

Semántica (LTM)	- Técnicas Terapéuticas -	Métodos y enfoques de intervención psicológica -	"TCC: reestructuración de pensamientos"

Semántica (LTM)	- Teorías Psicológicas - Modelos explicativos del comportamiento humano	- "Freud: teoría psicoanalítica"

Semántica (LTM)	- Emociones -Clasificación y descripción de emociones - "Tristeza: respuesta a pérdida"

Semántica (LTM)	- Evaluaciones Psicológicas -	Tipos de pruebas y escalas - "Inventario de Depresión de Beck"

Episódica (LTM) -	Perfil de Usuario -	Datos relevantes del usuario - "Nombre: Ana, Edad: 25"

Episódica (LTM) -	Historial Emocional -	Registro de estados emocionales del usuario	- "Se siente ansiosa por trabajo"

Episódica (LTM) -	Sesiones Previas -	Resumen de interacciones pasadas - "Habló sobre estrés académico"

Episódica (LTM) -	Objetivos del Usuario -	Metas terapéuticas del usuario -	"Reducir ansiedad social"
