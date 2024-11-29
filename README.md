# Saludos en Go

Este paquete proporciona una forma simple de obtener saludos personalizados en Go.

## Instalación
Ejecuta el siguiente comando para instalar el paquete:

```bash
go get -u github.com/albertomino/greetings
```

## Uso
Aquí tienes un ejemplo de cómo utilizar le paquete en tu código

```go
package main

import (
	"fmt"
	"github.com/albertomino/greetings"
)

func main() {
	message, err := greetings.Hello("Betun")
	if err != nil {
		log.Fatal(err)
	}
	fmt.Println(messages)
}
```
