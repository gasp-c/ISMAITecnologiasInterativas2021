# ISMAITecnologiasInterativas2021

- Bloco de notas colaborativo: http://collabedit.com/cmnvk
- Download gravações das aulas: https://www.dropbox.com/sh/6sgbhsra9lqryvm/AACjb8MWi_OSSiQLdCYBH7Tia?dl=0

* AULA 01.1 - 22/09/2020

** PROCESSING
- Baixar em https://processing.org/

#+BEGIN_QUOTE
"A flexible software sketchbook and a language for learning how to code within the context of the visual arts"
#+END_QUOTE

- Exemplos vistos em aula (Podem ser acessados no menu /File > Examples/ ou na pasta /processing-3.5.4 > modes > java > examples/):
  - Topics - Drawing - ContinuosLines & Pattern
  - Topics - Simulate - Chain & Flocking
  - Topics - Motion - Brownian & CircleCollision
  - Topics - Image Processing - LinearImage - http://dillonbaker.com/#/spectrum/
  - Demos - Performance - Esfera
  - https://www.instagram.com/colakollektiv/
  - http://www.continuumfashion.com/D.php
  - https://vimeo.com/163153865

- Daniel Shiffman
  - Canal de YouTube: https://www.youtube.com/user/shiffman
  - Livros:
    - https://www.amazon.com/gp/product/B003FL6X4I/ref=dbs_a_def_rwt_bibl_vppi_i2
    - https://www.amazon.com/gp/product/B00NBER0BO/ref=dbs_a_def_rwt_bibl_vppi_i3

* AULA 01.2 - 23/09/2020
- Não houve. Para compensar.

* AULA 02.1 - 29/09/2020
- Aspectos práticos:
  - Github - https://github.com/magnoCaliman/ismaiProgCriativa_2020-1
  - Downloads de exemplos via arquivo zip na pasta de cada aula

- Processing:
  - Convenção de nomenclatura de arquivos
  - Estrutura de pasta

- Exemplos:
  - ~bucho.pde~
  - ~catapora.pde~
  - ~cometa.pde~
  - ~infla.pde~

- Documentação:
  - https://processing.org/reference/

* AULA 02.2 - 30/09/2020

- Computador é burro...
- Texto -> Processing -> Imagens
- "Desenhe uma linha"
  - Vocabulário: linguagens de programação só entendem as palavras que fazem parte do vocabulário daquela linguagem!

- Conceitos:
  - *Funções*: /instruções/ para o computador que fazem parte do vocabulário daquela linguagem. "Faça isso..."
  - *Argumentos*: /qualificadores/ de uma função em particular. "...mas faça dessa maneira"
  - *Sintaxe*: /convenção/ de como a escrita de uma linguagem se dá.
    - RTFM! - https://processing.org/reference/

- Vocabulário:
  - ~size()~
  - ~point()~
  - ~line()~
  - ~rect()~
  - ~ellipse()~
  - ~triangle()~

- Especificidades do Processing:
  - Sistema de coordenadas: https://processing.org/tutorials/drawing/
  - Ordem de execução

- Desafios!
  - bauhaus_pb
  - bordas
  - cruzadas
  - pizza
  - ruleOfThirds
  - totalEclipseOfTheHeart
  - xadrez

* AULA 03.1 - 06/10/2020
- Discussão dos desafios da aula 02.2

* AULA 03.2 - 07/10/2020

- Conceitos:
  - *Modularidade*:
    - Funções às vezes /retornam valores/
    - Funções como argumento de outras funções!
  - *Blocos de código*:
    - Se funções são verbos, blocos são parágrafos.

- Vocabulário:
  - ~fill()~ / ~noFill()~
  - ~stroke()~ / ~noStroke~
  - ~background()~
  - ~strokeWeight()~
  - ~println()~
  - ~random()~
  - ~void setup(){}~
  - ~void draw(){}~

- Especificidades do Processing:
  - Cores: https://processing.org/tutorials/color/
  - Estrutura de ~setup()~ + ~draw()~

