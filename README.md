# Práctica 1
## Índice

- [Ajedrez](#ajedrez)
- [Mondrian](#mondrian)
- [Píxel más claro y oscuro](#píxel-más-claro-y-oscuro)
- [Pop art](#pop-art)

## Ajedrez

### Versión sin IA:

En esta tarea se ha realizado un tablero de ajedrez utilizando una medida de 800 de largo y 800 de ancho, teniendo cada casilla un tamaño de 100x100. Una vez establecida la medida se procede con el método que crea una matriz de ceros con dicha medida:  
  
**np.zeros((medida,medida,1), dtype = np.uint8)**  
  
Al ser creadas con ceros nos aseguramos que toda la imagen tenga un color negro y lo que se hará a continuación será rellenar con cuadrados blancos de tamaño 100x100 en los huecos correspondientes, "ahorrando" pintar los cuadrados negros al ser el fondo de dicho color.  
Recorremos la imagen mediante 2 bucles **for** con rango 8 cada uno (8x8= 64 casillas del tablero) buscando las posiciones de las casillas pares y pintando estas de color blanco asignando el valor 255:  

**img_tarea[100*i:100*(i+1),100*j:100*(j+1)] = 255**

### Versión con IA:

## Mondrian

## Píxel más claro y oscuro

## Pop art
