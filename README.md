# Backend para Home Broker/Tela de Cotações do Santander (Backend for Santander Home Broker)

**pt_BR:**

Backend para o clone da tela de cotações/home broker do Santander. Esse projeto foi feito na Santander Dev Week patrocionada pelo Santander. O projeto utiliza Maven, Spring, Hibernate e PostgreSQL.


**en:**

Backend for the clone of the Santander home broker. This project was done at Santander Dev Week sponsored by Santander. The project uses Maven, Spring, Hibernate and PostgreSQL.


## Documentação (Documentation)

**pt_BR:**

Para facilitar a documentação do projeto, é utilizada a especificação OpenAPI (OAS) para RESTful APIs através da interface provida pelo projeto Swagger. O swagger-ui pode ser acessado com `<seu-servidor-ou-localhost>/swagger-ui.html`. No swagger-ui você poderá consultar e testar as funcionalidades providas pela API REST desse projeto.

Se disponível, você pode estar testando a API pelo environment criado no Heroku pelo link disponível na seção de ![deployments](https://github.com/Yofiel/santander-homebroker-backend/deployments). Você pode acessar o serviço fornecido usando o endpoint `/stock`.

Segue prévia do swagger-ui:

![swagger-ui-example](https://user-images.githubusercontent.com/64466694/121282731-61783800-c8b0-11eb-9dac-4470e6733242.png)


Por questões de praticidade, um arquivo JSON com as definições da API está no repositório. Procure por `api-docs.json`.


**en:**

To help with project documentation, the OpenAPI specification (OAS) for RESTful APIs is used with the graphical interface (web based) provided by the Swagger project. The swagger-ui can be accessed with `<your-server-or-localhost>/swagger-ui.html`. With swagger-ui you will be able to consult and test the functionalities provided by the REST API of this project.

If available, you can test the API via Heroku through the link available in the section of ![deployments](https://github.com/Yofiel/santander-homebroker-backend/deployments). You can acess the service provided using the `/stock` endpoint.

Look above for a preview of swagger-ui.

For practicality reasons, a JSON file with the API definitions is in the repository. Search for `api-docs.json`.
