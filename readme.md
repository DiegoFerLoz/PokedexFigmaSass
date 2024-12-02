# P3.1 Maquetación responsiva con Vite y SASS

- Autor: Diego Fernández Lozano
- Asignatura: Desarrollo de Interfaces Web
- Curso: S2DAW
- Fecha de entrega: 02/12/2024

## 1. Descripción de la práctica.
Se trata de maquetar la página que diseñamos en Figma en una práctica anterior. Para ello, hemos utilizado la herramienta Vite, además de SASS para crear las reglas de diseño.
Específicamente se pide realizar el diseño de la página en formato tablet y móvil, para que sea responsiva independientemente del tamaño de la pantalla.

## 2. Diseño.
El concepto del diseño que he creado bebe directamente de la [página oficial de la Pokédex](https://www.pokemon.com/es/pokedex), donde aparecen todos los pokémon que existen en una lista.

Para mi versión de esta página, he utilizado colores distintos pero que se suelen asociar a Pokémon. A partir de esta base, he diseñado la página desde cero, con la idea de mostrar a los pokémon así como poder buscar por nombre u ordenar por diferentes campos.

Por ahora tan solo muestra los 8 primeros Pokémon, por razones de simplicidad.

## 3. Desarrollo.
Para la realización de la práctica, hemos creado un proyecto con Vite para facilitar el despliegue y la organizacion del proyecto.

Para especificar las normas de estilo hemos utilizado SASS, repartiendo las normas en cada archivo correspondiente. De esta forma, las reglas que atañen a los botones se especifican en el archivo "_button.scss", las reglas del header se encuentran en "_header.scss", etc.
Así podemos organizar el código de una forma más limpia y legible.

Para el diseño responsivo he utilizado un mapa con breakpoints que especifican en qué tamaños hay que cambiar de diseño, definiendo la variable que los almacena en "_variables.scss" y el código que las gestiona en "_mixins.scss". De esta forma, y siguiendo el diseño realizado en Figma, he ido maquetando los diferentes tamaños de la página.

Además, para el control de versiones he utilizado esta página, Github.

## 4. Enlaces de interés.

[1. Enlace a la página desplegada en Github Pages](https://diegoferloz.github.io/PokedexFigmaSass/)

[2. Enlace al diseño realizado en Figma](https://www.figma.com/design/rCEmVp3hlKRT5Y7M0i1XjJ/Practica-1.2?node-id=3-5)