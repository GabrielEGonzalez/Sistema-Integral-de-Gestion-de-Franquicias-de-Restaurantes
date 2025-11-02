Perfecto 🔥 Aquí tienes una **versión profesional y resumida** del README para tu repositorio en GitHub, manteniendo solo **la información relevante para presentación y comprensión del proyecto**, sin etapas internas de desarrollo:

---

# 🍔 Sistema Integral de Gestión de Franquicias de Restaurantes (SIGFR)

**SIGFR** es un sistema web completo para la **administración de franquicias de restaurantes**, permitiendo gestionar pedidos, empleados, clientes, productos e inventario, con integración de un **chatbot inteligente (BotMan)** que actúa como asistente virtual para clientes y empleados.

---

## 🎯 Objetivo

Centralizar la gestión operativa de múltiples sucursales de una red de restaurantes, optimizando procesos de atención, control de ventas y comunicación a través de un chatbot.

---

## 🧩 Módulos Principales

### 🔐 Autenticación y Roles

* Inicio de sesión y registro.
* Roles: **Administrador General**, **Gerente**, **Empleado**, **Cliente**.

### 🏢 Franquicias

* Registro y administración de sucursales.
* Asignación de empleados, menú, inventario y pedidos.

### 👨‍🍳 Empleados

* CRUD de empleados, control de horarios y reportes.
* Roles internos: cocinero, mesero, cajero, repartidor.

### 🧾 Menú y Productos

* CRUD de productos con nombre, descripción, precio, categoría e imagen.
* Control de disponibilidad e inventario por franquicia.

### 🛍️ Pedidos

* Registro y seguimiento de pedidos.
* Estados: *pendiente, en preparación, listo, entregado*.
* Control de ventas por día y sucursal.

### 💬 ChatBot (BotMan)

**Asistente Virtual Inteligente** con dos modos:

* **Modo Cliente:** ver menú, hacer pedido, consultar estado.
* **Modo Empleado:** consultar horario, reportar incidencias, revisar inventario.
  Interfaz accesible mediante un **ícono flotante** visible en todo el sistema.

### 📊 Reportes

* Ventas por franquicia.
* Desempeño de empleados.
* Productos y pedidos más vendidos.

---

## 🧮 Base de Datos (Resumen)

| Tabla         | Descripción                            |
| ------------- | -------------------------------------- |
| `usuarios`    | Datos y roles de usuarios del sistema. |
| `franquicias` | Información de cada sucursal.          |
| `empleados`   | Datos laborales y horarios.            |
| `productos`   | Menú, precios y disponibilidad.        |
| `pedidos`     | Pedidos y su estado actual.            |
| `clientes`    | Datos de clientes registrados.         |
| `reportes`    | Incidencias y reportes internos.       |
| `inventario`  | Control de stock por franquicia.       |

---

## 🧠 Tecnologías

| Área          | Tecnología                         |
| ------------- | ---------------------------------- |
| Backend       | PHP 8 (estructura MVC)             |
| Chatbot       | [BotMan](https://botman.io/)       |
| Base de Datos | MySQL                              |
| Frontend      | HTML5, CSS3, JavaScript, Bootstrap |
| Autenticación | PHP Sessions + bcrypt              |
| Diseño        | Responsive y adaptable             |

---

## 🏗️ Estructura del Proyecto

```
/sigfr
│
├── /public
│   ├── index.php
│   ├── chatbot.php
│   ├── /css
│   ├── /js
│   ├── /img
│   └── /chat
│
├── /app
│   ├── /controllers
│   ├── /models
│   ├── /views
│   └── /core
│
├── /database
│   └── script.sql
│
└── /config
    └── config.php
```

---

## 💡 Características Destacadas

* Arquitectura **MVC** en PHP puro.
* **Chatbot interactivo** con lógica real de atención.
* **Gestión multi-franquicia**.
* **Seguridad básica** y contraseñas cifradas.
* **Diseño adaptable** para escritorio y móvil.

---
                                                                                             Gabriel E. González
**Tecnologías:** PHP | BotMan | MySQL | Bootstrap

---

