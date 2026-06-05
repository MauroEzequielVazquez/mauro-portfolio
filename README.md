<<<<<<< HEAD
#  Portfolio
=======
# Portfolio Personal
>>>>>>> c9fa6b4 (Actualizado nombre del proyecto)

 Trabajo Práctico N°1 - Git y Docker

Este proyecto fue desarrollado como parte del Trabajo Práctico N°1 de la materia, con el objetivo de aplicar conceptos de control de versiones mediante Git y GitHub, y la utilización de contenedores Docker.

El proyecto consiste en un portfolio personal desarrollado con HTML y CSS, donde se presenta información sobre mi formación, tecnologías utilizadas y algunos proyectos realizados durante la carrera.

## Tecnologías utilizadas

- HTML5
- CSS3
- Git
- GitHub
- Docker
- Nginx

## Requisitos previos

Para ejecutar el proyecto es necesario tener instalado:

- Git
- Docker Desktop

## Clonar el repositorio

```bash
git clone https://github.com/MauroEzequielVazquez/Portfolio-Personal.git
```

## Construir la imagen Docker

Ubicarse en la carpeta del proyecto y ejecutar:

```bash
docker build -t portfolio-mauro .
```

## Ejecutar el contenedor

```bash
docker run -d -p 8080:80 --name portfolio portfolio-mauro
```

## Ejecución mediante Docker Compose

También es posible ejecutar la aplicación utilizando Docker Compose:

```bash
docker compose up -d
```

## Acceder a la aplicación

Abrir el navegador e ingresar a:

```text
http://localhost:8080
```

## Funcionalidades adicionales

- Implementación de Docker Compose para simplificar la ejecución del contenedor.
- Archivo .gitignore para excluir archivos innecesarios del repositorio.

## Autor

Mauro Ezequiel Vázquez Crossetto

Estudiante de la Tecnicatura Superior en Desarrollo de Software (ISTEA).
