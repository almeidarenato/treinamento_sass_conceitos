## Utilidade do SASS
Simplificar e Organizar o CSS
Manutenção
Rapidez e reuso de código
Maior compatibilidade com múltoplos navegadores
Permite Programar em CSS: Variáveis , Funções, Repetições , IF/Else

## Oque é 
Syntactically Awesome StyleSheets
Um pré processador CSS que irá dar poderes ao nossos estilos
Compila Estrutura de código de `.scss` ou `.sass` para `.css`


## Como usar
- Instalar o sass globalmente `npm i -g sass`
ou
- Instalar extensão no VSCode `live sass compiler` (necessário o live server instalado)

## Features 
- Organizar arquivos/pastas
- Importar : `@import`
- Partials: `_name.scss`
- Encadeamento
- Variáveis: `$varname`
- Escopos
- Mixins: `@mixin @include`
- Condicionais: `@if @else if @else`
- Herança: `@extends`
- Repetições: `@for e @each`
- Funções `ligthen() darken()`
- Referencing `&:hover`
- Fazer o arquivo ficar menor - basta nas configurações da extensão Live Sass configurar o format para `compressed`