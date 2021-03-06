<p align="center">
  <p align="center">
      <img src="/images/logo/logo.png" alt="" height="72">
  </p>
  <p align="center">
    E-Commerce BookStore
  </p>
</p>

## Descripci贸n

_Es un e-commerce de una librer铆a o bookstore, para realizar compras online de productos para la educaci贸n._

## Demo

[![alt text](https://gifyu.com/image/t4i2)]

## Comenzando 馃殌

_Para ver la navegabilidad de este proyecto puedes ingresar al siguiente enlace <https://elegant-volhard-51d912.netlify.app>._

_Para ejecutar el app de manera local sigue las instrucciones de **Instalaci贸n**_

### Pre-requisitos 馃搵

_Se necesita un editor de c贸digo fuente como:_

```
VsCode o Sublime
```

### Instalaci贸n 馃敡

_Clone or download este repositorio y abrelo en tu editor de c贸digo. En un terminal (mac/linux) o terminal de Windows, ejecuta el siguiente comando en el directorio base de este proyecto._

```
npm install
```

_Una vez culminada la instalac贸n, puedes correr el proyecto ejecutando este comando._

```
npm start
```

## Funcionamiento 鈿欙笍

<p align="center">
  <p align="center">
      <img src="/images/readmeImages/homePage.JPG" alt="" height="372">
  </p>
  <p align="center">
    P谩gina de inicio
  </p>
</p>

_Al ejecutar el app, el usuario recibe la p谩gina del home, el cual est谩 formado por un navbar o menu, un carousel y una secci贸n de categorias de productos._

_Desde el navbar el usuario tiene las opciones de ir al **home** <img src="/images/readmeImages/home.JPG" alt="" height="20">, la **colecci贸n de productos** <img src="/images/readmeImages/collection.JPG" alt="" height="20">, al **cart** <img src="/images/readmeImages/cart.JPG" alt="" height="20"> (deshabilitado si el usuario no ha agregado ning煤n producto al cart), al **contacto** <img src="/images/readmeImages/contacto.JPG" alt="" height="20"> (ruta que no existe y por lo cual al ingresar lo llevar谩 a la **p谩gina Error-404**), un bot贸n para **iniciar sesi贸n** y otro para **registrarse** <img src="/images/readmeImages/login-register.JPG" alt="" height="20">._

<p align="center">
  <p align="center">
      <img src="/images/readmeImages/pageNotFound.JPG" alt="" height="200">
  </p>
  <p align="center">
    P谩gina no encontrada
  </p>
</p>

***La p谩gina PageNotFound se mostrar谩 cada vez que el usuario intente ingresar a una ruta no definida en el proyecto como por ejemplo: /miscompras, /registrarme, /buscarunproducto, etc.***

_El corousel tiene un 煤nico link que lleva al usuario a ver todos los productos_

_En la secci贸n categor铆as, el usuario puede acceder a cada una de ellas similar a la opci贸n de colecci贸n de productos <img src="/images/readmeImages/collection.JPG" alt="" height="20"> del navbar._

<p align="center">
  <p align="center">
      <img src="/images/readmeImages/productsPage.JPG" alt="" height="372">
  </p>
  <p align="center">
    P谩gina de lista de productos
  </p>
</p>

_Una vez el usuario ingrese a una de las categor铆as, observar谩 un lista de productos._

<p align="center">
  <p align="center">
      <img src="/images/readmeImages/card-product.JPG" alt="" height="372">
  </p>
  <p align="center">
    Card de un producto
  </p>
</p>

_Cada producto se encuentra dentro de un card. Este card muestra una imagen, una marca, un t铆tulo o nombre, el precio y la cantidad en stock de cada producto, adem谩s de un contador para aumentar o disminuir la cantidad ha agregar al cart utilizando el bot贸n Agregar._

<p align="center">
  <p align="center">
      <img src="/images/readmeImages/pagination.JPG" alt="" height="70">
  </p>
  <p align="center">
    Paginaci贸n
  </p>
</p>

_En la parte inferior de la lista de productos hay una paginaci贸n, el cual aparecer谩 siempre y cuando la cantidad de productos supere a ocho productos por p谩gina (valor pre-configurado)._

_El usuario puede ver m谩s detalles de un producto presionando sobre su imagen o nombre._

<p align="center">
  <p align="center">
      <img src="/images/readmeImages/detailProductPage.JPG" alt="" height="372">
  </p>
  <p align="center">
    P谩gina de detalle del producto
  </p>
</p>

_Si el usuario ingresara al detalle de un producto, desde aqu铆 tambi茅n puede agregar dicho producto al cart. Una vez agregada la cantidad requerida, aparecer谩n dos botones, uno para regresar y seguir comprando y otro para terminar su compra e ir al cart._

_Una vez el usuario agregue al menos un producto, este valor se ver谩 reflejado en la opci贸n cart <img src="/images/readmeImages/cart-fill.JPG" alt="" height="20"> del navbar, mostrandose la cantidad de art铆culos agregados y al mismo tiempo, la opci贸n para ingresar al cart se habilitar谩._

<p align="center">
  <p align="center">
      <img src="/images/readmeImages/cartPage.JPG" alt="" height="372">
  </p>
  <p align="center">
    P谩gina Cart
  </p>
</p>

_Si el usuario decide ir al cart, aqu铆 se le mostrar谩 una tabla con la lista de productos, precio unitario, cantidad por producto y subTotal de un producto, adem谩s de un cuadro de resumen donde se muestra el precio total, un bot贸n para ir a pagar y otro para seguir comprando._

_El usuario en este punto puede modificar las cantidades agregadas <img src="/images/readmeImages/changeQty.JPG" alt="" height="20">, eliminar un producto <img src="/images/readmeImages/delete.JPG" alt="" height="20"> o vaciar por completo el carrito <img src="/images/readmeImages/emptyCart.JPG" alt="" height="20">._

<p align="center">
  <p align="center">
      <img src="/images/readmeImages/emptyCartPage.JPG" alt="" height="372">
  </p>
  <p align="center">
    P谩gina Cart vac铆o
  </p>
</p>

_Si el carrito quedase vac铆o, se le mostrar谩 un mensaje de que el cart est谩 vaci贸 y nuevamente la opci贸n de ingresar al cart <img src="/images/readmeImages/cart.JPG" alt="" height="20"> en el navbar quedar谩 deshabilitado._

***Si el usuario por alg煤n motivo saliese de la app o cerrara la p谩gina, los productos que agreg贸 no se borrar谩n, y podr谩 verlos en el cart la siguiente vez que ejecute la app.***

_Una vez el usuario este conforme con su lista de compras entonces estar谩 listo para presionar el bot贸n ir a pagar <img src="/images/readmeImages/goPay.JPG" alt="" height="20">. En caso el usuario no haya iniciado sesi贸n, ser谩 redirigido a la p谩gina de **inicio de sesi贸n**._

<p align="center">
  <p align="center">
      <img src="/images/readmeImages/loginPage.JPG" alt="" height="372">
  </p>
  <p align="center">
    P谩gina Inicio de sesi贸n
  </p>
</p>

_Para el inicio de sesi贸n, el usuario cuenta con tres opciones **iniciar sesi贸n con correo electr贸nico y password**, **iniciar sesi贸n con facebook** o **iniciar sesi贸n con google**._

<p align="center">
  <p align="center">
      <img src="/images/readmeImages/logUpPage.JPG" alt="" height="372">
  </p>
  <p align="center">
    P谩gina Registro
  </p>
</p>

_Si el usuario no contara con una cuenta, podr谩 crear una presionando el enlace **crea una cuenta** que le redirigir谩 al **registro**. Aqu铆 se le solicitar谩 al usuario un correo electr贸nico y un password. Una vez el usuario complete los datos solicitados, autom谩ticamente se iniciar谩 sesi贸n y el usuario podr谩 continuar con su compra._

<p align="center">
  <p align="center">
      <img src="/images/readmeImages/usuario.JPG" alt="" height="172">
  </p>
  <p align="center">
    Iniciar y cerrar sesi贸n
  </p>
</p>

_Visualmente, en el navbar los botones de iniciar sesi贸n y registrarse ser谩n remplazados por un icono que representa la opci贸n usuario <img src="/images/readmeImages/user.JPG" alt="" height="20">, si el usuario accediese a esta opci贸n se desplegar谩 un men煤 con las opciones de: nombre de usuario (correo electr贸nico en el caso haya iniciado sesi贸n con la opci贸n correo electronico y password o su nombre en el caso haya iniciado sesi贸n con google o facebook), Mis compras (a煤n en desarrollo) y la opci贸n de Cerrar Sesi贸n (si el usuario cerrara sesi贸n, los botones iniciar sesi贸n y registrarse volver铆an a aparecer)._

<p align="center">
  <p align="center">
      <img src="/images/readmeImages/paymentPage.JPG" alt="" height="372">
  </p>
  <p align="center">
    P谩gina Checkout
  </p>
</p>

_En este ultimo tramo, se le solicitar谩 al usuario informaci贸n adicional para validar su compra; **su nombre, su apellido, y su telefono o celular**. Aqu铆 el usario podr谩 ver un resumen de su compra, si en caso hubiese cometido un error, podr谩 regresar al cart y modificar su compra. Completado estos 煤ltimos tres datos, el usuario podr谩 generar su orden de compra presionando el bot贸n **Pagar** <img src="/images/readmeImages/confirm.JPG" alt="" height="20">._

<p align="center">
  <p align="center">
      <img src="/images/readmeImages/ordenPage.JPG" alt="" height="372">
  </p>
  <p align="center">
    P谩gina Orden de compra
  </p>
</p>

_Por 煤ltimo, se le mostrar谩 al usuario el c贸digo o id de su orden de compra y una tabla con los productos, precio unitario, cantidad, subtotal y precio total de su compra. Adem谩s de la opci贸n de un bot贸n **Imprimir** <img src="/images/readmeImages/print.JPG" alt="" height="20"> para guardar en su ordenador un pdf de su orden de compra. Asimismo, terminada la compra, la opci贸n al cart <img src="/images/readmeImages/cart.JPG" alt="" height="20"> en el navbar quedar谩 deshabilitada, puesto que ahora est谩 vac铆o nuevamente y el flujo se repite._

## Construido con 馃洜锔?

_En este proyecto se utiliz贸 lo siguiente:_

* Librer铆a: [React](https://es.reactjs.org/)
* Dependencias: 
    * [React-Router-Dom](https://reactrouter.com/) - Para el manejo de rutas din谩micas.
    * [React-Hook-Form](https://react-hook-form.com/) - Para validaci贸n de formularios.
    * [SweetAlert2](https://sweetalert2.github.io/) - Para animaciones con popups.
* CDN:
    * [Bootstrap](https://getbootstrap.com/) - Para los estilos, animaciones y el responsive.
    * [Bootstrap-Icons](https://icons.getbootstrap.com/) - Iconos utilizados.
* Plataforma: [Firebase](https://firebase.google.com/) - Para la base de datos y la autenticaci贸n de usuarios.

## Autor 鉁掞笍

* **Carlos Castillo** - *Desarrollador del Proyecto* - [carloscastillo369](https://github.com/carloscastillo369)