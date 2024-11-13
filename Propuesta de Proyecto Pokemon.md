# Propuesta de Proyecto: Creador de Equipos Pokemon

## 1. Idea de la Aplicación

La aplicación consistirá en una plataforma diseñada para que los usuarios puedan crear y personalizar sus equipos Pokemon ideales. El propósito dse la aplicación es facilitar una experiencia para los fans de Pokemon, permitiendo explorar y seleccionar diferentes Pokemon de acuerdo con sus preferencias. Además se podrá guardar sus equipos favoritos y en futuras implementaciones acceder a la información detallada de cada Pokemon.

La aplicación resuelve una necesidad de la comunidad de los fanáticos que muchas veces buscan herramientas para planificar equipos, conocer estadísticas y habilidades y visualizar sus Pokemon en un entorno organizado y visualmente atractivo.

## 2. Audiencia Objetivo

El público objetivo de esta aplicación simplemente serán fanáticos y jugadores de pokemon que quieran hacer un equipo para competitivo de manera personalizada.

## 3. Análisis de Mercado

Algunas aplicaciones y páginas web actuales que ofrecen funciones similares son:

- Pokémon Showdown: permite la creación de equipos con una simulación de batallas. Sin embargo, la experiencia está muy orientada a las batallas y no tanto a la visualización y exploración de Pokémon.
- Pokémon Database: ofrece información detallada sobre cada Pokémon, aunque no incluye funcionalidades interactivas para crear y personalizar equipos en una interfaz amigable.
- Pokémon Home: una aplicación oficial de Pokémon para almacenar y transferir Pokémon entre juegos, aunque está limitada en cuanto a personalización de equipos y no permite un acceso visual o directo a los datos.

### 3.1. Valor añadido de la aplicación

Lo que aportará nuestra aplicación y que hará destacar en el mercado serán los siguientes elementos:
- Una interfaz amigable y sencilla.
- Personalización avanzada. Se podrán crear múltiples equipos personalizados y en futuras implementaciones acceder a las estadísticas y datos de cada pokemon.
- Filtros y búsqueda avanzada. Se podrá encontrar Pokemon en base a unos criterios específicos (tipo, generación, habilidades).

En el siguiente punto entraré en detalle acerca de las funcionalidades de la aplicación.

## 4. Funcionalidades Clave

Las funcionalidades que pretenderá ofrecer la aplicación será:

#### Login/Registro

- Se permitirá el registro de nuevos usuarios y autenticación de usuarios existentes.
- Se almacenará las preferencias y equipos personalizados del usuario en localStorage.

#### Perfil de Usuario:

- Se podrá visualizar la información del usuario y sus equipos creados.
- Se podrá editar la información básica del usuario y su foto de perfil.

#### Exploración de Pokémon

- Página de búsqueda avanzada con filtros específicos para facilitar la selección de Pokémon.
- Paginación de resultados para una mejor navegación entre datos masivos.

#### Creador de Equipos

- El creador de equipos contará con una interfaz que permita a los usuarios agregar Pokémon a un equipo personalizado.
- Se almacenará los equipos creados en localStorage.
- Posibilidad de crear varios equipos y acceder a ellos desde el perfil.

#### Filtros de Búsqueda Avanzados

Filtros para tipo, generación, habilidades y estadísticas específicas.
La búsqueda se actualizará en tiempo real según el criterio del usuario.

#### Página de Contacto

Formulario de contacto con validación completa, incluyendo inputs variados como email, checkbox y radio button entre otros.

#### Despliegue

La aplicación finalmente será desplegada usando la página de Netlify.

## 5. Tecnologías a utilizar

### Frontend

Para el frontend se usará React y React Router para construir la página con componentes y para la navegación sin regarga de página seguido de Bootstrap para el diseño de la página web y fetch API para las llamadas asíncronas a la API de Pokemon.

### Backend

Para el backend he optado por utilizar PokeAPI, una API REST pública que ofrece datos de Pokemon y que se mantiene y se actualiza por la comunidad.

### Almacenamiento

Para este proyecto se ha optado por utilizar LocalStorage para guardar los equipos favoritos y los datos persistentes del usuario.

### Validación y Seguridad

Para validar de forma avanzada los formularios voy a utilizar React Hook Form y para las alertas visuales y las notificaciones usaré la librería SweetAlert.

### Despliegue

Se optará por utilizar el servicio de Netlify para desplegar la aplicación.