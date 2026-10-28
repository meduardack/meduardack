```sql
Data Analyst & Analytics Engineer | Pós-graduanda em Engenharia e Análise de Dados na CESAR School | Formada pela Laboratoria Brasil
```
```sql
= Stacks:                                                = Info:
-> SQL (BigQuery, PostgreSQL, MySQL)                     -> Recife, PE — Brasil
-> Python (Pandas, Scikit-Learn, Statsmodels)            -> English (C1 — EF SET 72/100)
-> Power BI, Looker Studio, Metabase                     -> linkedin.com/in/meduardack
-> Data Modeling, EDA & Statistics                       -> meduardack@gmail.com
-> AI / LLM Evaluation & Prompt Engineering              -> github.com/meduardack
```

---

## Projetos em Destaque (Portfólio de Dados)

### 🏦 [`meduardack/Risco_Relativo_Super_Caja`](https://github.com/meduardack/Risco_Relativo_Super_Caja)
```sql
SELECT status, recall, clientes_analisados FROM portfolio.super_caja;
-- Target: Automatizar concessão de crédito e prever default em base desbalanceada (1,9% inadimplência)
-- Stack:  Google BigQuery (SQL) | Python | Google Colab | Looker Studio
-- Output: 36.000 clientes | +305k empréstimos | Outliers isolados via IQR | Score com 84% de Recall
```
🔗 [Repositório](https://github.com/meduardack/Risco_Relativo_Super_Caja) • [Relatório no Notion](https://app.notion.com/p/PROJETO-3_-RISCO-RELATIVO-20db5d32202880f2b216c1479d4a976b?source=copy_link) • [Google Colab](https://colab.research.google.com/drive/1Yx-ip8KkN9QLWg-nfWph80RyN7PJzWO3?usp=sharing)

---

### 🎵 [`meduardack/Hipoteses_Musicais`](https://github.com/meduardack/Hipoteses_Musicais)
```sql
SELECT plataforma, r_quadrado, hipoteses_validadas FROM portfolio.streaming;
-- Target: Investigar fatores determinantes para faixas superarem 1 bilhão de streams
-- Stack:  Google BigQuery (SQL) | Python (Statsmodels, SciPy, Scikit-Learn) | Power BI
-- Output: 948 faixas e 644 artistas | 5 hipóteses testadas (OLS/VIF) | R² = 61% playlists -> streams (r = 0.78)
```
🔗 [Repositório](https://github.com/meduardack/Hipoteses_Musicais) • [Relatório no Notion](https://app.notion.com/p/FICHA-T-CNICA_-PROJETO-2-HIP-TESES-200b5d322028808ba872c03248cce5ac?source=copy_link) • [Google Colab](https://colab.research.google.com/drive/1quOxk92ReWGKQInZWJTejArk3STQUP76?usp=sharing) • [Apresentação Executiva](https://docs.google.com/presentation/d/1YaAlAVo6Mgmx3_J5_hPPOMxjTDW1e4HEAwfG4YMLL7s/edit?usp=sharing)

---

### 🏫 [`meduardack/EduConectada`](https://github.com/meduardack/EduConectada)
```sql
SELECT escolas_totais, medicao_simet, probabilidade_condicional FROM portfolio.educonectada;
-- Target: Diagnosticar qualidade real de internet frente à demanda por aluno em escolas do Brasil
-- Stack:  Python (Pandas, Seaborn, Scikit-Learn) | Estatística Inferencial | Google Colab
-- Output: 137.914 escolas (~77k SIMET) | Paradoxo Urbano-Rural (30,2% rurais vs 21,6% urbanas atendem meta) | Simulação TCL
```
🔗 [Repositório](https://github.com/meduardack/EduConectada) • [Notebook no GitHub](https://github.com/meduardack/EduConectada/blob/main/notebooks/educonectada.ipynb)

---

### 🛒 [`meduardack/O_Mercado`](https://github.com/meduardack/O_Mercado)
```sql
SELECT cluster_rfm, receita_contribuicao, plano_acao FROM portfolio.o_mercado;
-- Target: Segmentação de clientes e estratégias de retenção via metodologia RFM para varejo competitivo
-- Stack:  SQL | Google Sheets | Looker Studio | Python
-- Output: Mapeamento de 6 personas de consumo via quartis RFM com plano de ação de retenção e marketing
```
🔗 [Repositório](https://github.com/meduardack/O_Mercado) • [Dashboard Interativo Looker Studio](https://lookerstudio.google.com/s/hWxat2P-CSo)

---

### ✈️ [`meduardack/flight-tracker`](https://github.com/meduardack/flight-tracker)
```sql
SELECT rota, status_pipeline, trigger FROM portfolio.flight_tracker;
-- Target: Monitoramento autônomo diário de passagens aéreas e alertas instantâneos sem intervenção manual
-- Stack:  Python | Playwright | GitHub Actions (CI/CD) | Telegram Bot API
-- Output: Pipeline serverless em execução contínua (cron 2x/dia), scraping resiliente e alertas estruturados
```
🔗 [Repositório](https://github.com/meduardack/flight-tracker)

---

## 🛠️ Stack Técnica & Competências

- **Linguagens & Bancos de Dados:** SQL (Google BigQuery, Databricks, PostgreSQL, MySQL), Python (Pandas, NumPy, SciPy, Statsmodels, Scikit-Learn, Playwright)
- **Engenharia & Modelagem Analítica:** Processos ETL/ELT, Limpeza e Padronização com Regex, Modelagem de Views e Camadas Analíticas, Validação de Qualidade e Integridade de Dados, Git, GitHub Actions, Docker
- **Estatística & Machine Learning:** Testes de Hipóteses (Paramétricos e Não-Paramétricos), Regressão Linear Simples e Múltipla (OLS / VIF), Risco Relativo, Matriz de Confusão (Precision/Recall/F1), Segmentação RFM, Normalização e Amostragem
- **Visualização & Data Storytelling:** Power BI, Looker Studio, Tableau, Matplotlib, Seaborn
