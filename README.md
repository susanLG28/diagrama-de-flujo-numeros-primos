# Algoritmo para hallar números primos
Vamos a hacer un diagrama de flujo y un pseudocódigo para saber los numeros primos que hay hasta un numero n.

Los numeros primos son aquellos números que son divisibles entre 1 y ellos mismos, por ejemplo el 2,3,5.
### Pseudocódigo

bueno yo me ayude un poquito de IA pero no me sirvio de mucho asi que me toco modificarlo viendo que si sirviera claramente, tambien investigue sobre cosas que aparecian como por ejemplo el %. yo no sabia que eso en programación te da el residuo de la división.
    
    
    [variables]
    i=entero
    j=entero
    n=entero
    Inicio
        leer n
        Para i = 2 hasta N hacer
            esPrimo = verdadero
        
            Para j = 2 hasta i-1 hacer
                Si i % j == 0 entonces
                    esPrimo = falso
                    Romper el ciclo
                Fin Si
            Fin Para
        
            Si esPrimo == verdadero entonces
                Imprimir i
            Fin Si
        Fin Para
    Fin


### Diagrama de flujo
Para el diagrama de flujo use mermaid (como los verdaderos pros, no como noobs arrastrando bolitas y palitos) que fue recomendada por el profesor, al inicio me costo entenderla un poquito pero cuando uno le agarra la vuelta ya se pone facilito.


![image](https://github.com/user-attachments/assets/e0db1490-1593-4748-b726-51ee46057c1f)

![image](https://github.com/user-attachments/assets/421e5e9e-062e-4343-991e-e957a3a7fff2)


pd: perdon por algunas lineas que se cruzaron, no supe como arreglar eso.
    
