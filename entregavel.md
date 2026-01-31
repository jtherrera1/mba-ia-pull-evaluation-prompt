# Entregável

## Técnicas Aplicadas
- role_prompting
    Define explicitamente o papel, senioridade e modelo mental esperado
    Direciona o vocabulário, nível de detalhe, trade-offs e critérios de decisão
    Reduz respostas genéricas e “acadêmicas”

- few_shot_learning
    Definir exemplos realistas de entrada e saída

    Com isso o modelo entende:
    * Onde começa cada seção
    * Como os títulos são escritos
    * O nível de granularidade esperado em cada bloco

- rubric-based_prompting

    * Definir estrutura rígida em 13 seções

    * Criar Escalas definidas:

        Severidade (S0–S4)
        Prioridade (P0–P3)

    * Adicionar Regras claras de:
        Cobertura
        Limite de cenários
        Modo Simples / Moderado / Complexo
        Critérios objetivos de qualidade (DoD, Validação de Cobertura)

    * O mais importante, dada a severidade indicar quias regras usar, problemas complexos explicações claras, problemas simples soluções claras e curtas

## Modelos usados
LLM_PROVIDER=google
LLM_MODEL=gemini-2.5-pro
EVAL_MODEL=gemini-2.5-pro

## Custo

![custo gerado pelo processamento](custo.png)
## Resultados

![resultado esperado](resultado.png)

