# Gestão Financeira e Modelagem de Dados para Escolas: Inadimplência e Réguas de Cobrança

Este repositório ([ricramcezar/miniguia-estudos-notebooklm](https://github.com/ricramcezar/miniguia-estudos-notebooklm)) foi desenvolvido como parte do desafio prático **"Treinando uma IA de Aprendizagem: Explore o Poder do NotebookLM"** na [DIO](https://dio.me). 

O projeto vai além de uma simples entrega de curso: ele foi estruturado sob a ótica de **Modelagem de Dados e Lógica de Negócios**, conectando conceitos de gestão financeira escolar com lógica de programação, análise de dados e engenharia de prompts. O objetivo é criar uma base sólida para a transição de carreira para a área de tecnologia.

---

## 📂 Estrutura do Projeto

A organização de pastas foi estruturada para garantir a separação de responsabilidades e facilitar a curadoria do material utilizado no NotebookLM:

```text
desafio-notebooklm/
├── README.md                  # Apresentação do projeto e guia principal
├── fontes/                    # Curadoria de 3 a 5 fontes (PDFs, links e textos)
│   └── README.md              # Lista detalhada e links das fontes curadas
├── prompts/                   # Engenharia de prompts e logs de testes
│   ├── engenharia-prompts.md  # Testes de prompts, "cicatrizes" e troubleshooting
│   └── reutilizaveis.md       # Prompts prontos para futuras consultas/revisões
└── miniguia/                  # Entrega final consolidada do estudo
    ├── resumos.md             # Resumos estruturados sobre inadimplência e lógica de cálculo
    └── glossario.md           # Conceitos de gestão financeira e dados escolares
```

---

## 🎯 Contexto e Objetivos

### O Problema de Negócio
As instituições de ensino enfrentam desafios complexos de fluxo de caixa decorrentes da inadimplência. Para mitigar esse problema de forma eficiente e humanizada, é preciso estruturar uma **régua de cobrança automática** com base no comportamento de pagamento dos clientes.

### Objetivos de Aprendizado e Transição
- **Lógica e Modelagem:** Compreender e traduzir regras de negócios financeiras (juros, multas, dias de atraso) em lógica aplicável para banco de dados ou código de programação.
- **Engenharia de Prompts:** Utilizar o NotebookLM como parceiro de estudos para sintetizar informações e simular cenários de cálculo.
- **Domínio de Negócio:** Dominar conceitos de *fintechs*, réguas de cobrança e KPIs de inadimplência aplicados ao mercado educacional.

---

## 📚 Curadoria de Fontes (NotebookLM)

Foram estruturadas e selecionadas fontes locais e externas para alimentar o caderno no NotebookLM. O detalhamento completo está disponível em [`fontes/README.md`](./fontes/README.md):

### Fontes de Dados Locais (.txt)
1. **[Legislação de Inadimplência Escolar no Brasil](./fontes/fonte-01-legislacao-inadimplencia.txt):** Leis Federais (Lei nº 9.870/99) e Código de Defesa do Consumidor.
2. **[Aging List e Réguas de Cobrança Escolar](./fontes/fonte-02-aging-list-regua.txt):** Boas práticas de segmentação de devedores e canais de contato.
3. **[Lógica de Cálculo de Encargos e Modelagem de Dados](./fontes/fonte-03-logica-calculo-modelo.txt):** Lógica matemática de juros *pro rata die* e modelo relacional de banco de dados.

### Blogs de Referência e Artigos
4. **[Blog Sponte - Régua de cobrança para combater a inadimplência escolar](https://www.sponte.com.br/blog/regua-de-cobranca):** Planejamento e ações de réguas de cobrança na prática.
5. **[Blog Neofin - Aging list: entenda o que é, principais benefícios e como fazer](https://www.neofin.com.br/blog/aging-list):** Análise e interpretação de relatórios de envelhecimento de contas.

### Vídeos do YouTube
6. **[Como reduzir a inadimplência escolar, sem perder alunos](https://youtu.be/K4Oww2Cg4cE?si=3MMnJFI1sKxH7VsP):** Cobrança humanizada e relacionamento.
7. **[Inadimplência Escolar - Como realizar a cobrança](https://www.youtube.com/live/EY1CZM8pRtA?si=3lguObvpfHVUkLP6):** Live sobre fluxos práticos e perfis de atrasos.
8. **[Régua de cobrança e controle de inadimplência escolar](https://youtu.be/8Zq2_ySnirQ?si=d-2zUgI8dhdxKNXf):** Aplicação prática e automação de cobranças recorrentes.
9. **[6 dicas para acabar com a inadimplência escolar](https://youtu.be/QwaEA7kMEMQ?si=K3fsuLuuCt2OhbM_):** Ações diretas e rotina financeira escolar.

---

## 🧠 Engenharia de Prompts & "Cicatrizes"

A seção de engenharia de prompts documenta a jornada de refinamento das perguntas para extrair o melhor raciocínio lógico do NotebookLM. 

Os testes, variações de prompts e soluções de problemas (*troubleshooting*) estão documentados detalhadamente em [`prompts/engenharia-prompts.md`](./prompts/engenharia-prompts.md).

### Exemplo de Prompt de Raciocínio Testado:
> *"Como calcular a taxa de inadimplência escolar (ex: Over 30, Over 60) a partir de uma tabela com vencimentos e pagamentos?"*

---

## 🚀 Miniguia de Estudos (Entrega Final)

O resultado prático deste estudo está dividido em duas partes fundamentais para a fixação do conhecimento:

1. **Resumos Estruturados ([`miniguia/resumos.md`](./miniguia/resumos.md)):**
   - Lógica de cálculo de taxas de atraso.
   - Fluxograma de réguas de cobrança com alertas.
   - Aplicação de regras fiscais/legais sobre juros e multas de mensalidades escolares.
   - **Implementações Técnicas:** Query SQL para consultas em tempo real e função JavaScript para lógica de backend/APIs.
   
2. **Glossário Técnico ([`miniguia/glossario.md`](./miniguia/glossario.md)):**
   - Termos financeiros: *Multa moratória*, *Juros pro rata*, *Inadimplência ativa*, *Aging List*.
   - Termos de tecnologia/dados: *Campos calculados*, *Regras condicionais*, *Gatilhos (Triggers)*.

3. **Prompts Reutilizáveis ([`prompts/reutilizaveis.md`](./prompts/reutilizaveis.md)):**
   - Prompts otimizados para testar novos cenários e realizar revisões periódicas do tema.
