
# P-NP - Análisis Crítico

**Autor:** Cristian Ferney Ramirez Rave - Medellín, Colombia
**Fecha:** Octubre 2026

### Qué es esto
Intento de resolver 3-SAT con un resolvedor adaptativo con base de datos retroalimentativa y olvido dinámico.

### Qué pasó
El algoritmo falla por *thrashing* en fórmulas del Principio del Palomar (PHP_n).
Según Haken (1985), este tipo de resolvedores basados en resolución requieren tiempo exponencial Ω(2^{n^0.1}) en estos casos.

Por lo tanto, esta vía NO prueba P=NP.

### Qué demuestra
Que mi modelo específico no funciona. No demuestra que P != NP en general, que sigue abierto.

### Archivos
- `P_NP.pdf` - Documento final con análisis formal

Dejo esto público para que otros estudiantes no pierdan tiempo en la misma idea. 
