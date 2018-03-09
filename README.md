# Fresa

## Introdução

Por necessidade de precisão de algumas peças, além de facilitar o trabalho, teve-se a ideia de construir uma fresadora.

Uma fresora é uma maquina CNC semelhante à impressora 3D. Algumas diferenças da Impressora 3D para a Fresora está na forma de utilização:

* A impressora deposita material sobre a mesa e assim vai construindo a peça;
* A fresora arranca material de uma peça maior que a final.

Para fazer esse arrancamento de material, é utilizado uma ferramenta chamada Fresa em alta rotação. Existem diversos videos no YouTube que exemplificam esse processo, um deles:

* [Fresa](https://www.youtube.com/watch?v=3SUQKGu7F5w)

Esse projeto é basicamente dividido em 3 grandes partes:

* Mecânica - Responsável pela montagem da estrutura, verificação de folgas para aumentar imprecisão da maquina
* Eletrônica - Responsável pelo equipamento eletrônico, desde conectar os motores ao drive e ligar à unidade de controle
* Software - Responsável por receber as entradas referentes à peça, normalmente em ```gcode``` e controlar a rotação dos motores e indicar onde a ferramenta deve ir.

## Definições

Definição 		| Descrição
----------------|----------
Fresa			| Ferramenta a ser utilizada pela Fresadora
Fresadora		| Maquina CNC que utiliza a Fresa
Motor de Passo	| Motor que utiliza o sistema de bobinas para boa precisão
Gcode			| Extensão do arquivo utilizado pelo software para controlar os giros dos motores
Peça 		 	| A peça a ser fresada, por exemplo, uma placa PCB com varios furos nela
Ferramenta		| No nosso caso, significa o mesmo que a fresa

