# Markdown
## Sintaxis basica
### Estilo de texto
**Titulo en negrita**, __Titulo en negrita__, ***texto muy en negrita***, *en italica*, _italic_, ~~texto tachado~~, x<sub>subiondice</sub>, x<sup>superindice<s/sup>

>cita de texto

### Codigo
El codigo entre comillas simples lo podemos llamar: `git status` pero para darle espacios con 3 comillas:
```
git status -s
```
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

### Links
#### Links dentro del mismo documento?
#### Links en la web
Para crear enlaces o links dentro al clicar las palabras: [Esemtia](https://danielcastelao.esemtia.net/moodle/my/).

#### Links relativos
Es un enlace relativo al archivo actual. De esta forma podemos acceder facilmente a otros ficheros de nuestro repo. Esto nos sirve para por ejemplo hacer una carpeta con [imagenes](./Imagenes/imgagen1.jpg) donde tengamos todas.
  
#### Imagenes
![Esto es una imgagen](https://images.unsplash.com/photo-1601814933824-fd0b574dd592?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8YmFieSUyMHlvZGF8ZW58MHx8MHx8&auto=format&fit=crop&w=500&q=60)

### Crear pestañas
  <details><summary><h4>Pestaña</h4></summary>
  <p><h8>informacion de la pestaña</8></p>
</details>

### Para crear listas
  * titulo1
  * titulo2
  1. titulo1
  2. titulo2

