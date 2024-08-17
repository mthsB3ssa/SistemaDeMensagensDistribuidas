# Sistema de Mensagens Distribuídas

Este projeto implementa um sistema básico de mensagens distribuídas utilizando RabbitMQ e Golang. A estrutura divide os componentes em produtores e consumidores
## Pré-requisitos

Antes de iniciar, você precisará ter o RabbitMQ instalado em seu sistema. Para instalá-lo no Ubuntu, execute o seguinte comando no terminal:

```bash
sudo apt install rabbitmq-server
```

Feita a instalação, abra 2 terminais diferentes, um com o diretorio `consumer` e outro com o diretorio `producer`
Em um dos terminais, rode o consumer:
```bash
go run receive.go`
```
e em outro, rode o producer: 
```bash
go run send.go
```

Você pode abrir vários terminais e rodar vários "producers"

## Referências
[Tutorial RabbitMQ com Go](https://www.rabbitmq.com/tutorials/tutorial-one-go)

