# Análise dos Resultados das Eleições Presidenciais de 2022 - Segundo Turno

Este projeto realiza uma análise detalhada dos dados do segundo turno das eleições presidenciais de 2022 no Brasil, explorando informações como votos válidos, votos anulados e percentuais de votação por estado. A análise é baseada em dois conjuntos de dados: um arquivo com os totais de votos por candidato e outro com detalhes dos votos válidos e anulados por estado e município.

## Objetivo

O objetivo deste projeto é entender melhor a distribuição dos votos entre os estados brasileiros no segundo turno das eleições presidenciais de 2022, com foco em:
- Comparar o percentual de votos recebidos pelos dois principais candidatos (Lula e Bolsonaro) por estado.
- Analisar o percentual de votos válidos e anulados por estado, explorando a representatividade dos votos válidos e a presença de votos anulados.
- Prover uma base para possíveis correlações entre votos válidos/anulados e outras variáveis (como região, percentual de votos brancos, etc.), promovendo insights que possam contribuir para estudos políticos e eleitorais.

## Dados Utilizados

O projeto utiliza dois arquivos principais:
1. **Resultados de votação**: Contendo os totais de votos por candidato e percentuais por estado.
2. **Dados complementares de votos válidos e anulados**: Contendo informações adicionais sobre votos válidos e anulados (sub judice) por estado e município.

Os dados foram obtidos diretamente de fontes oficiais de resultados eleitorais e são tratados para extrair informações relevantes para a análise.

## Estrutura do Projeto

- **Data Cleaning**: Preparação e tratamento dos dados para análise, incluindo filtragem, agregação e cálculo de percentuais.
- **Análise Descritiva**: Cálculo de métricas como o percentual de votos válidos e anulados por estado.
- **Visualizações**: Gráficos de barras e outras visualizações para comparar percentuais de votos válidos, anulados e distribuição de votos entre os dois principais candidatos.
- **Insights**: Identificação de padrões e discussão dos resultados.

## Visualizações

Alguns gráficos de exemplo incluem:
- **Percentual de votos por candidato por estado**: Exibe a divisão dos votos entre os candidatos em cada estado.
- **Média da taxa de abstenção e votos anulados por estado**: Mostra os percentuais médios de votos válidos e anulados, destacando os estados com maior ou menor participação de votos válidos.

## Tecnologias Utilizadas

- **Python**: Para tratamento e análise dos dados.
- **Pandas**: Manipulação e limpeza de dados.
- **Matplotlib/Seaborn**: Criação de visualizações dos dados.

## Como Usar

1. **Pré-requisitos**: Instale as dependências necessárias.
   ```bash
   pip install pandas matplotlib seaborn

