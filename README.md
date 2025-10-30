# **Projeto de Inteligência Computacional: Análise e Predição de Preços de Imóveis no Paquistão**

> Projeto acadêmico desenvolvido para a disciplina de Inteligência Computacional, focado no ciclo completo de um projeto de dados, desde o tratamento e análise até a criação de um modelo preditivo.

### **1. Visão Geral do Projeto**

Este projeto utiliza um dataset de imóveis do Paquistão para aplicar conceitos práticos de Inteligência Computacional. O foco é explorar os dados para extrair insights sobre o mercado imobiliário local e, em seguida, construir um modelo de Machine Learning capaz de prever o preço de um imóvel com base em suas características.

### **2. Objetivo**

O principal objetivo é aplicar e demonstrar conhecimento nas três principais etapas de um projeto de ciência de dados:

- **Tratamento de Dados:** Preparar e limpar o dataset.
- **Análise Exploratória de Dados (EDA):** Investigar os dados para entender padrões, correlações e a distribuição das variáveis.
- **Modelagem Preditiva:** Desenvolver e avaliar modelos de regressão para estimar o valor de imóveis.

### **3. O Dataset**

O conjunto de dados contém informações sobre milhares de anúncios de imóveis no Paquistão. As principais colunas (features) incluem:

- `property_type`: Tipo do imóvel (Casa, Apartamento, etc.).
- `location`, `city`: Informações de localização.
- `price`: Preço do imóvel (nossa **variável alvo**).
- `bedrooms`, `baths`: Número de quartos e banheiros.
- `Area_in_marla`: Área do imóvel em "marlas" (uma unidade de medida local).
- `purpose`: Finalidade (Venda ou Aluguel).

### **4. Rodar o projeto**

- Ao executar todas as células do arquivo main, será gerado um arquivo resultado CSV que conterá os dados tratados.
- No final da main é possível escolher entre dados 'For Sale' e 'For Rent' para os modelos preditivos.
- Execute os outros arquivos para visualizar os resultados de predição.
