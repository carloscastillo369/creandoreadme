<p align="center">
  <p align="center">
      <img src="/images/logo/logo.png" alt="" height="72">
  </p>
  <p align="center">
    E-Commerce BookStore
  </p>
</p>

## Descripción

_Es un e-commerce de una librería o bookstore, para realizar compras online de productos para la educación._

## Comenzando 🚀

_Para ver la navegabilidad de este proyecto puedes ingresar al siguiente enlace <https://elegant-volhard-51d912.netlify.app>._

_Para ejecutar el app de manera local sigue las instrucciones de **Instalación**_

### Pre-requisitos 📋

_Se necesita un editor de código fuente como:_

```
VsCode o Sublime
```

### Instalación 🔧

_Clone or download este repositorio y abrelo en tu editor de código. En un terminal (mac/linux) o terminal de Windows, ejecuta el siguiente comando en el directorio base de este proyecto._

```
npm install
```

_Una vez culminada la instalacón, puedes correr el proyecto ejecutando este comando._

```
npm start
```

## Funcionamiento ⚙️

<p align="center">
  <p align="center">
    Página de inicio
  </p>
  <p align="center">
      <img src="/images/readmeImages/homePage.JPG" alt="" height="372">
  </p>
</p>

_Al ejecutar el app, el usuario recibe la página del home, el cual está formado por un navbar o menu, un carousel y una sección de categorias de productos._

_Desde el navbar el usuario tiene las opciones de ir al **home** <img src="/images/readmeImages/home.JPG" alt="" height="20">, la **colección de productos** <img src="/images/readmeImages/collection.JPG" alt="" height="20">, al **cart** <img src="/images/readmeImages/cart.JPG" alt="" height="20"> (deshabilitado si el usuario no ha agregado ningún producto al cart), al **contacto** <img src="/images/readmeImages/contacto.JPG" alt="" height="20"> (ruta que no existe y por lo cual al ingresar lo llevará a la **página Error-404**), un botón para **iniciar sesión** y otro para **registrarse** <img src="/images/readmeImages/login-register.JPG" alt="" height="20">._

_El corousel tiene un único link que lleva al usuario a ver todos los productos_

_En la sección categorías, el usuario puede acceder a cada una de ellas similar a la opción de colección de productos <img src="/images/readmeImages/collection.JPG" alt="" height="20"> del navbar_

<p align="center">
  <p align="center">
    Página de lista de productos
  </p>
  <p align="center">
      <img src="/images/readmeImages/productsPage.JPG" alt="" height="372">
  </p>
</p>

_Una vez el usuario ingrese a una de las categorías, observará un lista de productos._

<p align="center">
    <img src="/images/readmeImages/card-product.JPG" alt="" height="372">
</p>

_Cada producto se encuentra dentro de un card. Este card muestra una imagen, una marca, un título o nombre, el precio y la cantidad en stock de cada producto, además de un contador para aumentar o disminuir la cantidad ha agregar al cart utilizando el botón Agregar_

<p align="center">
    <img src="/images/readmeImages/pagination.JPG" alt="" height="372">
</p>

_En la parte inferior de la lista de productos hay una paginación, el cual aparecerá siempre y cuando la cantidad de productos supere a ocho productos por página (valor pre-configurado)._

_El usuario puede ver más detalles de un producto presionando sobre su imagen o nombre_

<p align="center">
  <p align="center">
    Página de detalle del producto
  </p>
  <p align="center">
      <img src="/images/readmeImages/detailProductPage.JPG" alt="" height="372">
  </p>
</p>

_Si el usuario ingresara al detalle de un producto, desde aquí también puede agregar dicho producto al cart. Una vez agregada la cantidad requerida, aparecerán dos botones, uno para regresar y seguir comprando y otro para terminar su compra e ir al cart_

_Una vez el usuario agregue al menos un producto, este valor se verá reflejado en la opción cart <img src="/images/readmeImages/cart-fill.JPG" alt="" height="20"> del navbar, mostrandose la cantidad de artículos agregados y al mismo tiempo, la opción para ingresar al cart se habilitará_

<p align="center">
  <p align="center">
    Página Cart
  </p>
  <p align="center">
      <img src="/images/readmeImages/cartPage.JPG" alt="" height="372">
  </p>
</p>

_Si el usuario decide ir al cart, aquí se le mostrará una tabla con la lista de productos, cantidad por producto, precio unitario y subTotal de un producto, además de un cuadro de resumen donde se muestra el precio total, un botón para ir a pagar y otro para seguir comprando_

_El usuario en este punto puede modificar las cantidades <img src="/images/readmeImages/changeQty.JPG" alt="" height="20">, eliminar un producto <img src="/images/readmeImages/delete.JPG" alt="" height="20"> o vaciar por completo el carrito <img src="/images/readmeImages/emptyCart.JPG" alt="" height="20">._

