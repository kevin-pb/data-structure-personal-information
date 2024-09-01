## Tipes of data structure

In this project we want to represent information in different data structures. The information we want to represent is the name, age, sex, status and addresses corresponding to people and the data structures in which I want to represent this information are:

### 1- CVS(Coma Separed Value)

CSV (Comma Separated Value), as the name implies, is a data structure where values ​​are separated by commas. CSV is readable by programs like Excel, with commas defining the columns. When I wanted to represent the information in CSV, I ran into a problem. This was that one of the data, to be more specific, the addresses could not be represented in a common way. I came up with two possible solutions; one was to duplicate the information so that the addresses matched their respective persons and the other was to create a separate file where the addresses could be placed.

#### Metod 1 :

[File_1](https://github.com/kevin-pbdata-structure-personal-information/blob/master/person_metod_1_file_1%20.csv)

[File_2](https://github.com/kevin-pb/data-structure-personal-information/blob/master/person_metod_1_file_2.csv)

#### Metod 2:

[Metod_2](https://github.com/kevin-pb/data-structure-personal-information/blob/master/person_metod_2.csv)

## 2- JSON(JavaScript Object Notation)

El JSON fue la estructura de datos más sencilla de trabajar por la simpleza de su código. El JSON se basa en la creación de objetos que a partir de bloques de código. En estos bloques de código se coloca información sobre el objeto en cuestión, a partir de eso cree objetos para cada persona. Para representar las direcciones, cree una lista de objetos, siendo cada uno de esos objetos una dirección asignada a la persona.

[JSON](https://github.com/kevin-pb/data-structure-personal-information/blob/master/person.json)

## 3- YAML( Ain't Markup Language)

El YAML sigue una estructura de jerarquía basada en las tabulaciones. En el YAML usé listas para representar toda la información incluida la de las direcciones.

[YAML](https://github.com/kevin-pb/data-structure-personal-information/blob/master/person.yaml)

## 4- TOML (Tom's Obvious Minimal Language)

El TOML Sigue una estructura clave valor simple. Use el clave valor para representar la información de las personas y para las direcciones use listas.

[TOML](https://github.com/kevin-pb/data-structure-personal-information/blob/master/person.toml)

## 5- XML (eXtensible Markup Language)

XML sigue un sistema de etiquetas mediante las cuales puedes almacenar informacion, es algo similar al HTML con la diferencia de que las etiquetas las pones tu. Habia dos posibles soluciones la primera era la de crear un solo tag y colocarle la informacion como atributos y la otra era la de crear varios tags para guardar la informacion. Por comodidad y gusto personal decidi usar la sengunda opcion.

[XML](https://github.com/kevin-pb/data-structure-personal-information/blob/master/person.xml)

## 6- INI (windows INItialization file)

En le archivo ini mediante el clave valor fue sencillo el representar la informacion y para crepresentar la fecha use una lista. En ini hay varias formas de hacer listas:

### [General]
comma_separated=Value1, Value2, Value3

semicolon_separated=Value1; Value2; Value3

space_separated=Value1 Value2 Value3

### [multi_line]
key=Value1

key=Value2

key=Value3

### [numbered_keys]
key1=Value1

key2=Value2

key3=Value3

### [indexed_keys]
key[0]=Value1

key[1]=Value2

key[2]=Value3

Por combeneiencia use el general con el comma_separated_value.

[INI](https://github.com/kevin-pb/data-structure-personal-information/blob/master/person.ini)