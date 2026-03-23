# 📊 Dashboard Financeiro: Análise de Resultados e Fluxo de Caixa

## 📌 Visão Geral
Solução *end-to-end* para controle de KPIs financeiros. Este projeto engloba: ETL de planilhas Excel (limpeza e padronização), modelagem relacional, criação de medidas DAX (Receita, Custos, Lucro) e DataViz focado em UX/UI. Destaque para a navegação fluida com menu lateral, gráfico de Cascata para Fluxo de Caixa e matriz de resultados com formatação condicional. Uma ferramenta analítica robusta que vai do macro ao detalhe.

## 📷 Telas do Projeto

### 1. Home - Recepção e Navegação
### 2. Visão Geral - KPIs e Tendências
### 3. Detalhamento - Fluxo de Caixa Mensal
## 🛠️ Processo de Desenvolvimento

O projeto foi construído passando por todas as etapas fundamentais de inteligência de negócios e análise de dados:

* **ETL (Power Query):** Extração de dados de múltiplos arquivos de Excel contendo históricos de pagamentos, recebimentos e cadastros. Realização de limpeza de dados, tratamento de valores nulos e padronização de tipagem.
* **Modelagem de Dados:** Construção de um modelo relacional (Star Schema) conectando as tabelas fato (movimentações financeiras) com as tabelas dimensão (calendário, clientes e tipos de conta).
* **Cálculos e Métricas (DAX):** Desenvolvimento de medidas analíticas avançadas para acompanhamento de Receita, Custos, Despesas Operacionais e Margem de Lucro.
* **Data Visualization:** Foco em usabilidade e design da interface. Utilização de gráficos de cascata (Waterfall) para demonstrar a variação do saldo, matrizes com formatação condicional e segmentadores de dados dinâmicos.

## 🚀 Como testar este projeto localmente

Para interagir com os filtros, *tooltips* e explorar a estrutura dos dados a fundo:

1. Faça o download do arquivo `dashboard_financeiro.pbix` presente na raiz deste repositório.
2. Certifique-se de ter o **Power BI Desktop** instalado na sua máquina (disponível gratuitamente para Windows).
3. Abra o arquivo e navegue livremente pelo menu lateral do dashboard.
