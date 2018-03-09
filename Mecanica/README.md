# Mecânica

## Das ideias iniciais

Devido à complexidade e alto custo de fazer fresadoras com 5 eixos(como mostra o [video](https://www.youtube.com/watch?v=3SUQKGu7F5w)), optou-se por fazer em 3 eixos cartesianos. As peças feitas não terão alta complexidade e 3 os eixos serão suficiente para fazer as peças necessitadas.

A princípio, utilizaremos a [Microrretífica Dremel 3000](http://dremel3000.ferramentasdremel.com/) para girar a ferramenta Fresa em alta rotação. Optou-se ela pois oferece uma alta rotação, cerca de 30000 rpm. Os outros motores disponíveis na Droid são de baixa rotação, e para utiliza-los seria necessário uma redução para aumentar a rotação e diminuiria o torque disponível.

Uma ideia futura é substituir a Dremel por um motor próprio para a Fresa. Um exemplo é o motor que atualmente custa R$ 300,00:

[Motor para Fresa no mercado Livre](https://produto.mercadolivre.com.br/MLB-762340182-motor-spindle-48v-300w-cnc-router-fresa-tb6560-_JM)

Além disso, será utilizada uma mesa fixa. Essa escolha foi feita devido à montagem final. Então até o momento temos:

* Fresora de apenas 3 eixos cartesianos
* Motor para a Fresa como a Dremel
* Mesa fixa

## Da escolha dos eixos e posição

É possivel escolher para cada eixo, utilizar:

* Barra roscada, com um fuso
* Correias

A vantagem para se utilizar a barra roscada é:

* A folga da correia é maior quando se altera o movimento de um sentido para o outro devido à elasticidade da correia.
* O torque resultante na barra é maior, depende quase totalmente do passo da rosca.

Por consequência, temos algumas desvantagens:

* A velocidade linear com que se move é menor, pois é necessário girar o motor mais vezes para uma mesma distância
* O preço é maior, pois as barras são mais caras, bem como os fusos

Contudo, devido às ideias iniciais de utilizar a Dremel, não temos um motor forte suficiente para arrancar muito material e assim a velocidade linear é limitada bem mais pelo motor(no caso Dremel) que pelos eixos. Consequentemente, demora-se mais para fabricar uma mesma peça.

Outra decisão que influenciou foi questão de condição da ferramenta: É melhor ter ferramentas com maior vida útil e demorar mais na peça, que fazer a peça mais rapidamente e diminuir a vida útil da mesma peça. Isso depende da força com que a ferramenta faz sobre a peça, e a velocidade de rotação da ferramenta.

### Eixo X

Como dissemos, a mesa ficará parada e então toda a estrutura é movida.

### Eixo Y


### Eixo Z

Para o eixo Z, utilizaremos uma barra roscada para fazer o controle de altura. Se os motores
