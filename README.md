# Lista de Personagens da Marvel 

Aplicativo para teste de desenvolvimento consumindo a api:  [marvel api](https://developer.marvel.com/docs) 

## Objetivo: 

*  Listagem de personagens:

* Detalhes do Personagem:

* Exiba a imagem do personagem, o nome, a descrição e um botão de direcionamento para a uma tela que mostre qual a HQ mais cara daquele personagem.

* Detalhe da HQ mais cara do personagem:

* FaC'a o consumo da API de listagem de HQs por personagem: "/v1/public/characters/{characterId}/comics";
* Exiba na tela somente a revista mais cara daquele personagem com imagem, tC-tulo, descriC'C#o e o preC'o.


## Arquitetura utilizada

MVVM (Movel-View-ViewModel) with Coordinator


## Dependências externas

#### Alamofire 


## Como compilar

1. Instale o CocoaPods: https://cocoapods.org/
2. No terminal, entre na pasta onde se encontra o arquivo 'Podfile' e digite: `pod install`
3. Abrir o projeto pelo arquivo **`desafio-ios-rodrigo-albuquerque.xcworkspace`**
4. Atualizar a SwiftVersion das dependencias externas(Alamofire, AlamofireObjectMapper, ObjectMapper) para 4.2
5. Command+R paraexecutar o aplicativo e Command+U para executar os testes.

## Features Desenvolvidas

#### Listagem de personagens:

* FaC'a o consumo da API de listagem de personagens: "/v1/public/characters"; 
* Exiba o nome e foto de cada personagem;
* Ao selecionar o personagem, deverC! direcionar para a tela de detalhes.


#### Detalhes do Personagem:

* Exiba a imagem do personagem, o nome, a descrição e um botão de direcionamento para a uma tela que mostre qual a HQ mais cara daquele personagem.


####  Detalhe da HQ mais cara do personagem:

* FaC'a o consumo da API de listagem de HQs por personagem: "/v1/public/characters/{characterId}/comics";
* Exiba na tela somente a revista mais cara daquele personagem com imagem, tC-tulo, descriC'C#o e o preC'o.


## Desenvolvimento

### Rodrigo Prado de Albuquerque
#### ralbuquerque.info@gmail.com






