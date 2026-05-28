# 🛒 SuperStore — Análise de Eficiência Logística e Margem de Lucro

---

## 📋 Sobre o Projeto

Este projeto analisa a eficiência operacional da **SuperStore**, uma grande rede de varejo global, com foco no equilíbrio estratégico entre o faturamento bruto e os custos logísticos associados à operação.

O objetivo principal foi diagnosticar os gargalos críticos que comprimem a margem de lucro líquido da organização, mapeando padrões de comportamento temporal e fornecendo recomendações acionáveis para a alta liderança executiva.

A investigação estruturou-se em torno de três pilares fundamentais:
- **Identificação de flutuações sazonais de receita:** Análise da queda histórica de faturamento na transição de final de ano.
- **Mapeamento de assimetrias financeiras por categoria:** Investigação do impacto do custo de envio na margem de lucro.
- **Investigação geooperacional de anomalias:** Identificação de praças específicas (cidades) que operam em déficit logístico.

---

## 🔗 Links Oficiais do Projeto

| Recurso | Link de Acesso |
|---|---|
| 📊 **Dashboard Interativo (Looker Studio)** | [Acessar Dashboard](https://datastudio.google.com/reporting/fe3e09e0-c357-4c13-ad85-9f62421c0569) |
| 💻 **Notebook de Processamento (Google Colab)** | [Acessar Notebook Python](https://colab.research.google.com/drive/1PUMKjo7TtsDaZkb44kYLPQ43JNMf7ZP6?usp=sharing) |
| 🤖 **Agente de IA Customizado (Gemini)** | [Acessar Custom Gem](https://gemini.google.com/gem/ccf9ac5cca37/9519d2b4f27d99b2) |
| 📄 **Ficha Técnica Detalhada (PDF)** | [Visualizar na Pasta Documents](Documents/Ficha_Tecnica_SuperStore.pdf) |

---

## 🛠️ Tecnologias e Metodologia Aplicada

### 1. Engenharia e Limpeza de Dados (Python)
Todo o processo de **ETL (Extract, Transform, Load)** foi inteiramente codificado em Python utilizando o ecossistema do Google Colab. As principais etapas incluíram:
- **Tratamento de Missing Values (NaNs):** Identificação e tratamento de registros nulos para garantir a consistência estatística.
- **Unificação de Bases (Merge):** Consolidação de tabelas relacionais de pedidos e envios para correlacionar o lucro com o esforço de entrega.
- **Manipulação Temporal:** Criação de colunas derivadas (`ano_mes`) para identificação precisa de tendências de sazonalidade.

### 2. Modelagem Visual e Storytelling (Looker Studio)
Desenvolvimento de um dashboard para análise rápida por parte dos tomadores de decisão, focando nos indicadores de *Sales*, *Profit* e *Shipping Cost*.

### 3. Governança e Inteligência Artificial (Generative AI)
Este projeto utilizou uma abordagem pioneira de **Governança de IA**, contando com o suporte de um **Gem personalizado no Gemini** para estruturação da narrativa técnica, refinamento dos insights de negócios e garantia de conformidade lógica nas análises de mercado.

---

## 🎯 Principais Insights de Negócio Encontrados

1. **A Ressaca de Janeiro:** Identificação de uma queda acentuada de aproximadamente 60% nas vendas globais na transição de dezembro para janeiro, exigindo uma estratégia ativa de queima de estoque e campanhas promocionais antecipadas.
2. **Inversão Crítica em Móveis (Furniture):** A categoria de móveis apresenta alto faturamento, porém o seu custo logístico consome a maior parte da margem gerada. Cidades densas como **New York City** e **Gold Coast** apresentaram severos ralos logísticos no modelo de *Last-Mile*.
3. **Assimetria de Descontos no Home Office:** O segmento de Home Office consome taxas de desconto elevadas (média de 14.7%) sem o retorno proporcional em margem líquida, sugerindo a necessidade de revisão da política de descontos automáticos.

---

## 📌 Pergunta Crítica para Reflexão dos Acionistas
> *"Se a SuperStore cortar a comercialização de produtos com margem negativa (como mesas e cadeiras com frete subsidiado) em praças críticas como Nova York, o faturamento bruto consolidado apresentará uma redução imediata, porém a margem de rentabilidade líquida da empresa subirá de forma expressiva. Para a governança de longo prazo da SuperStore perante os acionistas, o foco deve ser a sustentação de um faturamento inflado por operações ineficientes ou a maximização da margem operacional líquida através de uma contração estratégica e saudável?"*

---

## 🤖 Como Reproduzir esta Análise
1. Acesse o [Notebook no Google Colab](https://colab.research.google.com/drive/1PUMKjo7TtsDaZkb44kYLPQ43JNMf7ZP6?usp=sharing).
2. Execute as células em ordem cronológica para gerar a base tratada.
3. Utilize o arquivo estruturado final para conexão com ferramentas de BI de sua preferência.


**Autora:** Bruna Medeiros Brandão  
**Contexto:** Projeto Prático — Curso Análise de Dados - Laboratória  
**Data:** Maio de 2026
