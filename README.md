Francisca Villarroel
Desarrollo Orientado a Objetos I
Duoc UC
# Llanquihue Tour

## Descripción

Llanquihue Tour es un proyecto desarrollado en Java como parte de la asignatura Desarrollo Orientado a Objetos I.

El sistema representa de manera básica la gestión de personas vinculadas a una agencia de turismo mediante la aplicación de conceptos fundamentales de Programación Orientada a Objetos (POO), tales como encapsulamiento, herencia, composición y reutilización de clases.

## Objetivo

Diseñar e implementar un modelo de clases que permita representar la información de los guías turísticos de la agencia, incorporando direcciones y datos personales de manera estructurada.

## Estructura del proyecto

### Paquete model

Contiene las clases del dominio del sistema:

#### Direccion

Representa la dirección de una persona.

Atributos:

* Calle
* Número
* Comuna
* Región

#### Persona

Clase base que almacena información general de una persona.

Atributos:

* Rut
* Nombre
* Teléfono
* Correo electrónico
* Dirección

#### GuiaTuristico

Clase que hereda de Persona y representa a un guía turístico.

Atributos adicionales:

* Especialidad
* Años de experiencia

### Paquete app

#### Main

Clase principal encargada de crear objetos y mostrar la información por consola para comprobar el funcionamiento del sistema.

## Conceptos de POO aplicados

* Encapsulamiento mediante atributos privados.
* Uso de constructores para inicializar objetos.
* Métodos getters y setters para acceder a los atributos.
* Sobrescritura del método toString().
* Herencia entre Persona y GuiaTuristico.
* Composición entre Persona y Direccion.

## Ejecución

1. Abrir el proyecto en IntelliJ IDEA.
2. Compilar el proyecto.
3. Ejecutar la clase Main ubicada en el paquete app.
4. Verificar la salida de los datos de los guías turísticos en la consola.

## Autor

Francisca Villarroel

## Asignatura

Desarrollo Orientado a Objetos I

## Institución

Duoc UC

## Seccion
004A