- Exemplos:
  1. ~background.pde~
  2. ~fill_1arg.pde~
  3. ~fill_3arg.pde~
  4. ~fill_4arg.pde~
  5. ~fill_2arg.pde~
  6. ~stroke.pde~
  7. ~printRandom.pde~
  8. ~randomFillPos.pde~
  9. ~loopDraw.pde~
  10. ~loopBG.pde~
  11. ~linhaRandomBorda.pde~
  12. ~catapora.pde~

- Desafios!
  - ritualPassagem
  - aHa
  - divisaoCanvas
  - sandro
  - tunel
* AULA 04.1 - 13/10/2020
- Discussão dos desafios da aula 03.2
- Referências:
  - Norman McLaren
    - https://www.youtube.com/watch?v=E3-vsKwQ0Cg
    - https://www.youtube.com/watch?v=Q0vgZv_JWfM
    - https://www.youtube.com/watch?v=UmSzc8mBJCM
    - https://www.youtube.com/watch?v=7BeCPbNZ74s
  - Vera Molnar
    - https://en.wikipedia.org/wiki/Vera_Moln%C3%A1r
    - https://duckduckgo.com/?q=vera+molnar&iax=images&ia=images

[[/aula04.1/vera_molnar.jpg]]
* AULA 04.2 - 14/10/2020
- Não houve. Para compensar.
* AULA 05.1 - 20/10/2020
- Conceitos:
  - *Palavras como representates simbólicos de valores*
    - Dividir uma palavra por 2, agora faz sentido...
  - *Generalização da lógica*
    - Traduzir discurso humano para a máquina.

- Vocabulário:
  - ~mouseX~
  - ~mouseY~
  - ~width~
  - ~height~

- Exemplos:
  1. ~printMouseX.pde~
  2. ~bolaSegue.pde~
  3. ~funil.pde~
  4. ~linhaCorta.pde~
  5. ~meio.pde~
  6. ~proporcao.pde~
  7. ~wingman.pde~

- Desafios!
  - bond
  - operacaoMouse
  - larguraAltura
  - pontoLinha
  - constelacao
  - ruleOfThirds
* AULA 05.2 - 21/10/2020
- Para compensar (EAD não válido no sistema)

- Conceitos:
  - *Variáveis*
    - Caixas, com etiquetas, onde guardamos informação
  - *Declaração* da variável
    - Ato de criação da caixa
  - *Tipologia* da variável ("/data type/")
    - Que tipo de informação cabe na caixa
  - *Atribuição* de valores à variável ("/assignment/")
    - Colocação de valores dentro da caixa
  - *Escopo* da variável ("/scope/")
    - Local onde a caixa está guardada (e consequentemente quem tem permissão para acessar). Duas categorias:
      - /Global/
      - /Local/
  - *Iteração*
    - Modificação dos valores da caixa, de modo auto-referencial
    - ~x = x + 1~ é uma inverdade matemática, mas é computacionalmente válido

- Vocabulário:
  - ~frameRate()~
  - ~int~
  - ~float~
  - ~=~

- Exemplos:
  1. ~codigoBarra_desafioInicial.mov~
  2. ~introVar.pde~
  3. ~tipologia.pde~
  4. ~escopo.pde~
  5. ~circulosRandom.pde~
  6. ~animacao101.pde~
  7. ~operacaoMouse_refactorar.pde~

- Desafios!
  - squareLines
  - mouseExplode
  - rayTracing
  - corbusier
  - codigoBarra
* AULA 06.1 - 27/10/2020
- Discussão dos desafios da aula 05.2
* AULA 06.2 - 28/10/2020
- Dúvida:
  - Como usar cliques do rato e o teclado do portátil como input dos nossos programas?
- "Resposta":
  - "Tem umas /funções/ tipo ~mouseDragged()~ e ~keyPressed()~ (além de outras que não lembro o nome...) que fazem isso."

