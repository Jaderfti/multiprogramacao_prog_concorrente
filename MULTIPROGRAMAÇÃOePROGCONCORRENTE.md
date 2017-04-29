Multiprogramação

“A multiprogramação são vários programas que estão na memória ao mesmo tempo, de modo que, enquanto um esperava por entrada-saída para concluir sua tarefa, o outro podia executar, que resultava na utilização alta da CPU.”
 A Multiprogramação consiste em dividir a memória em várias partições de vários tamanhos fazendo com que a CPU fique com vários programas simultaneamente ativos na memória. Uma das vantagens da multiprogramação é de melhorar o rendimento de utilização da CPU e dos periféricos, outra vantagem é de permitir que o usuário explore tarefas correntes. Também temos a vantagem de permitir múltiplos utilizadores correntes e tendo a ilusão de que cada um tem um computador dedicado a ele mesmo. E isto é utilizado no Windows e na maioria dos sistemas operacionais.

Em um sistema de multiprogramação a CPU fica se alternando entre a execução de vários processos, cada um por dezenas ou centenas de milisegundos.
Um processo pode estar em um dos seguintes estados:

1. Running: usando a CPU naquele instante;
2. Ready: pronto para ser executado, temporariamente parado para que outro processo possa set executado;
3. Blocked: impossibilitado de ser executado até que algum evento externo ocorra. 

Programação Concorrente

Programação corrente significa “programação acontecendo ao mesmo tempo”. A mesma é um paradigma de programação para a construção de programas que fazem o uso da execução simultânea de várias tarefas computacionais interativas que podem ser implementadas como programas separados ou como um conjunto de threads criadas por um único programa. Essas tarefas podem ser executadas por um único processador, vários processadores em um único equipamento ou processadores distribuídos por uma rede. Programação concorrente é relacionada com programação paralela, mas foca mais na interação entre as tarefas. A interação e a comunicação correta entre as diferentes tarefas, além da coordenação do acesso concorrente aos recursos computacionais são as principais questões discutidas durante o desenvolvimento de sistemas concorrentes. Pioneiros na área de pesquisa incluem Edsger Dijkstra, Per Brinch Hansen, e C.A.R. Hoare.

Vantagens do paradigma incluem o aumento de desempenho, pois aumenta-se a quantidade de tarefas sendo executadas em determinado período de tempo, e a possibilidade de uma melhor modelagem de programas, pois determinados problemas computacionais são concorrentes por natureza.
