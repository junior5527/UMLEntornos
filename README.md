/*# Diagrama de classes

## Animales

El siguiente diagrama representa la estructura de clases de Animales

```java
Class estudiante {
      static protected String tipo;
      private String nombre;
      List<Float> notas;

      public String getNombre(){
            return nombre;
      }

      public void setNombres(String nombre){
            this.nombre = nombre;
      }
}
```






```mermaid
classDiagram

class estudent{
void notas()*
}

Estudiante <-- Notas
```*/



/*# Diagrama de classes

## Animales

El siguiente diagrama representa la estructura de clases de Animales

```java
class Perro extends Animal{
  String raza;
  
  String morder(String cosa){
  
  @Override
  void(){
  
  }
  }
  
  abstract class Animal{
  void alimentar(){
   }
   abstract 
  }
}
```






```mermaid
classDiagram
class Perro{
  +String raza
  +morder(cosa: String): String
}

class Animal{
void sonar()*
}

Animal <-- Perro
```
*/
