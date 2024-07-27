# Proyecto-Integrado-2

## Introducción
Soy empleado de una empresa emergente de alimentos y necesito estudiar el comportamiento de los usuarios de la aplicación de la empresa.

En primer lugar, necesito estudiar el embudo de ventas. Quiero saber cómo llegan los usuarios a la etapa de compra. ¿Cuántos usuarios llegan realmente a esta etapa? ¿Cuántos se quedaron atascados en los pasos anteriores?

Luego analizaré los resultados de la prueba A/A/B. Los diseñadores quieren cambiar las fuentes de toda la aplicación, pero los gerentes temen que el nuevo diseño pueda intimidar a los usuarios. Los usuarios se dividen en tres grupos: dos grupos de control reciben fuentes antiguas y un grupo de prueba recibe fuentes nuevas. Vamos a averiguar qué conjunto de fuentes proporciona la mejor conversión.

## Descripción de los datos
Cada entrada de registro es una acción de usuario o un evento:

- EventName: nombre del evento.
- DeviceIDHash: identificador de usuario unívoco.
- EventTimestamp: hora del evento.
- ExpId: número de experimento: 246 y 247 son los grupos de control, 248 es el grupo de prueba.
