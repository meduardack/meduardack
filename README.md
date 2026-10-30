> **Language / Idioma:** [English](README_en.md) | **Português**

```sql
Analista de Dados & Analytics Engineer Jr | Pós em Engenharia e Análise de Dados (CESAR School) | Laboratoria
```
```sql
= Stacks:                                                = Informações:
-> SQL (BigQuery, PostgreSQL, CTEs, Window Functions)    -> Recife, PE — Brasil (Remoto/Híbrido)
-> Python (Pandas, NumPy, Scikit-Learn, Seaborn, Plotly) -> Inglês Avançado (C1 — EF SET 72/100)
-> Analytics Engineering & BI (dbt, Metabase, Looker)    -> linkedin.com/in/meduardack
-> DuckDB, Streamlit, Git/GitHub & Modelagem Dimensional -> meduardack@gmail.com
-> Avaliação de Qualidade de Dados & IA (LLMs)           -> github.com/meduardack
```

---

## Projetos em Destaque | Portfólio de Dados

### [`meduardack/EduConectada`](https://github.com/meduardack/EduConectada)
```sql
SELECT total_schools, simet_telemetry, conditional_probability FROM portfolio.educonectada;
-- Objetivo: Avaliar a conectividade real de internet vs. demanda por aluno nas escolas públicas do Brasil
-- Stack:    Python (Pandas, Seaborn) | Estatística Inferencial | Google Colab
-- Entrega:  137.914 escolas (76k SIMET) | Paradoxo Urbano-Rural (30,2% rural vs 21,6% urbano atingem meta) | Simulação TCL
```
[GitHub](https://github.com/meduardack/EduConectada) | [Notebook](https://github.com/meduardack/EduConectada/blob/main/notebooks/educonectada.ipynb)

---

### [`meduardack/Risco_Relativo_Super_Caja`](https://github.com/meduardack/Risco_Relativo_Super_Caja)
```sql
SELECT status, recall, analyzed_clients FROM portfolio.super_caja;
-- Objetivo: Análise automatizada de concessão de crédito e predição de inadimplência em base desbalanceada (1,9% de default)
-- Stack:    Google BigQuery (SQL) | Python | Google Colab | Looker Studio
-- Entrega:  36.000 clientes | +305k empréstimos | Outliers isolados via IQR | 84% de Recall no Score de Risco
```
[GitHub](https://github.com/meduardack/Risco_Relativo_Super_Caja) | [Notion](https://app.notion.com/p/PROJETO-3_-RISCO-RELATIVO-20db5d32202880f2b216c1479d4a976b?source=copy_link) | [Google Colab](https://colab.research.google.com/drive/1Yx-ip8KkN9QLWg-nfWph80RyN7PJzWO3?usp=sharing)

---

### [`meduardack/Hipoteses_Musicais`](https://github.com/meduardack/Hipoteses_Musicais)
```sql
SELECT platform, r_squared, validated_hypotheses FROM portfolio.streaming;
-- Objetivo: Investigar os fatores determinantes para faixas musicais superarem 1 bilhão de streams
-- Stack:    Google BigQuery (SQL) | Python (Statsmodels, SciPy) | Power BI
-- Entrega:  948 faixas & 644 artistas | 5 hipóteses testadas (OLS/VIF) | R² = 61% playlists -> streams (r = 0,78)
```
[GitHub](https://github.com/meduardack/Hipoteses_Musicais) | [Notion](https://app.notion.com/p/FICHA-T-CNICA_-PROJETO-2-HIP-TESES-200b5d322028808ba872c03248cce5ac?source=copy_link) | [Google Colab](https://colab.research.google.com/drive/1quOxk92ReWGKQInZWJTejArk3STQUP76?usp=sharing) | [Google Slides](https://docs.google.com/presentation/d/1YaAlAVo6Mgmx3_J5_hPPOMxjTDW1e4HEAwfG4YMLL7s/edit?usp=sharing)

---

### [`meduardack/O_Mercado`](https://github.com/meduardack/O_Mercado)
```sql
SELECT rfm_cluster, revenue_contribution, action_plan FROM portfolio.o_mercado;
-- Objetivo: Segmentação de clientes e estratégias de retenção via metodologia RFM para varejo competitivo
-- Stack:    SQL | Google Sheets | Looker Studio | Python
-- Entrega:  6 personas comportamentais mapeadas via quartis RFM com ações direcionadas de retenção e marketing
```
[GitHub](https://github.com/meduardack/O_Mercado) | [Dashboard Looker Studio](https://lookerstudio.google.com/s/hWxat2P-CSo)

---

## Stack Tecnológico & Competências

- **Linguagens & Bancos de Dados:** SQL (Google BigQuery, Databricks, PostgreSQL, MySQL), Python (Pandas, NumPy, SciPy, Statsmodels, Scikit-Learn)
- **Engenharia de Dados & Analytics:** Pipelines ETL/ELT, Limpeza de Dados & Regex, Views Analíticas & Camadas de Dados, Qualidade & Integridade, Git, GitHub Actions, Docker
- **Estatística & Métodos Quantitativos:** Testes de Hipóteses (Paramétricos e Não-Paramétricos), Regressão Linear (OLS / VIF), Risco Relativo, Matriz de Confusão (Precisão/Recall/F1), Segmentação RFM, Amostragem & Normalização
- **Visualização & Storytelling:** Power BI, Looker Studio, Metabase, Matplotlib, Seaborn
