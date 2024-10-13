# Estudo de Estatística e Programação em Python (Em andamento- estou elaborando o código e interpretando resultados no momento)

Este repositório contém meu estudo e análises com dados de streaming musicais obtidos no Kaggle, combinando estatística e programação em Python. O objetivo é aprofundar meus conhecimentos em análise de dados, modelagem preditiva e técnicas de programação aplicadas a um conjunto de dados de música.

📊 Objetivos do Estudo
O estudo visa explorar diversas análises e metodologias estatísticas, incluindo:

Análise de Tendências Musicais: Como atributos musicais mudam ao longo do tempo.
Correlação entre Atributos e Popularidade: Identificação de variáveis que influenciam o número de streams.
Análise de Clusters: Agrupamento de músicas com base em características semelhantes para segmentação e insights.
Comparação de Popularidade em Diferentes Plataformas: Investigação de padrões de streaming em Spotify, Apple Music, Deezer e Shazam.

📚 Conhecimentos Aplicados
Durante o desenvolvimento deste estudo, utilizei e aprofundei meus conhecimentos em:

Estatística Descritiva: Entendimento dos principais atributos musicais.
Modelagem Estatística: Aplicação do algoritmo KMeans.
Visualização de Dados: Criação de gráficos interativos e intuitivos para comunicar insights.
Tratamento e Limpeza de Dados: Identificação e correção de valores ausentes, outliers e formatação inadequada.
Programação em Python: Desenvolvimento de soluções eficientes e modulares para análise de grandes conjuntos de dados.

🛠️ Ferramentas Utilizadas
Algumas das bibliotecas e ferramentas utilizadas nesse estudo:

Python: Linguagem principal para as análises.
Pandas: Manipulação de dados tabulares.
NumPy: Operações numéricas.
Matplotlib & Seaborn: Visualização de dados.
Scikit-learn: Algoritmos de machine learning.

🔍 Principais Análises
Distribuição de BPM (Batidas Por Minuto): Investigação das faixas de BPM mais comuns em músicas populares.
Impacto de Playlists no Sucesso: Análise do impacto de uma música estar presente em várias playlists e plataformas.
Clustering de Músicas: Uso de algoritmos de clustering para segmentar músicas com características semelhantes.
Comparação entre Músicas de Artistas Solo e Colaborações: Análise das diferenças em popularidade entre músicas com 1, 2, 3 ou 4 artistas.

📈 Análises e Resultados

# Quais são os artistas com mais músicas em playlists? 

![Gráfico de Barras](Imagens/Imagem1.png)

- Considerações 

Taylor Swift e The Weeknd aparecem como os dois artistas com o maior número de músicas em playlists.
Harry Styles também tem uma quantidade significativa de músicas em playlists, mas um pouco menos que os dois primeiros.
Eminem, Ed Sheeran, Imagine Dragons e Bad Bunny aparecem em seguida.
Olivia Rodrigo, Kanye West e Arctic Monkeys fecham a lista dos 10 artistas com mais músicas em playlists, cada um com entre 40.000 e 50.000 músicas.

- Insights

Logo, é observada a popularidade dos artistas nas plataformas de streaming, com Taylor Swift e The Weeknd dominando o topo. Esses dados podem ser usados para entender melhor quais artistas têm maior presença em playlists, o que pode indicar sua relevância no mercado musical atual.


# Como podemos agrupar músicas com características semelhantes para criar playlists personalizadas, recomendar conteúdos ou segmentar o público de forma mais eficiente?

![Gráfico de Dispersão](Imagens/Imagem2.png)

- Considerações 

Este é um gráfico de dispersão (scatter plot) que exibe os resultados do K-Means clustering aplicado a um conjunto de músicas com base em duas características principais: BPM (batidas por minuto) e energy % (porcentagem de energia). O gráfico divide as músicas em três grupos ou clusters (representados por cores diferentes: verde, azul e laranja), onde:

Eixo X (bpm): Representa a velocidade das músicas em batidas por minuto (BPM). Músicas com BPM mais alto tendem a ser mais rápidas.

Eixo Y (energy %): Representa a energia da música, onde valores mais altos indicam músicas mais energéticas.

Clusters:

O Cluster 0 (pontos verdes) agrupa músicas com BPM mais baixos (entre 60 e 120) e variação moderada de energia (em torno de 20% a 95%).
O Cluster 1 (pontos azuis) agrupa músicas com BPM mais altos (entre 110 e 150) e energia alta, principalmente entre 30% e 95%.
O Cluster 2 (pontos laranjas) é caracterizado por músicas com BPM elevados (acima de 140) e níveis de energia variados, entre 10% e 90%.

- Insights

O K-Means identificou três padrões distintos: músicas mais lentas e energéticas (cluster 0), músicas de BPM médio com alta energia (cluster 1), e músicas rápidas com grande variação de energia (cluster 2). Esse tipo de análise pode ser útil para identificar padrões de gosto musical ou para recomendações de playlists personalizadas.


💡 Próximos Passos
Explorar outros algoritmos de machine learning, como Gradient Boosting e Support Vector Machines.
Ampliar as análises com dados sobre preferências de usuários e padrões de consumo em plataformas de streaming.
Implementar análises de séries temporais para prever tendências futuras de popularidade musical.

✨ Conclusão
Este repositório reflete meu esforço contínuo em aprimorar minhas habilidades em estatística e ciência de dados, aplicando técnicas avançadas em um contexto prático de análise de dados musicais. Sinta-se à vontade para explorar, fazer perguntas ou contribuir com o projeto!