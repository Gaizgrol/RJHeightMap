# RJHeightMap

Repositório com os mapas de altitude, tipo de terreno e outras imagens do meu [trabalho final de Álgebra Linear](https://colab.research.google.com/drive/1JeulhMmxwGP0H9yFqCc5TwoVO8KlzRQY?usp=sharing) geradas utilizando terrain.party e o site da prefeitura do Rio de Janeiro.

## Informações

* [Link do Python Notebook do trabalho](https://colab.research.google.com/drive/1JeulhMmxwGP0H9yFqCc5TwoVO8KlzRQY?usp=sharing)

### Trabalho Final de Álgebra Linear Algorítmica (2019.1)

:technologist: Gabriel Izoton Graça de Oliveira

:email: gabrielizotongo@gmail.com

:thought_balloon: Tema: Previsão de Alagamentos e Deslizamentos (utilizando Gauss-Jordan)

O objetivo do trabalho é prever quais áreas de um determinado terreno ficarão alagadas ou terão deslizamentos dados o terreno, a pluviosidade e o tempo de chuva.

**Entrada:**

* Terreno
* Heightmap preto e branco do local
* Mapa dos tipos de solo do local
* Altura mínima do terreno (valor do pixel preto)
* Altura máxima do terreno (valor do pixel branco)
* Chuva
* Pluviosidade
* Tempo de chuva

Saída:

**Imagem**

* A imagem resultante será um mapa colorido. As áreas azuladas representarão o espaço com maior acúmulo de água. As áreas avermelhadas representarão locais de possíveis deslizamentos.

**Dados utilizados:**

* Terreno (36 km x 36 km)
* Heightmap preto e branco da cidade do Rio de Janeiro
* Mapa dos tipos de solo do local
* Altura mínima do terreno (valor do pixel preto)
* Altura máxima do terreno (valor do pixel branco)
