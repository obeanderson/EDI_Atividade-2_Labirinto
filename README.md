# EDI_Atividade-2_Labirinto

Discente: Anderson Alves

Este trabalho pode ser desenvolvido individualmente ou em dupla, seu objetivo é encontrar um caminho
de um ponto P1 a um ponto P2 em um labirinto por meio da estrutura de dados pilha. O problema de
encontrar caminhos entre pontos e de grande importância prática, por exemplo, para determinar canais de
comunicação (conexões) entre dois pontos em uma rede.

O labirinto e representado por uma matriz de N posições. Posições marcadas com “*” correspondem a
uma parede, enquanto posições marcadas com “.” são posições vazias, ou seja, que podem ser percorridas.
A técnica utilizada é conhecida como backtraking (ou retrocesso), comumente utilizada em inteligência
artificial.

Deverá ser definido um valor para a posição inicial e o programa deve apresentar o ponto onde um objeto
se encontra no labirinto.

Para contextualizar vamos imaginar que a posição inicial define onde está um ratinho, que procura seu
queijo dentro do mesmo. O Queijo está em uma posição aleatória.

A lógica consiste em visitar um ponto, marcá-lo, tentar percorrer o labirinto nos sentidos  ↓←↑ e
empilhá-lo, logicamente só é possível ir a alguns destes sentidos caso a posição seja um “.”, ou melhor
ainda se for nosso queijo. O percurso deverá ser interrompido quando o queijo for encontrado. Caso entre
em um beco, este deve ser marcado com “x” e a posição deve ser retrocedida ao ponto anterior, para nova
tentativa de percurso.

