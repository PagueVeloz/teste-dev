# Avaliação de Código

Instruções para realização do teste de código solicitado durante o processo de contratação.

**Ao concluir as implementações, disponibilize o código em um repositório público e nos encaminhe o link.**

## Instruções Iniciais

* Efetuar seu cadastro em https://sandbox.pagueveloz.com.br/cadastrar
    * É necessário utilizar um e-mail existente para que seja recebido o token de integração
    * Pode ser utilizado um serviço de e-mail temporário, sem problemas (https://temp-mail.org/pt)

* A documentação das API's pode ser visualizada em https://www.pagueveloz.com.br/help
    * As informações para realizar a autenticação da API estão no início da doc
    
* A url base para as requisições é https://sandbox.pagueveloz.com.br/api
    * Exemplo: GET https://sandbox.pagueveloz.com.br/api/v1/ping

## Implementações Solicitadas

* Implementar uma interface que permita a emissão de boletos
    * [API de emissão](https://www.pagueveloz.com.br/Help/Api/POST-api-v4-Boleto)
    
* Implementar uma interface para consulta (com filtros relevantes) dos boletos emitidos
    * [API de consulta](https://www.pagueveloz.com.br/Help/Api/GET-api-v4-Boleto_DataInicio_DataFim_Status_Documento_SeuNumero_IncluirCancelados_ApenasAgendados_NaoVisualizados)
    
* Permitir a visualização de boletos
    * A API de consulta retorna um campo URL para cada boleto ([campos](https://www.pagueveloz.com.br/Help/ResourceModel?modelName=ItemRelatorioBoletoDto))
    
* Permitir o cancelamento de boletos
    * [API de cancelamento](https://www.pagueveloz.com.br/Help/Api/DELETE-api-v4-Boleto-id)
