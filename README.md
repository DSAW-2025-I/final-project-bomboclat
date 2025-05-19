Juan Jose Campos Valderrama

Victor Andres Luna Mejia

Despliegue en Vercel
https://quick-meal-theta.vercel.app/

Repositorio 
https://github.com/vykymoon/AppQM.git


# QuickMeal - Sistema de Inventario y Pedidos para Puntos de Venta Universitarios

## Descripción

**QuickMeal** es una aplicación web fullstack desarrollada para la Universidad de La Sabana. Permite a estudiantes y personal consultar inventario, precios y realizar pedidos en tiempo real en los puntos de venta de alimentos y bebidas del campus. Los encargados de cada punto pueden gestionar su inventario y pedidos de manera eficiente, optimizando la operación diaria y reduciendo filas.

---

## Características Principales

### Perfil Cliente
- Consulta de productos y precios en tiempo real.
- Búsqueda y filtrado de productos.
- Realización y seguimiento de pedidos online.
- Historial de compras y calificación de productos.

### Perfil POS (Punto de Venta)
- Gestión completa de inventarios y precios.
- Actualización de stock en tiempo real.
- Registro, edición y eliminación de productos.
- Confirmación y procesamiento de pedidos.
- Notificaciones para cambios en inventario y pedidos.

---

## Tecnologías Utilizadas

- **Frontend:** React.js (Vite), Tailwind CSS
- **Backend:** Node.js, Express.js
- **Base de Datos y Notificaciones:** Firebase (Firestore)
- **Autenticación:** Firebase Auth, JWT, bcrypt
- **Despliegue:** Vercel

## **Tutorial de Usuario**

### **1. Inicio de Sesión**
- Accede a la página de inicio de sesión desde la URL del frontend desplegado.
- Ingresa tu correo electrónico y contraseña registrados.
- Si no tienes una cuenta, haz clic en **Sign Up** para registrarte.

### **2. Selección de Restaurante**
- Una vez autenticado, selecciona un restaurante desde la lista disponible en la pantalla principal.
- Cada restaurante muestra su horario de atención y un botón para consultar el menú.

### **3. Gestión del Carrito**
- Agrega productos al carrito desde el menú del restaurante.
- Puedes ajustar la cantidad de productos o eliminarlos directamente desde el carrito.
- Si un producto no tiene stock, se mostrará una alerta.

### **4. Confirmación del Pedido**
- Completa los detalles del pedido, como el lugar de entrega, hora de entrega y método de pago.
- Haz clic en **Confirmar Pedido** para finalizar la compra.

### **5. Seguimiento del Pedido**
- Puedes consultar el estado de tus pedidos en la sección **Order History**.
- Los pedidos pueden estar en estado "pendiente", "listo" o "entregado".

---


## Estructura del Proyecto 
AppQM/
├── .gitignore
├── package.json
├── vite.config.js
├── vercel.json
├── public/
│   └── index.html
├── src/
│   ├── App.jsx
│   ├── main.jsx
│   ├── index.css
│   ├── Firebase.js
│   ├── context/
│   │   └── AuthContext.js
│   ├── components/
│   │   ├── HeaderBar.jsx
│   │   ├── OrderHistory.jsx
│   │   ├── ProductList.jsx
│   │   ├── ProductListManagement.jsx
│   │   ├── ProtectedRoute.jsx
│   │   ├── RoleProtectedRoute.jsx
│   │   ├── POSProtectedRoute.jsx
│   │   ├── ShoppingCart.jsx
│   │   ├── UserProfile.jsx
│   │   ├── UserProfilePOS.jsx
│   │   ├── ServicePoints.jsx
│   │   ├── uploadServicePoints.js
│   │   ├── login/
│   │   │   ├── Home.jsx
│   │   │   ├── Login.jsx
│   │   │   ├── Signup2.jsx
│   │   │   ├── Welcome.jsx
│   │   │   ├── WelcomePOS.jsx
│   │   │   └── Assets/
│   │   │       └── ... (imágenes y recursos)
└── README.md
