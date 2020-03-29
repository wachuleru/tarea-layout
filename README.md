# Ejemplo de Layout
Se utilizarón tres bloques, cada uno con la propiedad `position: fixed;`

## Estructura de carpetas
```
.
├── README.md
├── assets
│   ├── css
│   │   ├── _resets.css
│   │   ├── maqueta.css
│   │   └── resets
│   │       ├── normalize.css
│   │       ├── reset.local.css
│   │       └── typography.css
│   └── images
│       └── user.png
└── maqueta.html

```

# `Trabajo a realizar`
 
Mediante el uso de medias queries se debe adaptar el contenido a dispositivos móviles.

En este trabajo se solicita:

1.- Agregar media queries donde el breakpoint será de una máximo de 800px

```
@media screen and (max-width: 800px) {
    ....
}
```

2.- Esconder o adaptar el conteniudo utilizando selectores
.- En Desktop se visualiza de la siguiente forma:

![Modo Desktop mayor o igual a 800px](assets/images/desktop.png?raw=true "Desktop")

.- En Mobile se debe visualizar de la siguiente forma:

![Modo Mobile menor a 800px](assets/images/mobile.png?raw=true "Mobile")