<p align="center">
  <p align="center">
    Página Cart vacío
  </p>
  <p align="center">
      <img src="/images/readmeImages/emptyCartPage.JPG" alt="" height="372">
  </p>
</p>

_Si el carrito quedase vacío, se le mostrará un mensaje de que el cart está vació y nuevamente la opción de ingresar al cart <img src="/images/readmeImages/cart.JPG" alt="" height="20"> en el navbar quedará deshabilitado_

_Si el usuario por algún motivo saliese de la app o cerrara la página, los productos que agregó no se borrarán, y podrá verlos en el cart la siguiente vez que ejecute la app._

_Una vez el usuario este conforme con su lista de compras entonces estará listo para presionar el botón ir a pagar <img src="/images/readmeImages/goPay.JPG" alt="" height="20">. En caso el usuario no haya iniciado sesión, será redirigido a la página de **inicio de sesión**._

<p align="center">
  <p align="center">
    Página Inicio de sesión
  </p>
  <p align="center">
      <img src="/images/readmeImages/loginPage.JPG" alt="" height="372">
  </p>
</p>

_Para el inicio de sesión, el usuario cuenta con tres opciones **iniciar sesión con correo electrónico y password**, **iniciar sesión con facebook** o **iniciar sesión con google**._

<p align="center">
  <p align="center">
    Página Registro
  </p>
  <p align="center">
      <img src="/images/readmeImages/logUpPage.JPG" alt="" height="372">
  </p>
</p>

_Si el usuario no contara con una cuenta, podrá crear una presionando el enlace **crea una cuenta** que le redirigirá al **registro**. Aquí se le solicitará al usuario un correo electrónico y un password. Una vez el usuario complete los datos solicitados, automáticamente se iniciará sesión y el usuario podrá continuar con su compra._

<p align="center">
  <p align="center">
    Iniciar y cerrar sesión
  </p>
  <p align="center">
      <img src="/images/readmeImages/usuario.JPG" alt="" height="372">
  </p>
</p>

_Visualmente, en el navbar los botones de iniciar sesión y registrarse serán remplazados por un icono que representa la opción usuario <img src="/images/readmeImages/user.JPG" alt="" height="20">, si el usuario accediese a esta opción podrá ver su nombre de usuario (correo electrónico en el caso haya iniciado con la opción correo electronico y password o su nombre en el caso haya iniciado sesión con google o facebook), sus compras (aún en desarrollo) y la opción de cerrar sesión(si el usuario cerrara sesión, los botones iniciar sesión y registrarse volverían a aparecer)._

<p align="center">
  <p align="center">
    Página Checkout
  </p>
  <p align="center">
      <img src="/images/readmeImages/paymentPage.JPG" alt="" height="372">
  </p>
</p>

_En este ultimo tramo, se le solicitará al usuario información adicional para validar su compra; **su nombre, su apellido, y su telefono o celular**. Aquí el usario podrá ver un resumen de su compra, si en caso hubiese cometido un error, pudrá regresar al cart y modificar su compra. Completado estos últimos tres datos, el usuario podrá generar su orden de compra presionando el botón **Pagar** <img src="/images/readmeImages/confirm.JPG" alt="" height="20">._

<p align="center">
  <p align="center">
    Página Orden de compra
  </p>
  <p align="center">
      <img src="/images/readmeImages/ordenPage.JPG" alt="" height="372">
  </p>
</p>

_Por último, se le mostrará al usuario el código o id de su orden de compra y una tabla con los productos, precio unitario, cantidad, subtotal y precio total de su compra. Además de la opción de un botón **Imprimir** <img src="/images/readmeImages/print.JPG" alt="" height="20"> para guardar en su ordenador un pdf de su orden de compra. Asimismo, terminada la compra la opción al cart en el navbar quedará deshabilitada, puesto que ahora está vacio nuevamente._

## Construido con 🛠️

_En este proyecto se utilizó lo siguiente:_

* Librería: [React](https://es.reactjs.org/)
* Dependencias: 
    * [React-Router-Dom](https://reactrouter.com/) - Para el manejo de rutas dinámicas.
    * [React-Hook-Form](https://react-hook-form.com/) - Para validación de formularios.
    * [SweetAlert2](https://sweetalert2.github.io/) - Para animaciones con popups.
* CDN:
    * [Bootstrap](https://getbootstrap.com/) - Para los estilos, animaciones y el responsive.
    * [Bootstrap-Icons](https://icons.getbootstrap.com/) - Iconos utilizados.
* Plataforma: [Firebase](https://firebase.google.com/) - Para la base de datos y la autenticación de usuarios.

## Autor ✒️

* **Carlos Castillo** - *Desarrollador del Proyecto* - [carloscastillo369](https://github.com/carloscastillo369)