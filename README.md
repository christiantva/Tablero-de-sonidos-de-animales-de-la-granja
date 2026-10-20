# Tablero de Sonidos de la Granja

Tablero interactivo para inicial y 1.er–2.º grado de primaria: 8 animales de la granja
con sus sonidos, onomatopeyas y verbos ("El caballo relincha"), y dos juegos.

- **Uso:** abre `index.html` con doble clic. No necesita internet ni instalación.
- **Modos:** Explorar · ¿Quién hace este sonido? · ¿Qué animal es?
- **Sonidos reales (opcional):** copia los mp3 en `sonidos/` (ver `sonidos/LEEME.txt`).
  Sin ellos, el tablero sintetiza un sonido parecido y la voz lee la onomatopeya.
- **Panel docente:** botón ⚙ en la esquina superior derecha (voz, volumen, textos,
  animales del juego, pantalla completa). Las preferencias se recuerdan en el navegador.

## Agregar un animal

En `index.html`, añade un objeto al arreglo `ANIMALES`
(`id, nombre, articulo, onomatopeya, verbo, color, audio, svg`) y, si quieres,
una receta con el mismo `id` en `SINTESIS`. Si no la agregas, se usa un sonido genérico.
