# alura-curso-regex

## Comandos rotineiros

### Âncoras
- **\b**   _word boundary_
- **^**   _início do alvo_
- **$**   _fim do alvo_

### Quantifer
- **{n, m}**  _no mínimo n, no máximo m vezes_
- **?**  _0 ou 1 vez_
- **\+**  _1 ou mais vezes_
- **\***  _0 ou mais vezes_

### Classes de char - []
- **[A-Z]**  _letras de A até Z_
- **[123]**  _1,2 ou 3_
- **\d**   _todos os dígitos = [0-9]_
- **\s**  _whitespace = [ \t\r\n\f]_
- **\w**  _wordchar [A-Za-z0-9_]_

### Grupos
- **(\w+)**  _grupo de word chars_
- **(\w+)?**  _grupo opcional_
- **(?:\w+)**  _non-capturing group_

### Outros
- **[^caracter]**  _negação_

## Help
1. _doc: https://www.rexegg.com/regex-quickstart.html_ 
2. _simulador: https://regexr.com/_
