# Análise Exploratória de Dados Agronômicos e Climáticos (AgTech)

Este repositório contém uma suíte de análises exploratórias de dados (EDA) e pipelines de pré-processamento desenvolvidos em Python. O projeto abrange desde o monitoramento de variáveis meteorológicas e controle de irrigação via sensores até a otimização de solos e o acompanhamento territorial de safras agrícolas.

---

## Funcionalidades e Etapas da Análise

### 1.  Processamento e Visualização de Dados Climáticos
- **Tratamento e Limpeza:** Conversão de formatos de datas (padrão PT-BR), padronização de decimais e imputação de valores ausentes pela média.
- **Análise de Séries Temporais:** Monitoramento contínuo de 17 variáveis meteorológicas (temperatura, umidade, vento, radiação, chuva).
- **Média Móvel e Heatmaps:** Suavização das oscilações diárias com Média Móvel de 7 dias e análise sazonal de temperaturas por mês/ano.

### 2.  Monitoramento Inteligente de Irrigação
- **Gatilho de Irrigação:** Análise de correlação entre umidade do solo e temperatura para ativação de bombas de água.
- **Alertas de Limite Crítico:** Visualização gráfica da umidade do solo com sinalização de patamares críticos de seca.

### 3.  Otimização de Culturas e Solos
- **Solo Ideal por Cultura:** Identificação do tipo de solo que maximiza a produtividade média de cada cultura.
- **Matriz de Frequência:** Mapeamento da densidade de plantio por combinação de cultura e tipo de solo.

### 4.  Gestão Territorial e Logística de Safras (SIGEF)
- **Evolução Histórica:** Acompanhamento do crescimento da área plantada em hectares por safra e por estado (UF).
- **Logística de Sementes:** Mapeamento dos Top 10 municípios com maior volume de sementes reservadas.
- **Variedades Líderes:** Identificação dos Top 20 cultivares mais expressivos por espécie agrícola.
- **Validação de Planejamento:** Comparação entre a área estimada e a área efetivamente plantada.

---

##  Tecnologias Utilizadas

- **Linguagem:** Python 3.x
- **Manipulação de Dados:** `pandas`
- **Visualização de Dados:** `matplotlib`, `seaborn`
- **Ambiente:** Google Colab / Jupyter Notebooks
