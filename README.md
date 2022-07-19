# Navegg Backend Challenge - APIs de Entrada de dados
Nós trabalhamos com microserviços, e precisamos processar uma grande quatidade de informações, precisamos ser rápidos para não depreciar a experiencia dos usuários que estão navegando nos sites dos nossos clientes. 

Sendo assim o seu test será criar um conjunto de microserviços capaz de receber de forma efeiciente estes dados.

## Resumo
Tenha que no site de nossos clientes teremos a inclusão de um Javascript que ira nos enviar o seguinte conjunto de dados:

```json
{
    "site_id": "7a05f6b5-3285-42a8-83af-9067e29cb963",
    "url": "https://client.site.com/blog/same-page-accessed",
    "context": ["noticia", "culinaria", "vegano"],
    "user": {
        "id": "73e11ba9-a12c-4ab8-9648-e65e8d7c4d9e",
        "device": "Mozilla Firefox"
    }
}
```

Com isto precisamos de uma API para receber este dados e persistir o mesmo o mais rápido possivel.

Precisamos relacionar (persistir) este acesso com o site do nosso cliente, de forma que seja possivel rastear os acessos que o site obteve durante um determinado periodo.

Ainda precisamos relacionar o nosso usuário com o contexto (`context`) do site de forma que seja possivel saber todos os contextos acessados por uma determinado user em um espaço de tempo.

## O que sua entrega precisa ter
1. Precisa rodar;
2. Precisa ter uma documentação de como rodar;
3. O código deve deve ser legivel;
4. Deve atender os requisitos

## O que será avaliado
 1. Separação de responsabilidade do(s) serviço(s);
 2. Caso necessária, a comunicação entre os serviços;
 3. Conceitos de Restful;
 4. Utilização de recursos adequados;
 5. Versionamento de código;
 6. Possuii documentação da(s) API(s) Restful

## Diferencial
1.  Utilizar o framework django;
2. Utilizar o docker ou algum ambiente de container para rodar;
3. Testes unitários, sugestão pytest

## Como devo iniciar e finalizar

Para realizar iniciar você deve fazer um fork deste projeto, e quando finalizar deve abrir um PR, caso queira pode entrar em contato com o Recutador para avisa que terminou, mas é importante abrir o PR.
