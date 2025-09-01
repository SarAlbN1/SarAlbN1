# 👋 ¡Hola, soy Sara Albarracín  

## 🚀 Sobre mí  
- 🎓 Estudiante de **Ingeniería de Sistemas** en la **Pontificia Universidad Javeriana**  
- 💻 Actualmente trabajando en el **departamento IT+D en INDESCO SAS BIC** como **Analista IT**, encargada de **mesa de ayuda y soporte para software**  
- 🌱 Interesada en **arquitectura de software, desarrollo móvil, cloud y automatización**  
- ⚡ Me gusta aprender constantemente y aplicar metodologías como **SCRUM, ITIL y Lean Startup** en proyectos reales.  

---

## 🛠️ Tecnologías y Herramientas  
💡 Algunas tecnologías con las que trabajo:  

- **Lenguajes:** ![Java](https://img.shields.io/badge/Java-ED8B00?logo=java&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)  

- **Frameworks/Librerías:** ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot&logoColor=white) ![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?logo=thymeleaf&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB) ![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)  

- **Bases de datos:** ![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white)  

- **DevOps / Cloud:** ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black) ![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)  

- **Otros:** ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) ![Office 365](https://img.shields.io/badge/Microsoft_365-D83B01?logo=microsoftoffice&logoColor=white) Rclone, PlantUML  

---

## 📌 Proyectos destacados  

🔹 **[Scripts IT]()** – Scripts en PowerShell y Python para automatización en servidores, backups y auditorías.  

🔹 **[EduVerse](https://github.com/SarAlbN1/eduverse-innovacion)** – Proyecto de gestión e innovación TI.  

🔹 **[Gestión de Aulas Distribuidas](https://github.com/SarAlbN1/gestion-aulas-distribuidas)** – Proyecto final de sistemas distribuidos con Java.  

🎓 **Gestión de Aulas Distribuidas - Pontificia Universidad Javeriana**  
Este proyecto implementa un sistema distribuido para la asignación de aulas (salones y laboratorios) entre programas académicos de distintas facultades universitarias.  
Es parte del curso **Introducción a los Sistemas Distribuidos**, y está desarrollado por **Sara Albarracín**.  

📂 **Estructura del Proyecto**  
```
GestionAulas-SisteDistri/
├── src/                    # Código fuente organizado por paquetes
│   ├── modelo/             # Clases de dominio: Solicitud, Aula, Constantes
│   ├── programas/          # Programas académicos (generan solicitudes)
│   ├── facultades/         # Facultades (intermediarios)
│   ├── servidor/           # Lógica de asignación y concurrencia
│   └── tolerancia/         # HealthChecker y Servidor réplica
├── target/                 # Archivos .class generados por Maven
├── run/                    # Scripts de ejecución por módulo
├── data/                   # Logs, asignaciones y solicitudes
├── pom.xml                 # Archivo de configuración de Maven
└── README.md               # Documentación del proyecto
```

📦 **Dependencias**  
- Gson 2.10.1 – Serialización/deserialización de objetos en JSON  
- JeroMQ 0.5.2 – Comunicación entre procesos con ZeroMQ  

🛠️ **Compilación con Maven**  
```bash
mvn clean compile
```

🚀 **Ejecución por módulo**  
```bash
# Iniciar el servidor principal
./run/run_servidor.sh

# Iniciar una facultad
./run/run_facultad.sh <ipServidor>

# Iniciar un programa académico
./run/run_programa.sh <nombre> <semestre> <salones> <laboratorios> <ipFacultad>

# Iniciar el servidor réplica (backup)
./run/run_backup.sh

# Iniciar el verificador de salud (tolerancia a fallos)
./run/health_check.sh
```

📁 **Carpetas de Datos**  
- `data/asignaciones/` → Asignaciones exitosas  
- `data/logs/` → Logs de errores, rechazos o alertas  
- `data/solicitudes/` → Historial de solicitudes  

👩‍💻 **Desarrollado por**  
Sara Albarracín – Pontificia Universidad Javeriana  

---

🔹 **[CampusGo](https://github.com/ICM2025/CampusGo)** – Aplicación móvil para compra y venta de materiales académicos en campus universitarios.  
   - 👥 Conexión entre estudiantes para economía colaborativa.  
   - 🏷️ Publicación y gestión de productos académicos.  
   - 💬 Chat y llamadas en tiempo real.  
   - 🗺️ Seguimiento de entregas con GPS.  
   - 🪪 Verificación universitaria con biometría y carnet estudiantil.  

🔹 **[HostGo Frontend](https://github.com/JuanPablogh0412/DesarrolloWeb_Host-Go)** – Aplicación frontend desarrollada con **Angular**.  
   - 🌐 Proyecto generado con **Angular CLI 19.2.6**.  
   - 🔄 Recarga automática con `ng serve`.  
   - 🛠️ Scaffolding de componentes, directivas y pipes.  
   - ✅ Pruebas unitarias con **Karma** y e2e configurables.  
   - 🚀 Optimización de builds para producción.  

---

## 📊 GitHub Stats  

![Sara's GitHub stats](https://github-readme-stats.vercel.app/api?username=SarAlbN1&show_icons=true&theme=transparent)  
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=SarAlbN1&layout=compact&theme=transparent)  
[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com?user=SarAlbN1&theme=transparent)](https://git.io/streak-stats)  

---

## 🌐 Conecta conmigo  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sara-albarracin-27991124b)  
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:sara.albar@altmail.kr)  

---

✨ Gracias por visitar mi perfil 
