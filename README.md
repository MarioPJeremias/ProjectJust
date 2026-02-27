📊 **Project Overview Dashboard**

📌 Descrição do Projeto

O Project Overview Dashboard é um painel analítico desenvolvido no Microsoft Power BI com foco na visualização estratégica de dados financeiros e operacionais relacionados a projetos organizacionais.

**O dashboard permite monitorar:**

- Distribuição de capital

- Orçamento total de projetos

- Custos por departamento

- Metas estratégicas

- Salários

- Orçamento bianual

**Status dos projetos**

Foi concebido para apoiar a tomada de decisão baseada em dados e melhorar a visibilidade financeira da organização.

🖼️ Preview do Dashboard

<img width="1146" height="735" alt="DashboardOver" src="https://github.com/user-attachments/assets/34f97716-e7e5-4636-9854-961ea4c8a331" />

🎯 Funcionalidades
🔹 1. Perfil do Colaborador

Painel lateral com informações do colaborador selecionado:

1. Employee_ID

2. Head Shot (Imagem)

3. Primeiro Nome

4. Último Nome

5. Cargo

6. Departamento

7. Compensação

Permite análise personalizada por funcionário.

🔹 2. Indicadores Principais (KPIs)

💰 Capital Total

📈 Project Budget Total

Visualizados através de gráficos do tipo Donut para demonstrar proporções percentuais.


🔹 3. Tabela de Metas Departamentais

Inclui as seguintes colunas:

1- Department Goals

2- Department Name

3- Soma de Project Cost

4- Soma de Salary Cost

5- Soma de 2-Year Budget

6- Capital

Com totalização automática para análise consolidada.

🔹 4. Análise de Orçamento
📊 Project Budget

Distribuição do orçamento por tipo de projeto:

1- Brand Repositioning

2- Customer Support

3- CRM Integration

4- Market Research

📊 Project Budget by Department

Distribuição do orçamento por departamento:

Human Resources

Sales

IT

🎛️ Filtros Interativos

O dashboard permite filtragem dinâmica por:

Employee_ID

Department_Name

Status (Estatus do Projeto)

Possibilitando análises segmentadas e personalizadas.

🛠️ Tecnologias Utilizadas

Microsoft Power BI

DAX (Data Analysis Expressions)

Modelagem de Dados Relacional

Visualizações Interativas

📐 Modelagem e Métricas (DAX)

Exemplos de medidas utilizadas:

_Total Project Cost = SUM(Projects[Project Cost])_

**Total Salary Cost = SUM(Projects[Salary Cost])**

Total 2 Year Budget = SUM(Projects[2-Year Budget])

Total Capital = SUM(Projects[Capital])

Total Project Budget = SUM(Projects[Project Budget])

Exemplo de Margem:

Lucro Bruto = [Total Project Budget] - [Total Project Cost]

Margem (%) = DIVIDE([Lucro Bruto], [Total Project Budget])

📊 **Objetivo Analítico***

**Este dashboard foi desenvolvido com os seguintes objetivos:**

**Centralizar informações financeiras**

**Monitorar alocação de capital**

**Comparar orçamento vs custos**

**Apoiar decisões estratégicas**

**Avaliar desempenho departamental**

**Melhorar transparência organizacional**


📁 **Estrutura Recomendada do Repositório**

project-overview-dashboard/

│
├
── images/

│   
└── dashboard.png

│
├
── dataset/

│ 
└── project_data.xlsx

│
├
── ProjectOverviewDashboard.pbix

│
└── README.md

🚀 Possíveis Melhorias Futuras

Implementação de Row-Level Security (RLS)

Integração com SQL Server

Atualização automática via API

Versão mobile otimizada

Exportação automática em PDF

Integração com Microsoft Fabric

👤 Autor

Mário Jeremias

Data Analyst | Power BI Developer

Luanda, Angola
