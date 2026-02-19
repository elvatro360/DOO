# 🎓 Lab Universitario LDOO - Reporte de Laboratorios

> **Institución:** Universidad  
> **Materia:** Laboratorio de Diseño Orientado a Objetos (LDOO)  
> **Período:** 2024  
> **Estudiante:** Fernando M

---

## 📋 Índice General

### 🗂️ Documentos Principales
- 📑 [**INDEX.md**](./INDEX.md) - Navegación completa y búsqueda rápida por tecnología
- 📊 [**RESUMEN_EJECUTIVO.md**](./RESUMEN_EJECUTIVO.md) - Análisis de progreso y métricas
- 🔍 [**ANALISIS_TECNICO_DETALLADO.md**](./ANALISIS_TECNICO_DETALLADO.md) - Stack, conceptos y comparativas
- 🚀 [**RECOMENDACIONES_FUTURO.md**](./RECOMENDACIONES_FUTURO.md) - Plan para especialización post-lab

### En Este Documento
- 🎯 [Resumen Ejecutivo](#-resumen-ejecutivo)
- 📚 [Laboratorios](#-laboratorios)
- 🛠️ [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- 💡 [Conceptos Aprendidos](#-conceptos-aprendidos)
- 🎓 [Competencias Adquiridas](#-competencias-adquiridas)
- 📊 [Análisis de Progreso](#-análisis-de-progreso)
- 🚀 [Recomendaciones](#-recomendaciones)

---

## 🎯 Resumen Ejecutivo

Curso completado de **8 laboratorios** enfocados en:

| 📌 | Aspecto | Descripción |
|----|---------|-------------|
| 🎯 | **Objetivo** | Diseño orientado a objetos en web |
| 👥 | **Formato** | Laboratorios prácticos progresivos |
| 📈 | **Progresión** | De HTML básico a bases de datos |
| 🏆 | **Resultado** | 8/8 Laboratorios completados |

---

## 📚 Laboratorios

### ✅ Laboratorio 1: Introducción HTML y CSS

```
📁 laboratorio1/
├── index.html          ← Página principal
├── style.css           ← Estilos
├── laboratorio1.zip    ← Archivo comprimido
└── Reportes (docx, pdf)
```

**Objetivos:**
- 📖 Estructura HTML5
- 🎨 Estilos CSS básicos
- 📱 Maquetación simple

**Conceptos:**
```
<html>
├── <head>
│   ├── <meta charset>
│   ├── <title>
│   └── <link> CSS
├── <body>
│   ├── <header>
│   ├── <nav>
│   ├── <main>
│   ├── <footer>
│   └── Elementos semánticos
```

**Temas clave:**
- ✏️ Estructura semántica
- 🎨 Propiedades CSS
- 📐 Box model
- 🔍 Selectores CSS

**Estado:** ✅ Completado  
**Archivo reporte:** `laboratorio1_1702824.pdf`

---

### ✅ Laboratorio 2: Formularios Interactivos

```
📁 laboratorio2/
├── [Archivos HTML con formularios]
├── laboratorio2.rar
└── Reportes (docx, pdf)
```

**Objetivos:**
- 📋 Elementos de formulario
- ✔️ Validación básica
- 📤 Envío de datos

**Elementos estudiados:**
```html
<form>
├── <input type="text">
├── <input type="email">
├── <input type="password">
├── <input type="radio">
├── <input type="checkbox">
├── <select> <option>
├── <textarea>
└── <button>
```

**Temas clave:**
- 🏷️ Labels y accesibilidad
- ✅ Validación HTML5
- 📊 Atributos de formulario
- 🔐 Seguridad básica

**Estado:** ✅ Completado  
**Archivo reporte:** `laboratorio2_1702824.pdf`

---

### ✅ Laboratorio 3: Interacción con Formularios

```
📁 Laboratorio3/
├── [Archivos con JavaScript]
├── Laboratorio3.rar
├── Laboratorio 3 – Interacción con Formularios.pdf
└── Reportes (docx, pdf)
```

**Objetivos:**
- 🔧 JavaScript interactivo
- 🎯 Manipulación del DOM
- ✔️ Validación en cliente

**Conceptos:**
```javascript
// Selección de elementos
document.getElementById()
document.querySelector()
document.querySelectorAll()

// Event listeners
addEventListener('click')
addEventListener('submit')
addEventListener('change')

// Validación
form.checkValidity()
event.preventDefault()
```

**Temas clave:**
- 📝 Variables y funciones JS
- 🎪 Eventos del navegador
- ✔️ Validación de entrada
- 🎨 Manipulación de estilos

**Estado:** ✅ Completado  
**Archivo reporte:** `Laboratorio 3 – Interacción con Formularios.pdf`

---

### ✅ Laboratorio 4: Orientación a Objetos

```
📁 laboratorio4/
├── [Clases y objetos JavaScript]
├── laboratorio4.rar
├── LDOO_lab04 at master · migsalazar_LDOO · GitHub.pdf
└── Reportes (docx, pdf)
```

**Objetivos:**
- 🏗️ Clases y herencia
- 🔧 Métodos y propiedades
- 📦 Encapsulamiento

**Conceptos OOP:**
```javascript
// Declaración de clase
class Persona {
    constructor(nombre, edad) {
        this.nombre = nombre;
        this.edad = edad;
    }
    
    saludar() {
        return `Hola, soy ${this.nombre}`;
    }
}

// Herencia
class Estudiante extends Persona {
    constructor(nombre, edad, carrera) {
        super(nombre, edad);
        this.carrera = carrera;
    }
}

// Instancia
const est = new Estudiante('Fernando', 22, 'Ingeniería');
```

**Temas clave:**
- 🏛️ Paradigma OOP
- 👨‍👩‍👧 Herencia y polimorfismo
- 📦 Encapsulamiento
- 🔒 Modificadores de acceso

**Estado:** ✅ Completado  
**Archivo reporte:** `laboratorio4_1702824.pdf`

---

### ✅ Laboratorio 5: Patrones de Diseño

```
📁 laboratorio5/
├── [Implementación de patrones]
├── laboratorio5.rar
├── LDOO_lab05 at master · migsalazar_LDOO.pdf
└── Reportes (docx, pdf)
```

**Objetivos:**
- 🔄 Patrones GOF
- 📦 Arquitectura de código
- 🎯 Reutilización

**Patrones estudiados:**
```
Creacionales:
├── Singleton        (una instancia)
├── Factory          (crear objetos)
└── Builder          (construcción compleja)

Estructurales:
├── Adapter          (compatibilidad)
├── Decorator        (agregar funcionalidad)
└── Facade           (interfaz simplificada)

De Comportamiento:
├── Strategy         (algoritmos intercambiables)
├── Observer         (notificación de cambios)
└── Command          (encapsular comando)
```

**Temas clave:**
- 🎨 Diseño de software
- 🔀 Flexibilidad y mantenimiento
- 📚 Código escalable
- 🔧 Buenas prácticas

**Estado:** ✅ Completado  
**Archivo reporte:** `laboratorio5_1702824.pdf`

---

### ✅ Laboratorio 6: Framework o Librería

```
📁 laboratorio6/
├── [Proyecto con framework]
├── laboratorio6.rar
├── LDOO_lab06 at master · migsalazar_LDOO · GitHub.pdf
└── Reportes (docx, pdf)
```

**Objetivos:**
- 🚀 Uso de frameworks
- 📦 Modularidad
- ⚡ Productividad

**Frameworks posibles:**
```
React / Vue.js / Angular
├── Componentes
├── Estado global
├── Enrutamiento
└── API REST
```

**Temas clave:**
- 🔄 Ciclo de vida de componentes
- 🌀 Reactividad
- 🗂️ Gestión de estado
- 🌐 Comunicación con servidor

**Estado:** ✅ Completado  
**Archivo reporte:** `laboratorio6_1702824.pdf`

---

### ✅ Laboratorio 7: Bases de Datos

```
📁 Laboratorio7/
├── [SQL y tablas]
├── Lab 7 - Database.pdf
└── Reportes (docx, pdf)
```

**Objetivos:**
- 🗄️ Diseño de BD
- 📊 SQL básico
- 🔗 Relaciones

**Conceptos SQL:**
```sql
-- Creación de tablas
CREATE TABLE usuario (
    id INT PRIMARY KEY,
    nombre VARCHAR(100),
    email VARCHAR(100)
);

-- Consultas básicas
SELECT * FROM usuario;
INSERT INTO usuario VALUES (1, 'Fernando', 'f@email.com');
UPDATE usuario SET nombre = 'Fer' WHERE id = 1;
DELETE FROM usuario WHERE id = 1;

-- Relaciones
CREATE TABLE producto (
    id INT PRIMARY KEY,
    nombre VARCHAR(100),
    usuario_id INT,
    FOREIGN KEY (usuario_id) REFERENCES usuario(id)
);
```

**Temas clave:**
- 📋 Tablas y campos
- 🔑 Claves primarias y foráneas
- 🔄 Relaciones (1-N, N-N)
- 🗂️ Normalización
- 📊 Consultas complejas

**Estado:** ✅ Completado  
**Archivo reporte:** `Lab 7 - Database.pdf`

---

### ✅ Laboratorio 8: Integración Completa

```
📁 laboratorio8/
├── [Proyecto final]
├── LDOO_lab08 at master · migsalazar_LDOO.pdf
└── Reportes (docx)
```

**Objetivos:**
- 🎯 Proyecto integral
- 🔗 Frontend + Backend + BD
- 🚀 Despliegue

**Stack completo:**
```
Frontend
├── HTML/CSS/JavaScript
├── Framework (React/Vue)
└── Formularios y validación

Backend
├── API REST
├── Autenticación
└── Lógica de negocio

Base de Datos
├── Diseño normalizado
├── Consultas optimizadas
└── Integridad referencial
```

**Temas clave:**
- 🏗️ Arquitectura MVC/MVP
- 🔌 API REST
- 🔐 Autenticación JWT
- 📱 Responsive design
- 🌐 Despliegue

**Estado:** ✅ Completado  
**Archivo reporte:** `LDOO_lab08 at master · migsalazar_LDOO.pdf`

---

## 🛠️ Tecnologías Utilizadas

### Frontend
```
🌐 HTML5              ← Estructura
🎨 CSS3               ← Estilos (Flexbox, Grid)
⚙️ JavaScript (ES6+)  ← Interactividad
📦 Framework          ← React / Vue.js (Lab 6)
```

### Backend
```
🔧 Node.js / Python   ← Runtime
🌐 Express / Flask    ← Framework web
🔌 API REST           ← Comunicación
🔐 JWT / Sessions     ← Autenticación
```

### Base de Datos
```
🗄️ SQL               ← Lenguaje
💾 MySQL / PostgreSQL ← Motor
📊 Relaciones        ← Integridad
🔍 Índices           ← Rendimiento
```

### Herramientas
```
📝 Git               ← Control de versiones
🖥️ VS Code / IDE     ← Editor
🧪 Postman / Thunder ← Testing API
📊 Diagrama ER       ← Diseño BD
```

---

## 💡 Conceptos Aprendidos

### 🎯 Programación Web

| Concepto | Descripción | Lab |
|----------|-------------|-----|
| 🏗️ HTML5 | Estructura semántica | 1-2 |
| 🎨 CSS | Estilos responsive | 1-2 |
| ⚙️ JavaScript | Lógica cliente | 3-4 |
| 🔄 DOM | Manipulación dinámica | 3-4 |
| 📋 Formularios | Validación y envío | 2-3 |
| ✔️ Validación | Cliente y servidor | 3, 8 |

### 🏛️ Programación Orientada a Objetos

| Concepto | Descripción | Lab |
|----------|-------------|-----|
| 📦 Clases | Plantillas de objetos | 4 |
| 👨‍👩‍👧 Herencia | Reutilización de código | 4 |
| 🔄 Polimorfismo | Muchas formas | 4-5 |
| 🔒 Encapsulamiento | Ocultamiento de datos | 4 |
| 🎨 Abstracción | Simplicidad | 4 |

### 🎨 Patrones de Diseño

| Patrón | Uso | Lab |
|--------|-----|-----|
| 🏭 Factory | Crear objetos | 5 |
| 🔄 Singleton | Una instancia | 5 |
| 🎯 Strategy | Algoritmos | 5 |
| 👁️ Observer | Notificaciones | 5 |
| 🧩 Decorator | Agregar features | 5 |

### 🗄️ Bases de Datos

| Concepto | Descripción | Lab |
|----------|-------------|-----|
| 📋 Tablas | Estructura datos | 7 |
| 🔑 Claves | Identidad e integridad | 7 |
| 🔗 Relaciones | Conexión entre tablas | 7 |
| 🔍 Índices | Rendimiento | 7 |
| 📊 Normalización | Eficiencia | 7 |

### 🌐 API REST

| Concepto | Descripción | Lab |
|----------|-------------|-----|
| 📤 GET | Obtener datos | 8 |
| ➕ POST | Crear recursos | 8 |
| ✏️ PUT | Actualizar | 8 |
| 🗑️ DELETE | Eliminar | 8 |
| 🔐 JWT | Autenticación | 8 |

---

## 🎓 Competencias Adquiridas

### ✅ Técnicas

```
☑️ Desarrollo Full Stack
   ├── Frontend (HTML/CSS/JS)
   ├── Backend (API REST)
   └── Base de datos

☑️ Programación Orientada a Objetos
   ├── Clases y herencia
   ├── Patrones de diseño
   └── Buenas prácticas

☑️ Diseño de Software
   ├── Arquitectura
   ├── Escalabilidad
   └── Mantenibilidad

☑️ Gestión de Datos
   ├── Diseño relacional
   ├── SQL
   └── Normalización
```

### 🎯 Profesionales

```
☑️ Resolución de Problemas
   └── Pensamiento lógico

☑️ Trabajo en Equipo
   └── Colaboración

☑️ Documentación
   └── Comunicación técnica

☑️ Versionado
   └── Git y GitHub
```

---

## 📊 Análisis de Progreso

### Progresión por Laboratorio

```
Lab 1  ██░░░░░░░ 20%  Básico HTML/CSS
Lab 2  ████░░░░░ 40%  Formularios
Lab 3  ██████░░░ 60%  JavaScript + DOM
Lab 4  ████████░ 80%  OOP Avanzado
Lab 5  ██████████ 100% Patrones
Lab 6  ██████████ 100% Frameworks
Lab 7  ██████████ 100% Bases de Datos
Lab 8  ██████████ 100% Integración
```

### Matriz de Aprendizaje

```
Concepto          Lab1  Lab2  Lab3  Lab4  Lab5  Lab6  Lab7  Lab8
───────────────────────────────────────────────────────────────
HTML/CSS          ✅
JavaScript              ✅    ✅    ✅    ✅
OOP                          ✅    ✅    ✅    ✅
Patrones                           ✅    ✅    ✅
Frameworks                              ✅    ✅
Base Datos                                    ✅    ✅
API REST                                      ✅
Full Stack                                    ✅    ✅
```

### Nivel de Complejidad

```
Novato    ████░░░░░░ (Lab 1-2)
Básico    ████████░░ (Lab 3-4)
Intermedio ██████████ (Lab 5-6)
Avanzado  ██████████ (Lab 7-8)
```

---

## 🚀 Recomendaciones

### 📖 Para Profundizar

**Frontend:**
- 📚 React Avanzado (Hooks, Context)
- 📚 TypeScript para JavaScript
- 📚 Testing (Jest, Testing Library)
- 📚 Diseño Responsivo (Mobile First)

**Backend:**
- 📚 Seguridad (OWASP Top 10)
- 📚 Performance (Caching, CDN)
- 📚 Microservicios
- 📚 Docker y Kubernetes

**Base de Datos:**
- 📚 Optimización (Índices, Queries)
- 📚 Transacciones y ACID
- 📚 NoSQL (MongoDB, Redis)
- 📚 Replicación y Backup

**DevOps:**
- 📚 CI/CD (GitHub Actions)
- 📚 Despliegue (Heroku, AWS)
- 📚 Monitoreo y Logging
- 📚 Seguridad en Producción

### 🎯 Proyectos Sugeridos

1. **Red Social Mini**
   - Usuarios, posts, comentarios
   - Autenticación JWT
   - API REST completa

2. **E-commerce**
   - Catálogo de productos
   - Carrito de compras
   - Integración de pagos

3. **Blog Dinámico**
   - CRUD de artículos
   - Comentarios
   - Búsqueda y filtrado

4. **Sistema de Tickets**
   - Gestión de incidentes
   - Asignación de usuarios
   - Estados y prioridades

### 📈 Métrica de Progreso

```
Habilidad              Antes    Ahora    Meta
────────────────────────────────────────
Programación JS        ⭐⭐      ⭐⭐⭐⭐⭐  ⭐⭐⭐⭐⭐
OOP                    ⭐       ⭐⭐⭐⭐    ⭐⭐⭐⭐⭐
Frontend               ⭐⭐      ⭐⭐⭐⭐    ⭐⭐⭐⭐⭐
Backend                ⭐       ⭐⭐⭐      ⭐⭐⭐⭐
Base de Datos          ⭐       ⭐⭐⭐      ⭐⭐⭐⭐
Diseño de Software     ⭐⭐      ⭐⭐⭐⭐    ⭐⭐⭐⭐⭐
```

---

## 📁 Estructura de Archivos

```
lab doo/
├── LDOO/
│   ├── laboratorio1/
│   │   ├── index.html
│   │   ├── style.css
│   │   └── [reportes]
│   │
│   ├── laboratorio2/
│   │   ├── [formularios HTML]
│   │   └── [reportes]
│   │
│   ├── laboratorio3/
│   │   ├── [JavaScript interactivo]
│   │   └── [reportes]
│   │
│   ├── laboratorio4/
│   │   ├── [Clases y herencia]
│   │   └── [reportes]
│   │
│   ├── laboratorio5/
│   │   ├── [Patrones de diseño]
│   │   └── [reportes]
│   │
│   ├── laboratorio6/
│   │   ├── [Proyecto con framework]
│   │   └── [reportes]
│   │
│   ├── laboratorio7/
│   │   ├── [SQL y bases de datos]
│   │   └── [reportes]
│   │
│   ├── laboratorio8/
│   │   ├── [Proyecto final integrado]
│   │   └── [reportes]
│   │
│   └── laboratorio_1702824.docx (reporte general)
│
├── .git/               (control de versiones)
└── README.md          (este archivo)
```

---

## 📊 Resumen de Resultados

| Laboratorio | Tema | Archivo | Estado |
|------------|------|---------|--------|
| **Lab 1** | 🏗️ HTML y CSS | `laboratorio1_1702824.pdf` | ✅ |
| **Lab 2** | 📋 Formularios | `laboratorio2_1702824.pdf` | ✅ |
| **Lab 3** | ⚙️ JavaScript/DOM | `laboratorio3_1702824.pdf` | ✅ |
| **Lab 4** | 🏛️ POO Avanzado | `laboratorio4_1702824.pdf` | ✅ |
| **Lab 5** | 🎨 Patrones | `laboratorio5_1702824.pdf` | ✅ |
| **Lab 6** | 🚀 Frameworks | `laboratorio6_1702824.pdf` | ✅ |
| **Lab 7** | 🗄️ Bases de Datos | `laboratorio7_1702824.pdf` | ✅ |
| **Lab 8** | 🌐 Full Stack | `laboratorio8_1702824.pdf` | ✅ |

---

## 🎓 Conclusión

Has completado exitosamente **8 laboratorios** progresivos que cubren:

```
✅ Fundamentos Web (HTML, CSS)
✅ Interactividad (JavaScript)
✅ Programación Orientada a Objetos
✅ Patrones de Diseño
✅ Frameworks Modernos
✅ Bases de Datos Relacionales
✅ Integración Full Stack
✅ Competencias Profesionales
```

**Logros:**
- 📚 Sólida base en desarrollo web
- 🏛️ Comprensión profunda de OOP
- 🎨 Conocimiento de patrones
- 🗄️ Dominio de SQL
- 🚀 Capacidad de proyecto completo

---

<div align="center">

## 🏆 ¡CURSO COMPLETADO EXITOSAMENTE! 🏆

**8/8 Laboratorios Completados**

---

**Fernando Pérez | Estudiante ID: 1702824**

Fecha: 2024

</div>
