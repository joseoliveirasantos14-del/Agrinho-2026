# Agrinho-2026 Aqui está o manual oficial para o seu novo jogo! Ele foi estruturado para explicar o conceito por trás do código e servir como um guia prático para os jogadores.

🛸 MANUAL DO JOGO: AGROFORTE – ECO DEFENDER
Gênero: Simulador Arcade / Gerenciamento Sustentável

Plataforma: Web (p5.js)

💡 A Ideia do Jogo
Em Agroforte: Eco Defender, você assume o controle de um drone agrícola de última geração em uma fazenda do futuro totalmente sustentável.

O objetivo do jogo é manter o equilíbrio ecológico da horta. Diferente de fazendas antigas que utilizavam agrotóxicos, a tecnologia da Agroforte utiliza um laser de bio-estimulação para acelerar o crescimento e monitorar a saúde das plantas em tempo real.

No entanto, a automação exige estratégia: o drone consome energia solar constantemente para funcionar. O jogador precisa se dividir entre nutrir as plantas com o laser e retornar à base de painéis solares para recarregar as baterias. Se você negligenciar a horta ou ficar sem energia, as plantas morrem e a missão falha!

🕹️ Controles
O jogo utiliza comandos simples e responsivos:

Seta para a Esquerda (◄) ou Tecla A: Move o drone para a esquerda.

Seta para a Direita (►) ou Tecla D: Move o drone para a direita.

Barra de Espaço (Space): Reinicia a partida após o Game Over.

📊 Elementos da Tela (Interface)
+---------------------------------------------------+
|  [ PONTOS: 0000 ]               ( SOL )           |
|  [ ENERGIA: |||||||||| ]                          |
|                                                   |
|         🛸 (DRONE)                                |
|          /\                                       |
|         /  \ (LASER)                              |
|        /____\                                     |
|                                     [CELEIRO]     |
|   (ÁRVORE)    [HORTA]              [PAINEL SOLAR] |
|              🌱 🌱 🌱 🌱                 🔋        |
|              [||] [||] [||] (Barras de Saúde)     |
+---------------------------------------------------+
Placar (Pontos): Mostra sua pontuação atual. Você ganha pontos a cada segundo que mantém o laser ativado sobre uma planta necessitada.

Barra de Energia: Indica o combustível restante do drone. Se chegar a zero, o laser desliga.

Barras de Saúde (Abaixo das Plantas): Indicadores individuais que vão de Verde (Saudável) a Marrom (Murchando).

🛠️ Mecânicas Práticas (Como Jogar)
1. O Ciclo de Cultivo
As plantas perdem saúde constantemente devido ao clima e ao desgaste natural. Para recuperá-las, posicione o drone diretamente acima delas. O feixe de luz azul/verde vai curá-las e fazê-las crescer, gerando pontos para você.

2. Gerenciamento de Energia
O drone gasta energia voando e usando o laser. No lado direito do cenário, há dois Painéis Solares. Para recarregar o drone, basta voar e estacionar o drone logo acima dos painéis. A barra de energia subirá rapidamente.

3. Condição de Game Over
O jogo é cooperativo com a natureza: nenhuma planta pode morrer. Se a barra de saúde de apenas uma das 8 plantas chegar a zero, a horta é considerada perdida, o jogo para e exibe sua pontuação final.

🏆 Dicas de Estratégia para Bater Recordes
Não espere secar: Não tente curar uma única planta até o tamanho máximo de uma vez só. É melhor ir movendo o drone de um lado para o outro para manter todas com a saúde média alta.

Recarga Eficiente: Não espere a energia do drone chegar ao fim para recarregar. Faça "viagens de abastecimento" rápidas aos painéis solares sempre que a energia cair da metade.

Aproveite a abertura do Laser: O laser do drone funciona em formato de cone (triângulo). Isso significa que, se você posicionar o drone no lugar certo, o feixe consegue atingir até duas plantas vizinhas ao mesmo tempo!
