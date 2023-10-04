# Objetivo
Este desafio tem por objetivo compreender as formas como você resolve um determinado problema. De acordo com o seu conhecimento de ferramentas e tecnologia
sua forma de resolver pode variar e ser mais ou menos detalhada. Não existe certo ou errado neste desafio, desde que o problema seja resolvido.

# Problema
Temos uma jornada de compra do nosso produto. Essa jornada possui 4 telas e uma aplicação no frontend foi construída para este processo. 
Na primeira tela, o front recupera informações de APIs externas.

Ao realizar uma integração com um parceiro, descobrimos que precisamos buscar informações em uma nova API, que vai retornar os 
dados do cliente do nosso parceiro, **então na primeira tela** da nossa jornada vamos receber um token do parceiro que vai nos dar acesso ao dados do cliente dele.

* O front precisa recuperar o token que chega via GET na URL. Parâmetro `token`;
* O backend vai receber o token do front e se comunicar com a API do parceiro para recuperar os registro do cliente;

1. Considerando as informações acima, descreva como seria a comunicação entre frontend > backend > API > backend > frontend;
2. Implemente uma classe que faz a recuperação do token chegando do front e consumindo uma API (fake).
   - A API só retorna dados dos clientes mediante o envio do token no cabeçalho;
   - A classe deve utilizar a estrutura de um projeto Laravel (controllers, services, etc) ou Nodejs;
   - O Laravel/Nodejs deve devolver dados cadastrais (nome, email, celular) para o front em formato json.
  
### Importante
- Não se preocupe com telas ou qualquer outra estrutura que não envolva o processo acima;
- Crie um repositório no github e envie o resultado para tiago[@]byecar.com.br em até 7 dias;
- Se tiver dúvidas entre em contato comigo pelo Linkedin https://www.linkedin.com/in/tiago-sabadini/
