# 🌾 Brazilian Crop Yield Analysis: Eficiência e Produção (1974-2019)

Este projeto apresenta uma análise técnica e estratégica da produção agrícola brasileira, simulando um cenário real de inteligência de dados voltado para o Agronegócio. O objetivo foi transformar dados brutos municipais em insights de produtividade e eficiência tecnológica.

## 🛠️ Tecnologias Utilizadas
* **Python & Pandas:** Reestruturação de matrizes (Melt), Integração de dados (Merge) e tratamento de séries históricas.
* **Matplotlib:** Visualização de tendências sazonais e rankings de produtividade.
* **Data Engineering:** Conversão de dados descentralizados (formato Wide) para modelos analíticos (formato Long).

## 📊 Destaques do Projeto
* **Engenharia de Dados (Melt & Merge):** Processamento de mais de 580.000 registros para integrar métricas de Volume (Produção Total) e Eficiência (Yield) em uma única visão consolidada.
* **Evolução do Milho (Maize):** Identificação de um salto tecnológico na produtividade do milho, que cresceu de **3.06 t/ha (2011)** para **3.82 t/ha (2019)**.
* **Análise de Polos Produtores:** Mapeamento dos 10 maiores municípios produtores, destacando a liderança de municípios paranaenses (Castro e Ponta Grossa).
* **Tratamento de Anomalias:** Limpeza de resíduos de indexação e tratamento de dados ausentes (NaN) para garantir a integridade estatística.

## 📂 Estrutura do Repositório
* **[analise_agro.ipynb](analise_agro.ipynb):** Notebook principal contendo todo o pipeline de dados.
* **[Bases de Dados Brutas](yield.csv):** Arquivos originais em CSV utilizados no processamento (devido ao grande volume de dados, o GitHub disponibiliza apenas para download/view raw).
* **[Resultados e Conclusões](analise_agro.ipynb#-7.-Análise-Estatística-Descritiva):** Seção interna do notebook focada em traduzir métricas técnicas em visão estratégica para o agronegócio.

---
*Projeto desenvolvido como parte da preparação técnica para atuação em Ciência de Dados no setor de Agronegócio.*
