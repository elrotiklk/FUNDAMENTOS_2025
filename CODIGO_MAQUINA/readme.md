5 + 11 = 16 
 
0       ['00000100'],     + 5                                       0   000
1		['00000101'],     + 11                                      1   001
2		['01100111'],     Mover a la Memoria 7                      2   010
3		['01110000'],     Fin                                       3   011
4		['00000101'],                                               4   100
5		['00001011'],                                               5   101
6		['00000000'],                                               6   110
7		['00000000']                                                7   111
                                                                    8  1000
Códigos de operación:
|  Inst  |  D  |  Comenatario      |
+--------+-----+-------------------+
|  0000  |  +  |  Suma             |
|  0001  |  -  |  Resta            |
|  0010  |  *  |  Producto         |
|  0011  |  ^  |  Exponente        |
|  0100  |  &  |  Operador AND     |
|  0101  |  |  |  Operador OR      |
|  0110  |  M  |  Mover a memoria  |
|  0111  |  …  |  Finalizar  


Memoria de 8 bytes, cada celda de memoria guarda 1 byte (8 bits)
Hay 8 instrucciones de 8 bits cada una.

 Una instrucción se puede interpretar de 2 maneras:
        1.- Código operación (primeros 4 bits) + posición memoria(los siguiente 4 bits)
        2.- Dato ó valor en binario(los 8 bits)
