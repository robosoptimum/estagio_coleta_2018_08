# estagio_coleta_2018_08
Prova de seleção estagiários coleta

Faça um programa em python para consumir a API do Vagalume (https://api.vagalume.com.br/) e criar uma lista de artistas com dados relacionados. O programa de conter necessariamente:
 - Uma classe que faz as requisiçes para API, cujo construtor deve receber como parâmetro o nome do artista]
 - Classes para armazenar atributos do artista, ranking, gênero, músicas mais acessadas (toplyrics) e albus
 - Métodos para:
  - retornar as N músicas mais acessadas (N >= 1)
  - retornar a posição do artista no ranking
  - retornar o último álbum do artista
  - retornar as palavras mais frequentes nas letras de músicas mais acessadas do artista. **Diferencial** utilize uma lista de [stopwords] (https://en.wikipedia.org/wiki/Stop_words) para melhorar a análise das palavras mais frequentes
