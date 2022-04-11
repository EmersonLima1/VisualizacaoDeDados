# data_science-visualizacao_de_dados

<div align="justify">

Nesse repositório estarei postando sobre visualização de dados utilizando as bibliotecas de ciência de dados do Python, como por exemplo: Matplotlib, Plotpy e Seaborn. 

# Breve resumo sobre Visualização de Dados

# O que é Visualização de Dados?
A Visualização de Dados é uma forma de comunicação visual com o objetivo de representar visualmente os dados. 

# Para que serve a Visualização de Dados?
A Visualização de Dados ajuda a entender e interpretar melhor os dados, principalmente quando trata-se de um grande volume de dados envolvidos. A Visualização de Dados serve para deixar os dados mais fáceis de compreender, contar uma história sobre os dados em questão, reforçar um argumento ou opinião, identificar tendências ou situações atípicas dentro do conjunto de dados, além de servir também para destacar algum ponto importante dentro do conjunto de dados etc.

# Alguns tipos de Visualizações de Dados:
  - **Infográficos**: um infográfico é uma coleção de elementos gráficos-visuais (imagens, gráficos, diagrama estatístico) e com pouco texto, que fornece uma visão abrangente e de fácil compreensão sobre determinado assunto;
  - **Gráficos**: um gráfico é uma representação geométrica e visual de um conjunto de dados. Os gráficos usam simbolos visuais como linhas, barras, pontos, setores para representar pontos de dados. Os gráficos auxiliam na identificação de padrões, na comparação de medidas e também na verificação de resultados. Alguns tipos de gráficos incluem: gráfico de barras, gráfico de setores, gráfico de linhas, gráficos de dispersão etc.
  - **Diagramas**: um diagrama é uma representação gráfica usada para demonstrar um esquema simplicado ou um resumo sobre um assunto. Os diagramas podem ser bidimensionais ou tridimensionais. Alguns diagramas famosos incluem: Diagrama de Venn, fluxogramas (que é um diagrama que descreve um processo, sistema ou algoritmo de computador), mapas mentais, diagrama de classes (que é usado na programação de computadores e nesse diagrama são representadas as estruturas e relações de classes de um projeto).
  - **Mapas**: um mapa é uma representação visual de uma área de um terreno. Os mapas mostram características físicas, como regiões, paisagens, estradas. Além disso, os mapas podem ser temáticos (políticos, físicos, demográficos, econômicos). A leitura do mapa é feita pela identificação dos elementos dos mapas (título, legenda, orientação, escala e projeção cartográfica) e interpretação dos seus símbolos.
  
# Como escolher os gráficos certos para o dados?
Primeiramente, antes de escolher qual gráfico utilizar, é necessário entender qual mensagem/informação/história desejamos passar com o gráfico.

Basicamente existem 4 tipos principais de gráficos, são eles:
  - **Gráficos de comparação**: são usados para comparar um ou mais conjunto de dados. Esses gráficos podem ser usados para comparar itens ou mostrar diferenças ao longo do tempo;
  - **Gráficos de relação**: são usados para mostrar uma conexão ou correlação entre duas ou mais variáveis;
  - **Gráficos de composição**: são usados para exibir partes de um todo;
  - **Gráficos de distribuição**: são usados para mostrar como as variáveis são distribuídas ao longo do tempo, ajudando a identificar valores discrepantes e tendências.
  
**Exemplos de Gráficos de comparação**
  - **Radar**: é usado para apresentar dados multivariáveis na forma de um gráfico bidimensional de três ou mais variáveis quantitativas representadas em eixos que partem do mesmo ponto. É muito utilizado no setor de RH, e bastante útil para representar características e competências de cada colaborador;
  - **Colunas**: esse tipo de gráfico é útil para mostrar mudanças de dados durante um período ou para apresentar a comparação entre itens;
  - **Linhas**: é mais utilizado quando precisa-se visualizar tendências e movimentos ao longo de espaçamentos de tempo, como meses, trimestres ou anos fiscais;
  - **Barras**: é um gráfico que usa barras com comprimentos proporcionais para comparar dados entre categorias;
  
