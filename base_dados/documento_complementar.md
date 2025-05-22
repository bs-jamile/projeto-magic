# Projeto Grupo MAGIC

## Contexto  
Este projeto simula a atuação de um Analista de Backoffice de Investimentos, com **foco em Controle de Riscos, Suitability e Acompanhamento das carteiras dos clientes.** 

A partir de uma base de dados fictícia, foram construídos indicadores estratégicos e um dashboard completo no Power BI, com o objetivo de representar os desafios reais de uma área de suporte à gestão de investimentos.

## Etapas do projeto:
1. **Selecionar a Base de Dados** [Escolher e explorar a base de dados relevante ao tema.]
2. **Definir Objetivo e Perguntas**  [Estabelecer o objetivo e formular perguntas-chave com base nas variáveis disponíveis.]
3. **Tratar informações com Power Query**  [Tratar informações e preparar modelagem]
4. **Criar Métricas com DAX**  [Criar indicadores e métricas personalizadas]
5. **Criar Visualizações no Power BI**  [Desenvolver painéis interativos com KPIs e análises segmentadas.]

---

## Base Escolhida 
- **Base:** Dados sintéticos simulando um cenário real de uma seguradora com clientes de previdência privada: [BASE_MAGIC](https://github.com/bs-jamile/projeto-magic/tree/main/base_dados)
- **Modelagem no Power BI:** Construção de um modelo relacional em estrela.
- **Transformação dos Dados:** Realizada no próprio Power BI (Power Query).
- **Medidas:** Indicadores e métricas personalizadas (DAX).
- **Visuais:** Dashboards interativos para responder às perguntas predefinidas.

A base de dados contém informações organizadas em oito tabelas principais:

- **fRisco** → Traz o perfil de risco real associado a cada cliente, além do rating interno
- **fSuitability** → Indica a adequação (ou não) entre o perfil do cliente e a composição da carteira
- **dCliente** → Dados cadastrais dos clientes
- **dCarteira** → Informações sobre o tipo e o nome da carteira de investimentos
- **dSegmento** → Classificação do segmento dos ativos que compõem a carteira dos clientes
- **dPlanejador** → Planejador responsável vinculado ao cliente
- **dPlataformaParceira** → Origem da captação ou distribuição (ex: plataforma parceira)
- **dRating** → Níveis de risco internos associados às carteiras dos clientes

## Arquivos:
- **Base de dados para download:** [Projeto Grupo MAGIC](https://docs.google.com/spreadsheets/d/1LgjHdjAOWsrUtkssDc-S3VOLN4c795Lg/edit?usp=sharing&ouid=109415313205868778102&rtpof=true&sd=true)
- **Dashboard Power BI (.pbix):** [Arquivo PBIX](https://github.com/bs-jamile/projeto-magic/tree/main/pbi)

## Dashboards:
- **Visualizações - Power BI:** [Dashboards](https://app.powerbi.com/view?r=eyJrIjoiYzliNWZlNzctNmFiMy00NTc2LTgxNzctNzQwYzg4NDhmZDJiIiwidCI6ImFhNTU0OTc3LTgyOTItNDg0ZS05MjZlLTM1MTMzMGE1M2I4MCJ9)

---

## Objetivo Geral:
Realizar uma análise dos dados com o objetivo de **avaliar a adequação das carteiras ao perfil do cliente (suitability), identificar níveis de risco e exposição e fornecer subsídios para decisões estratégicas de governança e conformidade na área de investimentos.**

### As perguntas norteadoras deste projeto são:  
**[Perguntas exploratórias]** - Quais insights podem ser extraídos a partir dos padrões identificados nos dados?

1. Quantos clientes estão com carteiras inadequadas ao seu perfil de risco?
2. Quais plataformas parceiras concentram mais casos de inadequação?
3. Quais são os perfis que mais contemplam inadequação?
4. Qual é a distribuição de perfis de risco entre os segmentos de clientes?
5. Qual é a volatilidade das carteiras?
6. Quais carteiras possuem ativos mais arriscados?
7. Qual é o VAR das carteiras em relação ao patrimônio?

---

## Ferramentas Utilizadas  
- **Power Query - Linguagem M:** Tratamento e estruturação dos dados dentro do Power BI.
- **DAX:** Indicadores e métricas personalizadas
- **Power BI**: Modelagem relacional, medidas DAX e visualizações interativas para apresentar os insights gerados.  
- **Excel**: Pré-processamento e visualização preliminar
- **GitHub**: Para armazenamento, versionamento do projeto e documentação.  