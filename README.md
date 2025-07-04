Telecom X – Previsão de Evasão de Clientes (Churn Prediction)
Descrição do Projeto
Este projeto tem como objetivo prever a evasão de clientes (churn) da empresa Telecom X utilizando técnicas de Machine Learning. Através da análise dos dados históricos dos clientes, desenvolvemos modelos preditivos que identificam quais clientes têm maior probabilidade de cancelar seus serviços. Com isso, a empresa pode antecipar riscos e agir para melhorar a retenção.

Estrutura do Projeto
Parte 1 – Análise Exploratória: Investigação dos dados para entender o perfil dos clientes e identificar padrões relevantes para a evasão.

Parte 2 – Modelagem Preditiva: Preparação dos dados, seleção de variáveis, construção e avaliação de modelos de classificação para prever churn.

Relatório: Análise detalhada dos resultados, importância das variáveis e recomendações estratégicas para redução da evasão.

Tecnologias Utilizadas
Python

Pandas, NumPy (manipulação e tratamento de dados)

Scikit-learn (modelagem e avaliação)

Matplotlib, Seaborn (visualização de dados)

Jupyter Notebook

Como Rodar o Projeto
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/seu-repositorio.git
Instale as dependências (recomenda-se usar um ambiente virtual):

bash
Copiar
Editar
pip install -r requirements.txt
Execute os notebooks em ordem para reproduzir a análise e os modelos:

Parte1_AnaliseExploratoria.ipynb

Parte2_ModelagemPreditiva.ipynb

Resultados
Modelos treinados: Regressão Logística e Random Forest.

Melhor modelo (Regressão Logística) atingiu Acurácia de ~79% e AUC-ROC de ~84%.

Variáveis mais influentes na evasão: tipo de contrato, cobrança mensal, suporte técnico, serviços de proteção e tempo de cliente.

