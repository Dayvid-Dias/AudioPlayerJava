# AudioPlayerJava

Este é o **projeto final do curso "Java: Aplicando a Orientação a Objetos" da Alura**, desenvolvido para praticar conceitos fundamentais da **Programação Orientada a Objetos (POO)**, como herança, polimorfismo e encapsulamento.

O sistema simula a reprodução de **músicas** e **podcasts**, permitindo reproduzir, curtir, classificar conteúdos e exibir informações detalhadas de cada mídia.

## Funcionalidades

- Classe base `Audio` com título, duração, total de reproduções, curtidas e classificação.
- Subclasses `Musica` e `Podcast` com atributos específicos.
- Métodos para:
  - Reproduzir e curtir áudios.
  - Exibir informações detalhadas.
  - Classificar conteúdos com base em notas de 1 a 5.

## Tecnologias usadas

- **Java SE**  
- Conceitos de **POO** (herança, encapsulamento, polimorfismo)

## Estrutura do projeto

```
src/
└─AulaModulo2/
   ├─ modelos/
   │   ├─ Audio.java
   │   ├─ Musica.java
   │   └─ Podcast.java
   └─ Principal.java
```

## Como rodar

1. Certifique-se de ter o **Java JDK** instalado.
2. Baixe ou clone este repositório.
3. Compile e execute o arquivo `Principal.java`:
    ```bash
    javac Principal.java
    java Principal
    ```

## Exemplo de uso

```
Título: Believer
Nome do Artista: Imagine Dragons
Nome do álbum: Evolve
Duração da Música: 4 minutos
Gênero da música: Pop Rock

Classificação: 5 estrelas - Excelente

Reproduzindo episódio 101 do podcast: The Daily

Título: The Daily
Nome do Apresentador: Michael Barbaro
Número do episódio: 101
Duração do episódio: 25 minutos

Classificação: 5 estrelas - Excelente
```

## Licença

Este projeto é livre para uso educacional.
