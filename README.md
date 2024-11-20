1. Cálculo da Média Aritmética
O código começa pedindo ao usuário que informe a quantidade de notas que ele deseja inserir. A quantidade de notas deve ser um número positivo, caso contrário, o código exibe uma mensagem de erro e termina a execução.

Após verificar se a quantidade de notas é válida, o código entra em um loop que permite ao usuário inserir as notas uma a uma. O código soma todas as notas inseridas e, ao final, calcula a média aritmética dividindo a soma das notas pelo número total de notas inseridas.

Depois de calcular a média aritmética, o programa classifica o aluno com base no valor da média:

Aprovado: Se a média for maior ou igual a 6.
Recuperação: Se a média estiver entre 5.0 e 6.0 (inclusive).
Reprovado: Se a média for menor que 5.0.
2. Cálculo da Média Ponderada
Após a classificação com base na média aritmética, o código solicita novamente ao usuário a quantidade de notas, mas agora com um limite máximo de 3 notas. O programa então pede para o usuário inserir essas três notas, mas, ao contrário da média simples, a média ponderada leva em consideração pesos diferentes para as notas.

As duas primeiras notas possuem peso 1.
A terceira nota possui peso 2.
O código calcula a média ponderada somando o produto de cada nota pelo seu peso correspondente e dividindo pela soma total dos pesos. Ou seja, o peso das notas altera a contribuição de cada uma para o resultado final.

3. Classificação com base na Média Ponderada
Após calcular a média ponderada, o programa exibe o valor da média com duas casas decimais e, assim como fez para a média aritmética, classifica o aluno com base no valor da média ponderada:

Aprovado: Se a média ponderada for maior que 6.
Recuperação: Se a média ponderada estiver entre 5.0 e 6.0 (exclusivo de 6).
Reprovado: Se a média ponderada for menor ou igual a 5.0.

*Objetivo do Código:*
O código tem como objetivo avaliar o desempenho de um aluno de duas maneiras:

Média aritmética, que leva em consideração todas as notas igualmente.
Média ponderada, que atribui diferentes pesos para as notas, dando mais importância à última (ou à que o professor achar mais relevante).
Com base nos resultados dessas médias, o aluno recebe uma classificação: Aprovado, Recuperação ou Reprovado. Essa abordagem permite avaliar o aluno de forma mais completa, levando em consideração tanto seu desempenho geral quanto a importância relativa das notas.