**Exemplos de Gráficos de relação**
  - **Dispersão**: também conhecido como scatter plot, esse tipo de gráfico é usado para analisar a relação entre duas variáveis quantitativas — uma de causa e uma de efeito. Isso não significa que uma variável causa efeito na outra, mas apenas se existe uma relação e qual intensidade entre essa relação. A relação entre duas variáveis pode ser positiva, negativa ou neutra, linear ou não linear. Quando temos uma hipótese de causa, mas ainda deseja comprová-la por meio de uma análise mais aprofundada, esse gráfico é a escolha ideal.
  - **Bolhas**: é uma variação de um gráfico de dispersão no qual os pontos de dados são substituídos por bolhas, e uma dimensão adicional dos dados é representada no tamanho das bolhas. Assim como um gráfico de dispersão, um gráfico de bolhas não usa um eixo de categoria — eixos horizontais e verticais são eixos de valor.
  
**Exemplos de Gráficos de composição**
  - **Setores**: também conhecido como gráfico de Pizza, esse tipo de gráfico é utilizado para analisar e comparar categorias de dados em relação ao todo; 
  - **Rosca**: Assim como o gráfico de setores, um gráfico de rosca mostra a relação das partes com um todo, mas um gráfico de rosca pode conter mais de um série de dados;
  - **Cascata**: é um gráfico de barras que tem o objetivo de mostrar um total cumulativo de perdas e ganhos ou entradas e saídas. É um gráfico onde o usuário poderá ver de forma visual o que está sendo somado e o que está sendo subtraído para verificar de forma mais clara esses aumentos e quedas;
  - **Empilhado**: é um gráfico com colunas empilhadas, essas colunas representam os dados. 
  - **Área**: é muito útil para enfatizar a magnitude das mudanças ao longo do período, mas sem a preocupação de exibir valores exatos.

**Exemplos de Gráficos de distribuição**
  - **Histograma**: é um gráfico de barras verticais que compartilha dados de diferentes categorias ou intervalos. Esse tipo de gráfico representa dados quantitativos, agrupados em classes de frequência que permite distinguir a forma, o ponto central e a variação da distribuição, além de outros dados como amplitude e simetria na distribuição dos dados.
  - **Box plot**: é uma ferramenta gráfica que permite visualizar a distribuição e valores discrepantes (outliers) dos dados. Além disso, o boxplot também é uma disposição gráfica comparativa. As medidas de estatísticas descritivas como o mínimo, máximo, primeiro quartil, segundo quartil ou mediana e o terceiro quartil formam o boxplot.
  
# Visualização de Dados com Python
  
 **3 bibliotecas Python para visualização de dados**
  - **Matplotlib**: é uma biblioteca de visualização de dados e biblioteca de plotagem 2-D do Python. Essa biblioteca pode ser usada para criar plotagens, gráficos de barras, gráficos de setores circulares, histogramas, gráficos de dispersão, gráficos de erro, espectros de potência, gráficos-tronco etc;
  - **Plotpy**: é uma biblioteca gráfica de código aberto gratuita que pode ser usada para formar visualizações de dados. Plotly fornece mais de 40 tipos de gráficos exclusivos, como gráficos de dispersão, histogramas, gráficos de linha, gráficos de barras, gráficos de pizza, barras de erro, gráficos de caixa, vários eixos, minigráficos, dendrogramas, gráficos 3D etc;
  - **Seaborn**: é uma biblioteca de visualização de dados Python baseada em Matplotlib e intimamente integrada com as estruturas de dados NumPy e pandas. Seaborn tem várias funções de plotagem orientadas a conjuntos de dados que operam em quadros de dados e matrizes que contêm conjuntos de dados inteiros. Os gráficos de dados Seaborn podem incluir gráficos de barras, gráficos de pizza, histogramas, gráficos de dispersão, gráficos de erro, etc. Seaborn também tem várias ferramentas para escolher paletas de cores que podem revelar padrões nos dados.
 

 </div>
