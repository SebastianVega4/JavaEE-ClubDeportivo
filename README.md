# ⚽ Club Deportivo Web App 🖥️

Este proyecto consiste en una aplicación web desarrollada con Java EE que permite gestionar y visualizar información almacenada en una base de datos MongoDB. La aplicación utiliza Servlets para la lógica de negocio y JSP para la presentación, mostrando en una página HTML los datos de los afiliados almacenados en la base de datos "clubDeportivo". El servicio es desplegado en un servidor Tomcat, garantizando un entorno robusto para aplicaciones empresariales.

---

### 🎓 Contexto Académico y Funcionalidad

El proyecto ha sido desarrollado en el marco de un trabajo académico para la carrera de Ingeniería de Sistemas, donde se aplican conceptos de desarrollo web, persistencia de datos y arquitecturas basadas en Java EE.  
La aplicación permite:
- 🔌 Conectar y gestionar la base de datos MongoDB mediante la clase `MongoDBManager`.
- ✅ Verificar la existencia de la colección "afiliados" y crearla si es necesario.
- 📝 Mostrar un formulario de afiliados con campos para registrar información personal, detalles de disciplinas y eventos deportivos.
- 📊 Listar en una tabla los datos de los afiliados, facilitando la consulta y administración de la información.

---

### 🛠️ Tecnologías y Herramientas Utilizadas

- **Lenguaje de Programación:** Java ☕
- **Servidor de Aplicaciones:** Tomcat 🐱
- **Framework Web:** Java EE (Servlets y JSP) 🌐
- **Base de Datos:** MongoDB 🍃
- **Estilos y Diseño:** HTML, CSS y Bootstrap 🎨
- **Conectividad:** Driver de MongoDB para Java 🔗

---

### 📁 Estructura del Repositorio

La organización del repositorio es la siguiente:
```
Ruta_Mas_Corta-Boyaca/
│
├── src/ 
│   ├── co/edu/uptc/persistence/
│   │     └── MongoDBManager.java     # Clase para gestionar la conexión con MongoDB
│   │
│   └── co/edu/uptc/servlets/
│         └── (Clases de Servlets)      # Clases encargadas del manejo de la lógica de negocio
│
├── WebContent/
│   ├── css/
│   │     └── estilos.css              # Archivo de estilos personalizados
│   │
│   ├── js/
│   │     └── script.js                # Scripts JavaScript para la interacción del formulario
│   │
│   ├── WEB-INF/
│   │     └── web.xml                  # Archivo de configuración de la aplicación web
│   │
│   ├── index.jsp                    # Página principal con el formulario de afiliados
│   └── consul.jsp                   # Página para realizar consultas y visualizar datos
│
└── README.md                        # Documentación del proyecto
```

---

### 🧠 Modelo de Datos y Lógica de Negocio

La clase `MongoDBManager` se encarga de establecer la conexión con MongoDB y garantizar la existencia de la colección "afiliados" en la base de datos "clubDeportivo". A partir de esta conexión, la aplicación permite insertar, actualizar y consultar registros de afiliados, los cuales incluyen información personal y detalles de participación en disciplinas y eventos deportivos.

El flujo principal de la aplicación se desarrolla en las páginas JSP, donde se presenta un formulario que recopila:
- 👤 Datos personales del afiliado (ID, nombre y apellido).
- 🏅 Información relacionada con disciplinas deportivas (ID y nombre, modalidad individual o grupal).
- 🏆 Datos de eventos deportivos (ID, nombre y puesto obtenido).

La información es enviada a los Servlets correspondientes, los cuales gestionan las operaciones CRUD (crear, leer, actualizar y eliminar) sobre la base de datos.

---

### 🚀 Instrucciones de Ejecución

1. **Clonar el repositorio:**
```bash
git clone https://github.com/SebastianVega4/JavaEE-ClubDeportivo.git
```

2. **Importar el proyecto en un IDE compatible con Java EE (como Eclipse o IntelliJ IDEA).**

3. **Configurar el Servidor:**
   - 🛠️ Instalar y configurar Apache Tomcat.
   - 🧪 Asegurarse de tener MongoDB corriendo en `localhost` en el puerto `27017`.

4. **Desplegar la aplicación:**
   - ⚙️ Configurar el proyecto como una aplicación web dinámica.
   - 🔄 Ejecutar el servidor Tomcat y desplegar el proyecto.

5. **Acceder a la aplicación:**
   - 🌐 Abrir un navegador y navegar a la URL: `http://localhost:8080/JavaEE-ClubDeportivo` para visualizar el formulario y consultar la información de afiliados.

---

### 🎯 Contribución Académica

Este proyecto permite a los estudiantes integrar conceptos de desarrollo web con Java EE y bases de datos NoSQL. Se enfatiza la importancia de:
- 🔗 Gestionar conexiones a bases de datos y la creación automática de colecciones.
- 🧱 Implementar una arquitectura basada en Servlets y JSP para separar la lógica de negocio de la presentación.
- 🎨 Aplicar buenas prácticas en el diseño de interfaces web utilizando Bootstrap.

---

## 👨‍🎓 Autor

Desarrollado por **Sebastián Vega**  
📧 *Sebastian.vegar2015@gmail.com*  
🔗 [LinkedIn - Johan Sebastián Vega Ruiz](https://www.linkedin.com/in/johan-sebastian-vega-ruiz-b1292011b/)

---
 
## 📜 Licencia

Este repositorio se encuentra bajo la Licencia GPL 3.0.

**Permisos:**
- Uso comercial
- Modificación
- Distribución
- Uso privado

---


Facultad de Ingeniería — Ingeniería de Sistemas 🧩
**🏫 Universidad Pedagógica y Tecnológica de Colombia**  
📍 Sogamoso, Boyacá 📍

© 2025 — Sebastian Vega
