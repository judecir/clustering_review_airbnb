# Informações

Segmentação (clustering) das reviews de Airbnb do Rio de Janeiro. O objetivo é analisar as reviews e buscar algum padrão no comportamento. Como há reviews em vários idiomas, então é necessário criar a feature 'language' nos dados.

O critério para escolha do método foi o critério da silhueta, que vai de -1 a 1. Quanto maior esse score melhor a qualidade dos grupos criados. O mesmo método foi escolhido para estimar a quantidade de grupos, contudo, em geral, essa informação também pode ser alinhado com a área de negócio.

Analisando a estrutura da solução, podemos verificar na nuvem de palavras temáticas obtidas em cada cluster.

# Ideias de trabalhos futuros

1. Testar outras funções de distâncias;
2. Testar outros métodos de agrupamento;
3. Corrigir possíveis erros ortográfica (biblioteca hunspell);
4. Desenvolver clusters para cada idioma;
5. Adicionar nas features do agrupamento variáveis dos imóveis alugados, como price, room_type, etc.