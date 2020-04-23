<gs-attire attire-url="https://raw.githubusercontent.com/MumukiProject/mumuki-guia-gobstones-general-secundaria/master/assets/attires/config_1587670844103.json"></gs-attire>

Juani está muy felíz por el programa que hiciste :grin: y ya quiere usarlo para marcar los destinos. Pero para eso, necesita un procedimiento que le permita moverse cierta cantidad de kilómetros en el mapa en una dirección :sweat_smile:. ¡Suena a que vos podés hacerlo! :stuck_out_tongue_winking_eye:

<gs-board>
     GBB/1.0
     size 5 4
     cell 0 3 Verde 4 
     cell 4 3 Verde 5 
     cell 1 1 Verde 3 
     cell 2 1 Verde 2 
     cell 4 0 Verde 1 
     head 0 0
</gs-board>

> Dado el tablero anterior, construí el programa para marcar estos 3 destinos: Ciudad de San Luis (2 kilómetros al Este y 1 al Norte), luego Villa Mercedes (2 al Este y 1 al Sur) y finalmente Sierra de las Quijadas (3 al Norte y 4 al Oeste). Para esto, necesitarás definir el procedimiento `Recorrer`. Comenzaremos en el casillero inferior izquierdo.
