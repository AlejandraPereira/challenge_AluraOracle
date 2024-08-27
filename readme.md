ENCRIPTADOR DE TEXTO

Este proyecto fue desarrollado en un entorno Mac utilizando el lenguaje de programación JavaScript como parte de un challenge del curso de Oracle ofrecido por Alura Latam. La herramienta está diseñada para encriptar y desencriptar texto utilizando un sistema de sustitución basado en las siguientes llaves de encriptación:

- La letra "a" es convertida a "ai"
- La letra "e" es convertida a "enter"
- La letra "i" es convertida a "imes"
- La letra "o" es convertida a "ober"
- La letra "u" es convertida a "ufat"

CONSIDERACIONES:

- Solo se permite el uso de letras minúsculas.
- No utilizar acentos, signos o caracteres especiales.

ELEMENTOS PRINCIPALES DE LA PÁGINA

- Campo para el texto que va a ser encriptado/desencriptado: Area ingresar el texto que se desea procesar.
- Botón para encriptar: Al hacer clic, convierte el texto ingresado en su versión encriptada.
- Botón para desencriptar: Al hacer clic, convierte el texto ingresado en su versión desencriptada.
- Área para mostrar el texto encriptado/desencriptado: donde se muestra el resultado después de procesar el texto.

COMO FUNCIONA

ENCRIPTACION:

El proceso de encriptación transforma el texto original en una versión encriptada basada en las llaves de encriptación. A continuación, se muestran algunos ejemplos:

Entrada: "gato"
Proceso: La letra "a" se convierte en "ai" y la letra "o" se convierte en "ober".
Salida: "gaitober"

Entrada: "cielo"
Proceso: La letra "i" se convierte en "imes" y la letra "o" se convierte en "ober".
Salida: "caieltober"

Entrada: "amigo"
Proceso: La letra "a" se convierte en "ai" y la letra "o" se convierte en "ober".
Salida: "aimigober"

DESENCRIPTACION:

El proceso de desencriptación convierte el texto encriptado de vuelta a su forma original. Ejemplos de este proceso son:

Entrada: "henterllober"
Proceso: La secuencia "enter" se convierte en "e" y "ober" se convierte en "o".
Salida: "hello"

Entrada: "friteriend"
Proceso: La secuencia "imes" se convierte en "i".
Salida: "friend"

Entrada: "cumpufater"
Proceso: La secuencia "ufat" se convierte en "u".
Salida: "computer"


FUNCIONALIDAD EXTRA: 

Botón Copiar: Permite copiar el texto encriptado o desencriptado al portapapeles. Este botón reemplaza la funcionalidad de Ctrl+C o la opción "Copiar" en el menú de aplicaciones.