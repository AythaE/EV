# Diario de la práctica 1
## 26/02/17
Hasta ahora he hecho alguna cosa inicial creando el filo de la espada partiendo de un cubo y moviéndole dos aristas opuestas hacia dentro para crear una forma de filo. Tras esto se hace una extrusión de las caras para hacerlo más alargado utilizando la transformación elemental _Mover_ para realizar la extrusión en el eje de la X solo.

Como se puede ver en las imágenes de Narsil las aristas no cortantes del filo están "comidas" hacia dentro formando un arco, para hacer esto a partir de un cilindro con centro esa arista hay que eliminarlo quedándome con el resto lo que me daría esa forma circular hacia dentro. Solo falta descubrir como hacer esto último. Parece que he logrado hacer algo parecido usando la operacion biselado _Bebel_ del submenú _Edges_ del menú _Mesh_ (Ctrl+E), como parametros le he dado offset 0.26, 5 segments y profile 0.150
