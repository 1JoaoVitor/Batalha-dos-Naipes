# Manual de Regras - Cartas Reais: Batalha dos Naipes

Bem-vindo ao Cartas Reais: Batalha dos Naipes! Este é um jogo de cartas para duas pessoas, onde vocês assumirão o papel de governantes em uma batalha estratégica e cheia de reviravoltas. Neste manual, você encontrará todas as informações necessárias para jogar e aproveitar ao máximo a experiência.

## Sumário

1. [Introdução e componentes](#introducao-e-componentes)
2. [Resumo](#resumo)
3. [Categoria de cartas](#categoria-de-cartas)
4. [Preparação](#preparacao)
5. [Tabuleiro](#tabuleiro)
6. [Desenvolvimento do jogo](#desenvolvimento-do-jogo)
7. [Tipos de ações](#tipos-de-acoes)
8. [Turnos do Jogo](#turnos-do-jogo)
9. [Habilidades das cartas](#habilidades-das-cartas)
   1. [Habilidades dos Governantes](#habilidades-dos-governantes)
   2. [Habilidades dos Comandantes](#habilidades-dos-comandantes)
10. [Exemplo de Turno](#exemplo-de-turno)
11. [Batalhas e Final do jogo](#batalhas-e-final-do-jogo)
12. [Créditos e agradecimentos](#creditos-e-agradecimentos)
13. [Patch Notes 1.4](#patch-notes-14)

## Introdução e componentes

- Um baralho padrão de 54 cartas, incluindo os Jokers.
- Tabuleiro com cinco slots (colunas) representando diferentes naipes: Paus, Espadas, Coringa, Copas e Ouros.
- Baralho de compras dividido entre os dois jogadores.
- O objetivo do jogo "Batalha dos Naipes" é vencer uma melhor de 5 entre as colunas, ou seja, vencer três ou mais batalhas de slots e se tornar o vencedor da guerra.


## Resumo

   <a name="_page1_x72.00_y227.43"></a>**Batalha dos Naipes** é um jogo de cartas que envolve estratégia e habilidade. O objetivo é vencer três ou mais batalhas dos slots (colunas) e se tornar o vencedor da guerra. O jogo é composto por um baralho padrão de 54 cartas, incluindo os Jokers.

   As cartas são divididas em **Governantes, Comandantes e Soldados**. Os Governantes são as cartas de figuras (Valete, Dama, Rei e Joker) e possuem habilidades especiais. Os Comandantes são as cartas Ás e têm habilidades ativadas imediatamente ao serem jogados. Os Soldados são cartas numeradas de 2 a 10 e participam das batalhas, eles são divididos em soldados baixos, 2 - 4., médios, 5- 7, e, altos 8 - 10.

   O tabuleiro possui **cinco slots** representando diferentes naipes: **Paus, Espadas, Coringa, Copas e Ouros**. Além disso, há slots específicos para os Comandantes que ficam atrás dos slots principais.

   Durante o jogo, os jogadores alternam seus turnos, realizando **ações principais e adicionais.** As ações incluem: **Comprar,** ativar habilidades dos Governantes, usar Comandantes, **posicionar cartas nos slots, fazer reforços,** substituir cartas, **comprar cartas adicionais,** mudança de ação e passar a vez.

   No final do jogo, quando o Baralho de Compras acaba, ocorre a **rodada final** e as batalhas entre os slots são resolvidas. O jogador que tiver **maior valor** numérico total em um único slot vence a batalha. Em caso de empate de todas as colunas, aquele que tiver **maior soma** dos valores de **todos** os slots **ganha** a partida.

## Categoria<a name="_page2_x72.00_y86.55"></a> de cartas
- **Governantes:** As cartas de figura (Valete, Dama, Rei e Joker) representam os Governantes, líderes das tropas.
- **Comandantes:** As cartas Ás (Ás de Espadas, Ás de Ouros, Ás de Paus e Ás de Copas) são os Comandantes, tropas que possuem destaque na batalha.
- **Soldados:** As cartas numeradas de 2 a 10 representam os Soldados, as tropas que participam das batalhas. Elas são divididas em:
- Cartas Altas (10-9-8)
- Cartas Médias (7-6-5)
- Cartas Baixas (4-3-2)
- **Cartas Âncoras:** Soldado principal do slot, jogado primeiro.
- **Cartas de Reforço:** Soldados adicionais em cada slot, jogados posteriormente.
  
## Preparação
- <a name="_page2_x72.00_y392.89"></a>Separe e embaralhe os Governantes (Valete, Dama, Rei e Joker). Embaralhe-as e distribua duas cartas de figura para cada jogador.
- Cada jogador escolhe um dos Governantes para jogar, descartando o outro. Remova do jogo as cartas de figura não escolhidas e as demais cartas de figura. Ambos os jogadores devem deixar virada para cima a carta escolhida.
- Separe e embaralhe o deck de compras. Cada jogador recebe cinco cartas desse baralho de compras. (Soldados e Comandantes).
- Decida quem irá começar, por exemplo, por ímpar ou par.
  
## Tabuleiro
- <a name="_page2_x72.00_y641.05"></a>De um lado ficará o baralho de compras, que será dividido entre os dois jogadores, e do outro a pilha de descartes, que ficará virada para baixo.
- Tabuleiro é dividido em cinco principais slots (colunas) representando diferentes naipes: Paus, Espadas, Coringa, Copas e Ouros, sendo o Coringa um slot em que qualquer naipe pode ser jogado. Eles representarão diferentes batalhas entre as cartas correspondentes.
- Também existem slots específicos para os Comandantes que se apresentam atrás do slot principal, um para cada naipe. O esquema se apresenta em:

![](https://github.com/1JoaoVitor/Batalha-dos-naipes/blob/045f853f4d48b6e829d6019ca00faede30951291/Imagem%20tabuleiro%20batalha%20dos%20naipes.jpeg)

## Desenvolvimento<a name="_page4_x72.00_y72.00"></a> do jogo
- Os jogadores alternam seus turnos, realizando ações de acordo com as possibilidades disponíveis.
- Durante o jogo, os jogadores posicionam cartas nos slots correspondentes, realizam reforços e utilizam as habilidades dos Governantes e Comandantes.
- O jogo continua até que o Baralho de Compras acabe. Tendo o outro jogador mais um turno para tentar finalizar a partida.
- Após a última jogada, as batalhas entre os slots são resolvidas.
  
## Tipos<a name="_page4_x72.00_y241.98"></a> de ações
- Comprar (ação obrigatória)
- Ação principal (uma por turno): É a ação que centra sua jogada, que normalmente possui maior impacto no turno.
- Ação adicional (duas por turno): São as ações extras de cada jogador, podem ser feitas até DUAS por turno e complementam e desenvolvem as ações principais.
  
## Turnos<a name="_page4_x72.00_y402.86"></a> do Jogo

   Cartas Reais é jogado em turnos alternados entre os jogadores. Durante o seu turno, você pode realizar as seguintes ações:

- **Comprar (ação obrigatória):** Todo início de turno, como primeira ação, você deve comprar uma carta do baralho de compras.
- **Ativar habilidades de Governantes (ação adicional):** Durante o seu turno, você pode ativar a habilidade de um Governante que esteja em jogo. Essas habilidades são aplicadas apenas uma vez por partida e proporcionam vantagens estratégicas.
- **Usar Comandantes (ação adicional):** Durante o seu turno, você pode usar um Comandante que esteja em sua mão. Os Comandantes têm habilidades específicas que são ativadas imediatamente ao serem jogados.
- **Posicionamento (ação principal):** Ao jogar uma carta, você a coloca virada para baixo em um dos slots correspondentes aos naipes no tabuleiro. Quando voltar a ser sua vez, você deve virar a carta e deixá-la à mostra.
- **Reforço (ação principal/ação adicional):** Você pode aprimorar os pontos de um slot que possua uma Carta Âncora que já esteja virada para cima. Para isso, jogue uma carta do mesmo naipe (em caso do slot coringa qualquer naipe) virada para cima. Existem as seguintes combinações possíveis: Alta+Baixa ; Média+Média ; Média+Baixa+Baixa e Baixa+Baixa+Baixa.
- Reforço Alto (ação principal): Você pode adicionar uma Carta Alta em cima de uma Carta Baixa ou adicionar uma Carta Baixa em cima de uma Alta já presente no slot.
- Reforço Médio (ação principal): Você pode adicionar uma Carta Média à outra Carta Média ou Carta Baixa já presente no slot.
- Reforço Baixo (ação adicional): Você pode adicionar uma Carta Baixa em cima de uma Carta Média ou em cima de outra Carta Baixa já existentes no slot.
- **Substituição (ação principal/ação adicional)**: Você pode substituir qualquer carta do slot por uma outra de sua mão sem penalidade, usando a ação referente aquela jogada. A carta substituída é descartada e as regras de reforço ainda devem ser respeitadas.
- **Compra Adicional (duas ações adicionais):** Você pode descartar uma carta da sua mão para comprar uma carta adicional do baralho de compras. Essa ação só pode ser realizada uma vez por turno. Descarte vem primeiro que a compra.
- **Mudança de ação (Mecânica):** Você pode mudar sua ação principal para ter uma ação adicional extra, ficando com 3 adicionais no turno.
- **Forjar 2 (Mecânica):** Sem usar ação e sem precisar anunciar para seu adversário, você pode juntar duas cartas da sua mão (2+2 / 2+5 / 2+8) de naipes diferentes e usar como se fosse uma carta só, com a soma de seus valores, e com o naipe da carta mais forte sendo o contabilizado. Em caso de 2+2 qualquer um dos naipes pode ser considerado. Para jogar a nova carta forjada, as regras e custos de ação referentes à jogada ainda valem.
- **Passar a vez:** Se você não desejar realizar mais nenhuma ação você pode passar a vez para o seu adversário.
  
## Habilidades<a name="_page5_x72.00_y610.21"></a> das cartas

   Algumas cartas possuem habilidades que aumentam a diversidade de jogadas e estratégia do jogo. Tanto os Governantes quanto os Comandantes possuem esse adicional. Entenda essas habilidades dos para usá-las no momento certo e dominar seu oponente.

   Existem várias habilidades diferentes, as dos Comandantes são ativadas imediatamente (caso o jogador deseje que aconteça), enquanto as ações dos Governantes podem ser aplicadas a qualquer momento do jogo pelo jogador durante seu turno. Ambos os tipos de habilidades são utilizadas apenas uma vez por partida.

### Habilidades<a name="_page6_x72.00_y72.00"></a> dos Governantes
- **Valete:** Você busca por qualquer carta do baralho, contudo deve mostrar ao seu oponente a carta que comprou. Embaralhe logo depois.
- **Dama:** Ao ativar, pode Realocar/Trocar de lugar até duas das suas cartas, independente do naipe, da forma que desejar, desde que esteja dentro das regras de reforço.
- **Rei**: Você olha toda a pilha de descartes e escolhe cartas para serem jogadas automaticamente nos seus slots. As opções são: Duas baixas ou uma média ou uma alta. Caso não tenha espaço apenas o possível será adicionado ou você poderá usar Substituição. Você pode forjar 2 a partir de qualquer combinação da(s) carta(s) comprada(s) com a habilidade e das cartas da sua mão.
- **Joker:** Ao ativar, durante este turno todos seus slots são coringa e todos seus reforços são adicionais. (Não gasta ação adicional para ativar).
### Habilidades<a name="_page6_x72.00_y386.12"></a> dos Comandantes
- **Ás de Ouros:** Vale um ponto no Slot de Ouros. Olhe as 3 primeiras cartas do deck e escolha uma para comprar. Embaralhe logo depois.
- **Ás de Copas:** Vale um ponto no Slot de Copas. Além disso, você pode mover uma carta baixa sua de qualquer naipe de um slot para outro e, se já estiver ocupado, fazer a troca entre cartas, sem importar
- naipe e considerando as regras de Reforço.
- **Ás de Espadas:** Vale um ponto no Slot de Espadas. Além disso, você pode trocar uma carta de reforço sua com a do adversário do mesmo slot. Porém, existe a necessidade de ambos terem alguma carta de reforço para ser trocado e as regras de reforço devem ser respeitadas.
- **Ás de Paus:** Vale um ponto no Slot de Paus. Quando colocado em campo, o jogador pode olhar todo o baralho de descarte e comprar uma carta que queira.
  
## Exemplo<a name="_page7_x72.00_y72.00"></a> de Turno

Suponha que seja o seu primeiro turno:

1. **Comprar uma Carta:**

   Você começa o turno comprando uma carta do baralho.

2. **Ação Principal:** Posicionar uma Carta no Slot

   Você escolhe um Soldado (por exemplo, um "6 de Espadas") e o posiciona virado para baixo no slot de Espadas.

3. **Ação Adicional:** Usar descarte e compra

   Descarte uma carta da sua mão e compre outra do baralho de compras usando duas ações adicionais para isso.

## Batalhas<a name="_page7_x72.00_y358.35"></a> e Final do jogo
- Quando o Baralho de Compras acabar o jogo entra na rodada final, o outro jogador tem mais um turno para finalizar a partida. Após a última jogada as batalhas serão feitas.
- As batalhas são vencidas pelo jogador que tiver maior valor numérico total de um único slot.
- Caso ocorra um empate geral entre todas as batalhas, a partida será decidida pela soma dos valores de todos os slots. Aquele que tiver a maior soma será
- vencedor.
- O jogo empata caso a soma de todas as cartas de ambos os jogadores tenham os mesmos valores.

***Divirta-se e boa sorte na guerra!***

## Créditos<a name="_page9_x72.00_y72.00"></a> e agradecimentos
Idealizado por:
- João Vitor Evangelista
- Álvaro Stein

Desenvolvido por:

- João Vitor Evangelista
- Álvaro Stein
- Alexandre Guariso

Agradecimentos especiais:

- Arthur Peixoto
- Thiago Lamin

Este jogo foi idealizado e criado com muita dedicação por João Vitor Evangelista e Álvaro Stein, com grande contribuição de Alexandre Guariso, um enorme contribuinte para o desenvolvimento, idealização e otimização do jogo. Agradecemos profundamente ao Arthur Peixoto e ao Thiago Lamin, os primeiros jogadores de Cartas Reais: Batalha dos Naipes, que permitiram que o jogo fosse testado continuamente e nos deram importantes feedbacks. Agradecemos também aos nossos amigos, familiares e a todos os jogadores que apoiaram este projeto desde o início e permitiram sua realização.

## Patch<a name="_page10_x72.00_y72.00"></a> Notes 1.4
- **Forjar 2 (Nova mecânica):** Sem usar ação e sem precisar anunciar para seu adversário essa mecânica você pode juntar duas cartas (2+2 / 2+5 / 2+8) de naipes diferentes e usar valendo uma só com a soma de seus valores e com naipe da carta mais forte sendo o contabilizado. Em caso de 2+2 qualquer um dos naipes pode ser considerado.
- **Todas as habilidades foram REFORMULADAS:**
- **Ás de Ouros:** Vale um ponto no Slot de Ouros. Olhar as 3 primeiras cartas do deck e escolher uma para comprar. Embaralhar logo depois.
- **Ás de Copas:** Vale um ponto no Slot de Copas. Além disso, você pode mover uma carta baixa de qualquer naipe um slot para outro slot e, se já estiver ocupado, então troca de lugar com ela. Sem importar o naipe e considerando as regras de Reforço.
- **Ás de Espadas:** Vale um ponto no Slot de Espadas. Além disso, você pode trocar uma carta de reforço sua com a do adversário do mesmo slot. Porém existe a necessidade de ambos terem alguma carta de reforço para ser trocado e as regras de reforço devem ser respeitadas.
- **Ás de Paus:** Vale um ponto no Slot de Paus. Quando colocado em campo, o jogador pode olhar todo o baralho de descarte e comprar uma carta que queira.
- **Valete:** Você busca por qualquer carta do baralho, contudo deve mostrar ao seu oponente a carta que comprou. Embaralhe logo depois.
- **Dama:** Ao ativar, pode (Realocar/Trocar de lugar) até duas cartas, independente do naipe, da forma que desejar, desde que esteja dentro das regras de reforço.
- **Rei**: Você olha toda a pilha de descartes e escolhe cartas para serem jogadas automaticamente nos seus slots. As opções são: Duas baixas ou uma média ou uma alta. Caso não tenha espaço apenas o possível será adicionado. E em caso de compra de 2 do descarte pode-se forjar com um outro 2 na mão, antes da sua aplicação.
- **Joker:** Ao ativar, durante este turno todos seus slots são coringa e todos seus reforços são adicionais. (Não gasta ação adicional para ativar).
- **A regra de desempate mudou!** Agora a categoria da Carta Âncora não importa mais, portanto apenas os pontos do Slot serão definitivos para o desempate. Por exemplo: 7+6 irá empatar com um 10+3 atualmente.
- **Novo sistema de Substituição:** Agora você pode substituir qualquer carta do slot por uma outra de sua mão sem penalidade. A carta substituída é descartada. As regras de reforço ainda devem ser respeitadas.
- **Tópico de Reforços melhor explicado.**
- **Criação do Tópico Feedbacks.**
- **Tópico das Ideias melhor organizado.**
- **Agora você pode transformar sua ação principal em +1 adicional. (ficando com 3 adicionais).**
- **Reformulação da ordem dos tópicos**

Para todas as versões e patches acesse: [Patch Notes Cartas Reais: Batalha dos Naipes](https://github.com/1JoaoVitor/Batalha-dos-naipes/blob/e122a7d960806b7d406d47b3080a3becfc7bb902/%5BMD%5D%20Patch%20Notes%20Cartas%20Reais_%20Batalha%20dos%20Naipes.md)
