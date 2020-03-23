# Quero ser 99er

É hora de mostrar suas habilidades!

Este exercício tem como objetivo ilustrar problemas de análise de dados e situações de tomada de decisão semelhantes aos desafios que as áreas de analytics da 99 encontram no dia a dia.

Este repositório git contém um conjunto de dados que deve ser utilizado para a realização dos problemas propostos. O exercício é composto de duas partes: técnica e analítica. 

- Parte I, de caráter técnico, compreende questões diretas, que envolvem consulta, manipulação e visualização de dados.
- Parte II, analítica, ilustra situações em que você deve utilizar os dados para sugerir e justificar um determinado posicionamento em um processo de tomada de decisão.

O conjunto de dados que iremos utilizar neste trabalho compreende uma base de ocorrências registradas nas rodovias federais através do sistema BR-Brasil entre Jan/2007 e Jun/2013. Esses dados foram disponibilizados para domínio público no [portal de dados abertos](http://www.dados.gov.br/) do governo federal (~~clique aqui para acessar o recurso~~ - atualmente o recurso está inacessível pelo portal, mas não se preocupe, temos uma cópia dos dados neste repositório :sunglasses:).

O conjunto de dados está no diretório `./dataset`, na pasta raiz deste repositório. Cada tabela do conjunto de dados está compactada em um único arquivo `.zip`. Contudo, antes de iniciar sua análise, recomendamos a leitura do modelo entidade relacionamento (`./docs/entidade-relacionamento-ocorrencias.pdf`) e do dicionário de dados (`./docs/dicionario-de-dados-ocorrencias.pdf`).

Você está livre para usar qualquer ferramenta na sua análise! Mostre todo o seu potencial: gráficos e tabelas são bem vindos!

#### Parte I:

1. Apresente em uma série temporal o número mensal de ocorrências de derramamento de carga registradas nas rodovias BR-116, BR-101 e BR-040.

2. Dentre todas as ocorrências registradas no sistema BR-Brasil, identifique: (1) a ocorrência com o maior número de veículos envolvidos; (2) a ocorrência com o maior número de pessoas envolvidas. (apresente os detalhes dessas duas ocorrências, ex: quando e onde ocorreu, quantos veículos e pessoas envolvidas etc…)

#### Parte II:

1. A Lei n.° 11.705/2008, publicada em junho de 2008, proibiu a venda de bebidas alcoólicas nas rodovias federais. Esta lei teve como objetivo reduzir os índices de acidentes causados pelo consumo de álcool. Com base nas ocorrências registradas no sistema BR-Brasil, verifique se a lei foi ou não efetiva. Apresente dados que justifiquem o seu posicionamento.

2. Estamos em julho de 2013. Você faz parte do time de ciência de dados do ministério do meio ambiente e está trabalhando em um projeto para a construção de passagens de fauna nas rodovias federais (saiba mais sobre passagens de fauna [aqui](https://g1.globo.com/sp/campinas-regiao/terra-da-gente/noticia/2019/07/10/passagens-de-fauna-criam-caminhos-seguros-para-o-trafego-de-animais.ghtml)). O objetivo do projeto é reduzir os indicadores nacionais de atropelamento de animais silvestres. Seu trabalho é recomendar onde as passagens de fauna devem ser construídas. Existe uma verba já aprovada para a construção de 10 passagens de fauna; contudo, para distribuir os recursos do Estado, o governo federal impôs que uma mesma unidade da federação poderá receber investimentos em, no máximo, dois municípios. Apresente uma proposta para os locais de construção das passagens de fauna e justifique as suas recomendações utilizando os dados do sistema BR-Brasil.

## Entrega

O prazo para a entrega deste exercício é de uma semana. A entrega deve conter:

- Documento com o relatório do exercício (pode ser um arquivo pdf, markdown, html, etc.)
- Scripts utilizados para fazer a análise dos dados, gerar os resultados, gráficos e etc.
- Qualquer outro arquivo que você julgar relevante
- Você pode usar qualquer ferramenta para produzir o relatório. O Jupyter Notebook ([http://jupyter.org/](http://jupyter.org/)) ou o R-markdown ([https://rmarkdown.rstudio.com/](https://rmarkdown.rstudio.com/)), por exemplo, são ferramentas gratuitas e muito úteis para fazer esse tipo de análise.

## Critérios de avaliação

Os critérios de avaliação deste exercício serão:

- Apresentação do relatório, com textos, gráficos e tabelas claros e objetivos;
- Domínio do ferramental técnico/teórico utilizado;
- Nível de profundidade e detalhe das análises apresentadas;
- Storytelling, com análise, interpretação e apresentação dos resultados observados;
- Qualidade, corretude, legibilidade e performance dos códigos.

**Bom trabalho! :)**
