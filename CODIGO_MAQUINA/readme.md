5 + 11 = 16 --> M7  
 
0  ['00000100'],     + 5                                         
1		['00000101'],     + 11                                        
2		['01100111'],     Mover a la Memoria 7                        
3		['01110000'],     Fin                                         
4		['00000101'],                                                 
5		['00001011'],                                                 
6		['00000000'],                                                 
7		['00000000']                                                  

12 - 7 = 5 --> M6
0   00000111   +12
1
2
3
4
5
6
7   00001100
                                                                 
Códigos de operación:  
|  Inst  |  D  |  Comentario      |  
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





