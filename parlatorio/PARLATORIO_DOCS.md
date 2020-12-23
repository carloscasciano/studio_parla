# Parlatorio Docs

## Sumário

1. [Movimentação](#movimentacao)
2. [Inventário](#inventario)
3. [Energia](#energia)
4. [Transportando e Carregando](#transportando)
5. [Minerando](#minerando)
6. [Fundições](#fundicoes)
7. [Máquinas de Montagem](#montagem)

### Movimentação  <a name="movimentacao"></a>

#### Andando

![](wasd.gif)

Use as teclas <kbd>W</kbd> <kbd>A</kbd> <kbd>S</kbd> <kbd>D</kbd> para se movimentar.

<kbd>W</kbd> para cima

<kbd>A</kbd> para esquerda

<kbd>S</kbd> para direita

<kbd>D</kbd> para baixo

As combinações das teclas faz com que você se movimente na diagonal (ex: <kbd>W</kbd> + <kbd>A</kbd> te movimenta para a diagonal superior direita)

#### Zoom

![](zoom.gif)

O <kbd>scroll</kbd> do mouse aumenta e diminui o zoom.

#### Mapa

A tecla <kbd>M</kbd> abre e fecha o mapa.

---

### Inventário

#### Abrir Fechar Inventário

![](inventory.gif)

A tecla <kbd>E</kbd> abre o seu inventário.

#### Baús

![](chest.gif)

Baús guardam items, você pode depositar ou retirar items deles para seu inventário e vice-versa.

:boom: DICAS QUENTES :boom:

- Clicar com o botão direito do mouse pega metade do stack desejado (no exemplo, segundo item tem stack de 50, usuário pega 25)

- Segurar a tecla <kbd>CTRL</kbd> e clicar com o botão esquerdo em um item, movimenta TODOS os itens do mesmo tipo (no exemplo, pegar várias esteiras)

#### Barra de Favoritos

![](favoritebar.gif)

Você pode arrastar itens do seu inventário para a barra de favoritos. Para limpar a barra de favoritos, clique com o botão do meio do mouse.

:boom: DICA QUENTE :boom: A tecla <kbd>Q</kbd> 'deseleciona' o item clicado, <b>é muito utilizado</b>.

---

### Energia

![](energy_main.gif)

A grande maioria dos elementos de trabalho exigem energia. A energia é fornecida por uma central e distribuída por postes.

![](no_energy_icon.gif)

Caso o ícone acima esteja piscando, o elemento em questão está sem energia e deve ser conectado a uma rede.

O raio de ação de um poste é determinado pela área azul ao redor dele (passe o mouse por cima).

Garanta que existam fios entre os postes, eles são criados automaticamente quando obedecem uma distância mínima.

![](fast_pole_building.gif)

:boom: DICA QUENTE :boom: Com o poste selecionado (e um número razoável de postes no invetário), pressione e segure o botão esquerdo do mouse e se movimente. Uma linha de postes otimizada será criada pelo caminho que você andar.

---

### Transportando e Carregando

#### Esteiras e produtos

As esteiras são o principal meio de locomoção do jogo. São por elas que é possível transportar os materiais crus ou produzidos.

#### Construindo Esteiras (Colocar, Tirar, Rotacionar)

![](building_tracks.gif)

Para construir uma estrada, basta ter a esteira selecionada e clicar com o botão direito do mouse. 

A tecla <kbd>R</kbd> rotaciona a estrada, é possível colocá-las nas 4 direções.

Para retirar uma estrada mal posicionada, clique e segure com o botão esquerdo do mouse.


#### Dois lados de uma esteira

![](esteira_2_elements.gif)

Uma esteira pode carregar materiais dos dois lados de sua esteira e podem ser dois materiais diferentes.

#### Separador

![](separator.gif)

É possível separar ou unir faixas de esteiras com o separador. <b>Importante para dividir recursos</b>.

#### Esteira subterrânea

![](tunnel.gif)

É possível fazer com que uma faixa de esteiras passe por baixo de outra se estiverem perpendiculares, usando as esteiras subterrâneas.

#### Estrutura em Cruz

![](t_structure.gif)

A estrutura mais simples para colocar dois elementos em uma esteira é a Cruz.

#### Balanceando uma esteira

![](rebalance.gif)

É possível balancear uma esteira com um separador.

#### Braços mecânicos

![](mech_arms.gif)

Os braços mecânicos jogam elementos do ponto A para o ponto B. Durante a construção, o item que está do lado da 'barra' será carregado para o lado da 'seta'.

É necessário energia para o braço funcionar.

O braço pode retirar e colocar items:

- em esteiras (dos dois lados)
- em baús
- em fundições
- em máquinas de automatização

:boom: DICAS QUENTES :boom:

![](fast_esteiras.gif)

- É possível construir uma faixa de esteiras mais rapidamente segurando o botão direito do mouse e andando.

![](walk_esteiras.gif)

- É possível se movimentar mais rápido (ou devagar) andando sobre uma faixa de esteira.

- Preste atenção na direção do braço mecânico (barra vs. seta), é um erro comum.

---

### Minerando

![](mining.gif)

Minério bruto é o elemento base para todas as construções. Ele tem o formato de 'pedrinhas' e é diferenciado por cores:

- Preto é o CARVÃO
- Marrom é o COBRE
- Azul é o FERRO
- Cinza é a PEDRA (não estará presente na dinâmica)

É possível retirar minérios do chão com a mineradora, ela precisa de energia para funcionar e deve ser colocada sobre uma camada de minérios qualquer.

A seta para onde a mineradora aponta é aonde será depositada a pedra do minério extraído. É recomendado jogá-lo em uma esteira ou em um baú.

:boom: DICAS QUENTES :boom:

- Mais mineradoras, mais minérios.

- Cuidado para não colocar uma mineradora sobre dois minérios diferentes.

---

### Fundições

![](smelting.gif)

Minério bruto pode ser transformado em chapas usando a Fornalha de Aço.

- Minério de Bronze em Chapa de Bronze
- Minério de Ferro em Chapa de Ferro

Uma mineradora precisa do minério desejado para chapa + um minério de Carvão para criar uma Chapa do minério desejado.

---

### Máquinas de Montagem

É possível construir produtos mais complexos com a máquina de montagem, seguindo os seguintes passos:

- Escolher a receita do que você quer construir
- Fornecer os materiais necessários


Principais receitas para a dinâmica:

- Cabo de Cobre
  - Chapa de Cobre
  
- Engrenagem
  - Chapa de Ferro
  
- Circuito Eletrônico
  - 1 Chapa de Ferro
  - 3 Cabo de Cobre
  
- Poção Vermelha (Pacote Científico)
  - 1 Chapa de Cobre
  - 1 Engrenagem de Ferro

---

#### :boom: Mais DICAS QUENTES :boom:

- Espaço também pode ser considerado um recurso, planejamento antes de construir garante organização.

- Linhas de produção podem (e devem) ser desenvolvidas, uma esteira de recursos abastacendo várias estruturas geralmente é o melhor caminha para uma produção maior.

- É possível limpar manualmente uma esteira segurando a <kbd>F</kbd>, cuidado, pois os itens vão para o inventário pessoal.
