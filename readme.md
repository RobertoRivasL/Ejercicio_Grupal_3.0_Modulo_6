| Módulo |  |  | Nivel de Dificultad |  |
| :---: | :---: | :---: | :---: | :---: |
|Desarrollo de aplicaciones JEE conSpring } |  |  | Medio |  |
| Tema: El Framework Spring MVC |  |  | Creación de un proyecto Spring MVC |  |
| Intención del aprendizaje o aprendizaje esperado: |  |  |  |  |
| Configura un proyecto Java utilizando el gestor Maven e incorporando las dependencias requeridas para obtener un proyecto Spring Framework MVC.  \\ Codifica vistas y controladores que permitan el despliegue de contenidos estáticos para permitir la navegación web de un usuario.|  |  |  |  |
| Planteamiento del Problema: |  |  |  |  |
| Una empresa de asesorías en prevención de riesgos necesita contar con un sistema de información } \\  que le permita administrar los principales procesos que se llevan a cabo en ella día a día. \\ 
Hasta el momento se han definido las siguientes funcionalidades en el sistema: | 
  |  |
| ID | Nombre | Detalle |  | Actor(es) |
| 1 | Inicio | Pagina de inicio del portal con informacion | relevante del  proyecto que se está realizando. | Cliente  Administrativo Profesional  |
| 2 | Contacto | Formulario de contacto para realizar consultas.|| Cliente |
| 3 | Crear Capacitacion | Formulario para crear una capacitacion | en el sistema | Cliente |
| 4 | Listar Capacitaciones | Listado de capacitaciones| registradas. | Cliente |
| 5 | Listado de Usuarios | Listado con los usuarios existentes | en plataforma | Administrativo |
| 6 | Crear Usuario | Formulario que permitira crear | un usuario en el sistema | Administrativo |
| 7 | Editar Cliente | Formulario que permite modificar los datos| de un usuario de tipo Cliente | Administrativo |
| 8 | Editar Administrativo | Formulario que permite modificar los datos | de un usuario de tipo Administrativo | Administrativo |
| 9 | Editar Profesional | Formulario que permite modificar los datos | de un usuario de tipo Profesional | Administrativo |


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


![Static Badge](https://img.shields.io/badge/Ejericio%20Grupal%203.0%20-%20green?labelColor=abcdef&cacheSeconds=3200)![Static Badge](https://img.shields.io/badge/Modulo%206%20-%20brown?labelColor=abcdef&cacheSeconds=3200)

<span style="color:red">**Ejercicio Grupal 4 Modulo 5**</span>

## **Integrantes :**

<table>
  <tr>
    <td><img src="https://img.shields.io/badge/Angelica%20-%20Romero%20-%20violet?cacheSeconds=3200" alt="Texto alternativo 1"></td>
    <td><img src="https://img.shields.io/badge/Bastian%20-%20Mariangel%20-%20red?cacheSeconds=3200" alt="Texto alternativo 2"></td>
    <td><img src="https://img.shields.io/badge/Ivan%20-%20Mieres%20-%20green?cacheSeconds=3200" alt="Texto alternativo 2"></td>
    <td><img src="https://img.shields.io/badge/Patricio%20-%20Bonnin%20-%20brown?cacheSeconds=3200" alt="Texto alternativo 2"></td>
    <td><img src="https://img.shields.io/badge/Roberto%20-%20Rivas%20-%20blue?cacheSeconds=3200" alt="Texto alternativo 2"></td>

  </tr>
</table>

![image](https://github.com/RobertoRivasL/Ejercicio_Grupal_3.0_Modulo_6/assets/131497718/fe1d8081-00ac-49b8-99c3-08004a8679c5)
![image](https://github.com/RobertoRivasL/Ejercicio_Grupal_3.0_Modulo_6/assets/131497718/8da02ac5-7079-49fe-8cf7-049a9812d460)
![image](https://github.com/RobertoRivasL/Ejercicio_Grupal_3.0_Modulo_6/assets/131497718/1a4daa25-32c5-4bca-9701-0922ec8317b3)
![image](https://github.com/RobertoRivasL/Ejercicio_Grupal_3.0_Modulo_6/assets/131497718/9d219dba-5975-425d-9373-4db604391928)
![image](https://github.com/RobertoRivasL/Ejercicio_Grupal_3.0_Modulo_6/assets/131497718/5d066a33-ccfc-48dc-85ed-efc6ee68ab05)
![image](https://github.com/RobertoRivasL/Ejercicio_Grupal_3.0_Modulo_6/assets/131497718/7403d422-90f3-4751-9056-b444d4a03034)







