# Previsão de Preços para Aluguéis Temporários

## Descrição do Projeto
Este projeto tem como objetivo prever valores de acomodações para aluguéis temporários na cidade de Nova York. A previsão de preços é baseada em variáveis como localização, número de noites mínimo e disponibilidade ao longo do ano.

## Perguntas de Negócio
1. Supondo que uma pessoa esteja pensando em investir em um apartamento para alugar na plataforma, onde seria mais indicada a compra?
     * Para investimento em um apratamento para alugar, com base nos dados, seria mais indicado em **Staten Island**. Pois possui o terceiro maior preco medio das acomodacoes, tambem conta com uma qauntidade de acomodacoes regsitradas muito menor que Manhttan e Brooklyn, ou seja teremos menos concorrentes. Porem como ponto negativo, os concorrentes ja intaladas tem uma grande disponibilidade de dias para serem alugados.
   
3. O número mínimo de noites e a disponibilidade ao longo do ano interferem no preço?
   * As duas variaveis nao impactuam no preco, ja que possuem uma correlacao abaixo de 0.1.
      
5. Existe algum padrão no texto do nome do local para lugares de mais alto valor?
   * Os apartamento de mais alto valor, sao provavelmente, com vista para o Central Park, ou contem luxury/vilage no nome.

## Etapas do Projeto
### 1. Análise Exploratória de Dados (EDA)
- Verificação de distribuição das variáveis
- Análise de outliers
- Correlação entre variáveis
- Visualização gráfica

### 2. Pré-Processamento
- Tratamento de valores ausentes
- Codificação de variáveis categóricas
- Normalização e padronização de dados
- Seleção de features

### 3. Modelagem
- Divisão do conjunto de dados (treino/teste)
- Testes com diferentes algoritmos (Regressão Linear, Random Forest, XGBoost, etc.)
- Avaliação de métricas (MAE, MSE, R²)

### 4. Experimentos
- Ajuste de hiperparâmetros
- Validação cruzada
- Comparativo entre modelos

### 5. Predição
- Aplicar o melhor modelo encontrado
- Análise dos resultados finais
- Considerações sobre os insights obtidos

## Como Executar o Projeto
1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/previsao-alugueis.git
   ```
2. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute os notebooks na pasta `notebooks/` para reproduzir as análises e previsões.



