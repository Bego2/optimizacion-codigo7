# TAREAS 
## & NOTAS PARA RECORDAR LO QUE HICE

- Comentar el código con lo que hace cada función

- Convertir las funciones nombradas en funciones flecha.
```js
        function nombreFuncion() {lo que hay}
        const nombreFuncion = () => { mantenemos lo que había }
```


- Quitar las funciones onClick y crear constantes para dichos botones con su addEventListener de click.
```js
        const btnAutoplay = document.querySelector(".btnAutoplay");
        btnAutoplay.addEventListener("click", () => {
        autoPlay();
      });
```

- Quitar paréntesis, llaves y return donde no sean necesarios en sus funciones flecha.

- Utilizar operaciones ternarias donde lo vean necesario.
```js
if (jugadorAI == usuario) {resultado = "Empate";} 
        else if (usuario == "piedra") {resultado = (jugadorAI == "papel") ? "Perdiste" : "Ganaste"; }
        else if (usuario == "papel") {resultado = (jugadorAI == "tijera") ? "Perdiste" : "Ganaste"; }
        else if (usuario == "tijera") {resultado = (jugadorAI == "piedra") ? "Perdiste" : "Ganaste"; }
```