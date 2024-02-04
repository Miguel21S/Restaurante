# Página del Restaurante

# Tecnologías

HTML5 + CSS Layout y Bootstrap 4

# Descripción

Los requisitos mínimos constaran de tres páginas html hipervinculadas, siendo las mínimas indispensables Home (Introducción del establecimiento), Contact (contacto) y Carta o menú.
La temática (tipo de establecimiento) es libre en este caso, siempre y cuando se trate de un establecimiento de restauración.
Se valorarán especialmente el diseño y la limpieza visual, así como la
funcionalidad responsive de la página.

# Requisitos:

Los requisitos mínimos del proyecto son:

- Vista Home/ Principal / Presentación del establecimiento.
- Vista Contacto, con información y formularios.
- Vista Carta, con una selección de productos con imágenes y precios.

# Extras

- La inclusión de más páginas o secciones además de los aspectos creativos a la hora de generar las vistas se tendrá en cuenta.
- Se valorará la subida a producción del proyecto, en este caso mediante Github Pages, y la buena explicación del mismo mediante un README/S con ilustraciones y animaciones (GIF, svg, etc).

# **Estructura del Proyecto**

El proyecto se encuentra estructurado de la siguiente manera:

- **Home**: Página de introducción del establecimiento. Aquí se puede encontrar algunas cartas del menu
- **Contact**: Página de contacto, donde los usuarios pueden encontrar información de contacto como dirección, teléfono, correo electrónico, y un formulario de contacto para enviar mensajes directamente al establecimiento.
- **Carta o Menú**: Página que muestra una selección de productos disponibles en el establecimiento, junto con imágenes y precios. Esta página puede incluir categorías de productos (entrantes, platos principales, postres, etc.) para una mejor organización.

# Estado

El proyecto se encuentra en una fase de conclusión para el proyecto ya que cumple con todo los requisitos.

# **Funcionalidades Diseño**

En este pequeño trozo de instrucciones se muestra la lineas de importación de ficheros de Bootstrap y Css3

```jsx
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Restaurante</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>

    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css">
    <script src="https://cdn.jsdelivr.net/npm/jquery@3.7.1/dist/jquery.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>

    <link rel='stylesheet' type='text/css' media='screen' href='css/estilos.css'>

</head>
```

![Captura de pantalla 2024-02-04 234224.png](Pa%CC%81gina%20del%20Restaurante%208db316ac6a2742e397c8aba8ff31c8cb/Captura_de_pantalla_2024-02-04_234224.png)

Aquí se ilustra las lineas de creación del formulario del contacto

```html
<section class="contact-info">
        <h1>Información de Contacto</h1>
        <p>Dirección: Calle Colon, 105</p>
        <p>Teléfono: 665-761-386</p>
        <p>Correo electrónico: info@restdelicia.com</p>
    </section>
    <section class="contact-form">
        <h2 class="hh2"> Formulario de Contacto </h2>
        <form action="submit.php" method="POST">
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Correo electrónico:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Mensaje:</label>
            <textarea id="message" name="message" required></textarea>
            <input type="submit" value="Enviar Pedido">
        </form>
    </section>
```

![Captura de pantalla 2024-02-04 234506.png](Pa%CC%81gina%20del%20Restaurante%208db316ac6a2742e397c8aba8ff31c8cb/Captura_de_pantalla_2024-02-04_234506.png)

Aquí se puede ver la creación del formulario del pedido mediante lineas de instrucciones html 5

```html
<div class="container">
    <h1>Selección de Comidas</h1>
    <h1>Comidas</h1>
    <div class="model">
      <form>
        <label for="bebidas">Selecciona Sitio</label>
        <select id="bebidas" name="bebidas">
          <option value="agua">Salon</option>
          <option value="refresco">Terraza</option>
          <option value="jugo">Fuera</option>
        </select>
        <label><input type="checkbox" name="comida" value="hamburguesa"> Hamburguesa</label>
        <input type="number" name="cantidad_hamburguesa" value="0" min="0">
        <label><input type="checkbox" name="comida" value="pizza"> Pizza</label>
        <input type="number" name="cantidad_pizza" value="0" min="0">
        <label><input type="checkbox" name="comida" value="ensalada"> Ensalada</label>
        <input type="number" name="cantidad_ensalada" value="0" min="0">
        <label><input type="checkbox" name="comida" value="sushi"> Sushi</label>
        <input type="number" name="cantidad_sushi" value="0" min="0">

        <input type="submit" value="Enviar Pedido">
      </form>
    </div>
```

Esta imagen es del formulario del pedido, esta corresponde con las lineas de instrucciones de arriba.

![Captura de pantalla 2024-02-04 234650.png](Pa%CC%81gina%20del%20Restaurante%208db316ac6a2742e397c8aba8ff31c8cb/Captura_de_pantalla_2024-02-04_234650.png)

# **Créditos**

Este proyecto fue desarrollado por Miguel Bengui
