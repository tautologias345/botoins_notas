# Jogo Botões e Notas

Quero criar um jogo eletrônico chamado Botões e Notas. Cada nota da moeda brasileira está escondido em um botão totalmente opaco de uma cor. Me inspirei no subjogo Thrill Digger (inglês) ou Agujeros y Rupias (espanhol) do superjogo eletrônico The Legend of Zelda: Skyward Sword da Nintendo. Ele será criado na Godot com um servidor online com a API da Stripe para PHP. Com este jogo, não é apenas eu, autor, que terei lucro. Todo jogador poderá ter lucro com esse jogo gratuito e de código aberto. O jogo é um projeto social. Ele é um jogo para Windows. Para quem usa Linux ou Mac precisa criar uma máquina virtual do Windows 11.

Os dois tipos de armadilha são:

- Perde o jogo
- Perde 5 reais e continua o jogo

Como são as notas do jogo?

- As notas de 5 reais tem 0 botões adjacentes com armadilha.
- As notas de 10 reais tem 1 botões adjacentes com armadilha.
- As notas de 20 reais tem 2 botões adjacentes com armadilha.
- As notas de 50 reais tem 3 ou 4 botões adjacentes com armadilha.
- As notas de 100 reais tem 5 ou 6 botões adjacentes com armadilha.
- As notas de 200 reais tem 7 ou 8 botões adjacentes com armadilha.

Como são os níveis do jogo?

- O jogo facílimo tem 4 botões que perdem o jogo. Ele tem 5 linhas e 5 colunas de botões.
- O jogo fácil tem 8 botões que perdem o jogo. Ele tem 5 linhas e 9 colunas de botões.
- O jogo normal tem 8 botões que perdem o jogo e 8 botões que perdem 5 reais. Ele tem 9 linhas e 9 colunas de botões.
- O jogo difícil tem 16 botões que perdem o jogo e 16 botões que perdem 5 reais. Ele tem 9 linhas e 13 colunas de botões.
- O jogo dificílimo tem 32 botões que perdem o jogo e 32 botões que perdem 5 reais. Ele tem 13 linhas e 13 colunas de botões.

Nas moedas estrangeiras, o valor será o equivalente em reais brasileiros após a conversão.
