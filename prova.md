# D

## Breu Introducció

D fou originat l'any 1999 per l'empresa **Digital Mars**, propietari de la qual **Walter Bright** amb primera versió estable el gener de 2007.

És un llenguatge **evolucionari**, el seu objectiu des d'un inici és substituïr un dels llenguatges més emprats en la actualitat, C++.

El que el caracteritza és la seva similaritat i conceptes heredats de C++, i la orientació a objectes influenciada per Java y C#.

Hello World en D:

~~~D
import std.stdio;

void main(){

	writeln("Hello World!");

}
~~~

---

## Paradigma

- Podem determinar que D és un llenguatge de programació **multiparadigma** ja que pot combinar-ne diferents.

- És **metaprogramat**, una línia en D pot significar-ne milions en la traducció a codi ensamblador.

- Com bé ja hem mencionat, és tambe **orientat a objectes** treballa amb herència simple, és a dir, com a màxim una subclasse podrà tenir una única superclasse.

- És un llenguatge **imperatiu i funcional**, per això l'hem definit com a multiparadigma. És capaç de declarar els canvis d'estat i el resultat final acaba sent un valor d'una composició d'aplicacions de funcions. A més també compte amb funcions d'ordre superior com map per a tractar llistes.

  ~~~D
  import std.stdio;
  
  ulong factorial(ulong n){
      if(n==0) return 1;
      else return n*factorial(n-1);
  }
  
  ulong fib(ulong n){
      if(n==0) return 0;
      else if(n==1) return 1;
      else return (fib(n-1)+(fibn-2));
  }
  
  void main(){
      writeln(factorial(5)); //imprimeix el factorial de 5
      writeln(fib(8));
  }
  ~~~

  

---

## Compilat o interpretat?

Sabem que és **compilat** per que el codi font es transforma a codi màquina creant un executable, per a després ser interpretat.

![Compilació i execució](https://github.com/Joang10/LP/blob/master/Compilat.png)

---

## Tipus

D té un sistema de tipus fort, estàtic i unsafe.

- **Fort**: No permet la barrejar ni de variables ni valors de diferents tipus.

  ![Tipat Fort](https://github.com/Joang10/LP/blob/master/TipusFort.png)

- **Estàtic**: Les comprovacions de tipus es realitzen a la fase de compilació, per així estalviar feina durant el període de execució.

- **Unsafe**: sabem que seria safe si **CAP PROGRAMA** pogués donar errors de tipus en temps d'execució, però el mateix llenguatge pot donar, per exemple, errors amb el treball amb punters en el període de execució.

  ![Tipat Unsafe](https://github.com/Joang10/LP/blob/master/TipusUnsafe.png)

---

## Principals Aplicacions

Com C++, un altre cop, les principals aplicacions de D són molt similars.

Principalment és un llenguatge de propòsit general i per a aplicacions, però, a més a més també inclou l'orientació a objectes, el qual el fa molt més capaç que no pas C/C++.

![PRO1 P79817](https://github.com/Joang10/LP/blob/master/PrincipalsApp.png)

---

## Similars

Com bé ja hem mencionat anteriorment, D es un redisseny de C/C++ que a més el preté substituir, donat el cas que la seva eficiència és la mateixa i en segons quines ocasions és un llenguatge més eficient, s'afegeix la orientació a objectes cosa la qual fa al llenguatge encara més competent i versàtil.

Té la mateixa expresivitat que C++, té una sintaxis i unes construccions que el fan encara més senzill i igual de eficient.

A més, te control d'excepcions i orientació a objectes, que com ja hem dit abans, és influenciada per Java i C#.

![Similaritat C++ i D](https://github.com/Joang10/LP/blob/master/Similars.png) 

---

## Exemples

![Exemple 1](https://github.com/Joang10/LP/blob/master/Exemples1.png)

![Exemple 2: P37500 de PRO1](https://github.com/Joang10/LP/blob/master/Exemples2.png)

## Bibliografía i webgrafía





