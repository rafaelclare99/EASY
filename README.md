Dado um array de inteiros e um valor alvo (target), retorna os índices de dois números que somam exatamente o alvo.

Usa um Dictionary<int, int> (hash map) para armazenar os números já vistos e seus índices.

Em cada iteração, verifica se o complemento (target - número atual) já foi visto.

Tempo de execução: O(n)

Espaço adicional: O(n)
