# Glossário de Conceitos

Dicionário prático unindo os mundos de Finanças Educacionais e Modelagem de Dados/Lógica de Programação.

## 💸 Conceitos Financeiros (Negócio)

* **Multa Moratória:** Penalidade cobrada pelo atraso no pagamento. Pelo Código de Defesa do Consumidor (CDC) brasileiro, é limitada a **2%** do valor da prestação para contratos escolares e de consumo.
* **Juros de Mora (Juros Moratórios):** Indenização devida pelo atraso no pagamento de uma obrigação. Geralmente estipulada em **1% ao mês**.
* **Pro Rata Die:** Expressão latina que significa "proporcional ao dia". É o cálculo de juros calculado dia a dia (ex: 1% dividido por 30 dias = 0,033% ao dia).
* **Aging List (Balanço de Idade das Contas):** Relatório financeiro que agrupa as contas a receber pelos dias em atraso (ex: 1-15 dias, 16-30 dias, 31-60 dias). Essencial para modelagem de risco.
* **Régua de Cobrança:** Fluxo automatizado de comunicações enviadas ao cliente antes, no dia e após o vencimento de uma fatura para incentivar o adimplemento.

## 💻 Conceitos de Dados e Lógica (Tecnologia)

* **Campos Calculados:** Campos em bancos de dados ou relatórios cujos valores dependem de fórmulas baseadas em outros campos (ex: `dias_atraso = data_pagamento - data_vencimento`).
* **Triggers (Gatilhos):** Bloco de código associado a um evento no banco de dados ou sistema (ex: disparar um alerta assim que um boleto atinge 5 dias de atraso).
* **Condicional (IF/ELSE):** Estrutura lógica essencial para aplicar a régua de cobrança (ex: `SE dias_atraso > 2 ENTÃO cobrar_multa = TRUE SENÃO cobrar_multa = FALSE`).
* **Modelagem de Entidades:** Estruturação das tabelas e relacionamentos necessários para o sistema (ex: tabelas `Alunos`, `Mensalidades`, `Pagamentos` e `HistoricoCobrancas`).
