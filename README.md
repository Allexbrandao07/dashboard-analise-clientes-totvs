# Análise Estratégica de Clientes TOTVS - FIAP Challenge

Este projeto foi desenvolvido como parte do desafio proposto pela **TOTVS** em parceria com a **FIAP**.  
O objetivo principal é transformar um conjunto de dados brutos sobre clientes, contratos e pesquisas de satisfação em um **dashboard estratégico e interativo no Power BI**.  

O dashboard visa fornecer **insights acionáveis** para a liderança da TOTVS, com foco em métricas de **receita, retenção, satisfação e análise de portfólio de produtos**.

> Importante: Os dados utilizados neste projeto são **sintéticos** e passaram por um processo de **pré-processamento, limpeza e enriquecimento na ferramenta de ETL KNIME** antes de serem carregados no Power BI para a modelagem e visualização.

---

## Dashboard Interativo
O resultado final do projeto é um **dashboard navegável e dinâmico**, publicado no serviço do Power BI.

[Clique aqui para acessar o dashboard interativo](https://app.powerbi.com/view?r=eyJrIjoiZmIzMWFmOWUtNzRhMi00ZmM3LWE2MTctMmI5MDE1ZTYwOTBmIiwidCI6IjExZGJiZmUyLTg5YjgtNDU0OS1iZTEwLWNlYzM2NGU1OTU1MSIsImMiOjR9&embedImagePlaceholder=true)

---

## Estrutura do Dashboard
O dashboard foi estruturado em **cinco páginas**, cada uma com um objetivo analítico claro, criando uma narrativa que vai do macro para o micro:

1. **Sumário Executivo** → Visão geral da saúde do negócio.  
2. **Análise de Receita** → Indicadores financeiros detalhados.  
3. **Análise de Clientes** → Perfil, comportamento e ciclo de vida.  
4. **Análise de Produtos** → Performance do portfólio.  
5. **Jornada do Cliente** → Diagnóstico de satisfação por ponto de contato.  

---

## Análise das Páginas, Métricas e Visuais

### 1. Sumário Executivo
**Objetivo:** Fornecer à liderança uma visão rápida dos indicadores mais críticos.  

**KPIs e Métricas:**
- **MRR Total (Receita Recorrente Mensal):** Indicador-chave para empresas SaaS.  
- **Taxa de Churn:** Mede a retenção e capacidade de crescimento sustentável.  
- **Score NPS Relacional:** Índice de lealdade e satisfação geral (-100 a 100).  

**Visuais:**
- Segmentação por Segmento (botões horizontais).  
- Tendência de MRR (gráfico de linhas).  
- MRR por Segmento (gráfico de barras).  

---

### 2. Análise de Receita
**Objetivo:** Detalhar a composição e as tendências da receita.  

**KPIs e Métricas:**
- **ARPA (Receita Média por Conta):** Perfil médio de faturamento.  
- **MRR Perdido com Churn:** Impacto monetário dos cancelamentos.  

**Visuais:**
- Composição do MRR ao longo do tempo (áreas empilhadas).  
- Top 10 Estados por MRR (barras).  
- Composição do MRR por Segmento (rosca).  

---

### 3. Análise de Clientes
**Objetivo:** Entender perfil, saúde e comportamento da base de clientes.  

**KPIs e Métricas:**
- **Total de Clientes Ativos.**  
- **Total de Novos Clientes (12M).**  
- **Tempo Médio de Vida (dias).**  

**Visuais:**
- **Análise de Risco (dispersão):** Cruza MRR × satisfação (NPS).  
- **Priorização de Contas:** Top 10 clientes por MRR.  
- **Análise de Retenção:** Por tempo de casa (barras).  

---

### 4. Análise de Produtos
**Objetivo:** Avaliar a performance e adoção do portfólio.  

**KPIs e Métricas:**
- **Contagem de Produtos Únicos.**  
- **Adoção Média de Produtos.**  

**Visuais:**
- Popularidade vs. Rentabilidade (barras lado a lado).  
- Top 10 / Bottom 10 Produtos Mais Populares.  

---

### 5. Jornada do Cliente
**Objetivo:** Diagnosticar satisfação em cada ponto de contato.  

**KPIs e Métricas:**
- **NPS Transacional:** Por ponto de contato (Suporte, Implantação, etc.).  
- **Média da Nota:** Submétrica detalhada (0 a 10).  

**Visuais:**
- Visão Geral da Jornada (barras comparativas).  
- Análise Detalhada (barras dinâmicas interativas).  

---

## 🛠️ Ferramentas e Tecnologias
- **KNIME:** Pré-processamento, limpeza e ETL.  
- **Power BI Desktop:** Modelagem, métricas DAX e visuais.  
- **DAX (Data Analysis Expressions):** Criação de KPIs customizados.  
- **Power Query:** Ajustes finais e unificação de fontes.    

