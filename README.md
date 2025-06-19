# Dashboard de Vendas Interativo 📊

[Clique aqui para executar o App no Streamlit](https://rodrslv-dashboard-vendas.streamlit.app/)  <img align="center" alt="Rod-Python" height="15" width="20" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/streamlit/streamlit-original.svg">

Este projeto apresenta um **Dashboard de Vendas dinâmico e interativo** desenvolvido em Python, utilizando as bibliotecas `Streamlit`, `Pandas` e `Plotly Express`. O objetivo principal é fornecer aos **gerentes de vendas** uma ferramenta visual e intuitiva para **monitorar a performance de vendas**, **identificar tendências** e, consequentemente, auxiliar na **tomada de decisões mais informadas e estratégicas**.

---

## 🚀 Funcionalidades Principais

O dashboard é estruturado em três abas principais, cada uma oferecendo uma perspectiva crucial sobre os dados de vendas:

* **Receita:** Analise a distribuição da receita por estado (com um mapa interativo), o desempenho mensal ao longo dos anos e a contribuição de cada categoria de produto.
* **Quantidade de Vendas:** Monitore o volume de vendas por estado (também com um mapa), a quantidade de vendas mensal e o desempenho das categorias de produtos em termos de unidades vendidas.
* **Vendedores:** Avalie a performance individual dos vendedores, identificando os que mais contribuem para a receita e para a quantidade de vendas.

Além disso, o dashboard conta com **filtros interativos** na barra lateral, permitindo que o usuário selecione:

* **Região:** Visualize dados específicos para diferentes regiões do Brasil (Norte, Nordeste, Sudeste, Sul, Centro-Oeste).
* **Ano:** Filtre os dados por ano ou visualize o período completo (2020 a 2023).
* **Vendedores:** Selecione vendedores específicos para analisar seu desempenho.

---

## ✨ Insights e Análises

Com este dashboard, é possível obter diversos *insights* valiosos, tais como:

* **Identificar os estados e regiões com maior faturamento e volume de vendas.**
* **Detectar meses de pico de vendas e períodos de baixa**, auxiliando no planejamento de campanhas.
* **Compreender quais categorias de produtos geram mais receita ou são mais vendidas.**
* **Avaliar o desempenho individual dos vendedores** para identificar os *top performers* e oportunidades de treinamento.
* **Visualizar tendências de vendas ao longo do tempo.**

---

## ⚙️ Tecnologias Utilizadas

* **Python:** Linguagem de programação principal.
* **Streamlit:** Framework para criação de aplicações web interativas e dashboards.
* **Pandas:** Biblioteca para manipulação e análise de dados.
* **Plotly Express:** Biblioteca para criação de gráficos interativos e visualizações de dados.
* **Requests:** Biblioteca para fazer requisições HTTP à API de dados.

---

## 📊 Fonte dos Dados

Os dados utilizados neste projeto são fornecidos por uma **API (`https://labdados.com/produtos`)** que simula informações de vendas de um negócio. Esta API faz parte de um projeto específico de um curso da Alura, ideal para fins de aprendizado e demonstração de conceitos de Ciência de Dados.

---

## 🛠️ Como Executar o Projeto Localmente

Para rodar este dashboard em sua máquina, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/rodrigorosalvos/dashboard_vendas.git](https://github.com/rodrigorosalvos/dashboard_vendas.git)
    cd dashboard_vendas
    ```
2.  **Crie um ambiente virtual (recomendado):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows: venv\Scripts\activate
    ```
3.  **Instale as dependências a partir do `requirements.txt`:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Execute o aplicativo Streamlit:**
    ```bash
    streamlit run Dashboard.py
    ```
   
Após executar o comando, o Streamlit abrirá o dashboard em seu navegador padrão.

---

## 💡 Desafios e Aprendizados

Durante o desenvolvimento deste projeto, enfrentei os **desafios comuns relacionados à compatibilidade de versões de bibliotecas**, um aspecto fundamental ao trabalhar com ambientes Python. Superar esses obstáculos reforçou a importância da gestão de dependências e do uso de ambientes virtuais para garantir a reprodutibilidade do projeto. Este projeto teve um caráter essencialmente de aprendizado, permitindo-me aprofundar conhecimentos em visualização de dados e desenvolvimento de aplicações interativas.
