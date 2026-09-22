### Identificando padrões e fatores dos acidentes em SP

#### 

#### Problemática



Através dessa análise espera-se identificar quais padrões e características estão associadas à ocorrência e à gravidade dos acidentes de trânsito no Estado de São Paulo e como a análise de dados pode auxiliar na definição de ações preventivas.

####

#### 1.1 Descrição do problema

Os acidentes de trânsito representam um problema relevante para a sociedade, pois podem provocar mortes, lesões, prejuízos materiais, impactos econômicos e sobrecarga dos serviços públicos de saúde e emergência. Além dos impactos diretamente às vítimas, os acidentes também podem gerar congestionamentos.
####

Apesar da existência de registros de ocorrências, o grande fluxo de informações geradas dificulta a identificação de padrões sem o uso de ferramentas adequadas de análise. Observar apenas os dados de quantidade de acidentes, não é suficiente para compreender quais locais, períodos, tipos de veículos ou características das ocorrências estão associados aos casos.
####

Dessa forma, torna-se relevante utilizar dados históricos de acidentes para identificar padrões e características que possam auxiliar na compreensão do problema e fornecer informações para apoiar ações de prevenção e mitigação dos acidentes.
####

#### 1.2 Relevância

A identificação de padrões de acidentes pode contribuir para que ações preventivas sejam direcionadas de maneira mais eficiente. Com os dados demonstrando concentração de acidentes graves em determinados municípios, horários, tipos de vias, entre outros, essas informações podem auxiliar órgãos responsáveis pelo trânsito na definição de prioridades para fiscalização, sinalização e outras medidas preventivas.
Neste projeto, a relevância está principalmente na possibilidade de utilizar dados públicos para identificar padrões existentes nos acidentes de trânsito e gerar informações que possam apoiar a compreensão e a prevenção do problema.
####

#### 1.3 Como a análise de dados pode ajudar

A análise de dados é adequada para esse problema devido à quantidade e à variedade de informações disponíveis sobre os acidentes de trânsito.
A análise será utilizada para transformar os registros em dados para que possam responder perguntas como:

Quais municípios apresentam maior número de acidentes e proporção de acidentes graves?
Qual período ocorre maior concentração?
Quais tipos de veículos estão mais envolvidos?
Existem diferenças entre acidentes ocorridos durante o dia e à noite?

####

#### 2 Fonte de Dados

Para a realização da análise, serão utilizadas três fontes de dados públicas disponibilizadas pelo Detran-SP, por meio do Infosiga. As bases são complementares e permitem analisar os sinistros de trânsito a partir das características das ocorrências, das pessoas e dos veículos envolvidos.
####

#### 2.1 Eventos de Sinistro — Detran-SP / Infosiga

Principal fonte de dados do projeto. A base contém informações relacionadas aos sinistros de trânsito registrados, permitindo analisar aspectos como localização, data, horário, município, tipo de sinistro, características da via e gravidade da ocorrência.

Tipo de dado: estruturado.

Formato: arquivos CSV.

Forma de acesso: download dos arquivos disponibilizados pelo portal de Dados Abertos do Estado de São Paulo.
####

#### 2.2 Pessoas Envolvidas em Sinistros — Detran-SP / Infosiga

Esta fonte complementará a análise dos eventos, auxiliando na avaliação das características das pessoas envolvidas nos sinistros registrados. Os dados poderão ser utilizados para identificar padrões relacionados ao perfil das pessoas e às características dos acidentes de maior gravidade.

Tipo de dado: estruturado.

Formato: arquivos CSV.

Forma de acesso: download dos arquivos disponibilizados pelo portal de Dados Abertos do Estado de São Paulo.
####

#### 2.3 Veículos Envolvidos em Sinistros — Detran-SP / Infosiga

Esta fonte será utilizada para complementar a análise dos eventos a partir das informações dos veículos envolvidos nos sinistros. A base permitirá investigar a participação de diferentes tipos de veículos e verificar sua relação com características dos acidentes identificados durante a análise exploratória.

Tipo de dado: estruturado.

Formato: arquivos CSV.

Forma de acesso: download dos arquivos disponibilizados pelo portal de Dados Abertos do Estado de São Paulo.

A utilização conjunta das três fontes permitirá relacionar informações sobre o sinistro, as pessoas envolvidas e os veículos envolvidos, proporcionando uma análise mais completa do problema.
####

#### 3. Escopo da análise

Para este projeto, serão utilizados dados públicos referentes aos acidentes de trânsito registrados no Estado de São Paulo durante os meses de maio, junho e julho de 2026.

Serão analisados três conjuntos de dados principais:

Sinistros/eventos de trânsito;
Pessoas envolvidas nos sinistros;
Veículos envolvidos nos sinistros.

A análise terá caráter exploratório e estará concentrada na identificação de padrões e associações presentes nos dados desse período. Portanto, os resultados representam apenas um recorte dos meses analisados.
