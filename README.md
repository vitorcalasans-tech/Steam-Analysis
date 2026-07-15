# 🎮 Análise Exploratória de Dados — Conjunto de Dados Steam

> Este projeto apresenta uma Análise Exploratória de Dados (EDA) detalhada sobre o catálogo de jogos da plataforma Steam, investigando dinâmicas de mercado, precificação e o comportamento dos usuários.

---

## 📌 Descrição do Projeto

O roteiro realiza uma investigação analítica completa em etapas estruturadas, projetadas para extrair insights de negócios a partir de dados brutos:

*   Gestão automatizada de dados diretamente da API do Kaggle.
*   Limpeza e Engenharia de Recursos para segmentação temporal e financeira.
*   Tratamento de dados categóricos complexos (múltiplos gêneros e plataformas).
*   Análise Estatística focada em correlações entre preço, volume de DLCs e aceitação do público.
*   Visualização Gráfica Avançada com distribuições, dispersões e índices de variáveis.
*   Geração de Insights de Negócio voltados para o mercado de games.

---

## 🎯 Objetivos

*   Identificar os gêneros dominantes e os padrões de preço médio no catálogo da Steam.
*   Mapear a proporção real entre jogos *Free-to-Play* e títulos pagos.
*   Avaliar o impacto direto de faixas de preço na percepção de qualidade do público.
*   Analisar se estratégias de múltiplos DLCs (*Live-Service*) impactam de maneira positiva ou negativa a satisfação dos usuários.
*   Traçar o perfil socioeconômico e mercadológico dos jogos considerados "Aclamados".

---

## 📂 Estrutura do Projeto

```text
steam-games-analysis/
│
├── steam_analysis_colab.py               # Script principal da análise
├── Steam Analysis Deck _standalone_.html # Deck de apresentação interativo
└── README.md                             # Documentação do projeto
🛠️ Tecnologias UtilizadasPython 3.8+Pandas: Manipulação, limpeza e estruturação de dados.  NumPy: Operações matemáticas e computação vetorizada.Matplotlib: Construção de base de gráficos e customizações de layout.  Seaborn: Visualizações estatísticas e gráficos complexos de dispersão e densidade.  Kagglehub: Integração e download direto do conjunto de dados público.  🚀 Como Executar o ProjetoFaça o upload do arquivo steam_analysis_colab.py ou copie o código para um novo notebook no Google Colab.  Execute as células em ordem sequencial (Shift + Enter).  Nota sobre autenticação: O pacote kagglehub baixará o arquivo games.csv automaticamente. Caso o Kaggle solicite suas credenciais, faça o upload do seu token pessoal (kaggle.json) gerado em sua conta da plataforma.  ⚙️ Dados Utilizados e Engenharia de RecursosO carregamento inicial extrai o arquivo games.csv bruto. Para viabilizar as respostas analíticas, as seguintes variáveis foram construídas e tratadas:  Variável CriadaTipo de DadoDescrição / ObjetivoYearInteiroExtração do ano de lançamento a partir dos dados originais.  Owners_estNumérico (Float)Conversão da string de estimativa de donos para um valor numérico calculável.  Total_reviewsInteiroSomatório de avaliações positivas e negativas.  Approval_ratePercentual (Float)Razão de análises positivas sobre o total: (Positivas / Total) * 100.  Is_freeBooleanoIdentificação binária de jogos gratuitos (True / False)[cite: 1].Price_bandCategóricoAgrupamento dos preços dos jogos em faixas de valor específicas[cite: 1].❓ Perguntas Analíticas RespondidasO escopo do projeto foi delimitado para solucionar 6 problemas de negócio:Precificação por Gênero: Qual o preço mediano praticado por nicho de mercado (considerando apenas títulos pagos)?Dinâmica Free-to-Play: Qual a proporção real de jogos gratuitos no catálogo e como se distribuem os preços dos jogos pagos?Saturação do Catálogo: Quais gêneros dominam massivamente a quantidade de lançamentos na plataforma?Valor vs. Percepção: Existe clareza matemática ou dispersão óbvia entre o preço cobrado e a taxa de aprovação dos usuários?Impacto dos DLCs: A estratégia de fragmentar o jogo em múltiplos conteúdos adicionais satura ou melhora a satisfação da comunidade?O Perfil da Alta Qualidade: Jogos aclamados pela crítica popular sustentam preços medianos de venda superiores aos demais?💡 Resultados e Insights de NegócioPredomínio de Gratuitos: A base histórica possui volumosa presença de jogos Free-to-Play, instalados como estratégia principal de aquisição de usuários.Ancoragem de Preço: O mercado de jogos pagos consolida faixas de preço em torno de valores medianos próximos a US$ 50, mostrando barreiras psicológicas tradicionais de precificação.Sensibilidade ao Preço: Jogos posicionados em faixas de preço mais baixas apresentam taxas de aprovação sutilmente superiores, indicando menor tolerância a falhas em jogos caros.O Limite dos DLCs: Títulos com um volume moderado de DLCs mantêm bons índices de aprovação. No entanto, o modelo agressivo de Live-Service (centenas de conteúdos adicionais) gera desgaste, não se convertendo necessariamente em satisfação do público.Prêmio por Qualidade: Há validação de valor em jogos bem avaliados; títulos classificados como "Aclamados" (com mais de 100 avaliações) sustentam preços medianos significativamente superiores.🧠 Conceitos de Ciência de Dados AbordadosAnálise Exploratória de Dados (EDA)Engenharia de Variáveis (Feature Engineering)Estatística Descritiva (Média, Mediana, Quartis e Distribuições)Visualização de Dados com foco em StorytellingSegmentação de Mercado e Análise de Coortes por Faixas de Preço🎓 Contexto AcadêmicoEste projeto compõe a avaliação prática da disciplina de Ciência de Dados, validando competências essenciais do ciclo de vida dos dados: desde a coleta automatizada, passando pelo tratamento de dados inconsistentes, até a comunicação visual e analítica dos resultados gerados[cite: 1].👤 AutorInstituição: UniCEUB[cite: 1]Curso: Bacharelado em Ciência de Dados e Machine Learning[cite: 1]GitHub: @vitorcalasans-tech[cite: 1]Data: Maio de 2026Status do Projeto: Concluído / Funcional[cite: 1]

