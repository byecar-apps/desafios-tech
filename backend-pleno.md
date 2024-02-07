### Descrição
#### Aplicação principal
Você deverá criar uma aplicação com Laravel 10 e Nginx, que tenha uma tela de edição e listagem de veículos com os dados: id (uuid), nome do veículo (varchar 150), código fipe (varchar 15) e preço (decimal 18,2).

OBS: O front pode ser com blade, vue, react, etc. É indiferente. Também não avaliamos o design das telas, apenas o funcional.
Esta aplicação deverá gerar uma imagem docker para deploy com Github Actions e um WebApp da Digital Ocean. O banco de dados poderá ficar na mesma imagem docker (mysql ou sqlite).

Envie as instruções para deploy e/ou o link de uma aplicação funcional para o email abaixo.

#### Aplicação secundária
Para alimentar a aplicação principal, crie um script em python que busque 10 modelos de veículos (carros) aleatórios no [site da FIPE](https://veiculos.fipe.org.br/) e armazene diretamente no banco de dados.
Esta aplicação não precisa ser armazenada na nuvem, pode ser enviada com instruções de configuração do ambiente para o email abaixo.

#### Envio do desafio
Envie o link dos 2 repositórios criados, juntamente com as instruções para subir os ambientes para tiago@byecar.com.br
