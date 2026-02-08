# 🌾 Brazilian Crop Yield Analysis: Eficiência e Produção (1974-2019)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Big Data](https://img.shields.io/badge/Data-Engineering-orange)

[English](#english) • [Português](#portugues)

---

<a name="english"></a>
## 🇺🇸 English

### 📝 Project Overview
This project presents a strategic analysis of Brazilian agricultural production, simulating a data intelligence scenario for the Agribusiness sector. The objective was to transform raw municipal data into actionable insights regarding yield efficiency and technological evolution.

### 🔬 Technical Methodology & Data Engineering
- **Data Restructuring (Melt):** Processed over **580,000 records** to convert decentralized data (Wide format) into analytical models (Long format).
- **Data Integration (Merge):** Integrated Volume (Total Production) and Efficiency (Yield) metrics into a single consolidated view using optimized `inner joins`.
- **Maize Evolution (Case Study):** Identified a significant technological leap in maize productivity, growing from **3.06 t/ha (2011)** to **3.82 t/ha (2019)**.
- **Data Auditing:** Performed index residue cleanup and NaN handling to ensure statistical integrity across the 45-year historical series.

### 📂 Repository Structure
- 📄 [analise_agro.ipynb](./analise_agro.ipynb): Main notebook containing the full data pipeline.
- 📊 [yield.csv](./yield.csv) / [production.csv](./production.csv): Original datasets (Large files, optimized for Raw view).
- 📈 [evolucao_milho.png](./evolucao_milho.png): Exported visualization of maize productivity trends.

---

<a name="portugues"></a>
## 🇧🇷 Português

### 📝 Resumo do Projeto
Este projeto apresenta uma análise técnica e estratégica da produção agrícola brasileira, simulando um cenário real de inteligência de dados voltado para o Agronegócio. O objetivo foi transformar dados brutos municipais em insights de produtividade e eficiência tecnológica.

### 🔬 Metodologia Técnica e Engenharia de Dados
- **Reestruturação de Dados (Melt):** Processamento de mais de **580.000 registros** para transformar dados descentralizados (formato Wide) para modelos analíticos (formato Long).
- **Integração de Dados (Merge):** Consolidação de métricas de Volume (Produção Total) e Eficiência (Yield) em uma única visão através de `inner joins`.
- **Evolução do Milho (Estudo de Caso):** Identificação de um salto tecnológico na produtividade do milho, que saltou de **3,06 t/ha (2011)** para **3,82 t/ha (2019)**.
- **Auditoria de Dados:** Limpeza de resíduos de indexação e tratamento de NaNs para garantir a integridade estatística em uma série histórica de 45 anos.

### 📊 Destaques e Resultados
* **Análise de Polos Produtores:** Mapeamento dos 10 maiores municípios produtores (ex: Castro e Ponta Grossa/PR).
* **Storytelling de Dados:** Tradução de métricas técnicas em visão estratégica para tomada de decisão no campo.

### 📂 Estrutura do Repositório
- 📄 [analise_agro.ipynb](./analise_agro.ipynb): Notebook principal contendo todo o pipeline de dados.
- 📊 [yield.csv](./yield.csv) / [production.csv](./production.csv): Bases de dados brutas utilizadas no processamento.
- 📈 [evolucao_milho.png](./evolucao_milho.png): Visualização exportada da tendência do milho.

---
👤 **Author:** Cleverson Moura Andrade
