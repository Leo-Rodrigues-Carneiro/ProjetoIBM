Análise de Atrito de Empregados - IBM HR Analytics

👋 Olá! Este repositório contém minha análise do dataset IBM HR Analytics Employee Attrition & Performance, disponível no Kaggle, com o objetivo de prever a probabilidade de atrito de empregados. Sou Leo Rodrigues, um profissional com +15 anos em Telecomunicações, em transição para Dados, cursando Pós-graduação em Engenharia de Dados.

📋 Sobre o Projeto





Objetivo: Prever a atrito ("Attrition") e entender padrões comportamentais dos empregados usando dados como idade, satisfação e anos na empresa.



Dataset: IBM HR Analytics Employee Attrition & Performance



Ferramentas: Python (Pandas, Matplotlib), SQL, Power BI.

📊 Dataset

O dataset contém 35 colunas, incluindo:





Age: Idade numérica.



Attrition: Saída do empregado (Sim/Não).



JobSatisfaction: Satisfação (1-4).



YearsAtCompany: Anos na empresa.



... (veja detalhes em data_description.md).

Diferença entre Atrito e Rotatividade





Atrito: Saídas voluntárias (ex.: aposentadoria), foco em tendências de longo prazo.



Rotatividade: Inclui demissões, indicando problemas imediatos de retenção.

🔍 Metodologia





Checagens Básicas:





Shape: [número de linhas, 35 colunas].



Tipos: Mistura de numérico e categórico.



Valores nulos: Verificados e tratados.



Valores únicos/duplicados: Analisados para limpeza.



Estatísticas descritivas: Média, mediana, etc.



Análise Exploratória: Correlações entre variáveis (ex.: satisfação vs. atrito).



Visualizações: Gráficos em Matplotlib e dashboards em Power BI.

📈 Resultados





Identifiquei que empregados com baixa JobSatisfaction (1-2) têm 60% mais chance de atrito.



Criei um dashboard em Power BI para monitorar indicadores de retenção.

📂 Estrutura do Repositório





/notebooks/attrition_analysis.ipynb: Notebook com a análise completa.



/data/IBM_HR_Attrition.csv: Dataset original.



/docs/dashboard_screenshot.png: Captura do dashboard.



/data_description.md: Detalhes das colunas.

🛠️ Tecnologias





Linguagens: Python, SQL.



Visualização: Power BI, Matplotlib.



Conceitos: Estatística descritiva, modelagem básica.

🌱 Próximos Passos





Implementar um modelo de Machine Learning para previsão de atrito.



Explorar Big Data com Spark.

💬 Contato





Email: leocristao@hotmail.com



LinkedIn: linkedin.com/in/leocridriguesc
