# Sesi-n7-tarea-individual
NOMBRE: Jorge Ruiz Soriano

Tarea de Sesión 7 - GitHub


Los ejercicios del tema de Shell Scrip son los siguientes:

1- (0,75 punto) Haz un script que calcule un número factorial pedido por pantalla: 

Un número factorial se calcula de la siguiente manera:

	N!=1 x 2 x 3 x 4 x…x (n-1)  x N

Por ejemplo, el 5 factorial (escrito 5!) sería:

	5!=1 x 2 x 3 x 4 x 5=120





2- (0,70 puntos) Escribe un script que usando bucles y de un número X, número pedido, muestre las tablas de multiplicar en pantalla (del 1 a N, número pedido). 

 

3- (0,70 puntos)  Escribe un script que calcule el tamaño de una lista de dimensión desconocida.
La lista está contenida dentro del script.
Por ejemplo estas listas:
	LISTA1="Lentejas Guistantes Huevos Naranjas Peras Manzanas Sandía Macarrones Tomate"
	LISTA2="Rojo Azul Amarillo Blanco"
	LISTA3="1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18"


(0,80 puntos) Escribe un script que pida un password por teclado, lo compare con el password guardado en el fichero password.txt (solo contiene el password) y hasta que no coincidan no te deje continuar




4- (0,70 Puntos) Haz un script que calcule la letra de un DNI.  Se pedirá el DNI por teclado y devolverá el DNI completo.

Para calcular la letra, se usa el resto de dividir el número de DNI entre 23, el resultado debe estar entre 0 y 22 el cual debe recorresponder con una letra de la siguiente tabla:

RESTO	LETRA		RESTO	LETRA
0	T		12	N
1	R		13	J
2	W		14	Z
3	A		15	S
4	G		16	Q
5	M		17	V
6	Y		18	H
7	F		19	L
8	P		20	C
9	D		21	K
10	X		22	E
11	B			

Por ejemplo, si se introduce 70588387, deberá devolver la letra ‘F’.


5- A- (1 punto) Haz un script que cree archivos dentro de un directorio llamado FILES/ con la siguiente sintaxis:
FILES/fileXY

Donde:
	FILES es el directorio que hay que crear y depositar dentro los ficheros.
	X es un valor del 1 al X (introducido por pantalla).
	Y es un valor de la A a la E

B- (1 Punto) Haz un script que verifique dentro del directorio FILES/ que existe el nombre de un archivo pasado por consola.


C- (0,50 Puntos) Modificar los permisos de todos los archivos dentro de FILES/ de la siguiente manera:

	rwx – rw- - r-- 	Contiene el número 4
	rw- – rw- - rw- 	Contiene el número 3
	rw- – r-x - rwx 	Contiene el número 1






6- Escribe un script que genere el siguiente menú (0,25 Puntos):


	Añadir
	Mostrar
	Ordenar
	Buscar
	Elimnar
	Salir

El menú no hace falta que aparezca cada vez que se seleccione una opción. Cada opción, por orden, debe realizar la siguiente acción:
	(0,50 Puntos) Añadir palabra en el fichero “nombres.txt”.
	(0,40 Puntos) Mostrar palabras del fichero
	(0,50 Puntos) Mostrar palabras alfabéticamente (no modifica el fichero)
	(1 Punto) Buscar si existe una palabra y decir nº de línea (no modifica el fichero)
	(1,10 Punto) Eliminar palabra (modifica el fichero)
	(0,10 Puntos) Salir del programa
El fichero se llama “nombres.txt” y en cada línea del fichero es un nombre.

