### Descrição
#### Aplicação principal
Você deverá criar uma aplicação com Laravel 10 e Nginx, que tenha uma tela de edição e listagem de veículos com os dados: id (uuid), nome do veículo (varchar 150), código fipe (varchar 15) e preço (decimal 18,2).
OBS: O front pode ser com blade, vue, react, etc. É indiferente. Também não avaliamos o design das telas, apenas o funcional.
Esta aplicação deverá gerar uma imagem docker para deploy com Github Actions e um WebApp da Digital Ocean. O banco de dados poderá ficar na mesma imagem docker (mysql ou sqlite).

#### Aplicação secundária
Para alimentar a aplicação principal, crie um script em python que busque 10 modelos de veículos (carros) aleatórios no [site da FIPE](https://veiculos.fipe.org.br/) e armazene diretamente no banco de dados.

#### Envio do desafio
Envie o link dos 2 repositórios criados, juntamente com as instruções para subir os ambientes para tiago@byecar.com.br
