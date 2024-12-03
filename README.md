# Socket.IO Chat Example

Este proyecto es una aplicación de chat en tiempo real desarrollada con **Node.js**, **Express** y **Socket.IO**. Es una implementación básica que permite la comunicación instantánea entre múltiples clientes.

---

## 📋 Requisitos

- **Node.js** instalado en tu máquina.
- **NPM** (incluido con Node.js).

---

## 🚀 Instalación

Sigue los pasos a continuación para configurar y ejecutar el proyecto.

### 1️⃣ Clonar el repositorio

Clona este repositorio en tu máquina local:
```bash
git clone https://github.com/nicolasscolnik/chat-example.git
cd chat-app
```

### 2️⃣ Instalar dependencias

Ejecuta el siguiente comando para instalar las dependencias necesarias:
```bash
npm install
```

---

## 📁 Estructura del proyecto

El proyecto está organizado de la siguiente manera:

```plaintext
chat-app/
├── index.js               # Servidor principal
├── package.json           # Información del proyecto y dependencias
├── public/                # Archivos estáticos
│   └── index.html         # Interfaz del cliente
└── node_modules/          # Módulos instalados
```

---

## ⚙️ Uso

### 1️⃣ Iniciar el servidor

Ejecuta el siguiente comando para iniciar el servidor:
```bash
node index.js
```

Esto iniciará el servidor en el puerto `3000`.

### 2️⃣ Probar la aplicación

1. Abre tu navegador y ve a: [http://localhost:3000](http://localhost:3000).
2. Escribe un mensaje en el campo de entrada y haz clic en "Enviar".
3. Abre múltiples pestañas o ventanas para probar la funcionalidad en tiempo real entre diferentes clientes.

---

## 🛠 Licencia

Este proyecto está bajo la licencia de **Nicolás Scolnik**.

---

## 🔗 Recursos adicionales

Para funcionalidades avanzadas, consulta la [documentación oficial de Socket.IO](https://socket.io/).
