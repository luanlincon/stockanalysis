# Análise de Performance de Portfólio de Ações (2022-2025)

## 📖 Visão Geral

Este projeto realiza uma análise quantitativa e exploratória de um portfólio de ações focado nos setores de tecnologia e veículos elétricos (EVs). Utilizando dados de mercado de 2022 até a data presente (Agosto de 2025), o objetivo é avaliar e comparar a performance, o risco e as principais características de cada ativo, gerando insights visuais e estatísticos.

O portfólio analisado inclui: **OPEN, NIO, INTC, NVDA, SOFI, PLTR, TSLA, e LCID**.

---

## 🚀 Análises Realizadas

Este notebook conduz o usuário através de uma jornada completa de análise de séries temporais financeiras, incluindo:

* **Análise Descritiva:** Visualização da evolução histórica dos preços e cálculo de retornos diários.
* **Análise de Sazonalidade:** Decomposição da série temporal para identificar componentes de **tendência**, **sazonalidade** e **resíduos**.
* **Análise Comparativa de Performance:**
    * Cálculo e visualização do **Retorno Acumulado Normalizado** para comparar diretamente o crescimento de cada ativo.
* **Análise de Correlação:**
    * **Matriz de Correlação** para entender como os retornos das ações se movem em conjunto.

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3.13.7
* **Bibliotecas Principais:**
    * `pandas`: Para manipulação e análise de dados.
    * `yfinance`: Para obtenção dos dados históricos das ações via API do Yahoo Finance.
    * `matplotlib` & `seaborn`: Para a criação de visualizações estáticas e interativas.
    * `statsmodels`: Para análises estatísticas, como a decomposição de séries temporais.

---

## ⚙️ Como Utilizar e Adaptar

Este projeto foi desenhado para ser flexível. Para analisar seu próprio portfólio de ações, siga os passos:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/luanlincon/stockanalysis.git](https://github.com/luanlincon/stockanalysis.git)
    cd stockanalysis
    ```

2.  **Modifique a lista de ações:**
    Abra o notebook ou script principal e localize a célula de configuração no início. Altere a lista `tickers` para incluir os ativos de sua escolha (utilizando o padrão do Yahoo Finance).

    ```python
    # MODIFIQUE AQUI PARA ANALISAR OUTRAS AÇÕES
    tickers = ['PETR4.SA', 'VALE3.SA', 'ITUB4.SA', 'MGLU3.SA']
    start = '2022-01-01'
    ```

3.  **Execute o código:**
    Execute todas as células do notebook para gerar as análises para o novo portfólio.

---

## 📊 Exemplos de Resultados


**Performance Normalizada das Ações**
![Performance Normalizada](https://github.com/luanlincon/stockanalysis/blob/master/images/perfomance.png)

**Correlação entre ações**
![Correlação](https://github.com/luanlincon/stockanalysis/blob/master/images/correla%C3%A7%C3%A3o.png)

---

## 👤 Autor

* **[Luan Lincon Benjamim]**
* **LinkedIn:** [https://www.linkedin.com/in/luanlinconbenjamim/](https://www.linkedin.com/in/luanlinconbenjamim)
* **GitHub:** [https://github.com/luanlincon](https://github.com/luanlincon)
