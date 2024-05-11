## Descripción general
La implementación que se encuentra en esta librería corresponde a la prueba Marlin descrita en el [paper](https://ia.cr/2019/1047.pdf) e implementada en [Rust](https://github.com/arkworks-rs/marlin) con algunas adaptaciones en el código para poder ejecutar mi [TFG](https://github.com/SaraSorianoRossa/TFG).

A esta implementación se han realizado tres modificaciones con tal de poder obtener un mejor rendimiento del algoritmo de Marlin:
1. [Primera modificación](https://github.com/SaraSorianoRossa/Marlin-v2)
2. [Segunda modificación](https://github.com/SaraSorianoRossa/Marlin-v3)
3. [Tercera modificación](https://github.com/SaraSorianoRossa/Marlin-v4)

Además de estas modificaciones se ha definido un [nuevo proceso inner](https://github.com/SaraSorianoRossa/New-inner) en el cual se comprobaba la veracidad de la abertura del polinomio $t(X)$.

## Ejecutar
Para ejecutar este programa es necesario tener previamente instalado cargo y rust. Una vez se tienen instaladas las librerías necesarias para poder ejecutar la prueba con esta versión es necesario estar en el directorio y escribir en la terminal:
```sh
cargo build --release
```

## Testear
En esta versión, igual que en el resto, se ofrece una serie de funciones para testear. Si se desea ejecutarlas para ver el resultado de ellas:
```sh
cargo test
```
