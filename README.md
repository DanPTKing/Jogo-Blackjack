# Jogo-Blackjack

Project for training purposes

Este projeto é um jogo simples de Blackjack implementado em Python, utilizando as bibliotecas tkinter para a interface gráfica e PIL (Pillow) para manipulação de imagens. O jogo permite ao usuário jogar uma partida de Blackjack contra o dealer, seguindo as regras clássicas do jogo.

Instalação:
Certifique-se de ter o Python instalado em sua máquina. O projeto foi desenvolvido utilizando Python 3.8+.
Instale as bibliotecas necessárias utilizando pip:
pip install tkinter pillow


O arquivo blackjack.py contém todo o código necessário para rodar o jogo. Aqui está uma visão geral das principais funções e funcionalidades:
carregar_imagens: Carrega as imagens das cartas na pasta images e armazena-as em um dicionário para fácil acesso.
distribuirCarta: Distribui uma carta aleatória do baralho para a mão do jogador ou do dealer.
total: Calcula o total de pontos na mão de um jogador ou do dealer.
revelarMaoDealer: Revela a mão do dealer, escondendo a segunda carta inicialmente.
Novo_jogo: Inicia um novo jogo, distribuindo duas cartas para o jogador e duas para o dealer.
atualizar_interface: Atualiza a interface gráfica para exibir as cartas atuais do jogador e do dealer.
bater: Permite ao jogador receber uma nova carta.
ficar: Faz o jogador parar de receber cartas e permite ao dealer jogar.
verificar_resultado: Verifica e exibe o resultado do jogo.

Contribuição:
Se desejar contribuir para o projeto, sinta-se à vontade para abrir uma issue ou um pull request no repositório. Qualquer sugestão de melhoria ou correção de bugs é bem-vinda!