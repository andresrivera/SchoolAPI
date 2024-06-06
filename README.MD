# SchoolAPI

Las escuelas enfrentan el desafío de gestionar de manera eficiente la información de sus
alumnos, profesores, cursos y matrículas. Un sistema manual o fragmentado puede
generar ineficiencias, errores y pérdida de datos importantes. Un sistema centralizado y
automatizado permitiría optimizar la gestión de la escuela y mejorar la experiencia de los
alumnos, profesores.

## Objetivo

Desarrollar servicios web para la gestión integral de una escuela, incluyendo la
administración de alumnos, profesores, cursos y matrículas. El sistema debe facilitar el
almacenamiento, consulta y actualización de datos, así como mantener la integridad de las
relaciones entre las diferentes entidades.

## Entidades principales:
### ● Alumno: 
Información sobre los alumnos de la escuela, incluyendo nombre
completo, fecha de nacimiento, dirección, teléfono, correo electrónico.
### ● Profesor: 
Información sobre los profesores de la escuela, incluyendo nombre
completo, especialidad, teléfono, correo electrónico y años de experiencia.
### ● Curso: 
Información sobre los cursos que se ofrecen en la escuela, incluyendo
nombre del curso, descripción, profesor a cargo, horario, duración y capacidad
máxima.
### ● Matrícula: 
Información sobre las matrículas de los alumnos en los cursos,
incluyendo fecha de matrícula, alumno matriculado, curso matriculado y estado de
la matrícula (pagada, pendiente de pago, cancelada).

```bash
http://localhost:5087/api/
```

## Usage

```python
# clonar git en escritorio local
git clone https://github.com/andresrivera/SchoolAPI.git

# Correr comando en carpeta
dotnet watch run

```

## Contributing

For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
