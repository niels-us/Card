# Posicionamiento en CSS
## `position: relative;`

- puedo mover el elemento con 2 ejes de referencia:
    -top: cantidad de pixeles desde el estremo superior
    -left: cantodad de pixeles desde el extremo izquierdo

- Si el elemento es movido su espacio original se respeta por los demas elementos.

-Un elemento tambien puede tener `position:relative` cuando tiene hijos con `position: absolute` de tal forma que dichos hijos no se salgan del area del padre.

## `position: absolute;`

-El elemento sale del contexto de los demas elementos (tiene el efecto de flotar sobre los demas elelmentos).

-los elementos que no tienen `position:absolute` ocupan el espacio de éste elemento.
-luego poner al elemento con 4 ejes de referencia:
    -top , left, right y bottom

-Obligatoriamente debemos especificar , al meos 2 ejes de referecnia.
-el elemento `absolute` se mueve por referencia al proximo padre directo que tenga `position relative`

-de no cumplirse el anterior punto , el padre de referencia seia el elemento HTML

## `position:fixed;`
- El elemento es posicionado con referencia al viewport (el area de visualizacion de l apagina)
- Es decir si el scroll se mueve por ejejmplo , el elemento se matine fijado con referncia del viewport.
- se puede anclar hasta con 4 puntos de referencias top, left, righ y bootom
