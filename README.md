# 📊 Streamlit Dashboard - FIFA Data Dashboard <img src="https://streamlit.io/images/brand/streamlit-mark-color.png" alt="Streamlit Logo" width="40"/>

## Imagem do App
![FIFA Data Dashboard](app_fifa_data_dashboard_home.png)

## Descrição

O projeto **FIFA Data Dashboard** é uma aplicação web interativa desenvolvida com o framework [Streamlit](https://streamlit.io). Esta aplicação permite a visualização e análise de dados de jogadores de futebol, fornecendo uma interface intuitiva para explorar informações detalhadas sobre jogadores e clubes.

## Acesso ao App na Streamlit Cloud

Você pode acessar o aplicativo em execução na [Streamlit Cloud](https://appfifadashboard.streamlit.app/).

## Funcionalidades

- **Home Page:** Apresenta uma visão geral do conjunto de dados e fornece um link para acessar os dados no Kaggle.
- **Jogadores:** Permite selecionar um jogador de um clube e exibe informações detalhadas, incluindo foto, estatísticas e métricas de desempenho.
- **Times:** Permite selecionar um clube e visualizar uma tabela com informações dos jogadores do clube, incluindo fotos e estatísticas.

## Como baixar o projeto

1. **Clonar o Repositório:**

   Clone este repositório para o seu ambiente local usando o comando:

   ```bash
   git clone https://github.com/josealexandre87/streamlit_fifa_dashboard.git

### Instale Dependências

1. **Navegue até o diretório do projeto e crie um ambiente virtual (opcional) para instalar as dependências:**

   ```bash
   cd streamlit_fifa_dashboard
   python -m venv venv
   source venv/bin/activate  # No Windows, use `venv\Scripts\activate`

2. **Instale as dependências listadas no requirements.txt:**
   ```bash
   pip install -r requirements.txt

3. **Execute a aplicação Streamlit com o comando::**
   ```bash
   streamlit run 1_🏠_home.py

### Estrutura do Projeto
    1_🏠_home.py: Página inicial do dashboard.
    2_🏃_players.py: Página para visualizar detalhes dos jogadores.
    3_⚽_teams.py: Página para visualizar informações dos clubes.
