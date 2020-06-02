Tutorial 0



- SASS - *Syntactically Awesome	 Stylesheets*  são pré-processadores que permitem que façamos mágicas ( oferecem poderes ilimitados!!!! ) com css

- Declarar variáveis *$nome: atributo;*

- Salva com extensão .scss

- Compilar: sass arquivo.scss:arquivo.css

- Para atualizar automaticamente:  *sass --watch arquivo.scss:arquivo.css*

- Mixin é como função, você pode reutilizar código, funciona como funções dinâmicas

- Nesting: aninhar seletores 

  **obs** Seletores descendentes com muitos níveis, cuidado com desempenho!! (nesting hell)

- Color functions :https://sass-lang.com/documentation/modules

- Extends: pode usar classes padrões, funciona como funções estáticas

- Placeholder: sobrescreve as classes extends

- Compass: framework de CSS baseado em SASS, é como o Bootstrap

  - gem update --system
  - gem install compass
  - Vá ate a raiz do projeto e crie com *compass create*
  - Para compilar : *compass watch css\estilos.scss*
  - **Bourbon**: biblioteca de mixins mais leve do que Compass. https://www.bourbon.io
  - http://compass-style.org

- Funções prontas https://sass-lang.com/documentation/modules

  Referências:

  - https://csspre.com/compare/
  - https://sass-lang.com
  - https://www.oddbird.net/susy/
  - https://sass-lang.com/blog
  - 