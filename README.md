# LEMP Stack (Nginx + PHP-FPM + MySQL)

Essa é uma simples implementação de uma LEMP Stack, que inclui o Nginx comunicando com o PHP-FPM e um container de base de dados MySQL.

## Dependências

- Docker [Instalação](https://docs.docker.com/engine/installation/#get-started)
- Docker-Compose [Instalação](https://docs.docker.com/compose/install/#install-compose)
- Um terminal qualquer

## Como utilizar

1. Clone o repositório
```sh
git clone git@github.com:DawTaylor/lemp-stack.git
```
2. Inicie os serviços
```sh
docker-compose up -d
```
3. Acesse [http://localhost:8000](http://localhost:8000) para testar se tudo funcionou.  
4. Seus arquivos devem ir para a pasta `src`.

## Como parar os serviços

Parando os serviços
```sh
docker-compose down
```

## Personalizar configurações

As configurações de do MySQL e de porta do container web ficam no arquivo `.env`.

Após alterar as configurações, pare e execute novamente os serviços.