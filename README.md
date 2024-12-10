# Análise Estatística-Econômica de Jogos na Steam  

## Introdução  
O mercado de jogos digitais cresce exponencialmente, mas entender como fatores como preço, número de donos, engajamento dos jogadores e tempo médio de jogo variam ao longo do tempo é essencial para economistas, analistas e desenvolvedores de jogos.
Este projeto explora dados sobre esses indicadores para identificar padrões, tendências temporais e gerar recursos econômicos relevantes.  

## Objetivos  
- Analisar a relação entre preço e engajamento dos jogos, utilizando modelos estatísticos robustos.  
- Avaliar tendências temporais no mercado de jogos agrupando dados por ano de lançamento.  
- Diagnosticar e corrigir possíveis violações nas premissas estatísticas de regressões.  
- Criar visualizações claras e informativas.  

## Principais Etapas do Projeto  
1. **Pré-processamento de Dados**  
   - Limpeza e preparação do dataset para análise.  

2. **Análise Estatística**  
   - Testes de homoscedasticidade, independência e normalidade para validação de modelos de regressão.  
   - Implementação de transformações e ajustes (logarítmicos e GLSAR) para atender às premissas dos testes.  

3. **Análise Temporal**  
   - Agrupamento dos dados por ano de lançamento e cálculo de métricas médias:  
     - Preço médio.  
     - Número médio de donos.  
     - Jogadores médios ativos.  
     - Tempo médio de jogo.  
   - Visualização de métricas por ano em gráficos de colunas.  

4. **Modelagem Estatística**  
   - Regressões lineares com diagnóstico e ajustes baseados em robustez e autocorrelação.  

   ## Ferramentas Utilizadas  
- **Python**: Linguagem de programação para análise de dados.  
- **Bibliotecas**:  
  - `pandas` para manipulação de dados.  
  - `matplotlib` e `seaborn` para visualização de dados.  
  - `statsmodels` para modelagem estatística.  
