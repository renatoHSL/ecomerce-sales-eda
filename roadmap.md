# 🛣️ Roadmap Técnico: Projeto EDA de Vendas de E-commerce

## 🚩 Fase 1: Planejamento e Entendimento Inicial

### ✅ 1.1. Definir objetivo de negócio e perguntas analíticas

- [ ] Esboçar de 3 a 5 perguntas que a análise tentará responder
  - [ ] Ex: Quais produtos geram mais receita?
  - [ ] Ex: Quais canais de venda são mais eficientes?
  - [ ] Ex: Qual o comportamento de recompra dos clientes?
- [ ] Anotar pelo menos 1 hipótese ou curiosidade para investigar
- [ ] Criar mini briefing no README simulando o pedido de um gestor
- [ ] Documentar todas as ideias no Notion, markdown ou caderno

### ✅ 1.2. Obter e validar o dataset

- [ ] Escolher um dataset realista (Kaggle, GitHub, etc)
- [ ] Fazer download ou conectar ao dataset
- [ ] Salvar dataset localmente ou conectar no Colab/Jupyter
- [ ] Carregar o dataset com `pandas`
- [ ] Rodar `.info()` para ver estrutura e tipos de dados
- [ ] Rodar `.head()` para ver amostra das primeiras linhas
- [ ] Inserir prints da estrutura e primeiras colunas no notebook

---

## 🧹 Fase 2: Limpeza e Preparação de Dados

### ✅ 2.1. Diagnóstico de problemas nos dados

- [ ] Verificar valores nulos com `.isnull().sum()`
- [ ] Verificar duplicatas com `.duplicated().sum()`
- [ ] Identificar tipos de dados errados com `.info()`
- [ ] Avaliar estatísticas com `.describe()`
- [ ] Listar todos os problemas encontrados
- [ ] Criar seção “Diagnóstico dos Dados” no notebook

### ✅ 2.2. Corrigir e padronizar os dados

- [ ] Converter colunas de data com `pd.to_datetime()`
- [ ] Remover duplicatas com `.drop_duplicates()`
- [ ] Tratar valores nulos: `.dropna()` ou `.fillna()`
- [ ] Corrigir tipos com `.astype()`
- [ ] Verificar consistência final dos dados
- [ ] Explicar no notebook as decisões de limpeza tomadas

---

## 🔍 Fase 3: Análise Exploratória e Estatística

### ✅ 3.1. Estatísticas descritivas

- [ ] Gerar `.describe()` para colunas numéricas
- [ ] Usar `.value_counts()` para variáveis categóricas
- [ ] Usar `.groupby()` para sumarizar dados por categoria
- [ ] Documentar os principais dados e insights numéricos no notebook

### ✅ 3.2. Análise por grupos (ex: por país, categoria, canal)

- [ ] Usar `.groupby()` + `.agg()` para analisar por segmentos
- [ ] Criar tabelas com `pivot_table()` se necessário
- [ ] Identificar top categorias, top países, top canais
- [ ] Documentar descobertas com explicações claras no notebook

---

## 📊 Fase 4: Visualização de Dados

### ✅ 4.1. Criar gráficos explicativos

- [ ] Criar pelo menos 5 gráficos relevantes
- [ ] Incluir título, legenda e cores coerentes
- [ ] Explicar o que cada gráfico revela
- [ ] Criar seção específica no notebook só para gráficos

### ✅ 4.2. Criar um painel resumo final (opcional)

- [ ] Escolher ferramenta para painel (Plotly, Streamlit, etc)
- [ ] Definir os KPIs principais: total de vendas, países, produtos mais vendidos
- [ ] Criar painel interativo ou imagem de resumo
- [ ] Incluir painel ou imagem no notebook ou README

---

## 📚 Fase 5: Documentação e Publicação

### ✅ 5.1. Criar o README para o GitHub

- [ ] Escrever título e descrição do projeto
- [ ] Incluir objetivo do projeto
- [ ] Informar a origem do dataset
- [ ] Descrever as etapas realizadas (pipeline)
- [ ] Destacar principais insights e aprendizados
- [ ] Usar markdown com formatação clara e atrativa

### ✅ 5.2. Postar no LinkedIn com storytelling

- [ ] Criar narrativa: problema > processo > descoberta
- [ ] Incluir imagem ou gráfico ilustrativo
- [ ] Adicionar link para o GitHub no post
- [ ] Escrever convite para feedback ou interação
