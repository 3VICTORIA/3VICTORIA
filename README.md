# 3VICTORIA
## Documentación JS
Para ver toda la documentación referirse a mis archivos JS

## Sentencias básicas

### Switch

* Ejemplo piedra papel o tijera
``` javascript
function juego(parametro1, parametro2) {
    switch (parametro1) {
        case "tijera":
            switch (parametro2) {
                case "tijera":
                    console.log("Empate")
                    break;
                case "papel":
                    console.log("Gano parametro1")
                    break;
                case "piedra":
                    console.log("Gano parametro2")
                    break;
                default:
                    console.log("Parametro 2 debe arrojar un valor valido")
                    break;
            }
            break;
        case "papel":
            switch (parametro2) {
                case "tijera":
                    console.log("Gano parametro2")
                    break;
                case "papel":
                    console.log("Empate")
                    break;
                case "piedra":
                    console.log("Gano parametro1")
                    break;
                default:
                    console.log("Parametro 2 debe arrojar")
                    break;
            }
            break;
        case "piedra":
            switch (parametro2) {
                case "tijera":
                    console.log("Gano parametro1")
                    break;
                case "papel":
                    console.log("Gano parametro2")
                    break;
                case "piedra":
                    console.log("Empate")
                    break;
                default:
                    console.log("Parametro 2 debe arrojar valor")
                    break;
            }
            break;

        default:
            console.log("Parametro 1 debe arrojar valor")
            break;
    }
}; 



juego("piedra", "avion")
```