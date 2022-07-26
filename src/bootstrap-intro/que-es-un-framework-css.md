# ¿Qué es un framework CSS?

Un _framework_ de CSS es una colección de clases con declaraciones de CSS predefinidas que pueden ser utilizadas de manera aislada para agregar estilos a elementos en nuestro código, ó en conjunto para crear componentes ya existentes en el framework

## Ejemplo

Nosotros podemos crear nuestro propio _framework_ de CSS de la siguiente manera:

```css
.text-blue {
  color: steelblue;
}

.text-green {
  color: mediumaquamarine;
}

.text-red {
  color: crimson;
}

.center-all {
  display: flex;
  align-items: center;
  justify-content: center;
}

.center-y {
  display: flex;
  align-items: center;
}
.center-x {
  display: flex;
  justify-content: center;
}
```

Estas declaraciones de CSS las podríamos utilizar en varios proyectos y sabríamos que la clase `.center-all` nos centraría los hijos de un elemento en ambos ejes utilizando Flexbox . Lo anterior sin necesidad de reescribir nuestro CSS, sino unicamente copiando y pegando o importando desde un link nuestro _framework_ de CSS.
