# Tablero de Sonidos de la Granja

Tablero interactivo para inicial y 1.er–2.º grado de primaria: 8 animales de la granja
con sus sonidos, onomatopeyas y verbos ("El caballo relincha"), juegos, una canción
y fichas para imprimir. Pensado para proyector, pizarra digital y tablets.

- **Uso:** abre `index.html` con doble clic. No necesita internet ni instalación.
- **Sonidos reales (opcional):** copia los mp3 en `sonidos/` (ver `sonidos/LEEME.txt`).
  Sin ellos, el tablero sintetiza un sonido parecido y la voz lee la onomatopeya.

## Modos

| Menú | Qué hace |
|------|----------|
| Explorar | Tarjetas de los 8 animales: suenan, se mueven y muestran la frase. |
| Granja | Escena con cada animal en su lugar; el granero se abre y adentro está la vaca. |
| Jugar | ¿Quién hace este sonido?, ¿Qué animal es?, Memoria y ¡Imítalo! (con micrófono). |
| Cantar | «En la granja de Rosa»: melodía con palmas, letra resaltada y adivinanza del animal. |
| Álbum | 24 stickers (cada animal con accesorios) que se ganan al acertar en los juegos. |

- **Sol y luna (esquina superior izquierda):** cambia a tarde y noche; de noche los animales duermen
  y se despiertan al tocarlos.
- **Rosa, la granjera:** explica cada juego con voz; si se toca, repite lo que dijo.
- **¡Imítalo!:** el micrófono solo mide el volumen, no graba ni guarda nada. Si no hay micrófono
  o no hay permiso, la docente toca «¡Lo hizo!».

## Panel docente (botón ⚙)

Voz, volumen, mostrar u ocultar textos, mostrar a Rosa, animales que entran en los juegos,
vaciar el álbum, pantalla completa y **fichas para imprimir** (láminas para colorear y
«Une cada animal con su sonido», en A4). Las preferencias y el álbum se recuerdan en el navegador.

## Agregar un animal

En `index.html`, añade un objeto al arreglo `ANIMALES`
(`id, nombre, articulo, onomatopeya, verbo, color, audio, canto, stickers, svg`) y, si quieres,
una receta con el mismo `id` en `SINTESIS` y un lugar en `LUGARES` (escena de la granja).
Si no agregas la receta, se usa un sonido genérico.
