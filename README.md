# Algerian Forest Fires Data Analysis & EDA

Este repositório contém o processo de limpeza de dados e a análise exploratória (EDA) do **Algerian Forest Fires Dataset**[cite: 12]. O conjunto de dados abrange observações de duas regiões da Argélia (Bejaia e Sidi-Bel Abbes) coletadas entre junho e setembro de 2012[cite: 12].

## 📊 Sobre o Conjunto de Dados
O dataset contém 244 instâncias com registros meteorológicos e índices do sistema FWI (Fire Weather Index)[cite: 12]:
* **Data:** Dia, mês (junho a setembro) e ano (2012)[cite: 12]
* **Variáveis Meteorológicas:** Temperatura, Umidade Relativa (RH), Velocidade do Vento (Ws) e Chuva (Rain)[cite: 12]
* **Componentes FWI:** FFMC, DMC, DC, ISI, BUI e FWI[cite: 12]
* **Classes:** Classificação entre ocorrência de incêndio (`fire`) e ausência de incêndio (`not fire`)[cite: 12]

## 🛠️ Etapas do Projeto
1. **Limpeza de Dados:** Tratamento de valores ausentes, divisão e criação da coluna de regiões, remoção de espaços em branco nos nomes das colunas e conversão de tipos de dados para inteiros e flutuantes.
2. **Análise Exploratória (EDA):** Geração de gráficos estatísticos, análise de proporção de classes por meio de gráficos de pizza e estudo da matriz de correlação entre as variáveis climáticas e os índices de incêndio.

## 🚀 Tecnologias Utilizadas
* Python[cite: 12]
* Pandas[cite: 12]
* NumPy[cite: 12]
* Matplotlib[cite: 12]
* Seaborn[cite: 12]
