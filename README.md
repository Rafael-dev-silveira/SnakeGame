Criação do Jogo da Cobrinha com HTML, CSS e JavaScript :
=

Neste projeto, criamos uma versão simples e funcional do clássico jogo da cobrinha (Snake), usando apenas HTML, CSS e JavaScript. O jogo é renderizado em um elemento canvas, com movimentação controlada pelo teclado. O projeto envolve a configuração visual, a lógica do jogo, e a manipulação de eventos e atualizações em tempo real para garantir a interatividade.

Etapas de Desenvolvimento
Configuração do Canvas:
=

Criamos um elemento <canvas> no HTML que serve como tabuleiro para o jogo.
Configuramos o tamanho, cor de fundo, e escala do tabuleiro no CSS.
Usamos JavaScript para manipular o contexto gráfico (2D) do canvas.

Estrutura Inicial do Jogo:
=

Definimos variáveis para a posição inicial da cobrinha, direção, tamanho, e a posição da comida.
Criamos a lógica para desenhar a cobrinha e a comida no tabuleiro.

Movimentação da Cobrinha:
=

Implementamos um evento de teclado (keydown) para capturar as setas direcionais e alterar a direção do movimento.
Atualizamos a posição da cobrinha em cada quadro, adicionando um novo segmento na frente e removendo o último para simular o movimento.


Implementamos condições para detectar colisões:
=
Colisão com as bordas do canvas.
Colisão com o próprio corpo da cobrinha.
Quando ocorre uma colisão, o jogo é reiniciado ou exibe uma mensagem de "Game Over".

Comida e Crescimento da Cobrinha:
=

Criamos a lógica para posicionar a comida em locais aleatórios no canvas.
Detectamos quando a cobrinha come a comida (sobreposição de posições) e adicionamos um segmento ao corpo.

Atualização do Tabuleiro em Tempo Real:
=

Usamos a função setInterval para criar a atualização contínua do jogo.
Limpeza do canvas e redesenho da cobrinha e da comida a cada quadro.

Estilização Básica:
=

Usamos CSS para centralizar o canvas na página e aplicar um design simples e limpo.

Funcionalidades Principais
=
Controle da direção com as setas do teclado.
Incremento no tamanho da cobrinha ao comer a comida.
Detecção de colisões para encerrar o jogo.
Pontuação exibida em tempo real.

Tecnologias Utilizadas
=
HTML: Criação do canvas e estrutura do jogo.

CSS: Estilização do layout da página.

JavaScript: Lógica do jogo, manipulação do canvas e eventos do teclado.

Aprendizados e Benefícios
=
Introdução ao uso de canvas em JavaScript para gráficos 2D.
Manipulação de eventos de teclado e lógica de jogos.
Prática de lógica de programação para controle de estados.
Experiência com animação em tempo real usando setInterval.
