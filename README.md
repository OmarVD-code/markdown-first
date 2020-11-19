<!-- Comment -->

# my title 1
## my title 2
### my title 3
#### my title 4
##### my title 5
###### my title 6

this is an *italic* text

this is an **strong** text

este es un texto ~~tachado~~

<!-- LISTA DESORDENADA -->
* Manzana
    * Manzana 2
* Naranja
    * Naranja 2
* Fresa
    * Fresa 2

<!-- LISTA ORDENADA -->
1. Manzana
    1. Manzana 2
2. Naranja
    1. Naranja 2
3. Fresa
    1. Fresa 2

<!-- Enlace -->
[Faztweb.com](https://www.faztweb.com "Custom title")

<!-- CITAS -->
> esto es una cita

<!-- GENERA SALTOS DE LINEA -->

---
___

<!-- Porciones de código -->
`console.log('hello world')`

```C++
//	Clases en C++

#include<iostream>
#include<conio.h>
using namespace std;

class Persona{
	private: // atributos
		int edad;
		string nombre;
	public: // métodos
		Persona(int,string); // constructor
		void leer();
		void correr();
};

Persona::Persona(int _edad, string _nombre){
	edad = _edad;
	nombre = _nombre;
}

void Persona::leer(){
	cout<<nombre<<" ha leido un libro"<<endl;
}

void Persona::correr(){
	cout<<nombre<<" ha corrido por la playa"<<endl;
}

int main(){
	Persona p1 = Persona(20,"Omar");
	Persona p2 = Persona(58, "Edwin");
	
	p1.leer();
	p2.correr();
	
	getch();
	return 0;
}
```

```python
print("hellow world")
```

```html
<h1>Title1</h1>
<h2>Title2</h2>
```


<!-- IMAGEN -->
![visual studio code logo](vscode_logo.png "vscodelogo")

<!-- GITHUB MARKDOWN -->
* [X] Task 1
* [ ] Task 2
* [ ] Task 3
* [X] Task 4

@warevil :smiley: :+1:

<!-- TABLAS -->
| Nombre        | Apellido      | Edad  |
| ------------- |:-------------:| -----:|
| *Iker*        | *Casillas*  | `40`    |
| **Sergio**       | **Ramos**    | `40`    |
| ~~Usuario~~       | ~~Desconocido~~  | `80`    |
    
