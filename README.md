Análise de Evasão de Clientes (Churn) – Google Colab
Este projeto tem como objetivo realizar uma análise exploratória sobre o comportamento de evasão de clientes (churn) em uma empresa de telecomunicações. Através da manipulação e visualização de dados, buscamos identificar padrões que possam explicar o cancelamento de contratos e propor estratégias para retenção.
 Objetivo
Aplicar técnicas de análise de dados para compreender os fatores que influenciam o churn, utilizando Python e bibliotecas especializadas em um ambiente de notebooks interativos (Google Colab).
 Tecnologias e Ferramentas
- Google Colab – ambiente de desenvolvimento baseado em notebooks
- Python 3.10+
- Pandas – manipulação de dados
- Matplotlib & Seaborn – visualização gráfica
- NumPy – suporte a operações numéricas
- Plotly (opcional) – gráficos interativos
 Estrutura do Projeto
├── data/
│   └── churn_data.json
├── churn_analysis_colab.ipynb
├── README.md


 Etapas da Análise
1. Importação e Normalização dos Dados
- Leitura de arquivo .json com estrutura aninhada
- Normalização com pd.json_normalize para consolidar colunas como account, internet, phone, customer
2. Limpeza e Tratamento
- Padronização de valores categóricos e binários
- Conversão de colunas booleanas
- Criação de colunas derivadas como Total_Pago e conta_diaria
- Validação de consistência entre variáveis relacionadas
3. Análise Exploratória (EDA)
- Visualização da distribuição de churn
- Relação entre churn e variáveis como:
- Tipo de contrato
- Forma de pagamento
- Tempo de relacionamento (tenure)
- Serviços contratados (internet, telefone, suporte técnico)
- Uso de gráficos de barras, histogramas, boxplots e KDE plots
4. Conclusões e Insights
- Contratos mensais e pagamentos via boleto estão fortemente associados ao churn
- Clientes com menor tempo de relacionamento apresentam maior risco
- Serviços adicionais como suporte técnico e segurança online correlacionam com maior retenção
5. Recomendações Estratégicas
- Incentivar contratos de longo prazo com benefícios
- Migrar clientes para métodos de pagamento automáticos
- Oferecer pacotes com serviços adicionais
- Criar campanhas de engajamento para clientes com baixo tenure
✅ Resultados Esperados
A análise fornece subsídios para ações estratégicas de retenção, segmentação de clientes e melhoria da experiência. Os insights obtidos podem ser integrados a modelos preditivos ou utilizados diretamente por equipes de marketing e atendimento.