- Desafio!
  - Investigar a documentação e descobrir:
    1. Quais funções resolvem nosso problema
    2. Ler suas documentações (em https://processing.org/reference/) e decifrar como suas implementações funcionam
    3. Criar ao menos /4 exemplos/ que demonstrem o funcionamento dessas funções

- Observação:
  - Ao navegar a documentação dessas funções, provavelmente irá encontrar algo chamado "/if statement/". Algo como: ~if(value > 255)~. Não é necessário o seu uso. Isso será assunto de aula posterior.
* AULA 07.1 - 03/11/2020

- Conceitos:
  - *Estruturas de controle*
    - Estruturas no nosso programa que permitem controlar a /ordem de execução/ das nossas instruções.
    - Mudamos a regra que diz que o programa deve ser lido da primeira até a última linha, do início ao fim do programa, repetindo o ~void draw()~ uma vez por frame.

- Especificidades do Processing:
  - Relação entre a ordem de execução das funções de input de usuário e a renderização do frame ao final do ~void draw()~

- Vocabulário:
  - ~void mouseClicked(){}~
  - ~void mouseDragged(){}~
  - ~void mouseMoved(){}~
  - ~void mousePressed(){}~
  - ~void mouseReleased(){}~
  - ~void mouseWheel(){}~
  - ~void keyPressed(){}~
  - ~void keyReleased(){}~
  - ~void keyTyped(){}~

- Exemplos:
  1. ~drawVazio.pde~
  2. ~clica_desenhaRect.pde~
  3. ~void_mouse.pde~
  4. ~mudaVar.pde~

* AULA 07.2 - 04/11/2020

- Conceitos:
  - *Condicional*
    - Estrutura lógica que /condiciona/ a execução de um bloco de código ao resultado de um /teste booleano/.
  - *Booleano*
    - Caractetística de algo que só possui dois estados possíveis e opostos: /verdadeiro/ ou /falso/, /ligado/ ou /desligado/, /0/ ou /1/.

- Vocabulário:
  - ~if(){}~
  - ~else{}~
  - ~<~ (operador /menor que/)
  - ~>~ (operador /maior que/)
  - ~>=~ (operador /maior ou igual que/)
  - ~<=~ (operador /menor ou igual que/)
  - ~||~ (operador /OU/ "OR")
  - ~&&~ (operador /E/ "AND")
  - ~==~ (operador /igual/)

- Exemplos:
  1. ~if_01.pde~
  2. ~if_02.pde~
  3. ~if_03.pde~
  4. ~elseIf_04.pde~
  5. ~elseIfProbabilidade_05.pde~
  6. ~elseIfProbabilidade_06.pde~
  7. ~ifCirculo_07.pde~

- Desafios!
  - bolaQuadrada
  - elseIfQuadrante
  - fadeBG
  - igualdade
* AULA 08.1 - 10/11/2020
- Aula em horário regular (11:15 às 12:15) + compensação da aula 01.2 - 23/09/2020 (12:15 às 14:15)

- Continuação da discussão da aula 07.2

- Exemplos de data visualization:
  - https://media.giphy.com/media/LT6MTwW0MY5sl71X85/giphy.gif
  - https://www.reddit.com/r/dataisbeautiful/comments/fxoxti/coronavirus_deaths_vs_other_epidemics_from_day_of/
  - http://dillonbaker.com/#/spectrum/
* AULA 08.2 - 11/11/2020
- Continuação da discussão da aula 07.2
* AULA 09.1 - 17/11/2020

- Conceitos:
  - *Palavras reservadas* ("/keyword/")
  - *Variável do sistema* ("/system variable/") 

- Vocabulário:
  - ~true~
  - ~false~
  - ~LEFT~
  - ~RIGHT~
  - ~mousePressed~
  - ~mouseButton~

- Exemplo:
  - ~ifClick.pde~

- Desafio
  - clicaRectEllipse
* AULA 09.2 - 18/11/2020
- Random walk: https://en.wikipedia.org/wiki/Random_walk
  - "An elementary example of a random walk is the random walk on the integer number line, Z, which starts at 0 and at each step moves +1 or −1 with equal probability"

* AULA 10.1 - 24/11/2020
- Ponto onde paramos na aula 09.2:
#+BEGIN_SRC java
float x=0;
float posx=0;

void setup()
{
  size(400, 400);
  background(255);
  frameRate(3);
}

void draw()
{
  background(255);
  
  x = random (1, 10);

  if ( x > 5)
  {
  
  } 
  else if ( x < 5 );
  {
    x = x - 1;
  }
  
  posx = posx + x;

  ellipse (posx, 0, 10, 10);
}
#+END_SRC
* AULA 10.2 - 25/11/2020
** Random walk em uma dimensão
#+BEGIN_SRC java
float sorteio = 0;
float posX;

void setup()
{
  size(400, 400);
  background(255);
  //frameRate(3);
  
  posX = width/2;
}

void draw()
{
  background(255);
  
  sorteio = random(10);

  if(sorteio < 5) //cara
  {
    posX = posX + 1; //anda para direita
  } 
  else if(sorteio > 5) //coroa
  { 
    posX = posX - 1; //anda para esquerda
  }

  ellipse(posX, height/2, 10, 10);
}
#+END_SRC

** Random walk em duas dimensões
#+BEGIN_SRC java
float sorteio = 0;
int step = 1;
int tamEllipse = 10;
float posX;
float posY;

void setup()
{
  size(400, 400);
  background(255);
  //frameRate(1);
  
  posX = width/2;
  posY = width/2;
}

void draw()
{
  //background(255);
  
  sorteio = random(4);
  println(sorteio);

  if (sorteio < 1)
  {
    posX = posX + step; //anda para direita
  } 
  else if ( sorteio > 1 && sorteio < 2) 
  {
    posX = posX - step; //anda para esquerda
  }

  if (sorteio > 2 && sorteio < 3)
  {
    posY = posY + step; //anda para baixo
  } 
  else if (sorteio > 3 && sorteio < 4) 
  {
    posY = posY - step; //anda para cima
  }
  
  ellipse(posX, posY, tamEllipse, tamEllipse);
}
#+END_SRC

# * AULA 11.1 - 30/11/2020
# - Return type função customizada
# - Argumentos de inicialização
- Desafio
  - Criar *dois programas* de livre escolha que fazem uso do algoritmo de random walk. No nosso exemplo em aula, utilizamos como método para determinar a posição de um círculo em um plano 2D. Pense que outros elementos gráficos e seus parâmetros podem ser explorados criativamente. Trate o  código como /elemento plástico/: experimente, especule, tente coisas diferentes e veja o que ideias o material lhe sugere!
  - Lembre-se, o que implementamos em aula é apenas o /princípio de operação/ do algoritmo, ou seja, uma demonstração de como ele funciona. Isso significa que você provavelmente terá de fazer grandes adaptações (ou talvez reescrever quase que por completo) quando for utilizar nos seus exemplos pessoais. 
* AULA 11.1 - 02/12/2020
- Grupo A
  - Paulo Miguel da Silva Vilar
  - Vitória dos Santos Pereira

- Grupo B
  - Daniel Jerónimo Martins Pinho
  - Bárbara Valente Gomes Taveira
  - Leonor Martins Raimundo
  - Rafael da Rocha Moreira
  - Tiago Varejão Duarte

- Grupo C1
  - Vera Lúcia Graça Maio 
  - Alex Filipe Martins de Castro
  - Beatriz Moreira Rocha do Amparo
  - Catarina Sofia Mota Ferreira

- Grupo C2
  - João Carlos Gonçalves Rodrigues
  - José Pedro de Fontes Ferreira
  - Mariana Moreira de Sousa Teixeira
  - Raquel Martins Prata Costa
  - Beatriz Osório Martins

- Grupo D1
  - Alexandra Micaela Pereira Mendes
  - Diogo Miguel Costa Azevedo
  - Alexandre Baldo Oliveira
  - Bernardo Amorim Lage de Carvalho
  - Rodrigo Magalhães Cardoso

- Grupo D2
  - Miguel Ivo Ramos Afonso
  - Alexandre dos Santos Barrocas
  - Alexandra Manuela Lopes Custódio
  - Ana Isabel Mesquita Matos
  - Dinis Mariano Guedes dos Anjos

* AULA 12.1 - 09/12/2020
** AVALIAÇÃO - MOMENTO 1 (50%) - DESAFIOS
- Descrição:
  - Entrega dos códigos de implementaçãos de exercícios práticos propostos nas aulas:
    - Aula 02.2 - 7 desafios
    - Aula 03.2 - 5 desafios
    - Aula 05.1 - 6 desafios
    - Aula 05.2 - 5 desafios
    - Aula 06.2 - 4 desafios
    - Aula 07.2 - 4 desafios
    - Aula 09.1 - 1 desafio
    - Aula 10.2 - 2 desafios
      - *TOTAL*: --> 34 exercícios
- Formato de entrega:
  - Arquivo zip contendo os códigos de Processing, *organizados em ficheiros de acordo com o número das aulas, e o nome dos desafios*
  - Deve ser submetido no portal da ISMAI, na opção "Entrega de trabalhos"
- Data de entrega:
  - 18/12/2020
** AVALIAÇÃO - MOMENTO 2 (50%) - PROJETO INDIVIDUAL
- Descrição:
  - Apresentação de protótipo de objeto artístico-exploratório em media de livre escolha (instalação interativa, impresso, escultura, video, web art, etc.) que faça uso de sistema computacional realizado em Processing.
- Formato de entrega:
  - PDF contendo texto investigativo, maquete visual e texto técnico
  - Código de Processing de protótipo funcional
  - Deve ser submetido no portal da ISMAI, na opção "Entrega de trabalhos"
- Datas de entrega:
  - 05/01/2021 - Apresentação verbal de *5 minutos* com idéia principal do projeto
  - 22/01/2021 - Upload no portal ISMAI
  - +Última semana de aulas (entre 18 e 21 de Janeiro-2021) - Entrega final e talvez apresentação para turma (à confirmar)+
* AULA 13.1 - 14/12/2020
- Trabalhos práticos em grupo
* AULA 13.2 - 16/12/2020
- Trabalhos práticos em grupo
* ORIENTAÇÕES PROJETOS FINAIS

** Alex Castro
*** Aula 14.1 - 05/01/2021
- conta de instagram. pontilhismo de obras famosas.
- sugestão: bot autônomo. agente não humano que faz o remix.

** Alexandre Barrocas
*** Aula 14.1 - 05/01/2021
- cartaz. sem tema ainda.
- explorar exemplos de aula que não sejam interativos

*** Aula 15.2 - 13/01/2021
- 

** Alexandra Custódio
*** Aula 14.2 - 06/01/2021
- recriar tetris / lógica de jogos "3 of a kind" (candycrush, etc)
*** Aula 16.2 - 20/01/2021
- https://www.youtube.com/c/TheCodingTrain/search?query=computer%20vision
- https://www.joe.co.uk/gaming/tetris-block-names-221127
** Alexandra Mendes
*** Aula 14.1 - 05/01/2021
- generative music / interacao som/imagem
- referências:
  - https://www.youtube.com/watch?v=qolz0gmWkqg&list=PLbLdd1fdNg5w0x_XldV9O5X4SL5hkEQ9O&index=3
  - http://generative-music-patterns.schloss-post.com/
  - https://thedotisblack.com/
  - https://processing.org/reference/libraries/sound/index.html (começar com amplitude)
  - http://code.compartmental.net/tools/minim/
  - data / image sonification

** Alexandre Oliveira
** Ana Matos
*** Aula 14.1 - 05/01/2021
- pixel art de obras de arte famosas
- referências:
  - deep dream: https://duckduckgo.com/?q=deep+dream&iax=images&ia=images&iai=https%3A%2F%2Fi.ytimg.com%2Fvi%2FIUOxzAoXy0o%2Fmaxresdefault.jpg
  - https://processing.org/reference/PImage.html
  - https://www.youtube.com/watch?v=-f0WEitGmiw&list=PLRqwX-V7Uu6YB9x6f23CBftiyx0u_5sO9
  - https://www.youtube.com/watch?v=70-4l7P6UB8
  - https://processing.org/reference/for.html

** Bárbara Taveira
*** Aula 14.1 - 05/01/2021
- teclado interativo estilo guitar hero
  - https://www.youtube.com/watch?v=egZXmG4eyiQ&ab_channel=Rousseau
  - http://www.smallbutdigital.com/projects/themidibus/
  - termos importantes do protocolo midi:
    - midi number
    - velocity
    - note on/off

** Beatriz Amparo
*** Aula 14.1 - 05/01/2021
- instalacao interativa (reativa?). estagios da vida / estacoes do ano / salas em ambiente físico.
- exploracão da poéticas das cores das estacões
- referências:
  - https://processing.org/tutorials/color/
  - color spaces (HSB vs. RGB vs. CMYK) - https://en.wikipedia.org/wiki/Color_space
  - https://www.imdb.com/title/tt0421715/

** Beatriz Martins
*** Aula 14.2 - 06/01/2021
- mashup pop art
- referencias:
  - style transfer (machine learning)
  - https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fmiro.medium.com%2Fmax%2F767%2F1*B5zSHvNBUP6gaoOtaIy4wg.jpeg&f=1&nofb=1
  - https://duckduckgo.com/?q=style+transfer&page=1&sexp=%7B%22cdrexp%22%3A%22b%22%2C%22artexp%22%3A%22c%22%2C%22prodexp%22%3A%22b%22%2C%22prdsdexp%22%3A%22c%22%2C%22biaexp%22%3A%22b%22%2C%22msvrtexp%22%3A%22b%22%2C%22bltexp%22%3A%22b%22%2C%22djsdexp%22%3A%22b%22%7D&iax=images&ia=images&iai=https%3A%2F%2Fmiro.medium.com%2Fmax%2F767%2F1*B5zSHvNBUP6gaoOtaIy4wg.jpeg
  - rasterização: https://www.youtube.com/watch?v=XO8u0Y75FRk

** Bernardo Carvalho
*** Aula 14.2 - 06/01/2021
- visualização de som / midi multichannel
- mesmas referências da bárbara
- 3d
- qual a estética?
- referências:
  - https://www.youtube.com/watch?v=HNPDAfJTN10
  - https://www.youtube.com/watch?v=MiSr8iNwWsw

** Catarina Ferreira
*** Aula 14.2 - 06/01/2021
- espaço físico "psicodélico", que perturba percepcão da realidade do espectador
- ilusão de ótica: https://en.wikipedia.org/wiki/Optical_illusion
- referências
  - https://mymodernmet.com/wp/wp-content/uploads/2017/10/casa-ceramica-optical-illusion-tiles-1-1.jpg

** Daniel Pinho
*** Aula 14.2 - 06/01/2021
- referências:
  - motion tracking: https://duckduckgo.com/?q=processing+motion+tracking&ia=web&iai=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DQLHMtE5XsMs
  - computer vision: https://www.youtube.com/watch?v=h8tk0hmWB44&list=PLRqwX-V7Uu6aG2RJHErXKSWFDXU4qo_ro

** Dinis Anjos
** Diogo Azevedo
*** Aula 16.2 - 20/01/2021
- recriar jogo de scratch - https://scratch.mit.edu/projects/365329695/
  - https://www.youtube.com/watch?v=7BoJBYh16CQ
  - https://www.youtube.com/watch?v=DPFJROWdkQ8&t=3s
  - https://www.youtube.com/watch?v=nBKwCCtWlUg
** Inês Braga
** José Ferreira
*** Aula 14.2 - 06/01/2021
- reconstrução de jogos atari/pong
- explorar outros dispositivos de entrada? (mic/webcam) e consequentemente outras formas de interacão
- bibliotecas de som (minim). mesmas referências do trabalho da alexandra

** João Rodrigues
** Leonor Raimundo
*** Aula 14.2 - 06/01/2021
- série de posteres interativos (online ou físico)
- tim rodenbröker / rasterizacão: https://www.youtube.com/c/timrodenbr%C3%B6kercreativecoding/videos
- bauhaus: https://www.google.com/search?tbm=isch&q=bauhaus&tbs=imgo:1
- qual o tema?
*** Aula 15.2 - 13/01/2021
- estados de espírito
  - spring - https://www.youtube.com/watch?v=cluKQOY92Dw&list=PLRqwX-V7Uu6aFlwukCmDf0-1-uSR7mklK&index=23
  - site

** Mariana Teixeira
*** Aula 15.2 - 13/01/2021
- flappy bird "ao meu estilo"
  - mudar estética
  - nature of code
    - https://www.youtube.com/playlist?list=PLRqwX-V7Uu6aFlwukCmDf0-1-uSR7mklK
    - https://natureofcode.com/book/
    - https://www.youtube.com/watch?v=cXgA1d_E-jY

** Miguel Afonso
*** Aula 14.2 - 06/01/2021
- paralax: https://www.youtube.com/watch?v=YdHTlUGN1zw
- https://www.youtube.com/results?search_query=coding+purple+rain
- https://www.youtube.com/results?search_query=coding+train+stars
- https://www.youtube.com/results?search_query=conways+game+of+life
- The Nature of Code: https://natureofcode.com/book/

** Paulo Vilar
*** Aula 14.2 - 06/01/2021
- random walk + bot de instagram. 
- mesma pergunta do alex. pq postar no instagram? como pensar um agente não-humano que faz a arte?
  - https://www.studiointernational.com/index.php/chance-and-control-art-in-the-age-of-computers-review-victoria-albert-museum

** Rafael Moreira
*** Aula 14.2 - 06/01/2021
- visualizador de som em tempo real
- live cinema
  - [[https://www.dropbox.com/s/zby9e71nro97srr/Youngblood%2C%20G%20-%20Expanded%20Cinema.pdf?dl=0][Youngblood, G - Expanded Cinema (capt.4)]]
  - [[https://www.dropbox.com/s/di3sdgc1ql03vjc/Curtis%2C%20D%20-%20Expanded%20Cinema.pdf?dl=0][Curtis, D - Expanded Cinema (p.252)]]
  - Guy Sherwin - Man With Mirror - https://www.youtube.com/watch?v=DX1-xuCNIeg
- "visualists" em live coding
  - https://www.youtube.com/watch?v=cw7tPDrFIQg
  - https://www.nadyaprimak.com/blog/creativity/hydra-tutorial-live-coding-visuals/

** Raquel Costa
*** Aula 14.2 - 06/01/2021
- mural de photos projetadas, fotos que deixam a marca dos visitantes
- timeline, passagem do tempo
- referências
  - People Staring at Computers: https://www.wired.com/2012/07/people-staring-at-computers/
  - process art e passagem do tempo
    - https://en.wikipedia.org/wiki/Process_art (trabalho do William Basinki)
    - https://mymodernmet.com/japanese-flower-art-azuma-makoto/
    - https://mymodernmet.com/wp/wp-content/uploads/2017/09/azuma-makoto-flower-art-7.jpg
    - https://www.andrewmaxedon.com/generational-decay

** Rodrigo Cardoso
** Rui Teixeira

** Tiago Duarte
*** Aula 14.2 - 06/01/2021
- frogger
  - object orientation: https://www.youtube.com/watch?v=YcbcfkLzgvs&list=PLRqwX-V7Uu6bb7z2IJaTlzwzIg_5yvL4i
  - mesma referência do José, explorar outros dispositivos de entrada

** Vera Maio
*** Aula 14.2 - 06/01/2021
- sala com luzes. exploracão de mudancas graduais, lentas de cor. sincronia com áudio, para pessoas com ansiedade.
- referências:
  - mesmas referências de cor da Beatriz (explorar HSB em vez de RGB)
  - mundanca do sistema de coordenadas cartesianas (plano XY), para coordenadas polares (curvas e ângulos, para explorar formas circulares: https://www.youtube.com/results?search_query=processing+cartedian+to+polar

** Vitória Pereira
*** Aula 14.2 - 06/01/2021 
- plataforma de criacão controlada pelo usuário
- movimentacão livre de objetos gráficos, imagens/formas pré-definidas (não desenho)
- referências:
  - zine: https://www.google.com/search?tbm=isch&q=zine&tbs=imgo:1#imgrc=OO8U-sHXLD7A_M
  - [[https://www.dropbox.com/s/na5fxbexkvkr0uo/Ludovico%2C%20A%20-%20Post-Digital%20Print%20-%20The%20Mutation%20of%20Publishing%20Since%201894.pdf?dl=0][Ludovico, A - Post-Digital Print (capítulos 2.6 e 2.7)]]

** ---

*** André Fonseca Ventura                    
*** Carolina Michaélis Domingues Marques     
*** Diogo Manuel Vasconcelos Pinto Oliveira  
*** Isabella Palma Passos Bertini            
*** Rafael da Graça Fortes                   
*** Rogério Cannella                         
*** Yasmin Soares de Brito de Sousa Lobo     
