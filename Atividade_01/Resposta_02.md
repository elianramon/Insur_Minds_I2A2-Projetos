Arquivo: Defective_Equipment_v2026-04-14

```
Você é um Engenheiro de Confiabilidade Especialista em Monitoramento de Condição. Sua tarefa é realizar uma análise de detecção de anomalias em um conjunto de dados de sensores de ativos industriais.

Configuração dos Dados:
Colunas: Representam os equipamentos (identificados de V1 a V9).
Linhas: Representam 17 sensores distintos. Cada linha contém medições de mesma grandeza para todos os equipamentos.
Cenário: Existe variação padrão entre os sensores. No entanto, um dos equipamentos apresenta um comportamento fora do padrão estatístico dos demais.

Identifique qual equipamento (coluna) apresenta valores consistentemente divergentes da média ou da tendência dos outros 8 equipamentos.
Considere que um defeito raramente afeta apenas um sensor; procure por um padrão de anomalia que se repita em diferentes linhas para o mesmo equipamento.

Saída Esperada:
´´´
Equipamento: [Identificador do Equipamento, ex: V1]
Explicação: [Descreva de forma concisa quais sensores/linhas apresentaram a maior divergência e se o valor estava acima ou abaixo da média do grupo].
´´´
Pronto?
```

## Resposta:
- DeepSeek
  
Equipamento: V7

Explicação: O equipamento V7 apresenta valores sistematicamente abaixo da média dos outros 8 equipamentos em 14 de 17 sensores, com diferenças acentuadas nas linhas 5 (sensor 5: -41 abaixo da média), 8 (-38), 9 (-326), 11 (-52) e uma inversão na linha 10 (+439 acima). Esse padrão consistente em múltiplos sensores indica uma anomalia operacional no ativo V7.

- Gemini
  
Equipamento: V7

Explicação: O equipamento V7 apresenta uma anomalia sistêmica negativa, com valores consistentemente abaixo da média da frota em 12 dos 17 sensores. As divergências mais críticas ocorreram nos sensores 1, 5, 6 e 9 (com desvios superiores a 2 desvios padrão negativos), indicando uma falha que afeta a assinatura operacional global do ativo, e não apenas um componente isolado.
  
