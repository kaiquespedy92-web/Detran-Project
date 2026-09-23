### Fontes de dados e método de coleta
####

1. Descrição das fontes de dados

Para a realização do projeto, foram utilizadas três bases de dados públicas disponibilizadas pelo Departamento Estadual de Trânsito de São Paulo (Detran-SP), por meio do Infosiga, sistema de informações sobre acidentes de trânsito do Estado de São Paulo.

As bases são complementares e apresentam informações sobre diferentes aspectos dos sinistros de trânsito: os eventos registrados, as pessoas envolvidas e os veículos envolvidos.

Foram utilizados dados referentes aos meses de maio, junho e julho de 2026, totalizando nove arquivos, porém os arquivos foram consolidados através do "pandas" e "os" para melhor manipulação no relatório criado.
####

1.1 Eventos de Sinistro — Detran-SP / Infosiga

A base de Eventos de Sinistro contém informações relacionadas aos sinistros de trânsito registrados no Estado de São Paulo.

Entre as informações disponíveis estão dados sobre:

data e horário do sinistro;
dia da semana;
município;
tipo de local;
características do sinistro;

Tipo de dado: estruturado.

Formato: CSV.

URL da fonte: https://dadosabertos.sp.gov.br/dataset/eventos-de-sinistro

Período utilizado: maio, junho e julho de 2026.

####

1.2 Pessoas Envolvidas em Sinistros — Detran-SP / Infosiga

A base de Pessoas Envolvidas em Sinistros apresenta informações referentes às pessoas registradas nos sinistros de trânsito.

Entre as variáveis utilizadas na análise estão:

idade;
sexo;
tipo de vítima;
modo de transporte;
gravidade da lesão;
município;
tipo de via;

Tipo de dado: estruturado.

Formato: CSV.

URL: https://dadosabertos.sp.gov.br/dataset/pessoas-envolvidas-em-sinistros

Período utilizado: maio, junho e julho de 2026.
####

1.3 Veículos Envolvidos em Sinistros — Detran-SP / Infosiga

A base de Veículos Envolvidos em Sinistros contém informações sobre os veículos registrados nos sinistros analisados.

Entre as principais variáveis utilizadas estão:

tipo de veículo;
marca e modelo;
ano de fabricação;
data do sinistro;
município e informações relacionadas ao evento.

Tipo de dado: estruturado.

Formato: CSV.

URL: https://dadosabertos.sp.gov.br/dataset/veiculos-envolvidos-em-sinistros

Período utilizado: maio, junho e julho de 2026.
####

1.4 Método de coleta e preparação

A coleta dos dados foi realizada por meio do download direto dos arquivos CSV disponibilizados publicamente pelo portal de Dados Abertos do Estado de São Paulo.

Foram coletados três arquivos mensais para cada uma das bases utilizadas:

Base
Eventos de Sinistro
Pessoas Envolvidas
Veículos Envolvidos

Após a coleta, os arquivos correspondentes a cada base foram consolidados. Dessa forma, foram gerados três arquivos principais para a análise:

sinistros_consolidado.csv;
pessoas_consolidado.csv;
veiculos_consolidado.csv.

A consolidação foi realizada para facilitar o tratamento e a análise dos dados;

Posteriormente, os dados foram utilizados nas etapas de limpeza, pré-processamento e análise exploratória. Os resultados da análise foram posteriormente utilizados na construção das visualizações no Looker Studio.
####

1.5 Relação entre as fontes

As três bases possuem informações complementares e podem ser relacionadas pelo identificador

Entretanto, as bases possuem diferentes níveis de granularidade. A base de sinistros apresenta registros dos eventos, enquanto as bases de pessoas e veículos podem complementar nossa análise, trazendo informações sobre os envolvidos no acidente, veiculo, entre outras.