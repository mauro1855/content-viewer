# content-viewer

A polymer element to previews images, pdfs ans xmls.

It detects the correct previewer from the file extension and loads it. For files that it does not supports, it provides a link to download the file so the user can open it in their computer.

The PDF previewer used is [streetturtle/pdf-element](https://github.com/streetturtle/pdf-element)

The XML previewer used is [himdel/xml_display](https://github.com/himdel/xml_display)

## Try it yourself

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally. By default, this tool will create a server accessible in port 8080

To access the element documentation, access [http://localhost:8080/components/content-viewer/](http://localhost:8080/components/content-viewer/)

To access a demo of the element, go to [http://localhost:8080/components/content-viewer/demo/](http://localhost:8080/components/content-viewer/demo/)


![Capturar.png](https://s27.postimg.org/rcwq8gnyr/Capturar.png)

## Compatibility notes

The element was tested in Firefox, IE 11, Edge and Google Chrome.
The XML previewer seems to not work propertly in Firefox.
