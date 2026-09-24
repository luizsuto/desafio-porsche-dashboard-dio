# 🏎️ Dashboard Interativo de Vendas Porsche | Desafio DIO

Este projeto consiste em um dashboard analítico executivo e interativo para análise do desempenho de vendas da **Porsche**, desenvolvido como parte do desafio prático da plataforma **DIO (Digital Innovation One)**.

🔗 **Acesse o Dashboard Online:** [GitHub Pages - Dashboard Porsche](https://luizsuto.github.io/desafio-porsche-dashboard-dio/)

---

## 📌 Objetivos & Perguntas de Negócio

O dashboard foi desenhado para apoiar a tomada de decisão da diretoria comercial e executiva, respondendo a três perguntas-chave de negócio:

1. **Visão Geral & Evolução Histórica de Faturamento:** Como o faturamento total e o volume de vendas evoluíram ao longo dos anos?
2. **Desempenho Geográfico (Top 10 Estados):** Quais estados lideram a receita e o volume de veículos Porsche comercializados no Brasil?
3. **Análise de Portfólio (Top 10 vs. Modelos com Menor Desempenho):** Quais modelos representam os principais pilares de receita e quais demandam estratégias de incentivo ou revisão de estoque?

---

## 🧠 Metodologia & Prompt Utilizado (Engenharia de Prompt)

Para a construção desta solução, foi utilizada a técnica de **Meta-Prompting** (estruturação de contexto e instrução de persona/regra de negócio antes da geração do código).

### **Prompt Utilizado:**
> *"Atue como um Engenheiro de Dados e Desenvolvedor Front-end Sênior. Crie uma aplicação Web em arquivo único HTML (contendo CSS customizado e JavaScript) utilizando Chart.js para criar um dashboard executivo e interativo da Porsche. O dashboard deve possuir tema Dark Mode refinado com paleta de cores da Porsche (Preto, Grafite e Vermelho #D5001C). Inclua cartões de KPIs (Faturamento Total, Volume, Ticket Médio e Modelo Mais Vendido), filtros interativos (Modelo, Estado, Ano e Método de Pagamento) e responda visualmente a 3 perguntas essenciais de negócio: Evolução do Faturamento por Ano, Top 10 Estados por Faturamento/Volume e Comparativo entre os Top 10 Modelos vs. Modelos com Menor Desempenho. Garanta que todos os filtros atualizem dinamicamente os gráficos e indicadores."*

---

## 🧹 Tratamento & Sanitização dos Dados

A base de dados original (`porsche.xlsx`) passou por uma etapa de higienização e estruturação para garantir a consistência das análises:

* **Isolamento de Colunas:** Apenas as colunas sanitizadas relevantes para análise financeira e comercial foram consolidadas no conjunto de dados do dashboard.
* **Tratamento de Inconsistências:** Registros com datas atípicas ou corrompidas foram higienizados mantendo a integridade dos valores financeiros (faturamento e ticket médio).
* **Formatos Monetários:** Os valores de receita foram formatados para o padrão monetário brasileiro (**R$**), garantindo clareza na leitura executiva.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 & CSS3:** Estrutura responsiva e estilização moderna no padrão *Dark Mode Executivo*.
* **JavaScript (ES6+):** Lógica de manipulação de dados, agrupamento e filtragem em tempo real.
* **Chart.js (via CDN):** Renderização dos gráficos interativos de alta performance.
* **GitHub Pages:** Hospedagem gratuita e publicação contínua da aplicação web.

---

## 🚀 Como Executar o Projeto Localmente

1. Clone este repositório:
   ```bash
   git clone [https://github.com/luizsuto/desafio-porsche-dashboard-dio.git](https://github.com/luizsuto/desafio-porsche-dashboard-dio.git)
