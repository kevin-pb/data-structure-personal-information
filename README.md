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

JSON was the easiest data structure to work with because of the simplicity of its code. JSON is based on the creation of objects from blocks of code. In these blocks of code, information about the object in question is placed, from which objects are created for each person. To represent addresses, a list of objects is created, each of these objects being an address assigned to the person.

[JSON](https://github.com/kevin-pb/data-structure-personal-information/blob/master/person.json)

## 3- YAML( Ain't Markup Language)

The YAML follows a tab-based hierarchy structure. In the YAML I used lists to represent all the information including the address information.

[YAML](https://github.com/kevin-pb/data-structure-personal-information/blob/master/person.yaml)

## 4- TOML (Tom's Obvious Minimal Language)

TOML follows a simple key-value structure. Use key-values ​​to represent information about people and use lists for addresses.

[TOML](https://github.com/kevin-pb/data-structure-personal-information/blob/master/person.toml)

## 5- XML (eXtensible Markup Language)

XML sigue un sistema de etiquetas mediante las cuales puedes almacenar información, es algo similar al HTML con la diferencia de que las etiquetas las pones tú. Había dos posibles soluciones, la primera era la de crear un solo tag y colocarle la información como atributos y la otra era la de crear varios tags para guardar la información. Por comodidad y gusto personal decidí usar la segunda opción.

[XML](https://github.com/kevin-pb/data-structure-personal-information/blob/master/person.xml)

## 6- INI (windows INItialization file)

In the INI file, it was easy to represent the information using the key value, and to represent the date I used a list. In INI there are several ways to make lists:

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

For convenience I use the general with the comma_separated_value.

[INI](https://github.com/kevin-pb/data-structure-personal-information/blob/master/person.ini)