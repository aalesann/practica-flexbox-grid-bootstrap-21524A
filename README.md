# Argentina Programa 4.0

## Flexbox y Grid CSS

> Links de interés:

1. [Documentación Flexbox](https://developer.mozilla.org/es/docs/Web/CSS/CSS_flexible_box_layout/Basic_concepts_of_flexbox)

2. [Documentación CSS Grid Layout](https://developer.mozilla.org/es/docs/Web/CSS/CSS_grid_layout)

3. [Learn CSS Grid](https://learncssgrid.com/#grid-container) 

![FLEXBOX VS GRID CSS](https://carontestudio.com/blog/wp-content/uploads/2022/07/flexbox-vs-css-grid.jpg)

> Juegos para aprender:

* [Flexbox Froggy](https://flexboxfroggy.com/#es)
* [Grid Attack](https://codingfantasy.com/games/css-grid-attack/play)

Para configurar Snippets en VS Code:

1. Presionar la siguiente combinación de teclas:
```bash
CTRL + SHIFT + P
```

2. Tipear y/o seleccionar la siguiente opción:
```bash
Fragmentos de código:Configurar fragmentos de usuario
```

3. Seleccionar el tipo de archivo
```bash
Ej: html.json (HTML)
```

4. Borrar todo el contenido del archivo y reemplazarlo por el contenido del archivo **snippet-html.json**
```JSON
{
	"Link de Bootstrap 5": {
		"prefix": "b5-link",
		"body":[
			"<link href='https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css' rel='stylesheet' integrity='sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9' crossorigin='anonymous'>"
		],
		"description": "Link de Bootstrap 5"
	},
	"Script de Bootstrap 5": {
		"prefix": "b5-script",
		"body":[
			"<script src='https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js' integrity='sha384-HwwvtgBNo3bZJJLYd8oVXjrBZt8cqVSpeBNS5n7C8IVInixGAoxmnlMuBnhbgrkm' crossorigin='anonymous'></script>"
		],
		"description": "Script de Bootstrap 5"
	}
}
```