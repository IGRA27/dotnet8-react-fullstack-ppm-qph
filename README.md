# 🧠 Workshop: .NET 8 + React (Vite) – Fullstack Local

## Quito Publishing House QPH
### PPM (Cursor)

#### AUTOR: Isaac Reyes

Este proyecto forma parte de un **workshop práctico** para desarrolladores, enfocado en construir una solución fullstack simple usando:

- 🔙 **Backend:** Microservicio en C# con .NET 8
- 🌐 **Frontend:** React con Vite (interfaz web ligera)
- ⚙️ **IDE:** [Cursor](https://www.cursor.so)

> Todo el stack funciona de forma 100% local, sin emuladores ni servicios en la nube. Ideal para formación rápida, hands-on y evaluación de buenas prácticas con IA.

---

## 📦 Estructura del Proyecto

```
dotnet8-react-fullstack-ppm-qph/
├── backend/
│ └── MyService/ # Proyecto .NET 8
│ ├── Program.cs
│ ├── Controllers/
│ │ └── SaludoController.cs
│ └── MyService.csproj
└── frontend/ # Proyecto React + Vite
├── src/
│ ├── App.jsx
│ └── main.jsx
├── index.html
├── package.json
└── vite.config.js
```



---

## ✅ Requisitos previos

Asegúrate de tener instalado:

- [Visual Studio Code](https://code.visualstudio.com/)
- [Extensión Cursor IDE](https://marketplace.visualstudio.com/items?itemName=cursor.cursor-vscode)
- [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)
- [Node.js (última LTS)](https://nodejs.org/)
- Navegador web moderno (Chrome, Edge)

---

## 🔧 Instalación y ejecución

### 1. Iniciar el backend

```
cd backend/MyService
dotnet run
```

🔗 Abre en navegador: http://localhost:5000/saludo

### 2. Iniciar el frontend

```
cd frontend
npm install
npm run dev
```

🔗 Abre en navegador: http://localhost:5173



-

# 🧠 Uso con Cursor (Prompts recomendados)
Prompt Backend
Genera un microservicio básico en C# .NET 8 que exponga un endpoint GET `/saludo` que devuelva "Hola desde el backend". Usa controladores y configura `Program.cs` para permitir rutas.


Prompt Frontend
Genera un componente en React que tenga un botón. Al hacer clic, debe hacer un `fetch` al endpoint `http://localhost:5000/saludo` y mostrar la respuesta en pantalla.


# 🧪 Objetivo del Workshop
Aplicar buenas prácticas con generación asistida por IA

Probar prompts efectivos y específicos con Cursor IDE

Demostrar una arquitectura mínima funcional backend + frontend

Ejecutar todo 100% en entorno local sin dependencias externas

# Autor 

 Facilitado por: Isaac Reyes
Rol: IT & AI Engineering – Fullstack, DevOps, AI Strategy
Objetivo: Elevar capacidades técnicas de desarrollo ágil y guiado con herramientas modernas de productividad como Cursor y Copilot.

# Licencia
Isaac Reyes
