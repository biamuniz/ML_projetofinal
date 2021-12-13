# Machine Learning Aplicado ao Jornalismo: Modelo para clusterizar os deputados a partir das votações das PECs
Repositório para documentar o trabalho final da disciplina Machine Learning Aplicado ao Jornalismo, do Master em Jornalismo de Dados, Automação e Data Storytelling do Insper

**Grupo:** Alessandro Feitosa Jr, Bianca Muniz, Jéssica Avelar, Renan Cavalcante, Ricardo Grinbaum, Vinicius Marques

## Proposta do trabalho:
### Modelo para segmentar, a partir dos votos, os grupos de votação na Câmara.
* Bases de dados a serem utilizadas: As bases de votação da Câmara de 2021
* Variáveis explicativas: nome do político, partido, votações anteriores
* Utilidade do modelo: entender sobre os partidos/políticos, as diferenças entre as casas e as posições partidárias.

**Queremos dividir nossas observações em grupos**
* Diferente dos problemas de classificação, não temos grupos pré-definidos, nem temos a classificação destes grupos em nossas observações;
* O objetivo é criar grupos a partir de características dos nossos dados;
* Queremos grupos diferentes uns dos outros e com observações dentro de cada grupo parecidas.

## Como usar este repositório:
* Em [`códigos`](https://github.com/biamuniz/cluster-deputados/tree/main/c%C3%B3digos) estão os notebooks em Python utilizados para baixar as bases, formatar planilhas e clusterizar os grupos de votação;
* Em [`dados`](https://github.com/biamuniz/cluster-deputados/tree/main/dados) estão os arquivos de entrada e saída dos códigos;
* Em [`análises`](https://github.com/biamuniz/cluster-deputados/tree/main/an%C3%A1lises) fizemos o upload de arquivos auxiliares das análises: visualizações, arquivos de texto, planilhas;
* Em [`atividades`](https://github.com/biamuniz/cluster-deputados/tree/main/atividades) estão arquivos criados para a resolução de tarefas anteriores relacionadas ao trabalho final da disciplina.
