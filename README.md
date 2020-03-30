# SASS-Alura

## O que é? 
  - Projeto para consolidar conhecimento na utilização do SASS no dia-a-dia. Objetivo é compreender a importância do SASS e por quê é tão importante para aumentarmos nossa performance!
  
  #### SASS:
  - <img src="https://media.giphy.com/media/VIWFqjoDrSaqnU4eHL/giphy.gif">  
  #### VSCODE:
  - <img src="https://media.giphy.com/media/dvaqMSN50XupPABGBb/giphy.gif">

## Ferramentas utilizadas: 
  - VSCode
  - Ruby

## Objetivo:
  - Aprofundar os conceitos de SASS e suas vantagens no dia-a-dia de desenvolvimento, com um projeto prático. Aprenderemos sobre __*mixins, placeholders, variáveis e criação de funções*__
  
## O que aprendi e conhecimentos consolidados: 
  
### SASS:
  - Como pré-configurar nossa máquina para começar a utilizar o SASS, instalando o [Ruby](http://rubyinstaller.org/downloads)
  - Processo para utilizar o SASS: 
    1) Renomear todos arquivos .css;
    2) No prompt do Ruby entre até a pasta do seu projeto onde estão o arquivos css e rode o seguinte comando:
    ```
    sass estilos.scss:estilos.css
    ```
    3) Deixe seu editor de texto com duas colunas para melhor visualização das alterações e compilações
    4) Para não ter que ficar compilando todas as vezes o arquivos .scss para .css, rode o seguinte comando:
    ```
    sass --watch estilos.scss:estilos.css
    ```
    Obs: estilos.scss é o arquivo .css que você renomeou e será compilado para estilos.css
    
  - Como e quando devemos declarar variáveis. Como por exemplo: cores padrões, secundárias, textos, ponto de quebras, max-width para media queries, ou, qualquer estilização CSS que esteja repetindo em diversos lugares. Assim, caso algum dia alguém solicite a mudança de uma cor padrão, iremos apenas entrar no arquivo onde está localizada nossa variável que armazena a cor e padrão e mudaremos apenas naquele local;
  - Diferenças entre __*mixins e placeholders*__. Os **mixins e placholders** são indicados sempre que temos um padrão de estilização de alguns elementos agrupados, porém, os **mixins** são indicados quando devemos passar um parâmetro, como por exemplo o raio padrão de de botões com bordas arredondadas;
  #### - Variáveis:
  - Para criar as **variáveis**, utilize: $nome-variavel: #fff; (#fff = cor que você deseja inserir de estilização);
  - Para importar as **variáveis**, utilizando em seu arquivo .scss: $nome-variavel;
  #### - Placeholders:
  - Para criar um **placeholder**, utilize: %nome-placeholder { ESTILIZAÇÕES AQUI };
  - Para importar um **placeholder**, utilizando em seu arquivo de estilizações .scss: @extend %nome-placeholder;
  #### - Mixins:
  - Para criar um **mixin**, utilize: @mixin nome-mixin(parâmetro) { ESTILIZAÇÃO AQUI };
  - Para importar **mixins**, utilizando em seu arquivo de estilização.scss: @include nome-mixin;
  
## Contribuições
Pull requests são bem-vindo. Para maiores alterações favor abrir uma issue para conversarmos.
Caso tenha algo que possa ser melhorado, não hesite em me contatar :smile:

## License
- MIT License - Copyright (c) 2020 william-takayama
- [@alura-cursos](https://cursos.alura.com.br/course/sass)
