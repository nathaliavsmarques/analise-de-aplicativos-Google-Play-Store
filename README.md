📊 Análise de Aplicativos da Google Play Store

📌 Descrição do Projeto
Este projeto consiste em uma análise exploratória de dados (EDA) utilizando um dataset público da Google Play Store, com o objetivo de compreender padrões de distribuição, engajamento e avaliação dos aplicativos disponíveis na plataforma.

O estudo aborda aspectos como:
* Distribuição de aplicativos por categoria;
* Comparação entre aplicativos gratuitos e pagos;
* Relação entre número de instalações e avaliações;
* Análise de engajamento dos usuários;
* Impacto do modelo de monetização na percepção de qualidade;

📂 Fonte dos Dados
Dataset:[ Google Play Store Apps](https://www.kaggle.com/lava18/google-play-store-apps)

- Autor: Lavanya Gupta;
- Plataforma: Kaggle;
- Período: Fevereiro de 2019;


🛠️ Tecnologias Utilizadas
- Python;
- Pandas – manipulação e limpeza dos dados; 
- Matplotlib – visualizações gráficas;
- Jupyter Notebook;

🧹 Tratamento dos Dados
As principais etapas de preparação dos dados incluíram:
- Remoção de colunas não relevantes para a análise;
- Tratamento de valores ausentes;
- Identificação e remoção de outliers;
- Conversão de tipos de dados (installs e price);
- Remoção de registros duplicados.

📈 Principais Análises Realizadas
- Comparação entre número de aplicativos e volume total de instalações por categoria;
- Identificação dos aplicativos mais baixados;
- Análise da taxa de engajamento (reviews vs installs);
- Comparação de avaliações médias entre aplicativos pagos e gratuitos;
- Avaliação do comportamento do usuário em diferentes segmentos.

💡 Principais Insights
- A categoria GAME lidera em volume de instalações, apesar de não ser a maior em número de aplicativos;
- Aplicativos gratuitos concentram a maior parte dos usuários e avaliações, refletindo seu alcance massivo;
- Aplicativos pagos apresentam, em média, avaliações ligeiramente superiores, indicando um engajamento mais qualificado;
- Mesmo aplicativos com bilhões de downloads apresentam taxas de avaliação inferiores a 3%.


⚠️ Limitações
- Os dados de instalações fornecidos pela Google Play Store são apresentados em faixas mínimas, o que impede uma ordenação precisa entre aplicativos dentro da mesma faixa de downloads;
- Dataset de 2019, o que pode não demostrar o atual perfil dos usuários da play store.






















