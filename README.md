# Sistema de Mensagens Distribuídas

Este projeto implementa um sistema básico de mensagens distribuídas utilizando RabbitMQ e Golang. A estrutura divide os componentes em produtores e consumidores
## Pré-requisitos

Antes de iniciar, você precisará ter o RabbitMQ instalado em seu sistema. Para instalá-lo no Ubuntu, execute o seguinte comando no terminal:

```bash
sudo apt install rabbitmq-server
```

Feita a instalação, abra 2 terminais diferentes, um com o diretorio `consumer` e outro com o diretorio `producer`
No terminal, rode o consumer: - `go run receive.go` 
e então, rode o producer: - `go run send.go`

Você pode abrir vários terminais e rodar vários "producers"


## Futuras implementações


## Referências
https://www.rabbitmq.com/tutorials/tutorial-one-go


# Sistema de Mensagens Distribuídas

Este projeto implementa um sistema básico de mensagens distribuídas utilizando RabbitMQ e Golang, dividindo os componentes em produtores e consumidores para demonstrar uma comunicação eficiente entre múltiplas instâncias. Antes de iniciar, você precisará ter o RabbitMQ instalado em seu sistema. Para instalá-lo no Ubuntu, execute o comando `sudo apt install rabbitmq-server`. Após a instalação do RabbitMQ, prepare o ambiente para rodar os componentes do sistema: abra dois terminais, navegue até o diretório `consumer` em um e `producer` no outro. Para iniciar o sistema, rode os componentes nos terminais preparados: no terminal do consumidor, execute `go run receive.go`; no terminal do produtor, execute `go run send.go`. Você pode iniciar múltiplos produtores abrindo novos terminais e executando o comando para rodar `send.go` em cada um. Para mais informações sobre como trabalhar com RabbitMQ e Go, visite a documentação oficial do RabbitMQ: [Tutorial RabbitMQ com Go](https://www.rabbitmq.com/tutorials/tutorial-one-go). Contribuições são bem-vindas! Sinta-se livre para forkar o repositório e submeter pull requests.
