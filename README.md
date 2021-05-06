# FSD01_Microservices_Serverless_Architecture

## Entrega do Trabalho - FSD01_Microservices_Serverless_Architecture



### Integrantes

* Alexandre Martins
* Camila Marcelino Rodrigues 
* Gercino Luiz da Silva Neto
* Luan de Oliveira Pereira
* Nikolas Mallmann Sugo



### Ambiente

1. Instalar Java 11
2. Criar as variáveis de ambiente


```
GITHUB_USER=alexmart001

GITHUB_PASS=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
```

3. Clonar o repositório, branch main

```
git clone https://github.com/alexmart001/FSD01_Microservices_Serverless_Architecture.git
```

4. Executar os comandos abaixo para iniciar os micro serviços

```
java -jar ./ibpf-config-server/ibpf-config-server-0.0.1-SNAPSHOT.jar
java -jar ./ibpf-eureka-server/ibpf-eureka-server-0.0.1-SNAPSHOT.jar
java -jar ./ibpf-user/ibpf-user-0.0.1-SNAPSHOT.jar 
java -jar ./ibpf-oauth/ibpf-oauth-0.0.1-SNAPSHOT.jar 
java -jar ./ibpf-lancamentos/ibpf-lancamentos-0.0.1-SNAPSHOT.jar 
java -jar ./ibpf-conta-saldo/ibpf-conta-saldo-0.0.2-SNAPSHOT.jar
java -jar ./ibpf-conta/ibpf-conta-0.0.1-SNAPSHOT.jar
java -jar ./ibpf-conta-corrente/ibpf-conta-corrente-0.0.2-SNAPSHOT.jar
java -jar ./ibpf-cartao-credito/ibpf-cartao-credito-0.0.1-SNAPSHOT.jar
java -jar ./ibpf-investimento/ibpf-investimento-0.0.1-SNAPSHOT.jar
java -jar ./ibpf-api-gateway-zuul/ibpf-api-gateway-zuu-0.0.1-SNAPSHOT.jar
```


Está disponível no root do repositório o arquivo com os EndPoints para o Postman.
* Impacta - IBPF.postman_collection.json
### Painel para Visualização dos Micro serviços

* http://localhost:8761



