# Aleatoriedade

Como vimos em aula, aleatoriedade é uma estratégia bastante comum para construção de algoritmos de busca local, podendo ser usada
de forma isolada ou de forma complementar a outra estratégia de varredura de um espaço de soluções. 




Essa implementação consiste na adaptação da heurística gulosa de nosso projeto. A proposta é que você modifique a sua heurística gulosa de modo que ao longo da seleção de um filme você tenha 25% de chance de pegar outro filme qualquer que respeite o horário. Isso fará com que sua heurística tenha um pouco mais de exploration e possamos ter alguns resultados melhores. 

*Importante*: é essencial que você guarde todos os inputs usados ao longo do projeto, para que possa comparar o desempenho de seus algoritmos conforme mudamos a heurística. Ou seja, todas as heurísticas devem ser submetidas aos mesmos arquivos de input. O seu resultado deve ser comparado sob duas perspectivas, no mínimo: (i) tempo de execução em função do aumento de filmes e de categorias e (ii) tempo de tela (isto é, será que estamos conseguindo ocupar bem as 24h do dia assitindo filmes?).
