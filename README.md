## ¿QUÉ ES SQL?

    Structured Query Language ➡ Lenguaje de consultas estructuradas.
    Es un lenguaje de programación estándar utilizado para gestionar y 
    manipular bases de datos relacionales.

## ¿QUÉ HACER EN SQL?
    
    ➡ Administrar: Crear, Modificar, Eliminar; Bases de Datos, Tablas u Objetos.
    ➡ Solicitar: Realizar consultas de datos para obtener información específica.
    ➡ Restricciones: Aplicar reglas específicas a las tablas.
    ➡ Otras funcionalidades: Generar informes, Analizar datos, etc.

## Modelo ER
    Es un modelo de datos que representa la estructura de una base de datos de manera gráfica.

    ➡ Entidades: Representan objetos del mundo real que tienen una existencia independiente. 
       Ejemplo: Una universidad, las entidades son: "Estudiante", "Profesor" y "Curso".

    ➡ Atributos: Son las propiedades o características de las entidades. 
       Ejemplo: "Estudiante" tiene atributos como "Nombre", "Edad" y "Matrícula".
            ➡ Atributos simples: no pueden dividirse en subpartes más pequeñas, 
            "Edad" de un "Estudiante" no se puede descomponer en partes más pequeñas.
            ➡ Atributos complejos: pueden dividirse en subpartes más pequeñas que 
            tienen su propio significado, "Nombre Completo" puede dividirse en "Nombre" y "Apellido".
            ➡ Key: Son atributos identifican de manera única a una entidad dentro de un conjunto de entidades

    ➡ Relaciones: Describen cómo las entidades están asociadas entre sí. 
       Ejemplo: La relación entre "Estudiante" y "Curso" sería "Inscrito en"..

## Ejercicio 1 🤓☝🏻:
    
#### Pensar una *ENTIDAD* que tenga 5 atributos, 1 _Multivalor_ , 1 KEY.

    ➡ Entidad: Automovil
        ➡ Atributos
            ➡ Multivalor: Accesorios
            ➡ Key: Patente
            ➡ Atributo: Modelo
            ➡ Atributo: Marca
            ➡ Atributo: Color
![Diagrama ER ejercicio 1](./public/img/MERej1.png)

## Conceptos
    ➡ Tabla (Table): Organiza los datos en filas y columnas, 
    cada fila representa un registro único, y cada columna 
    representa un campo dentro del registro.
    ➡ Campo (Field): Es una columna en una tabla que representa 
    un atributo específico de los datos almacenados.
    ➡ Regristo (Record): Es una fila en una tabla que representa 
    una única instancia de los datos almacenados.