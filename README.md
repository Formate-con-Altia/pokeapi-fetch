# La PokeAPI en acción

Implementa un selector de pokemon que, al escoger el nombre de un pokemon, se realice una llamada a la [PokeAPI](https://pokeapi.co/) y recupere el nombre y la ruta a una imagen del Pokemon.

Además, al hacer clic en el botón **Change to Shiny** se debe cargar la imagen "shiny" del pokemon. Utiliza la [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) para realizar la llamada,

Aquí tienes una [DEMO](https://formate-con-altia.github.io/pokeapi-fetch/)


## BONUS

- El selector de pokemons deberia **bloquearse** hasta que no hemos conseguido cargar el pokemon, y **desbloquearse** una vez cargado (mirar atributo **disabled**) [Bootstrap disbled](https://getbootstrap.com/docs/5.0/forms/form-control/#disabled)
- Actualmente, la lista de Pokemon se llena "manualmente" desde el HTML. Crea una función que permite crear tantos <option> como especifique una variable de estado; realizando una llamada a la la PokeApi.

  - Deberás realizar una llamada a la PokeApi pasándole un parámetro por QueryString. Por ejemplo, la siguiente llamada a la PokeApi devuelve los **10** primeros Pokemons de la base de datos [ejemplo](https://pokeapi.co/api/v2/pokemon?limit=10)
  - ¿Cómo se hace para crear opciones de un control \<select>? [Ayuda](https://www.w3schools.com/jsref/met_select_add.asp)
  - ¿Puedes hacer que dicha variable de estado sea establecida desde un control en la interfaz de usuario?

  Adjunto un [vídeo](https://oscarm.tinytake.com/tt/NTQwNDY5MV8xNjkwMzk3Ng) aproximado de esta implementación.
  
## Posible implementación de la app con bonus

[PokeAPI Full](https://pokemon-api-two-nu.vercel.app/#)
  
## MEGA-BONUS

- Existe una **biblioteca** para facilitar la comunicación con esta API. Búscala en la documentación de la misma página de la PokeApi y úsala en vez de hacer las llamadas directamente a la API. Tienes la solución a cómo usarla en la carpeta **solution_using_library**

## Soluciones

[Solución](https://github.com/Formate-con-Altia/pokeapi-fetch/blob/solution-withoutbonus/index.html) sin el bonus.

[Solución concatenando promesas en vez de usar await/async](https://github.com/Formate-con-Altia/pokeapi-fetch/tree/solution)

En la carpeta **solution_using_library** tenéis la solución usando la biblioteca que comentamos en el BONUS.

Podéis encontrar las solcuiones en las diferentes ramas de este repositorio, Podéis también comprobar la solución de [Cristian Cullell](https://github.com/cristian-cll/pokeapi-fetch/)
