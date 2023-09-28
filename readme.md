| Módulo |  |  | Nivel de Dificultad |  |
| :---: | :---: | :---: | :---: | :---: |
| $\begin{array}{l}\text { Desarrollo de aplicaciones JEE conSpring } \\ \text { Framework }\end{array}$ |  |  | Medio |  |
| Tema: El Framework Spring MVC |  |  | Creación de un proyecto Spring MVC |  |
| Intención del aprendizaje o aprendizaje esperado: |  |  |  |  |
| $\begin{array}{l}\text { Configura un proyecto Java utilizando el gestor Maven e incorporando las dependencias } \\ \text { requeridas para obtener un proyecto Spring Framework MVC. } \\ \text { Codifica vistas y controladores que permitan el despliegue de contenidos estáticos para } \\ \text { permitir la navegación web de un usuario. }\end{array}$ |  |  |  |  |
| Planteamiento del Problema: |  |  |  |  |
| $\begin{array}{l}\text { Una empresa de asesorías en prevención de riesgos necesita contar con un sistema de información } \\ \text { que le permita administrar los principales procesos que se llevan a cabo en ella día a día. } \\ \text { Hasta el momento se han definido las siguientes funcionalidades en el sistema: }\end{array}$ |  |  |  |  |
|  |  |  |  |  |
| ID | Nombre | Detalle |  | Actor(es) |
| 1 | Inicio | $\begin{array}{l}\text { Página } \\ \text { informa } \\ \text { que se }\end{array}$ | $\begin{array}{l}\text { nicio del portal con } \\ \text { elevante del proyecto } \\ \text { alizando. }\end{array}$ | $\begin{array}{l}\text { Cliente } \\ \text { Administrativo } \\ \text { Profesional }\end{array}$ |
| 2 | Contacto | $\begin{array}{l}\text { Formul } \\ \text { consult }\end{array}$ | contacto para realizar | Cliente |
| 3 | Crear Capacitación | $\begin{array}{l}\text { Formul } \\ \text { capacit }\end{array}$ | $\begin{array}{l}\text { para crear una } \\ \text { n el sistema. }\end{array}$ | Cliente |
| 4 | Listar Capacitaciones | Listado | acitaciones registradas. | Cliente |
| 5 | Listado de Usuarios | $\begin{array}{l}\text { Listado } \\ \text { platafo }\end{array}$ | usuarios existentes en | Administrativo |
| 6 | Crear Usuario | $\begin{array}{l}\text { Formul } \\ \text { usuario }\end{array}$ | $\begin{array}{l}\text { e permitirá crear un } \\ \text { ema. }\end{array}$ | Administrativo |
| 7 | Editar Cliente | $\begin{array}{l}\text { Formul } \\ \text { datos d }\end{array}$ | $\begin{array}{l}\text { e permite modificar los } \\ \text { uario de tipo cliente. }\end{array}$ | Administrativo |
| 8 | Editar Administrativo | $\begin{array}{l}\text { Formul } \\ \text { datos } \\ \text { adminis }\end{array}$ | $\begin{array}{l}\text { e permite modificar los } \\ \text { In usuario de tipo }\end{array}$ | Administrativo |
| 9 | Editar Profesional | $\begin{array}{l}\text { Formul } \\ \text { datos } \\ \text { profesi }\end{array}$ | $\begin{array}{l}\text { e permite modificar los } \\ \text { in usuario de tipo }\end{array}$ | Administrativo |


| 10 | Listado Visitas | $\begin{array}{l}\text { Lista de todas las visitas realizadas a } \\ \text { cada uno de los clientes. Además, } \\ \text { posee un formulario que permite } \\ \text { agregar nuevas visitas a sistema. }\end{array}$ | Profesional |
| :---: | :---: | :---: | :---: |
| 11 | Responder checklist | Listado de chequeos de una visita. | Profesional |
| 12 | Listado Pago | $\begin{array}{l}\text { Lista de todos los pagos realizados por } \\ \text { los clientes. }\end{array}$ | Administrativo |
| 13 | Crear Pago | Permitirá agregar un pago al sistema. | Administrativo |
| 14 | Listado Asesorías | $\begin{array}{l}\text { Lista con las asesorías realizadas hasta } \\ \text { el momento. }\end{array}$ | Profesional |
| 15 | Crear Asesorías | $\begin{array}{l}\text { Contiene un formulario para agregar } \\ \text { una nueva asesoría. }\end{array}$ | Profesional |
| 16 | Reportes | Despliega reportes específicos. | Profesional |
| 17 | $\begin{array}{l}\text { Administrar } \\ \text { Asistentes }\end{array}$ | $\begin{array}{l}\text { Administración de asistentes a una } \\ \text { capacitación; incluye listarlos, poder } \\ \text { agregar asistentes y eliminarlos. }\end{array}$ | Cliente |
| 18 | Login | $\begin{array}{l}\text { Contendrá un acceso a un usuario al } \\ \text { portal a través de un RUT de usuario y } \\ \text { una clave. }\end{array}$ | $\begin{array}{l}\text { Cliente } \\ \text { Administrativo } \\ \text { Profesional } \\ \end{array}$ |
| 19 | Gestionar accidentes | $\begin{array}{l}\text { Listado con todos los accidentes } \\ \text { registrados en plataforma. Además, } \\ \text { permite editarlos, agregar uno nuevo y } \\ \text { eliminarlos. En esta sección cada } \\ \text { cliente administra sus propios } \\ \text { accidentes. }\end{array}$ | Cliente |
| 20 | Administrar chequeos | $\begin{array}{l}\text { Permite mostrar los distintos } \\ \text { chequeos realizados a cada cliente en } \\ \text { una visita a terreno, y permite agregar } \\ \text { uno nuevo, y cambiar su estado. }\end{array}$ | Administrativo |

En los módulos anteriores de este curso se crearon vistas para algunos de los casos de uso indicados en el listado anterior.

Como parte de este ejercicio se pide realizar lo siguiente:

1. Cree un proyecto web a través del framework Spring MVC. Se recomienda hacerlo a través de STS, pero la metodología queda a discreción del equipo.
2. Cree una clase controlador para cada uno de los siguientes casos de uso: Inicio, Contacto, Crear Capacitación. Cada controlador debe tener un método que despliegue la interfaz respectiva del caso de uso a través de un archivo JSP.
3. Pruebe el proyecto y verifique que todo está en orden.

El entregable debe ser un archivo RAR o ZIP con el contenido asociado al proyecto.

Nota 1: No es necesario que en este ejercicio haga referencia a archivos CSS o JS.

Nota 2: No es necesario que la plataforma se conecte a una base de datos Oracle; solo debe desplegar la interfaz respectiva.

## 1. El Datos de apoyo al planteamiento

Ejecución: Grupal (equipo de no más 4 personas)

Componentes para evaluar: Se deberá entregar un archivo RAR o ZIP con el proyecto comprimido.

Preguntas guía:

Recursos Bibliográficos:

Spring MVC: Configuración

https://www.javatutoriales.com/2015/12/spring-mvc-parte-1-configuracion.html

Introducción a MVC en Spring

http://www.jtech.ua.es/j2ee/publico/spring-2012-13/sesion03-apuntes.html

Crear un proyecto MVC con Spring Tool Suite (STS)

https://www.youtube.com/watch?v=eMG9qi061D8

