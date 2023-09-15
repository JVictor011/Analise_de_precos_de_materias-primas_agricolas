# Análise de Preços de Matérias-Primas Agrícolas

Este projeto concentra-se na análise dos dados de preços de várias matérias-primas agrícolas ao longo do tempo. O conjunto de dados usado para esta análise é chamado de `agricultural_raw_material.csv`.

## Limpeza de Dados

Antes de nos aprofundarmos na análise, realizamos algumas etapas de limpeza de dados para garantir a qualidade do conjunto de dados:

- **Tratamento de Dados Ausentes**: Verificamos a existência de dados ausentes no conjunto de dados e removemos as linhas com valores ausentes. Após essa etapa, o conjunto de dados não possui mais dados faltantes.

- **Conversão de Tipos de Dados**: Convertemos as colunas relevantes para seus tipos de dados apropriados. As colunas relacionadas às variações de preço foram convertidas para números de ponto flutuante, e a coluna 'Mês' foi convertida para um formato de data.

## Análise Exploratória de Dados (AED)

### Análise de Correlação

Exploramos a correlação entre os preços de diferentes matérias-primas. Abaixo estão algumas visualizações:

- **Mapa de Calor da Correlação de Preços**: Criamos um mapa de calor para visualizar a correlação entre os preços de matérias-primas, incluindo Coarse wool, Copra, Cotton, Fine wool, Hard log, Hard sawnwood, Hide, Plywood, Rubber, Softlog, Soft sawnwood e Wood pulp.

- **Mapa de Calor da Correlação das Variações de Preço**: Outro mapa de calor mostra a correlação entre a variação percentual nos preços das matérias-primas.

### Evolução de Preços

Plotamos a evolução do preço de Coarse wool junto com sua variação percentual ao longo do tempo. Esta visualização nos ajuda a entender como o preço de Coarse wool mudou ao longo dos anos.

### Distribuição da Variação de Preços

Examinamos a distribuição das variações de preço de várias matérias-primas. Histogramas das variações percentuais nos preços fornecem insights sobre a variabilidade e tendências desses materiais.

### Comparação de Preços

Comparamos os preços de diferentes matérias-primas ao longo dos anos. Um subplot para cada material mostra sua tendência de preço, permitindo-nos identificar qual material teve o preço mais baixo ao longo do tempo.

## Conclusão

Esta análise fornece uma compreensão abrangente da dinâmica de preços das matérias-primas agrícolas. As visualizações e insights obtidos podem ser valiosos para a tomada de decisões na indústria agrícola.

Consulte o código e as visualizações acima para obter mais detalhes sobre a análise.
