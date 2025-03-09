# Introdução

Texto descritivo introdutório apresentando a visão geral do projeto a ser desenvolvido considerando o contexto em que ele se insere, os objetivos gerais, a justificativa e o público-alvo do projeto.

## Problema

Nesta seção, você deve apresentar o problema que a sua investigação/experimentação busca resolver. Por exemplo, caso o _dataset_ selecionado, seja um _dataset_ que contenha uma série temporal com o preço de diversas ações da bolsa de valores, o problema pode estar relacionado a dificuldade em saber a melhor hora (hora certa??) de comprar ou então, de executar a venda de uma determinada ação.

Descreva ainda o contexto em que essa aplicação será usada, se houver: empresa parceira, tecnologias etc. Novamente, descreva apenas o que de fato existir, pois ainda não é a hora de apresentar requisitos  detalhados ou projetos.

> **Links Úteis**:
> - [Objetivos, Problema de pesquisa e Justificativa](https://medium.com/@versioparole/objetivos-problema-de-pesquisa-e-justificativa-c98c8233b9c3)
> - [Matriz Certezas, Suposições e Dúvidas](https://medium.com/educa%C3%A7%C3%A3o-fora-da-caixa/matriz-certezas-suposi%C3%A7%C3%B5es-e-d%C3%BAvidas-fa2263633655)
> - [Brainstorming](https://www.euax.com.br/2018/09/brainstorming/)

## Questão de pesquisa

A questão de pesquisa é a base de todo o trabalho que será desenvolvido. É ela que motiva a realização da pesquisa e deverá ser adequada ao problema identificado. Ao término de sua pesquisa/experimentação, o objetivo é que seja encontrada a resposta da questão de pesquisa previamente definida.

> **Links Úteis**:
> - [Questão de pesquisa](https://www.enago.com.br/academy/how-to-develop-good-research-question-types-examples/)
> - [Problema de pesquisa](https://blog.even3.com.br/problema-de-pesquisa/)

## Objetivos preliminares

Aqui você deve descrever os objetivos preliminares do trabalho indicando que o objetivo geral é experimentar modelos de aprendizado de máquina adequados para solucionar o problema apresentado acima. 

Apresente também alguns (pelo menos 2) objetivos específicos dependendo de onde você vai querer concentrar a sua prática investigativa, ou como você vai aprofundar no seu trabalho.

Por exemplo: um objetivo específico pode estar relacionado a predizer a tendência de alta, estabilidade ou queda de uma determinada ação em uma determinada janela do tempo ou então, predizer o valor exato de uma determinada ação.
Lembre-se que, à medida que a pesquisa/experimentação evolui, os objetivos podem evoluir também, portanto, não se esqueça de fazer as atualizações necessárias.
 
> **Links Úteis**:
> - [Objetivo geral e objetivo específico: como fazer e quais verbos utilizar](https://blog.mettzer.com/diferenca-entre-objetivo-geral-e-objetivo-especifico/)

## Justificativa

Descreva a importância ou a motivação para trabalhar com o conjunto de dados escolhido. Indique as razões pelas quais você escolheu seus objetivos específicos, as razões para aprofundar o estudo do problema identificado e qual o impacto que tal problema provoca na sociedade. Lembre-se de quantificar (com dados reais e suas respectivas fontes) este impacto.

> **Links Úteis**:
> - [Como montar a justificativa](https://guiadamonografia.com.br/como-montar-justificativa-do-tcc/)

## Público-Alvo

Descreva quem serão as pessoas que poderão se beneficiar com a sua investigação indicando os diferentes perfis. O objetivo aqui não é definir quem serão os clientes ou quais serão os papéis dos usuários na aplicação. A ideia é, dentro do possível, conhecer um pouco mais sobre o perfil dos usuários: conhecimentos prévios, relação com a tecnologia, relações hierárquicas, etc.

Adicione informações sobre o público-alvo por meio de uma descrição textual, diagramas de personas e mapa de stakeholders.

> **Links Úteis**:
> - [Público-alvo](https://blog.hotmart.com/pt-br/publico-alvo/)
> - [Como definir o público alvo](https://exame.com/pme/5-dicas-essenciais-para-definir-o-publico-alvo-do-seu-negocio/)
> - [Público-alvo: o que é, tipos, como definir seu público e exemplos](https://klickpages.com.br/blog/publico-alvo-o-que-e/)
> - [Qual a diferença entre público-alvo e persona?](https://rockcontent.com/blog/diferenca-publico-alvo-e-persona/)

## Estado da arte

Nesta seção, deverão ser descritas outras abordagens identificadas na literatura que foram utilizadas para resolver problemas similares ao problema em questão. Para isso, faça uma pesquisa detalhada e identifique, no mínimo, 5 trabalhos que tenham utilizado dados em contexto similares e então: (a) detalhe e contextualize o problema a ser solucionado no trabalho, (b) descreva as principais características do _dataset_ utilizado, (c) detalhe quais abordagens/algoritmos foram utilizados (e seus parâmetros), (d) identifique as métricas de avaliação empregadas, e (e) fale sobre os resultados obtidos. 

> **Links Úteis**:
> - [Google Scholar](https://scholar.google.com/)
> - [IEEE Xplore](https://ieeexplore.ieee.org/Xplore/home.jsp)
> - [Science Direct](https://www.sciencedirect.com/)
> - [ACM Digital Library](https://dl.acm.org/)

# Descrição do _dataset_ selecionado

O dataset selecionado contém informações sobre preços de venda de casas no condado de King, nos Estados Unidos, abrangendo o período entre maio de 2014 e maio de 2015. Esse conjunto de dados é amplamente utilizado para análises de mercado imobiliário, estudos de predição de preços e modelagem estatística de propriedades residenciais.

Link Dataset: https://www.kaggle.com/datasets/soylevbeytullah/house-prices-dataset

Descrição dos Atributos

O dataset possui as seguintes colunas, cada uma representando uma característica específica das casas:

> - id: Identificação única para cada casa (numérico).

> - date: Data em que a casa foi vendida (formato de data).

> - price: Preço de venda da casa (variável alvo da predição, numérico).

> - bedrooms: Número de quartos na casa (numérico).

> - bathrooms: Número de banheiros na casa (numérico, pode incluir frações para indicar lavabos).

> - sqft_living: Área total da casa em pés quadrados (numérico).

> - sqft_lot: Área total do terreno em pés quadrados (numérico).

> - floors: Número total de andares na casa (numérico, podendo incluir frações se houver mezaninos ou níveis intermediários).

> - waterfront: Indica se a casa possui vista para a orla marítima (binário: 0 = não, 1 = sim).

> - view: Número de vezes que a casa foi visualizada (numérico).

> - condition: Avaliação geral da condição da casa (escala categórica de 1 a 5, sendo 1 a pior condição e 5 a melhor).

> - grade: Classificação geral da casa com base no sistema de pontuação do Condado de King (escala de 1 a 13, sendo 1 muito baixo e 13 muito alto).

> - sqft_above: Área construída acima do solo em pés quadrados (numérico).

> - sqft_basement: Área do porão em pés quadrados (numérico).

> - yr_built: Ano de construção da casa (numérico).

> - yr_renovated: Ano da última reforma da casa (numérico; 0 indica que nunca foi reformada).

> - zipcode: Código postal da localização da casa (categórico).

> - lat: Coordenada de latitude da casa (numérico, geoespacial).

> - long: Coordenada de longitude da casa (numérico, geoespacial).

> - sqft_living15: Área da sala de estar medida em 2015, podendo indicar reformas recentes (numérico).

> - sqft_lot15: Área total do lote medida em 2015, podendo indicar mudanças no terreno (numérico).

Esse dataset fornece um conjunto rico de informações sobre propriedades residenciais vendidas no Condado de King, sendo útil para análises estatísticas, predição de preços e estudos sobre tendências do mercado imobiliário. As informações geoespaciais e estruturais das casas permitem a aplicação de diversos métodos de machine learning e estatística para extrair insights valiosos.

Nesta seção, você deverá descrever detalhadamente o _dataset_ selecionado. Lembre-se de informar o link de acesso a ele, bem como, de descrever cada um dos seus atributos (a que se refere, tipo do atributo etc.), se existem atributos faltantes etc.

# Canvas analítico

Nesta seção, você deverá estruturar o seu Canvas Analítico. O Canvas Analítico tem o papel de registrar a organização das ideias e apresentar o modelo de negócio. O Canvas Analítico deverá ser preenchido integralmente mesmo que você não tenha "tantas certezas".

> **Links Úteis**:
> - [Modelo do Canvas Analítico](https://github.com/ICEI-PUC-Minas-PMV-SI/PesquisaExperimentacao-Template/blob/main/help/Software-Analtics-Canvas-v1.0.pdf)

# Vídeo de apresentação da Etapa 01

Nesta seção, um vídeo de, 5 a 8 minutos deverá ser produzido. No vídeo, cada aluno do grupo deverá apresentar uma parte do trabalho realizado nesta etapa. Todos os alunos deverão participar do vídeo. Alunos que não participarem, serão penalizados na nota final da etapa.

# Referências

Inclua todas as referências (livros, artigos, sites, etc) utilizados no desenvolvimento do trabalho utilizando o padrão ABNT.

> **Links Úteis**:
> - [Padrão ABNT PUC Minas](https://portal.pucminas.br/biblioteca/index_padrao.php?pagina=5886)
