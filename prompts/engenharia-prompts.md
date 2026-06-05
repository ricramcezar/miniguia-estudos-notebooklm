# Engenharia de Prompts e "Cicatrizes"

Registro do processo de refinamento de prompts e os desafios encontrados (*troubleshooting*) para extrair o melhor raciocínio lógico da IA durante os estudos.

## 🧪 Prompts Testados e Resultados

### Cenário 1: Cálculo de Taxas de Atraso
* **Prompt Inicial:**
  > *"Como calcular juros de mensalidade atrasada?"*
* **Problema Encontrado:** A IA deu uma resposta muito genérica sem considerar a legislação escolar brasileira (limite de multa moratória) ou a lógica de banco de dados (SQL).
* **Prompt Refinado:**
  > *"Aja como um engenheiro de dados especialista em lógica de negócios para ERPs escolares. Como modelar o cálculo de atraso de uma mensalidade considerando: data de vencimento, data de pagamento, multa moratória de 2% (limite do CDC) e juros de 1% ao mês pro rata die? Forneça a lógica em pseudocódigo ou SQL."*
* **Resultado:** [Descreva aqui brevemente o retorno da IA e se foi útil]

---

## 🩹 "Cicatrizes" e Resolução de Problemas (Troubleshooting)

Ao longo dos testes, documente aqui as maiores dificuldades que teve com a IA e como as contornou:
* **Problema:** A IA confundiu juros simples mensais com juros compostos na simulação pro rata.
* **Solução:** Adicionei uma instrução explícita no prompt dividindo a taxa mensal de 1% por 30 dias para obter a taxa diária exata antes de multiplicar pelos dias de atraso.
