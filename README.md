# Ephemer Gaming


## 1. Descripción

Ephemer Gaming es un proyecto e-commerce. Creé una tienda en línea de artículos de computación, la misma es capaz de mostrar los productos desde una base de datos, incluyendo sus detalles. El usuario podrá navegar por cada uno de los artículos y realizar compras en la aplicación, la misma se encargará de gestionar una órden única, manipulando los datos del usuario y del pedido, también actualizará el stock de los items a medida que son comprados. Para poder realizar compras, el usuario deberá registrar una cuenta con mail y contraseña, o a través de proveedores como Google o GitHub, una vez logueado, podrá realizar compras con su cuenta y acceder a ellas desde el menú de usuario.

<a name="technologies-es"></a>

## 2. Tecnologías utilizadas

| Front-End         |
| ----------------- |
| React.JS          |
| JSX			    |
| Tailwind 3 CSS    |
| HeroIcons React   |
| Headless UI React |
| Firebase          |

| NPM Packages      |
| ----------------- |
| SweetAlert2       |
| Formik            |
| Yup               |

[SweetAlert2:](https://sweetalert2.github.io/) Se utilizó ésta dependencia para notificar al usuario de los diferentes eventos de la interfaz, tales como cuando se agrega un producto al carrito, informar de errores, y permitir al usuario cargar sus datos para realizar un pedido.

[Formik:](https://formik.org/) Usé Formik para crear un formulario en React, validar y manipular los datos del mismo de manera sencilla.

[Yup:](https://www.npmjs.com/package/yup) Junto con Formik, Yup ayudó a realizar la validación de los datos ingresados en el formulario.

[HeadlessUI:](https://headlessui.com/) Usé el componente "Menu (Dropdown)" para generar el menú de Categorías mobile y el menú de Usuario.