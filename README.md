# 🎮 Projeto de Análise de Vendas de Jogos (Loja ICE - 2016)

Este projeto simula uma análise para a loja online **Ice**, que comercializa jogos no mundo todo. A tarefa consiste em estudar dados históricos de vendas, notas de usuários e críticos, plataformas, gêneros e classificações ESRB com o objetivo de **identificar os fatores que influenciam o sucesso de um jogo**.

## 📌 Objetivo
Planejar uma campanha de marketing eficaz para 2017, baseada nos padrões identificados em dados até 2016.

---

## 📊 Etapas do Projeto

1. **Preparação dos Dados**
   - Padronização de colunas e tipos
   - Tratamento de valores ausentes (incluindo 'TBD')
   - Cálculo da coluna de vendas globais

2. **Análise Exploratória**
   - Vendas por ano, plataforma e região (NA, EU, JP)
   - Ciclo de vida das plataformas
   - Gêneros mais lucrativos
   - Efeito das notas dos críticos e usuários nas vendas

3. **Perfil Regional**
   - Diferença nas preferências por plataforma e gênero em cada região
   - Variações por classificação ESRB

4. **Testes de Hipóteses**
   - Diferença entre as notas médias de usuários para:
     - Xbox One vs PC
     - Gênero Action vs Sports

---

## 🔧 Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- SciPy (testes estatísticos)
- Jupyter Notebook

---

## 📈 Conclusões

- Gêneros como **Action** e **Shooter** dominam as vendas.
- Japão tem preferências específicas como RPG.
- Há **diferença significativa nas notas de usuários entre Action e Sports**, mas não entre PC e Xbox One.
- As vendas estão concentradas em poucas plataformas com ciclos previsíveis.
