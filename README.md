# bimestral
 Calcular el área de un triángulo equilátero
## variables de entrada:
*numerica:* lado;
## variables de salida:
*numerica:* area;
## proceso:
area = (lado * lado * (3 ** 0.5)) / 4;
imprime(area);

# Calcular la suma de los primeros n números 
## variables de entrada:
*numerica:* n;
## variables de salida:
*numerica:* suma;
## proceso:
pedir n
suma = (n*n+1)/2
*imprimir*(suma)

# Convertir una distancia en metros a pies
## variables de entrada:
*numerica:* metros;
## variables de salida:
*numerica:* pies;
## proceso:
pies = metros * 3.281;
*imprimir*(pies);

# Convertir una cantidad en atmósferas a Pascales
## variables de entrada:
*numerica:* atmósferas;
## variables de salida:
*numerica:* Pascales;
## proceso:
Pascales = atmósferas * 101325;
*imprimir*(Pascales);

# Crear y subir un repositorio a Github
## variables de entrada:
*cadena:* nombre_repositorio;
*cadena:* descripcion;
*cadena:* nombre_usuario;
*cadena:* token_acceso; 
## variables de salida:
*cadena:* url_repositorio;
## proceso:
1. Crear una cuenta en Github si aún no tienes una.
2. Utilizar el token de acceso para autenticarse en Github.
3. Crear un nuevo repositorio con el nombre especificado en la variable "nombre_repositorio".
4. Agregar una descripción del repositorio en la variable "descripcion".
5. Inicializar el repositorio con un archivo README.md.
6. Realizar el primer commit y hacer un push a la rama principal del repositorio.
7. Asignar el nombre de usuario especificado en la variable "nombre_usuario" como colaborador del repositorio.
8. Generar la URL del repositorio en base a la información proporcionada.
9. Asignar la URL del repositorio a la variable "url_repositorio".
10. Imprimir en pantalla la URL del repositorio utilizando la función "imprimir".

# Calcular el módulo de dos números
## variables de entrada:
*numerica:* num1;
*numerica:* num2;
## variables de salida:
*numerica:* modulo;
## proceso:
1. Dividir el primer número "num1" por el segundo número "num2".
2. Obtener el residuo de la división anterior utilizando el operador módulo (%).
3. Asignar el residuo a la variable "modulo".
4. Imprimir en pantalla el valor de la variable "modulo" utilizando la función "imprimir".
