# SLER - Sistema de Lectura y Escritura Recíproco

Repositorio central del ecosistema SLER. Este proyecto centraliza las herramientas y documentación del sistema desarrollado por **Jonatan Ribot** en Bell Ville, Córdoba, Argentina.

## 🛠 Metodología y Lógica del Algoritmo
El motor de renderizado **SLER V2** no altera la cadena de caracteres ni el orden de las letras. Su función principal es la **reestructuración dinámica del flujo de texto** mediante las siguientes reglas lógicas:

1. **Gestión de Ruptura de Línea:** El algoritmo calcula el espacio disponible y permite que una palabra se fragmente si al menos una sílaba encaja, utilizando un guion para indicar la continuidad.
2. **Alternancia de Referencia (M/C):** Implementa un sistema de saltos entre líneas pares e impares donde el guion actúa como un puntero visual. En líneas específicas, el guion precede a la palabra para advertir que el término es inconcluso y debe completarse en la línea antagonista.
3. **Respeto Semántico:** A pesar de la fragmentación técnica para aprovechar el espacio, la integridad de la palabra y el orden gramatical se mantienen intactos, optimizando solo la disposición visual del bloque.

## 📝 Registro y Autoría
* **Desarrollador:** Jonatan Ribot.
* **Estado:** Software registrado como Propiedad Intelectual y Copyright (2025).
* **Ubicación:** Bell Ville, Córdoba, Argentina.

## 🔗 Enlaces del Ecosistema
- [Conversor SLER V2 (Motor)](https://jonatan823.github.io/Sler-V2-Engine/)
- [Blog Oficial](https://sler13.blogspot.com)
