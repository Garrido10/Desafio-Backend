#Desafio back-end para cadastro de Pessoas e Endereços

Aplicação feita em Spring Boot 2.3.4 para realizar o cadastro de pessoas e em seguida as relacionando com seu endereço consultado através do CEP, 
utilizando a API externa do endereço https://viacep.com.br/ws/01001000/json/ para realizar as consultas.

A aplicação consiste em:

Cadastro Pessoa com Endereço = POST;

Cadastro Pessoa sem Endereço = POST;

Atualizar Cadastro = PUT;

Consulta de Cadastro = GET;

Consulta de CEP = GET;

A entidade Pessoa possui Nome, CPF, RG e Endereço. 

Aa entidade Endreço possui CEP, Rua, Número, Bairro, Cidade e Estado.

PARA TESTAR A APLICAÇÃO:

Clonando o repositório será possível importar o projeto no Spring Boot e importar o arquivo de testes no Postman, disponível neste Git junto com a aplicação.

Nome do arquivo: "Desafio Backend - Garrido.postman_collection"

