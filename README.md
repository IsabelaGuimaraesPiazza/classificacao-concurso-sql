# Classificação de Concurso Público 
Repositório com a resolução de um desafio prático de banco de dados aplicado ao setor de Concursos Públicos e Auditoria Legal. O projeto foca no uso de Funções de Janela (Window Functions) para avaliar o comportamento de regras de negócio distintas diante de cenários com empates de notas.

## Descrição do Desafio
O objetivo do projeto é estruturar um relatório de classificação oficial para uma banca examinadora. A regra de negócio exige a simulação de duas visões legais de classificação lado a lado para determinar o impacto na listagem de candidatos aprovados quando há notas idênticas na mesma posição.

### Comportamento das Regras nos Empates:
*   **RANK()**: Atribui classificações idênticas aos empates e "pula" as posições subsequentes com base no número de registros empatados (Gera lacunas).
*   **DENSE_RANK()**: Atribui classificações idênticas aos empates, mas mantém a numeração da sequência de forma contínua, sem deixar buracos na numeração (Ordenação densa).

UTILIZEI SQL, RANK(), DENSE_RANK(), OVER, ORDER BY
