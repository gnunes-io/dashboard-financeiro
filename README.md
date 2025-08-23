# 📊 Relatório Financeiro - Dash Descritivo para Análise do Exercício

## 📌 Descrição
Este relatório em **Power BI** apresenta uma análise **financeira consolidada**, com foco no acompanhamento de **Receita, Custo, Despesas e Lucro**.  
O painel foi desenvolvido para fornecer **insights estratégicos** à **Diretoria Financeira**, apoiando o monitoramento do desempenho econômico e a priorização de ações para eficiência e rentabilidade.

## 🚀 Objetivos do Relatório
- Monitorar a **receita mensal** comparando **Ano Atual vs Ano Anterior (YoY)**.
- Avaliar a **composição de custos e despesas** e seu peso sobre a receita.
- Acompanhar **KPIs** principais (Receita, %YoY, %Receita por Custo/Despesa, Lucro).
- Identificar **participação por contas** (operacional vs não operacional) e **por clientes**.
- Analisar a **distribuição dos pagamentos** (**Fixo x Variável** e por lançamento).
- Fornecer **visão consolidada** com possibilidade de **análise granular**.

## 📊 Imagens do Relatório
![Dashboard Financeiro](./dash-financeiro.PNG)

## 🗂️ Fontes de Dados
- **SQL Server** → Base contábil/financeira, *views* para ETL e integração.
- **Planilhas Excel (.xlsx)** → Custos operacionais e despesas administrativas.
- **Arquivos CSV (.csv)** → Complemento de dados transacionais.

## 🔄 Atualização dos Dados
- Frequência: **Diária** (agendada no **Power BI Service**).

## 📈 Funcionalidades
- **Comparação temporal**: Ano atual vs ano anterior por mês (com variação %).
- **KPIs financeiros**: Receita, Custo, Despesa e Lucro (com % sobre a receita).
- **Receita por Conta**: **Operacional vs Não Operacional**.
- **Receita por Cliente**: ranking dos principais clientes.
- **Pagamentos**: **por Tipo** (fixo x variável) e **por Lançamento**.
- **Filtros dinâmicos**: **Ano**, **Mês** e **Conta**.

## 👥 Público-Alvo
- **Diretoria Financeira** – visão estratégica e consolidada.
- **Gerência Administrativa/Controladoria** – gestão de custos e despesas.
- **Analistas Financeiros** – detalhamento de pagamentos e clientes.

## 🖼️ Exemplos de Visualizações
- **Receita Ano Anterior vs Atual por mês** (barras com variação percentual).
- **Receita por Conta** (barra empilhada: operacional x não operacional).
- **Receita por Cliente** (ranking dos maiores contribuintes).
- **Pagamento por Tipo** (fixo x variável, % e valores).
- **Pagamento por Lançamento** (categorias como custo e despesa).

## 📌 Tecnologias Utilizadas
- **Power BI** (ETL, modelagem, DAX, visualização).
- **SQL Server** (armazenamento, *views* e consultas).
- **Excel / CSV** (dados auxiliares e cadastros).

## 📂 Estrutura do Relatório
1. **Visão Geral** → KPIs principais (Receita, Custo, Despesa, Lucro) e variações.
2. **Receita Ano Atual vs Anterior** → Comparativo mensal (YoY).
3. **Receita por Conta e Cliente** → Composição e concentração.
4. **Pagamentos** → Distribuição por tipo (fixo/variável) e por lançamento.
5. **Indicadores Estratégicos** → Percentuais e relações para tomada de decisão.
