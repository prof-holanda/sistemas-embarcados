# Exercícios
## Operações de Memória

1. Converta para a linguagem Assembly as operações a seguir:
    1. Mover o valor 5 para o acumulador A.
    
    2. Mover o valor 8 para o acumulador A e depois para o registrador R1.
    
    3. Atribuir o valor 30 para o endereço de memória 4 na RAM, copiar o valor deste endereço para o acumulador A e depois para o registrador R4.
    
    4. Copiar o valor contido no endereço de memória RAM armazenado no registrador R4 para o registrador R1.

2. Teste os trechos de Assembly no EdSim51. Descreva a operação que cada instrução realiza.

    1.
```assembly
MOV A, #4
```


    2.
```assembly
MOV A, #3
MOV R0, A
```


    3.
```assembly
MOV A, 4
MOV R4, A
; Atribua um valor qualquer no endereço 4 da RAM
```


    4.
```assembly
MOV 32, #10
MOV R7, 32
```


    5.
```assembly
MOV R1, #7
MOV 0, @R1
MOV 4, R1
; Atribua um valor qualquer no endereço 7 da RAM
```