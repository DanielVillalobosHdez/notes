#PROGRAMACIÓN

## LINUX
* FHS: gerarquia de sistemas de ficheros
* nombre completo del archivo: ruta y nombre del archivo
```
EJEMPLO

/home/usuario/programación/c.txt
```

* NTFS: diario, no realiza las operaciones, las apunta y posteriormente las realiza.

```
2 bytes = 1 palabra
8 bytes = 1 parrafo
2¹⁰ = 1024bytes = 1KB
2²⁰ = 1 MB
2³⁰ = 1 GB
2⁴⁰ = 1 TB
```
```
0 - 0000
1 - 0001
2 - 0010
3 - 0011
4 - 0100
5 - 0101
6 - 0110
7 - 0111
8 - 1000
9 - 1001
A - 1010
B - 1011
C - 1100
D - 1101
E - 1110
F - 1111
```
* información: reducir posibilidades
```
I=-log2P(x)

I: información
-log2: menos logaritmo en base dos
P(x): probabilidad

1.__________________
I=-log2P(x)
I=-log2(1/27)
I=-log2(0.037)
I= 4'75
2.__________________
I=-log2P(x)
I=-log2(1/27)
I=-log2(1)+log2(27)
I=0+4'75
I=0'75
3.__________________
I=-log2P(x)
I=-log2(1/27)
I=-log2(1/27)-¹
I=-log2(27)
I=4'75
_____________________
```
```
comilla simple (''): el número asociado a un caracter
en C: al final se pone un valor centinela (0)
char (byte - 8 bits): caracter
string (valor centinela)
estenografia: meter codigo en una imagen
null: final de cadena de caracteres
10 --> '\n' --> '\012' --> '\x10' (LF: salto de linea)
```
### HELLO WORLD EN C
```
#include <stdio.h>
int main(){
	prinf ("HOLA MUNDO\n");
	return 0;
}
```

## CARPETAS LINUX

* /home: contiene las carpetas personales de cada usuario
* /bin: ejecutables
* /sbin: ejecutables del administrador
* /etc: configuración de los programas
* /boot: menú de arranque
* /var: documentos que varian
* /tmp: archivos temporales
* /svr: ficheros que sirve un servidor
* /media: se montan las unidades externas
* /opt: los programas guardan las extensiones
* /root: procesos del sistema
* /usr: carpetas de la distro

* PATH: variable que contiene la lista de todos los ejecutables

```
export PATH=$PATH:$HOME
```

