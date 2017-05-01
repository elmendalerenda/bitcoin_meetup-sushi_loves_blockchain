
# Demo

1. Instalar `docker-compose`
2. Descargar el chaincode que esta en [hyperledger-example](https://github.com/elmendalerenda/Hyperledger-Example)
3. Editar [docker-compose.yml](https://github.com/elmendalerenda/bitcoin_meetup-sushi_loves_blockchain/blob/master/demo/docker-compose.yml) y editar el montaje del volumen en la linea 37 para que `starter` pueda acceder a hyperledger-example

4. Poner en marcha los dockers con `docker-compose up`
5. Entrar en `starter`, instalar ``go get github.com/op/go-logging`y compilar `go build test_contract.go`

