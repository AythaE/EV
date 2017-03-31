# Práctica 3
### 15/03/17
Para crear la doble ventana pinchar en la esquina superior dcha rallada.

La opción de _Unwrap_ se encuentra en _Mesh_ > _Shading/UVs_ con el objeto en _Edit mode_.

Para solucionar los puntos que quedan fuera de la textura habria que moverlos hacia dentro, desplazando las filas de los polos hacia arriba.

### 29/03/2017
Para aplicar una textura a mi modelo de la práctica, la espada, no valen ninguna de las proyecciones vistas para crear el resto de modelos. La proyección cilíndrica es aplicable en modelos con forma esférica o cilíndrica, lo que no es el caso. Se podría aplicar la técnica de la textura desplegada y aplicando costuras en la textura, pero no tengo una textura desplegada de la espada, solo algunas fotografías; se podría intentar hacer esto simplificando a 2 caras en la espada y usar una fotografía de la espada como textura desplegada, pero es probable que al desplegarlo quedara extraño debido a la simplificación realizada.

**Comentar como añadir fotografía**
Por ello he pensado que lo mejor sería una proyección plana. Para ello selecciono la espada en _Object mode_ y paso a _Edit mode_. Tras esto situo la vista en una posición similar a la fotografía que usaré, por ello me situo en la vista frontal ortogonal y para realizar la proyección plana selecciono _Mesh_ > _UV Unwrap_ > _Project from view_.

Ahora es necesario ajustar los vértices a los extremos de la imagen usando translaciones y escalados
