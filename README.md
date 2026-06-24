# 🐶 VetCare Manager

Aplicación móvil desarrollada en React Native con Expo y TypeScript para la gestión de solicitudes de atención en una clínica veterinaria.

## 📋 Descripción

VetCare Manager permite registrar, consultar, actualizar y eliminar solicitudes de atención veterinaria, facilitando la organización de consultas, vacunaciones, emergencias y servicios de grooming.

La aplicación implementa los fundamentos del desarrollo móvil utilizando:

- React Native
- Expo
- TypeScript
- React Navigation
- Context API
- useReducer
- Componentes reutilizables
- Diseño UI/UX moderno

---

## 🎯 Problemática

Actualmente muchas clínicas veterinarias registran solicitudes mediante llamadas telefónicas y WhatsApp, generando problemas como:

- Pérdida de información
- Duplicidad de registros
- Falta de seguimiento
- Desorganización en las atenciones

VetCare Manager proporciona una solución inicial para gestionar estas solicitudes de manera estructurada.

---

## 🚀 Funcionalidades

### 🔐 Login

- Validación de usuario y contraseña.
- Acceso a la aplicación.

### 🏠 Dashboard

- Total de solicitudes.
- Solicitudes pendientes.
- Solicitudes en atención.
- Solicitudes finalizadas.

### 📋 Gestión de Solicitudes

- Listar solicitudes.
- Buscar por cliente o mascota.
- Filtrar por estado.
- Ver detalle de solicitud.
- Editar solicitud.
- Eliminar solicitud.

### ➕ Registro de Solicitudes

Permite registrar:

- Nombre del cliente
- Teléfono
- Nombre de la mascota
- Tipo de servicio
- Descripción
- Prioridad

### 📊 Estados

- PENDIENTE
- EN_ATENCION
- FINALIZADO

### ⚡ Prioridades

- BAJA
- MEDIA
- ALTA

---

## 🏗️ Arquitectura del Proyecto

```text
VetCareManager
│
├── src
│   │
│   ├── components
│   │   ├── CustomButton.tsx
│   │   ├── CustomInput.tsx
│   │   ├── FilterChip.tsx
│   │   ├── PriorityChip.tsx
│   │   ├── SolicitudCard.tsx
│   │   └── StatusChip.tsx
│   │
│   ├── context
│   │   ├── SolicitudContext.tsx
│   │   └── SolicitudReducer.ts
│   │
│   ├── data
│   │   └── mockSolicitudes.ts
│   │
│   ├── models
│   │   └── Solicitud.ts
│   │
│   ├── navigation
│   │   └── AppNavigator.tsx
│   │
│   ├── screens
│   │   ├── LoginScreen.tsx
│   │   ├── HomeScreen.tsx
│   │   ├── SolicitudesScreen.tsx
│   │   ├── DetailSolicitudScreen.tsx
│   │   ├── EditSolicitudScreen.tsx
│   │   └── CreateSolicitudScreen.tsx
│   │
│   └── utils
│
├── App.tsx
├── package.json
└── README.md
```

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Versión |
|------------|----------|
| React Native | 0.85 |
| Expo | 56 |
| TypeScript | 6 |
| React Navigation | 7 |
| Expo Vector Icons | 15 |

---

## 📦 Instalación

### 1. Clonar repositorio

```bash
git clone https://github.com/TU-USUARIO/VetCareManager.git
```

### 2. Ingresar al proyecto

```bash
cd VetCareManager
```

### 3. Instalar dependencias

```bash
npm install
```

### 4. Instalar Picker

```bash
npx expo install @react-native-picker/picker
```

---

## ▶️ Ejecución

### Iniciar Expo

```bash
npx expo start
```

### Android

```bash
npx expo start --android
```

### iOS

```bash
npx expo start --ios
```

---

## 🧪 Cómo Probar el CRUD

### Login

Ingresar:

```text
Usuario: admin
Contraseña: 123456
```

---

### Crear Solicitud

Home → Nueva Solicitud

Completar:

```text
Cliente:
Adrian Santisteban

Teléfono:
999888777

Mascota:
Chocolate

Servicio:
Consulta

Descripción:
Control veterinario anual.

Prioridad:
MEDIA
```

Guardar solicitud.

---

### Ver Solicitudes

Home → Ver Solicitudes

Visualizar todas las solicitudes registradas.

---

### Buscar

Utilizar la barra de búsqueda:

```text
Chocolate
Carlos
Firulais
```

---

### Filtrar

Utilizar los chips:

- Todos
- Pendientes
- En Atención
- Finalizados

---

### Editar

Seleccionar una solicitud.

Presionar:

```text
Editar Solicitud
```

Modificar:

- Estado
- Prioridad
- Descripción

Guardar cambios.

---

### Eliminar

Seleccionar una solicitud.

Presionar:

```text
Eliminar Solicitud
```

Confirmar eliminación.

---

## 📱 Capturas de Pantalla

Agregar aquí capturas de:

- Login
  <img width="483" height="879" alt="Login aplicativo VetCareManager" src="https://github.com/user-attachments/assets/b14fb3c4-9687-4f9a-a472-93d60be6576f" />

- Home Dashboard
  <img width="484" height="879" alt="Home Dashboard aplicativo VetCareManager" src="https://github.com/user-attachments/assets/2da1d96e-fa70-4b0a-b5db-0740366aca2e" />

- Listado de Solicitudes
  <img width="481" height="879" alt="Lista de Solicitudes aplicativo VetCareManager" src="https://github.com/user-attachments/assets/6d14bc72-9640-4ef2-80b5-b590d4216a1f" />

- Detalle de Solicitud
  <img width="479" height="879" alt="Detalle de Solicitudes aplicativo VetCareManager" src="https://github.com/user-attachments/assets/616cd8ed-937b-4069-a656-635c8e4c6d52" />

- Crear Solicitud
  <img width="478" height="879" alt="Crear Solicitudes aplicativo VetCareManager" src="https://github.com/user-attachments/assets/0b64929d-b876-4a4d-881b-854776eb91c2" />


---

## 👥 Integrantes

| Integrante | Rol |
|------------|------|
| Santisteban Manrique Adrian Daniel | Frontend Developer |
| Siri Vergara Maria Alejandra | Backend / QA |
| Villasante Contreras Jean Paul | UX/UI |

---

## 🎓 Proyecto Académico

Desarrollado para el curso de Desarrollo de Aplicativos Móviles utilizando React Native, Expo y TypeScript.

Instituto: IDAT

Año: 2026

---

## 📄 Licencia

Proyecto desarrollado con fines educativos.
