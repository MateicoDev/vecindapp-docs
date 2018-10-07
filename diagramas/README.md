# Diagramas

## Para pre-visualizar con Visual Studio Code:

- Instalar 'Graphviz' [Docs](http://plantuml.com/graphviz-dot)

```
sudo apt install graphviz
```

- Instalar el plugin para Visual Studio Code. [Descargar](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml#use-plantuml-server-as-render)

## Para generar las imágenes:

- Por única vez ejecutar:

```
npm install node-plantuml -g
```

- Para generar el diagrama:

```
puml generate clases.puml -o diagrama_de_clases.png
```

## Online:

- [PlantUML Server Online](http://www.plantuml.com/plantuml/uml/SoWkIImgAStDuNBEIImkDZ1KiAdHrLM0S8oWWiOAMd0n4wYOgK8-NCmCAcQkeAS75RA02bagm5GP6d0vfEQb0Aq20000)