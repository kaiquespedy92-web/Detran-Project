# Identificando padrões e fatores dos acidentes em SP

## Sobre o projeto

Este projeto foi desenvolvido com o objetivo de analisar dados públicos de acidentes de trânsito no Estado de São Paulo.

Através da análise exploratória dos dados, foram investigados padrões temporais, geográficos e características dos veículos e das pessoas envolvidas nos acidentes, buscando identificar fatores associados à ocorrência e à gravidade dos sinistros.

O projeto utiliza dados públicos disponibilizados pelo Detran-SP por meio do Infosiga.

## Dados utilizados

Foram utilizados dados públicos do **Detran-SP / Infosiga**, referentes aos meses de **maio, junho e julho de 2026**.

Foram analisadas três bases:

| Sinistros | Informações gerais sobre os acidentes |
| Pessoas | Informações sobre as pessoas envolvidas |
| Veículos | Informações sobre os veículos envolvidos |

### Fonte dos dados

[Portal de Dados Abertos do Estado de São Paulo – Sinistros (Infosiga)](https://dadosabertos.sp.gov.br/dataset/sinistros-infosiga)

Os dados foram disponibilizados em arquivos CSV e coletados por meio de download direto do portal.

---

### Tratamento e preparação

Os dados passaram por etapas de:

- consolidação dos arquivos mensais;
- verificação da estrutura das bases;
- tratamento de valores ausentes;
- análise de duplicidades;
- preparação das variáveis para análise.

### Análise exploratória

Foram analisados aspectos como:

- distribuição dos sinistros por município;
- evolução mensal;
- dia da semana;
- horário e turno;
- tipo de via;
- tipo de sinistro;
- tipo de veículo;
- faixa etária;
- sexo;
- tipo de vítima;
- gravidade das lesões.

## Principais insights

Entre os principais padrões identificados na análise estão:

- São Paulo apresentou a maior concentração de sinistros entre os municípios analisados;
- houve maior concentração de registros durante os períodos da tarde e noite;
- sextas-feiras e sábados apresentaram maior concentração de ocorrências, especialmente entre 17h e 20h;
- pessoas do sexo masculino apresentaram maior participação nos registros analisados;
- carros e motocicletas foram os tipos de veículos com maior quantidade de registros;
- as categorias de lesão leve e ileso apresentaram maior frequência;

## Possíveis ações

A partir dos padrões identificados, algumas ações podem ser consideradas:

- direcionamento de ações de fiscalização para períodos de maior concentração;
- desenvolvimento de campanhas educativas direcionadas aos grupos mais presentes nos registros;
- ações de conscientização voltadas à segurança de motociclistas;
- avaliação das condições de infraestrutura e sinalização em regiões com maior concentração de ocorrências;
- monitoramento contínuo dos indicadores de acidentes;

## Dashboard

O projeto conta com um dashboard desenvolvido no **Looker Studio**, contendo indicadores e visualizações:

🔗 **Dashboard:** [https://datastudio.google.com/reporting/3b7060cb-d29f-43ee-bdde-ef9a07e2970c]
