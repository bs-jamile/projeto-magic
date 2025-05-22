# Projeto Grupo MAGIC

Este projeto simula uma atuação como **Analista de Backoffice de Investimentos**, com foco em **Controle de Riscos, Suitability e Acompanhamento da Carteira dos Clientes**.

Foi construído com base em dados fictícios, representando os desafios reais enfrentados por times de suporte à gestão de investimentos em instituições financeiras.

---

## Objetivo

Realizar uma análise integrada dos dados de clientes, seus perfis de risco e a aderência (suitability) das carteiras, com foco em:

- Conformidade com normativos internos e externos;
- Governança e controle de riscos das carteiras;
- Geração de indicadores estratégicos para a área de investimentos.

---

## Estrutura da Base de Dados

A modelagem foi realizada com base em um **modelo em estrela**, composto por 8 tabelas principais:

- `fRisco` → Perfil de risco real do cliente e rating interno da carteira  
- `fSuitability` → Nível de adequação da carteira ao perfil do cliente  
- `dCliente` → Dados cadastrais  
- `dCarteira` → Tipo e nome das carteiras  
- `dSegmento` → Segmento dos ativos  
- `dPlanejador` → Responsável pela carteira  
- `dPlataformaParceira` → Origem da captação (ex: plataformas)  
- `dRating` → Classificação de risco das carteiras  

📥 [Download da base de dados (.xlsx)](https://docs.google.com/spreadsheets/d/1LgjHdjAOWsrUtkssDc-S3VOLN4c795Lg/edit?usp=sharing) 

📁 [Pastas no GitHub](https://github.com/bsjamile/projeto-magic/tree/main/base_dados)

---

## Dashboards Desenvolvidos (Power BI)

O projeto foi dividido em três páginas principais no Power BI:

- **Clientes** → Análise de suitability, plataformas e planejadores  
- **Geral** → Alocação por segmento, tipo de carteira e perfil  
- **Risco** → VAR, volatilidade e exposição ao risco por carteira e cliente  

📌 [Veja os dashboards publicados](https://app.powerbi.com/view?r=eyJrIjoiYzliNWZlNzctNmFiMy00NTc2LTgxNzctNzQwYzg4NDhmZDJiIiwidCI6ImFhNTU0OTc3LTgyOTItNDg0ZS05MjZlLTM1MTMzMGE1M2I4MCJ9)  
📁 [Arquivo PBIX para download](https://github.com/bsjamile/projeto-magic/tree/main/pbi)  
📁 [Imagens utilizadas nos dashboards](https://github.com/bsjamile/projeto-magic/tree/main/pbi/imgs_pbi)

---

## Ferramentas Utilizadas

- **Power BI** → Modelagem, medidas DAX e visualizações  
- **Power Query** → Transformações via M  
- **Python (Jupyter Notebook)** → Análise exploratória inicial  
  → [Exploração de dados com Python](https://github.com/bsjamile/projeto-magic/blob/main/python/PROJETO-GRUPO-MAGIC.ipynb)  
- **Excel** → Pré-processamento e verificação dos dados  
- **GitHub** → Versionamento, documentação e disponibilização do projeto  

---

## Documento Complementar

Este repositório é acompanhado por um documento de apoio em PDF, com a descrição das **etapas do projeto**, decisões de modelagem e perguntas orientadoras da análise.

📄 [Documento Complementar)](https://github.com/bsjamile/projeto-magic/blob/main/documento_complementar.pdf)

---

