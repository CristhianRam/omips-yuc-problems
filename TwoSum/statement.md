
## Historia

Karel se encuentra explorando un antiguo pasillo lleno de montones de zumbadores. Su maestro le ha encomendado una tarea: descubrir si entre todos esos montones existen exactamente **dos distintos** cuya suma sea exactamente igual al número mágico **K**. Como Karel es un robot sumamente ordenado, los montones ya han sido organizados de menor a mayor cantidad de zumbadores.

## Problema

Dada una lista de montones de zumbadores ordenados de forma ascendente en la primera fila del mundo, y sabiendo que Karel lleva exactamente **K** zumbadores en su mochila, escribe un programa que determine si existen dos montones en posiciones diferentes que sumen exactamente **K**.

## Entrada

-   Karel inicia en la coordenada (1,1) orientado hacia el Este.
    
-   En la fila 1, a partir de la columna 1, hay una secuencia de celdas contiguas, cada una con un montón de zumbadores.
    
-   La cantidad de zumbadores en cada celda está **ordenada de menor a mayor** (pueden existir montones con la misma cantidad).
    
-   La secuencia termina en la primera celda vacía (0 zumbadores).
    
-   Karel lleva exactamente **K** zumbadores en su mochila (con **K** > 0).
    
-   El mundo no tiene paredes internas.
    

## Salida

-   Si **existe** un par de montones distintos cuya suma sea exactamente igual a **K**, Karel debe terminar su ejecución orientado al **Norte** y apagarse.
    
-   Si **no existe** ningún par que sume **K**, Karel debe terminar orientado al **Sur** y apagarse.
    
-   La posición final de Karel y los zumbadores que queden en el mundo no importan al momento de la evaluación.

## Ejemplo
Entrada:
![Mundo de entrada]()

Salida:
![Mundo de salida]()
    

## Consideraciones

-   El número de montones en el pasillo es al menos 2 y a lo sumo 100.
    
-   Un "par" obligatoriamente requiere usar dos montones en celdas diferentes. No es válido sumar un montón consigo mismo.
