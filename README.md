# EBC-Web-II
Proyecto final - Aplicacion para la gestion de negocios de arquitectura
# Texas Stone Creations: Gestion Integral de Proyectos y Materiales en Arquitectura
          
## Descripcion
La aplicación ”Texas Stone Creations” está diseñada para satisfacer las necesidades tanto de administradores como de clientes, ofreciendo una plataforma centralizada para la gestión de proyectos, generación de cotizaciones y mantenimiento de inventario de productos.
## Requerimientos
* Funcionales
  * Gestion de Proyectos
  * Generacion de Cotizaciones
  * Inventario de Productos
  * Gestion de Clientes
  * Reportes y Analisis
  * Interaccion del Cliente
* No funcionales
  * Rendimiento
  * Escalabilidad
  * Seguridad
  * Usabilidad
  * Mantenibilidad
  * Disponibilidad
  * Compatibilidad
  * Portabilidad
## Stack de tecnologias
*	Backend: Python con Django, SQL/MySQL
*	Frontend: HTML, CSS, JavaScript
*	Frameworks: React.js para la creacion de interfaces dinamicas y responsivas
*	Servidor: Node.js con Express para la gestion del servidor y las API
*	Base de Datos: MongoDB para un almacenamiento flexible y escalable de datos
*	Control de Versiones: Git y GitHub para la gestion del codigo fuente
# Instrucciones de Instalacion y commit de cambios
## Metodo 1

    git clone https://github.com/Leonardo1278/EBC-Web-II.git
    git init
    *insertar archivo en la carpeta local del proyecto*
    git add *nombre* *nuevo nombre.xlsx*   (nombre del archivo a subir)
    git commit -m "first commit"  (entre comillas va el nombre del commit, como un identicador)
    git branch -M main
    git remote add origin https://github.com/Leonardo1278/EBC-APP-2.git
    git push -u origin main

## Metodo 2

    *abrir carpeta vacia con Git Bash*
    git clone https://github.com/Leonardo1278/EBC-Web-II.git
    cd EBC-Web-II (Para abrir main branch)
    *insertar archivo en la carpeta local del proyecto*
    git add . (añade todos los archivos diferentes de la carpeta local al repositorio)
    git commit -m "descripcion del commit"
    git push -u origin main
    
### En caso de requerir branch diferente
reemplazar git push -u origin main por los siguientes pasos

          git checkout -b *nombre-branch*
          git push origin *nombre-branch*
