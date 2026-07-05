# 4. Infraestructura Tecnologica

## 4.1 Arquitectura de Cuatro Capas

La infraestructura se disena como una arquitectura de cuatro capas
completamente libre, donde cada componente puede ser auditado, modificado y
autogestionado por la comunidad.

### Capa 1: Infraestructura Fisica y de Red
- **Sistema operativo**: Debian GNU/Linux
- **Bases de datos**: PostgreSQL / MariaDB
- **Servidores web**: Apache / Nginx
- **Conectividad rural**: Redes mesh comunitarias (LibreMesh)
- **Modelo referencia**: Altermundi (Argentina), Rhizomatica (Mexico)

### Capa 2: Plataforma Educativa
- **LMS**: Moodle (GPL v3, 400M+ usuarios en 240 paises)
- **Videoconferencia**: BigBlueButton (GPL)
- **Colaboracion en documentos**: Nextcloud (AGPL)
- **Mensajeria**: Matrix / Element
- **Desarrollo colaborativo**: GitLab (MIT)

### Capa 3: Contenido y Conocimiento
- **OER**: Recursos Educativos Abiertos bajo licencias Creative Commons
- **Repositorios externos**: MIT OpenCourseWare, Free Technology Academy,
  cursos FSF
- **Hardware libre**: Estandares OSHWA, licencias CERN OHL

### Capa 4: Certificacion y Verificacion
- **Open Badges** (Mozilla) para insignias digitales
- **Modelo SENA** para certificaciones formales
- **Portafolios digitales** para acreditacion integral
- **Blockchain** para verificacion descentralizada de credenciales

---

## 4.2 Escalabilidad y Descentralizacion

La infraestructura es federal y descentralizada:

- Moodle requiere solo **2 vCPU y 2 GB RAM** para 50-100 usuarios
  concurrentes
- Cada region opera su propia instancia de Moodle federada
- Nodos comunitarios en zonas sin internet operan con redes mesh,
  sincronizando contenido asincronicamente
- Cada campus es una replica autonoma que opera independientemente
