# Sobre o Repositório
Dados utilizados nos experimentos de Seleção de Características Orientada por Classe sob financiamento da Fundação de Amparo à Pesquisa do Estado de São Paulo (Fapesp).

# Dados

## Datasets
Todas as bases de dados utilizadas nos experimentos. 
Observação: Todos os arquivos seguem a seguinte formatação quanto à suas colunas: coluna0: ID da linga, coluna1: target, coluna2...colunaN: features.

## Images
Imagens da análise da evolução do hipervolume e da população ao decorrer das gerações.

## Weights
Pesos utilizados durante os experimentos. Foi adotado o método Riesz s-Energy.
Observação: estão no formato `.npy`, basta usar o comando numpy.load(`/caminho/do/arquivo/.npy`) para consultar os pesos gerados. Outra possibilidade é utilizar o framework pymoo e inserir as mesmas seeds, indicadas no nome do arquivo (seed 0 a 19).




