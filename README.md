# IN8 Shop

> Esse repositório foi criado com o intuito de centralizar algumas informações sobre o projeto feito.

O Repositório dos dois projetos pode ser encontrado nos links abaixo. 

- [Backend](https://github.com/vasconceloscezar/in8_shop_api) </br>
- [Frontend](https://github.com/vasconceloscezar/in8_shop_app)


## Overview do projeto. 
> Um resumo geral do projeto, visto que há mais detalhes dentro de cada repositório mo `readme`, além de instruções de instalação e também alguns detalhes como tomadas > de decisão durante o desenvolvimento. 

O projeto foi feito em duas partes:

- Uma `API Rest` escrita em `TS` utizando `NodeJS`; 
- Um `App` escrito em `dart` utilizando `Flutter`;

Durante todo o desenvolvimento do projeto, utilizei o [GitHubProjects](https://docs.github.com/en/issues/planning-and-tracking-with-projects/creating-projects/creating-a-project) para organizar e centralizar as tarefas, e como separar o desenvolvimento por PRs, cada nova feature foi sendo vinculada com a respectiva PR. [Aqui](https://github.com/users/vasconceloscezar/projects/3/views/2) pode ser visualizado todas as issues criadas, junto com as PRs.  

### API 

Optei por iniciar o projeto pela API, para deixar tudo pronto e depois só consumir os dados no `front`. 
Decidi reunir as chamadas dos dois `providers` dentro de uma request só da API criada, assim o consumidor final busca todos produtos por lá. 

Venho estudando sobre Arquitetura Limpa, e tentei aplicar nessa API. Gostei do resultado mesmo tendo um pouco mais de dificuldade por conta das abstrações. 

No final gostei do resultado e muito do que eu utilizei nessa API vou reaproveitar em futuros projetos pessoais. 

### APP

`Flutter` não era utilizado no dia a dia por mim, fiz manutenção em alguns apps, mas nunca criei um projeto utilizando o sdk. 
Resolvi apostar em um template de e-commerce previamente pronto, pois assim eu perderia mais tempo nas funcionalidades e menos no layout em geral, como sou de aprender fazendo, preferi esse método e acredito que foi mais eficiente. 

Em geral o resultado do app ficou bom, mas sinto que pela minha falta de experiência com Flutter posso ter deixado a desejar em alguns pontos. Mas gostei muito do que aprendi enquanto realizei o projeto, e a experiência como dev foi muito prazerosa. Com certeza vou utilizar Flutter em próximos app que criar. 
