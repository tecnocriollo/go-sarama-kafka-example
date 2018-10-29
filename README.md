# go-sarama-kafka-example

## English
[Leer en Español](#español)

Example of using Kafka with GO and Sarama. Based on the examples from the official site, but structured in one folder for easy testing.

### Steps
Asumes that you have installed Go and you have set up the GOPATH and you have a little knowledge of Go.

1. Download and start kafka using the Quickstart from the official page 
    https://kafka.apache.org/quickstart
2. Get Sarama 
```import github.com/Shopify/sarama```
3. Clone this repository on the src folder in your GOPATH
4. Open a new terminal, go to src/go-sarama-kafka-example/consumer and run
```go run consumer.go```
5. Open a second terminal, make sure you can see the another terminal, go to src/go-sarama-kafka-example/producer and run
```go run producer.go```

You can check the messages received on the consumer. You can play with the code as you want to test different cases.


## Español

[Read in English](#english) 

Ejemplo de uso de Kafka con Go y Sarama. Basado en los ejemplos del sitio oficial, pero estructurados en una carpeta para probar facilmente.

### Pasos
Asume ya se tiene instalado Go y que se ha configurado la variable de entorno GOPATH adems de un pequeño conocimiento del lenguaje.

1. Descargar e iniciar kafka usando el quickstart de la página oficial 
    https://kafka.apache.org/quickstart
2. Obtener Sarama
```import github.com/Shopify/sarama```
3. Clonar este repositorio en el src del GOPATH definido
4. Abrir un terminal, ir a src/go-sarama-kafka-example/consumer y ejecutar
```go run consumer.go```
5. Abrir un segundo terminal, dejar visible el primero, ir a src/go-sarama-kafka-example/producer y ejecutar
```go run producer.go```

Con esto se debería verificar el envío de mensajes en el consumer. Puedes jugar con el código como quieras para probar distintas situaciones.
