\# 📄 Data Description – Salesforce CRM Analytics



\## 🎯 Objetivo

Descrever os dados utilizados no projeto de análise de performance de vendas, detalhando os principais objetos do Salesforce e os campos relevantes para as análises de negócio.



Os dados representam um cenário fictício, porém realista, de uma empresa B2B que utiliza Salesforce como CRM.



---



\## 🧱 Fonte de Dados

\- Plataforma: Salesforce

\- Tipo de dados: CRM (Customer Relationship Management)

\- Granularidade: Leads, oportunidades e vendedores

\- Período de análise: Dados históricos simulados



---



\## 🔹 Objetos do Salesforce Utilizados



\### 1️⃣ Lead

Representa potenciais clientes que ainda não entraram no funil de vendas.



\*\*Campos principais:\*\*

\- Lead ID  

\- Data de criação  

\- Origem do lead (Lead Source)  

\- Status do lead  

\- Responsável (Owner)  



\*\*Uso na análise:\*\*

\- Análise de geração de leads

\- Conversão de leads em oportunidades

\- Qualidade do funil comercial



---



\### 2️⃣ Account

Representa empresas ou clientes cadastrados no CRM.



\*\*Campos principais:\*\*

\- Account ID  

\- Nome da conta  

\- Segmento / Indústria  

\- Data de criação  



\*\*Uso na análise:\*\*

\- Análise de clientes

\- Receita por cliente

\- Segmentação de contas



---



\### 3️⃣ Opportunity

Representa oportunidades comerciais em andamento ou finalizadas.



\*\*Campos principais:\*\*

\- Opportunity ID  

\- Account ID  

\- Data de criação  

\- Data de fechamento  

\- Estágio (Stage)  

\- Valor (Amount)  

\- Status (Ganha / Perdida)  

\- Responsável (Owner)  



\*\*Uso na análise:\*\*

\- Funil de vendas

\- Receita total e por período

\- Taxa de ganho (win rate)

\- Ticket médio

\- Tempo de fechamento



---



\### 4️⃣ User (Vendedores)

Representa os usuários responsáveis pelas oportunidades.



\*\*Campos principais:\*\*

\- User ID  

\- Nome do vendedor  

\- Perfil / Função  



\*\*Uso na análise:\*\*

\- Performance individual de vendedores

\- Receita por vendedor

\- Comparação de resultados entre membros do time



---



\## 🔗 Relacionamento entre os Dados

\- Um \*\*Lead\*\* pode ser convertido em uma \*\*Opportunity\*\*

\- Uma \*\*Opportunity\*\* está associada a uma \*\*Account\*\*

\- Uma \*\*Opportunity\*\* possui um \*\*User\*\* responsável

\- Uma \*\*Account\*\* pode ter múltiplas oportunidades



---



\## 📊 Considerações sobre Qualidade dos Dados

\- Campos nulos ou inconsistentes podem impactar análises

\- Datas são fundamentais para análises temporais

\- Estágios do funil precisam estar bem definidos

\- Valores devem estar padronizados para cálculo de receita



---



\## 🚀 Próximos Passos

\- Validação de consistência dos dados

\- Criação de métricas derivadas (KPIs)

\- Integração com Power BI para análises avançadas



