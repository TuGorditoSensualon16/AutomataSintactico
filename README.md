# AutomataSintactico
Analizador Sintactico del lenguaje 
Documentación del Analizador Léxico para Código C++ utilizando PLY
Introducción
El analizador léxico es una herramienta esencial en la compilación de código fuente, ya que se encarga de reconocer y clasificar los componentes léxicos, o tokens, que conforman un programa. En este contexto, se presenta un analizador léxico implementado en Python utilizando la librería PLY (Python Lex-Yacc) para el lenguaje de programación C++.

Objetivo
El objetivo principal de este analizador léxico es identificar y categorizar los elementos fundamentales de un código C++, como palabras reservadas, identificadores, operadores aritméticos, lógicos y otros símbolos relevantes.

Implementación
Herramientas Utilizadas
Python 3.x
Biblioteca PLY
Funcionamiento
El funcionamiento del analizador léxico se basa en la definición de expresiones regulares para reconocer los tokens presentes en el código fuente. Se han definido patrones para identificar palabras reservadas, operadores, identificadores, números enteros, cadenas y otros elementos característicos del lenguaje C++.

Tokens Reconocidos
El analizador léxico reconoce una variedad de tokens, incluyendo:

Palabras reservadas como include, using, namespace, std, cout, cin, get, return, void, entre otras.
Operadores aritméticos y lógicos como +, -, *, /, &&, ||, entre otros.
Símbolos de puntuación como ;, ,, {, }, [, ], (), #, <<, >>, entre otros.
Uso del Código
El código implementado consiste en la definición de las expresiones regulares para cada token reconocido, así como funciones asociadas a las palabras reservadas y reglas para manejar errores o comentarios presentes en el código fuente.

Consideraciones al Usar el Analizador
Se recomienda introducir código C++ válido para obtener resultados precisos y evitar errores durante el análisis léxico.
Los comentarios (de una línea o multilineales) son ignorados durante el proceso de análisis.
Si se introduce un token no reconocido, el analizador generará un mensaje indicando la línea, el valor y la posición del token no válido.
Ejemplo de Uso
Ejecutar el script proporcionado.
Ingresar código C++ válido cuando se solicite la entrada.
Observar los resultados generados por el analizador léxico en la consola, indicando el tipo, valor, línea y posición de cada token reconocido.
Conclusiones
El analizador léxico desarrollado utilizando PLY en Python es capaz de identificar y clasificar los tokens presentes en un código C++ proporcionado como entrada, facilitando así el proceso de análisis y comprensión del código fuente.
