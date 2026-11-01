# Relatório Mundial de Felicidade (World Happiness Report 2015) - Análise Exploratória

Este repositório contém a documentação e os artefatos de uma Análise Exploratória de Dados (AED) realizada sobre o **World Happiness Report 2015**, desenvolvida como parte das atividades práticas de Inteligência Artificial da UNINASSAU Maceió.

## 📋 Identificação da Aluna
* **Candidata:** Karine Evelyn Dias Santos
* **Curso:** Ciência da Computação
* **Instituição:** UNINASSAU Maceió | SYNAPTA (Laboratório de Dados e Inteligência Artificial)
* **Opção Escolhida:** Análise de indicadores de felicidade e bem-estar (Dataset 2015).

---

## 🎯 Objetivo e Pergunta Orientadora
O objetivo deste projeto é analisar pontuações de felicidade e fatores socioeconômicos associados de diferentes países no ano de 2015, construindo um dashboard interativo e interpretando as relações estatísticas encontradas.

* **Pergunta Orientadora:** Quais fatores aparecem associados às maiores pontuações de felicidade e quais cuidados devem ser tomados ao interpretar essa relação?

---

## 🔗 Fonte dos Dados
* **Dataset:** [World Happiness Report (Kaggle)](https://www.kaggle.com/datasets/unsdsn/world-happiness)
* **Condições de Uso:** O dataset público foi utilizado em conformidade com as diretrizes e licenças de uso disponíveis na plataforma do Kaggle, servindo exclusivamente para fins acadêmicos.

---

## 📊 Descrição das Variáveis Utilizadas
O dataset de 2015 é composto por **158 países** e **12 variáveis** principais:
* **Country:** País participante.
* **Region:** Região geográfica do país participante.
* **Happiness Rank:** Posição do país no ranking global de felicidade.
* **Happiness Score:** Pontuação de felicidade obtida pelo país.
* **Standard Error:** Erro padrão associado à precisão da amostra.
* **Economy (GDP per Capita):** Nível de produção econômica e PIB per capita.
* **Family (Suporte Social):** Percepção de apoio familiar e social.
* **Health (Life Expectancy):** Expectativa de vida saudável ao nascer.
* **Freedom:** Grau de liberdade individual para fazer escolhas na vida.
* **Trust (Government Corruption):** Percepção dos cidadãos sobre a corrupção no governo e nos negócios.
* **Generosity:** Nível de generosidade da população (doações/caridade).
* **Dystopia Residual:** Métrica residual utilizada para calibrar a escala e comparar contra um modelo hipotético de "distopia".

---

## 🛠️ Ferramentas e Tecnologias Empregadas
* **Power BI / Power Query:** Ferramentas principais para modelagem, tratamento e criação do dashboard interativo.
* **Formatação DAX:** Utilizada para métricas calculadas (como média, mediana e destaques temáticos).

---

## 🧹 Limpeza e Preparação dos Dados
O pré-processamento realizado no **Power Query** seguiu as seguintes etapas:
1. Carregamento do arquivo CSV original do World Happiness Report (2015).
2. Promoção da primeira linha para cabeçalho da tabela.
3. Ajuste de separadores decimais (conversão de pontos para vírgulas/padrão numérico) para correta interpretação pelo Power BI.
4. Tradução e adaptação de termos/rótulos textuais para facilitar a leitura em português.

---

## 📈 Resultados e Estatísticas Descritivas

### 1. Medidas de Tendência Central (Pontuação de Felicidade)
* **Média ($5.38$):** Representa a pontuação de felicidade caso o total global fosse distribuído de forma totalmente igualitária entre todos os países analisados.
* **Mediana ($5.23$):** Divide o ranking global exatamente ao meio, indicando que metade dos países avaliados possui pontuação abaixo desse valor e a outra metade acima.

### 2. Extremos do Ranking (Top 10 Melhores e 10 Piores)

* **Top 10 Países com Maiores Pontuações:**
  1. Suíça
  2. Islândia
  3. Dinamarca
  4. Noruega
  5. Canadá
  6. Finlândia
  7. Países Baixos
  8. Suécia
  9. Nova Zelândia
  10. Austrália

* **Top 10 Países com Menores Pontuações:**
  1. Togo
  2. Burundi
  3. Síria
  4. Benin
  5. Ruanda
  6. Afeganistão
  7. Burquina Fasso
  8. Costa do Marfim
  9. Guiné
  10. Chade

---

## 📉 Visualizações e Gráficos do Dashboard
O relatório interativo desenvolvido no Power BI conta com uma estrutura em grade simétrica e cartões de destaque, incluindo:
* **Cartões de Indicadores Gerais:** Exibição da Média, Mediana e destaques de *Top Generosidade* (Mianmar) e *Top Suporte Familiar* (Islândia).
* **Gráfico de Maiores Pontuações:** Exibe o Top 10 países líderes em felicidade.
* **Gráfico de Menores Pontuações:** Evidencia o grupo de países nas posições inferiores do ranking.
* **Média de Felicidade por Região:** Gráfico de barras ordenado permitindo comparar o desempenho de blocos geográficos globais (com destaque para a Europa Ocidental e América do Norte nas primeiras posições).

---

## 💡 Conclusões Objetivas
1. O desenvolvimento econômico (*GDP per capita*) caminha fortemente atrelado a patamares mais elevados de bem-estar e felicidade reportada.
2. A expectativa de vida saudável exerce forte impacto correlacional na pontuação geral obtida pelos países no topo do ranking.
3. O fator *Generosidade* não demonstra relação direta e linear de causa com o topo da felicidade; nações em posições inferiores do ranking (como a Síria) apresentam índices de generosidade expressivos, muitas vezes superiores aos líderes globais.
4. Regiões geográficas específicas agrupa padrões semelhantes de pontuação, sugerindo influências culturais ou socioeconômicas regionais marcantes.
5. Fatores de apoio social e estrutural são fundamentais para sustentar o bem-estar populacional a longo prazo.

---

## ⚠️ Limitações da Análise
* **Diferenças Culturais:** O conceito subjetivo de "felicidade" e "satisfação com a vida" varia drasticamente entre culturas, povos e idiomas, podendo enviesar comparações diretas.
* **Fragilidade de Indicadores Macroeconômicos:** O uso do PIB per capita como métrica econômica é raso, pois mede apenas a produção agregada sem refletir a real distribuição de renda ou desigualdade interna.
* **Retrato Temporal:** Os dados representam um recorte específico do ano de 2015; contextos de crises humanitárias, conflitos armados ou instabilidade política pontuais vividos por determinados países naquele período geram distorções severas nos escores de felicidade.

---

## 🤖 Declaração sobre o Uso de IA Generativa
Este projeto utilizou ferramenta de Inteligência Artificial Generativa (Gemini) estritamente como suporte auxiliar para a estruturação, organização textual, revisão gramatical e formatação deste documento `README.md`, com base exclusiva nas informações e análises previamente coletadas pela autora. Os datos brutos antes da formatação estão disponíveis no arquivo Dados Brutos.docx presente neste respositório

---

## 🚀 Instruções de Execução
Para visualizar o dashboard interativo:
1. Certifique-se de possuir o **Power BI Desktop** instalado em seu computador.
2. Baixe o arquivo de dados original correspondente na página oficial do Kaggle.
3. Abra o arquivo `.pbix` do projeto no Power BI Desktop para navegar entre os visuais e filtros.
