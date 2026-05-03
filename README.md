# Sobre o Repositório
Dados utilizados nos experimentos de Seleção de Características Orientada por Classe sob financiamento da Fundação de Amparo à Pesquisa do Estado de São Paulo (Fapesp).

# Dados

## Datasets
Todas as bases de dados utilizadas nos experimentos. 
Observação: Todos os arquivos seguem a seguinte formatação quanto à suas colunas: coluna0: ID da linha, coluna1: target, coluna2...colunaN: features.

## Images
Imagens da análise da evolução do hipervolume e da população ao decorrer das gerações.

## Weights
Pesos utilizados durante os experimentos. Foi adotado o método Riesz s-Energy.
Observação: estão no formato `.npy`, basta usar o comando numpy.load(`/caminho/do/arquivo/.npy`) para consultar os pesos gerados. Outra possibilidade é utilizar o framework pymoo e inserir as mesmas seeds, indicadas no nome do arquivo (seed 0 a 19).

## Arquivos das Fronteiras de Pareto encontradas

Os arquivos .pkl estão disponíveis no seguinte repositório: [Repositório Google Drive](https://drive.google.com/file/d/1KYcBVi8As9g02r4w844bLbhaouAnVQe_/view?usp=share_link).
Foram mais de 20GB de dados produzidos, não sendo possível armazenar no GitHub. Os arquivos .pkl correspondem a classe `History` da Opytimizer, para mais detalhes, consulte o [Repositório da Biblioteca](https://github.com/recogna-lab/opytimizer).

## Tabelas

Tabelas das métricas dos resultados encontrados.




