#  Portfolio

## Trabajo Práctico N°1 - Git y Docker

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
git clone https://github.com/MauroEzequielVazquez/mauro-portfolio.git
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

## Acceder a la aplicación

Abrir el navegador e ingresar a:

```text
http://localhost:8080
```

## Autor

Mauro Ezequiel Vázquez Crossetto

Estudiante de la Tecnicatura Superior en Desarrollo de Software (ISTEA).
