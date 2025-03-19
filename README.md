# AppDeEstatistica

Este é um aplicativo de visualização de cotações de ações utilizando **Streamlit**. Ele permite que você consulte o histórico de preços de ações de diferentes empresas, usando o **Yahoo Finance** como fonte de dados.

## Funcionalidades

- **Consulta de Ticker**: O usuário pode digitar o **ticker** da ação na barra lateral para visualizar o gráfico de preços históricos.
- **Visualização de Gráficos**: O aplicativo gera gráficos interativos usando a biblioteca **Plotly**.
- **Interface Simples**: Desenvolvido com **Streamlit** para garantir uma interface de fácil utilização e rápida visualização.

## Tecnologias

- **Streamlit**: Framework para criação de interfaces web interativas.
- **yFinance**: Biblioteca Python para acessar dados financeiros históricos de ações.
- **Plotly**: Biblioteca de visualização para gráficos interativos.
- **Python 3.x**

## Pré-requisitos

1. **Instalar o Python** (versão recomendada: 3.7 ou superior)
   - Baixe e instale o Python em [python.org](https://www.python.org/downloads/).

2. **Instalar as dependências**:
   - Abra o terminal ou o prompt de comando e execute:
     ```sh
     pip install -r requirements.txt
     ```

## Como rodar

1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/AppDeEstatistica.git
   cd AppDeEstatistica
'''

2. Instale as dependências (se já não tiver feito):
```sh
pip install -r requirements.txt
```
3. Execute o aplicativo Streamlit:
```sh
streamlit run app.py
```
