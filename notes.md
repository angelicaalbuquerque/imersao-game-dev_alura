# Aula 1: Animações básicas e trilha sonora

[_Assistir_](https://www.youtube.com/watch?v=8glxH8aS7ko)

Usaremos a p5.js: uma biblioteca JavaScript específica para animações, muito utilizada por programadores e programadoras no mundo todo, mas ainda deixa o principal do jogo para escrevermos.

Nesta primeira aula, nosso objetivo principal é criar as animações iniciais do nosso game: da personagem e do background! E o que é um jogo sem uma boa trilha sonora? Pois vamos trabalhar nisso também. :) Ah! Você pode criar seus próprios personagens e música, claro!

Ao final desta aula já teremos a versão inicial do nosso jogo, que poderá ser compartilhado (e jogado) com seus amigos e amigas!

O que você vai precisar para o primeiro jogo?

- Um computador. Não precisa instalar nada! Mas se quiser usar editores, fique a vontade. Sim, é possível fazer só através do celular, mas será muito trabalhoso.

- Fazer uma [cópia do projeto inicial](https://editor.p5js.org/alura/sketches/D_eq5CU6T), que já contém as imagens que utilizaremos nesse início de projeto.

- Baixar os chamados [assets](https://www.alura.com.br/imersao-gamedev-javascript/assets/assets.zip), isto é, os recursos, como essas imagens e outras. Vale lembrar que você pode criar as próprias imagens e herois. A versão original dessa bruxa e inimigos [está aqui](https://pipoya.itch.io/pipoya-free-2d-game-character-sprites).

## Desafios:

- Organizar a matriz no personagem.js, tirando os números fixos e substituindo-os por um cálculo
- Criar sua conta no codepen.io
- Criar a história da bruxa Hipsta. Por que ela está andando nessa floresta?
- Fazer seus próprios sprites, criando um jogo com visual bem diferente! Homenageie seu heroi preferido, seu youtuber mais amado :).
- Deixar a função de imagem mais limpa e organizada!

# Aula 2: Fluxo de vida, missão e falha

[_Assistir_](https://www.youtube.com/watch?v=tlkOFTWIrCo)

Vamos começar a dar vida ao nosso endless runner. Você vai ver que a matemática por trás dos pulos, da gravidade e da colisão são bem mais simples do que imaginamos.

Usaremos pouco código da biblioteca. Espero que você se impressione com a simplicidade da aplicação da gravidade.

[Aqui tem a matriz de posição](https://gist.github.com/juunegreiros/fcb9bd1e842375d72e80f3f10d4552e1) para desenhar nossos novos inimigos.

Caso você queira ver tudo o que já fizemos na aula 1, pode baixar o [código aqui](https://editor.p5js.org/alura/sketches/DtcUcnUnh).

## Desafios:

- Fixe o pulo duplo em no máximo 2!

- Faça um background com aparência 3D usando duas imagens diferentes, com velocidades diferentes. É o efeito paralaxe. Para isso, você precisa que o da frente tenha transparência

- Coloque elementos diferentes em seu jogo: abelhas, borboletas, o que você achar que vai ficar legal!

- Faça uma tela de game over mais elaborada, explicando o que aconteceu com a personagem e porque a pessoa perdeu.

# Aula 3: Mais inimigos e pontuação

[_Assistir_](https://youtu.be/IuVlkxZd4GE)

Nosso jogo está ficando super legal, não é mesmo? Chegou a hora de deixar ele ainda mais legal! Vamos incluir tipos diferentes de inimigos! Vamos até colocar um voador 🦇

E o que é um jogo sem pontos? Quanto mais longe quem estiver jogando conseguir ir com a Hipsta, mais pontos a pessoa irá ganhar. E dá para ir bem mais longe que isso...

E ah...sabe aquela tela de game over que ficou como desafio ontem? Também faremos ela juntos :)

Você pode ver o código de tudo que já fizemos [aqui](https://editor.p5js.org/alura/sketches/K2EIO2uVu). Baixe a matriz que comentamos no vídeo [aqui](https://gist.github.com/juunegreiros/4cd7bd68836ac6c65985298fc264a366).

## Desafios:

- Configure o jogo para que tenhamos apenas um inimigo aparecendo de cada vez.

- A colisão da Hipsta com os inimigos não está muito legal...será que conseguimos melhorar isso?

- Crie uma tela inicial para o jogo.

- Faça com que moedas apareçam durante o jogo e, conforme a Hipsta as pega, ela acumula mais pontos.

# Aula 4: Estado do jogo com cenas diferentes

[_Assistir_](https://youtu.be/2nETUc4MCZo)

Seria legal se nosso jogo tivesse uma tela inicial, não acha? Uma apresentação ou algo do tipo antes do jogo começar pra valer. Pois bem, faremos isso nessa aula :)

E nossos inimigos, hein?
O jogo está legal, mas eles estão aparecendo de forma muito aleatória e em alguns momentos fica difícil demais conseguir passar. Vamos resolver isso!

Pra fechar, também daremos uma boa organizada no código pra deixar ele mais fácil de entender e fazer alterações.

Você pode ver tudo o que já fizemos até agora [aqui](https://editor.p5js.org/alura/sketches/XYLfoz6Lp).

Desafios:

- Crie a história do seu jogo através de várias cenas diferentes, por exemplo: qual a missão da Hipsta? O que acontece se ela não chegar onde precisa?

- Onde mais você pode colocar estado? Criar uma segunda fase, depois de ter atingido X pontos ou passado N inimigos, é um bom desafio.

- Quer ir realmente longe: a passagem de fase poderia ser feita de forma transparente: o novo background começa a aparecer, mas encaixando no background antigo. Entao voce precisa achar imagens de background que se encaixem e que, duas ou tres passadas de tela depois, possa levar a Hipsta de uma floresta a um deserto.

# Aula 5: Fluxo de vida, missão e falha

[_Assistir_](https://youtu.be/HD1knuq2v2g)

O nosso jogo está cada dia melhor, mas se errarmos e colidirmos com um inimigo apenas uma vez a Hipsta morre. Vamos resolver isso adicionando vidas! E com esse mesmo mecanismo você pode criar power ups.

Além disso, vamos centralizar as configurações como a quantidade de vidas, que tipos de inimigo que irão aparecer e com que frequência. Um mapa!
Essas configurações ficarão em um arquivo que você poderá compartilhar com outros amigos e amigas que estiverem fazerndo a imersão para que eles possam jogar a sua versão do game!

Vamos lá?

Você pode ver tudo o que já fizemos até agora [aqui](https://editor.p5js.org/alura/sketches/QFtvZ6Ks2).

## Certificado

Quer criar um certificado como [esse](https://imersao-gamedev.github.io/certificado/)? Basta clonar esse repositório e embedar o próprio jogo criado, como ensinado no final da aula 5 :)

https://github.com/imersao-gamedev/certificado Você pode usar o certificado na seção "Educação" do seu linkedin e incrementar seu currículo :)

## Desafios:

- Crie a história do seu jogo através de várias cenas diferentes, por exemplo: qual a missão da Hipsta? O que acontece se ela não chegar onde precisa?
