Jogo da Velha (Tic-Tac-Toe)
Uma aplicação interativa do clássico Jogo da Velha construída com React. Dois jogadores se alternam marcando os espaços em um tabuleiro 3x3, e o primeiro a conseguir uma linha (horizontal, vertical ou diagonal) vence!

✨ Funcionalidades
-Jogabilidade para dois jogadores (um usa X, o outro usa O)
-Indicação visual de quem ganhou a partida
-Botão Resetar para reiniciar o jogo a qualquer momento
-Interface limpa e responsiva com ícones personalizados (círculo e xis)
-Detecção automática de vitória em todas as direções possíveis

🛠️ Tecnologias Utilizadas
-React (com Hooks: useState, useRef)
-CSS3 (layout flexível, cores temáticas)
-Imagens locais (círculo e xis importados via import)

📦 Como executar o projeto
1.Clone o repositório:
git clone https://github.com/seu-usuario/jogo-da-velha-react.git
cd jogo-da-velha-react

2.Instale as dependências:
npm install

3.Inicie o servidor de desenvolvimento:
npm start

🎮 Como jogar
O primeiro jogador começa com X.

Clique em qualquer quadrado vazio para marcar sua jogada.

O próximo jogador usará O.

Continue alternando até alguém formar uma linha reta (horizontal, vertical ou diagonal) com seu símbolo.

Ao vencer, uma mensagem será exibida e o tabuleiro será bloqueado.

Pressione Resetar para começar uma nova partida.

🧠 Estrutura do Código (Principais Componentes)
TicTacToe.jsx – componente principal que gerencia:

Estado do tabuleiro (através de um array data)

Alternância de turnos (count)

Travamento após vitória (lock)

Referências para cada célula (useRef) e para o título (titleRef)

TicTacToe.css – estilização do tabuleiro, botões e imagens.

Assets/ – imagens circle.png e cross.png.