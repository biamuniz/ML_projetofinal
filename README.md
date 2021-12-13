# Machine Learning Aplicado ao Jornalismo: Modelo para clusterizar os deputados a partir das votações das PECs
Repositório para documentar o trabalho final da disciplina Machine Learning Aplicado ao Jornalismo, do Master em Jornalismo de Dados, Automação e Data Storytelling do Insper

**Grupo:** Alessandro Feitosa Jr, Bianca Muniz, Jéssica Avelar, Renan Cavalcante, Ricardo Grinbaum, Vinicius Marques

## Proposta do trabalho:
### Modelo para segmentar, a partir dos votos, os grupos de votação na Câmara.
* Bases de dados a serem utilizadas: As bases de votação da Câmara de 2021
* Variáveis explicativas: nome do político, partido, votações anteriores
* Utilidade do modelo: entender sobre os partidos/políticos, as diferenças entre as casas e as posições partidárias.

**Queremos dividir nossas observações em grupos**
* Diferente dos problemas de classificação, não temos grupos pré-definidos, nem temos a classificação destes grupos em nossas observações.
* O objetivo é criar grupos a partir de características dos nossos dados.
**Queremos grupos:**
* Diferentes uns dos outros
* Observações dentro de cada grupo parecidas

## Como usar este repositório:
* Em `códigos` estão os notebooks em Python utilizados para baixar as bases, formatar planilhas e clusterizar os grupos de votação;
* Em `dados` estão os arquivos de entrada e saída dos códigos;
* Em `análises` fizemos o upload de arquivos auxiliares das análises: visualizações, arquivos de texto, planilhas;
* Em `atividades` estão arquivos criados para a resolução de tarefas anteriores relacionadas ao trabalho final da disciplina.
