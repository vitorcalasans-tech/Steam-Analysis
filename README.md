Markdown
# 🎮 Análise Exploratória — Steam Games Dataset

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/Seaborn-4C5B5C?style=for-the-badge&logo=scipy&logoColor=white" alt="Seaborn" />
  <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" />
</p>

Este projeto consiste em uma **Análise Exploratória de Dados (EDA)** detalhada sobre a biblioteca de jogos da plataforma Steam. O objetivo principal é extrair insights valiosos de negócios e responder a perguntas estratégicas sobre o ecossistema de games utilizando ciência de dados.

O conjunto de dados abrange informações de identificação dos jogos, data de lançamento, preço, número estimado de jogadores, avaliações (positivas e negativas), tempo médio de jogo, quantidade de DLCs, conquistas e recomendações.

---

## 📌 Conteúdo do Projeto

O notebook está estruturado para responder a perguntas de negócio através de análises estatísticas e visualizações gráficas:
* **Perguntas de Negócio:** Análise focada em responder 6 perguntas fundamentais sobre o mercado de jogos da Steam.
* **Visualização de Dados:** Mais de 6 gráficos interativos e estáticos gerados com `matplotlib` e `seaborn`[cite: 1].
* **Tratamento de Dados:** Pipeline de limpeza, conversão de tipos de dados (como datas e faixas de usuários) e engenharia de novas features (taxa de aprovação, faixas de preços, etc.)[cite: 1].

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

* **Python** (Linguagem base)
* **Pandas** (Manipulação e análise de dados)
* **NumPy** (Operações matemáticas)
* **Matplotlib** (Geração de gráficos)
* **Seaborn** (Visualização estatística de dados)
* **KaggleHub API** (Integração direta com datasets do Kaggle)[cite: 1]

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
Certifique-se de ter o Python instalado ou utilize um ambiente de execução em nuvem como o **Google Colab** ou **Kaggle Notebooks**.

### Passo a Passo

1. **Clonar o repositório:**
   ```bash
   git clone [https://github.com/vitorcalasans-tech/steam-games-eda.git](https://github.com/vitorcalasans-tech/steam-games-eda.git)
   cd steam-games-eda
Instalar as dependências necessárias:

Bash
pip install -q "kagglehub[pandas-datasets]" pandas numpy matplotlib seaborn
Autenticação no Kaggle (Se necessário):
Caso ocorra erro de autenticação ao baixar o dataset, obtenha sua credencial em Kaggle Settings clicando em Create New Token. Coloque o arquivo kaggle.json gerado no diretório adequado ou faça o upload dele no ambiente do Colab utilizando o bloco de código disponibilizado no notebook[cite: 1].

Executar as células:
Abra o arquivo .ipynb e execute as células em ordem sequencial (Shift + Enter)[cite: 1].

👤 Autor
Formação: Bacharel em Ciências de Dados e Machine Learning[cite: 1].

GitHub: @vitorcalasans-tech

[cite: 1]

LinkedIn: [Adicione o link do seu LinkedIn aqui se desejar]

Fique à vontade para entrar em contato, dar sugestões ou contribuir com o projeto através de pull requests!
