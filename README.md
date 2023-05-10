# SPD_Dojo1


## Integrantes 
- Nicolas Dekker
- Ivan Curto
- Tobias Esquivel
- Jorge Cabezas
- Silvina Gauto
- Alvaro Braddy Calla Huangal


## Descripción
El proyecto cumple la funcion de informar al usuario a estación de subte esta
llegando

## Función principal
Esta funcion se encarga de encender las partes del 7 segmentos para conseguir el numero 
deseado

#define A 7
#define B 8
#define C A1
#define D A2
#define E A3
#define F 6
#define G 5


~~~ c++
void prendeLed(int pin1, int pin2, int pin3,int pin4,int pin5,int pin6,int pin7)
{
  digitalWrite(pin1,LOW);
  digitalWrite(pin2,LOW);
  digitalWrite(pin3,LOW);
  digitalWrite(pin4,LOW);
  digitalWrite(pin5,LOW);
  digitalWrite(pin6,LOW);
  digitalWrite(pin7,LOW);
  delay(TIEMPO_ON);
  
}
~~~

## :Subte: Link al proyecto
- [proyecto](https://www.tinkercad.com/things/3AJxCEWCk9Y-shiny-juttuli-albar/editel?sharecode=skCBaNWChDs9K9cLDOGixHVa0cADXVyzZpssxic02vw)


---
### Fuentes
- [Consejos para documentar](https://www.sohamkamani.com/how-to-write-good-documentation/#architecture-documentation).

- [Lenguaje Markdown](https://markdown.es/sintaxis-markdown/#linkauto).

- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

- [Tutorial](https://www.youtube.com/watch?v=oxaH9CFpeEE).

- [Emojis](https://gist.github.com/rxaviers/7360908).

---





