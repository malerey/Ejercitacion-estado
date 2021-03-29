# Ejercitacion estado
## Clases 96 y 97

El objetivo de estas clases es que puedas poner en práctica lo aprendido de estado para hacer una web que parezca mas real. Usaremos [el maquetado que hiciste en las clases 90 y 91](https://github.com/malerey/ejercicio-clase-89-y-90), pero modificaremos levemente el array de objetos:

```js
  const products = [
    {
      title: 'Coombes',
      type: 'Lounge',
      price: 2600,
      rating: 4,
      img: 'https://i.imgur.com/ZAxMGG5.png',
      category: 'furniture',
      color: 'gray',
      collection: 'classic',
    },
    {
      title: 'Keeve Set',
      type: 'Table & Chairs',
      price: 590,
      rating: 4,
      img: 'https://i.imgur.com/tT8sFIs.jpeg',
      category: 'furniture',
      color: 'wood',
      collection: 'modern',
    },
    {
      title: 'Nillè',
      type: 'Armchair',
      price: 950,
      rating: 5,
      img: 'https://i.imgur.com/Vx1cZY0.png',
      category: 'furniture',
      color: 'orange',
      collection: 'classic',
    },
    {
      title: 'Blanko',
      type: 'Side table',
      price: 90,
      rating: 4,
      img: 'https://i.imgur.com/N1Bf4ox.jpg',
      category: 'furniture',
      color: 'white',
      collection: 'modern',
    },
    {
      title: 'Momo',
      type: 'Shelves',
      price: 890,
      rating: 4,
      img: 'https://i.imgur.com/AlKxDE4.jpeg',
      category: 'auxiliars',
      color: 'wood',
      collection: 'classic',
    },
    {
      title: 'Penemillè',
      type: 'Chair',
      price: 120,
      rating: 4,
      img: 'https://i.imgur.com/pmANPjN.jpeg',
      category: 'furniture',
      color: 'white',
      collection: 'modern',
    },
    {
      title: 'Kappu',
      type: 'Shelves',
      price: 420,
      rating: 4,
      img: 'https://i.imgur.com/s2rsPa1.jpg',
      category: 'auxiliars',
      color: 'wood',
      collection: 'classic',
    },
  ];
  ```
  
### Primera parte (obligatoria)

1. Agrega la barra de busqueda en un componente llamado `Search.js`
2. Al buscar en el input, los productos deben filtrarse automáticamente. 

Modelo funcional: https://eshop-ada-5ta.netlify.app/



### Segunda parte (optativa)

1. Utilizando Material UI, hace los filtros de la izquierda. 
2. Los filtros deben usar los componentes `Accordion`, `Slider` y `Radio` para poder filtrar los productos por color, categoria, coleccion y precio. No es necesario que el estilado quede perfecto. 
3. Al cerrar un acordeon, todos los productos deben volver a mostrarse (los filtros no se persisten)
4. Idealmente, los filtros no estan en `App.js` sino en un componente propio. 

Modelo funcional: https://eshop-material-ada-5ta.netlify.app/

