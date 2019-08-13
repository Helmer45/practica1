# <center> PRÁCTICA Nº # 1 </center>
# <center>SISTEMAS EMPRESARIALES </center>

| Carrera: | Ingenieria de Sistemas |
    | :--- | --- |
| Materia: | Emergentes II     |   ||
| Apellidos: | Mamani Felipe |
| Nombres :  |Helmer Placido| 
| C.I: | 12451754 L.P. | 
| Lugar y Fecha: | El Alto, 13 de Agosto de 2019| 


#### 1) Explique que son los sistemas empresariales
 El sistema de información empresarial constituye el conjunto de recursos de la empresa que sirven como soporte para el proceso básico de captación, transformación y comunicación de la información.

 Un sistema de información debe ser eficaz y eficiente. Es eficaz si facilita la información necesaria, y es eficiente si lo realiza con los menores recursos posibles.
#### 2) Describa cuales son las características más importantes de una aplicación empresarial
** 1.- DISPONIBILIDAD **

La capacidad de un sistema de ser accesible, teniendo un tiempo de inactividad limitado.

** ejemplo:** 24/7/365     
24 horas ,7 dias de la semana y 365 dias del año 

** 2.- CAPACIDAD **

La capacidad de un sistema de ejecutar varias tareas dentro de un periodo de tiempo.

** ejemplo:**
El sistema puede mantener 3 millones de ususario concurrentes.

**  3.- EXTENSIBILIDAD ** 

La capacidad de extender la funcionalidad del sistema.

** ejemplo: ** El sistema puede facilmente agregar una libreria que genere PDFs.

**  4.-FLEXIBILIDAD ** 

La capacidad de realizar cambios d configuracion, manteniendo la integridad del sistema.

** ejemplo: ** el sistema puede cambiarse de servidor de base de datos, con cambios de configuracion minimos.

**  5.- MANEJABILIDAD** 

La capacidad de gestionar los recursos del sistema.

** ejemplo: ** El sistema puede cambiar los permisos de acceso de los usuarios mientras esta en operacion.

**  6.- RENDIMIENTO** 

La capacidad de realizar  funciones dentro de objetivos especificos.

** ejemplo: ** El sistema debe recuperar las consultas de la base de datos en 3 seg.

**  7.- CONFIABILIDAD ** 

La capacidad de garantizar la integridad y consistencia del sistema y sus transacciones.

** ejemplo: ** El sistema envia e-mails que no son corruptos.


**  8.- REUSABILIDAD ** 

la capacidad de reutilizar un componte.

** ejemplo: ** El sistema usa el mismo componente de seguridad para varias aplicaciones.

**  9.- ESCALABILIDAD** 

la capacidad de soportar la funciobnalidad cuando la carga aumenta.

** ejemplo: ** El servicio de consultas a la base de datos respondera en el tiempo establecido, sin importar el numero de usuarios.

**  10.- SEGURIDAD** 

La capacidad de garantizar la seguridad de la informacion.

** ejemplo: ** El sistema encripta y desencripta los datos que viajan en la red.

**  11.- VALIDEZ** 

la capacidad de validar los resultados del sistema o una entrada de ususario.

** ejemplo: ** El sistema no permite los ampos de entrada que no estan en el formato especifico.
#### 3) ![Investigue y proponga cinco (5) instituciones que requerirían aplicaciones de misión crítica. Justifique su respuesta](/20190813151722642/Investigue y proponga cinco (5) instituciones que requerirían aplicaciones de misión crítica. Justifique su respuesta.png)

#### 4) Explique cuáles son las diferencias entre la escalabilidad horizontal y escalabilidad vertical
** Escalabilidad Vertical**

El escalar hacia arriba un sistema viene a significar una migración de todo el sistema a un nuevo hardware que es mas potente y eficaz que el actual. Una vez se ha configurado el sistema futuro, se realizan una serie de validaciones y copias de seguridad y se pone en funcionamiento. Las aplicaciones que estén funcionando bajo la arquitectura hardware antigua no sufren con la migración, el impacto en el código es mínimo.

Este modelo de escalabilidad tiene un aspecto negativo. Al aumentar la potencia en base a ampliaciones de hardware, llegara un momento que existirá algún tipo de limitación hardware. Además a medida que se invierte en hardware de muy altas prestaciones, los costos se disparan tanto de forma temporal (ya que si se ha llegado al umbral máximo , hay componentes hardware que tardan mucho tiempo en ampliar su potencia de forma significativa) como económicos. Sin embargo a nivel estructural no supone ninguna modificación reseñable, lo que la convierte en una buena opción si los costos anteriores son asumibles.

** Escalabilidad Horizontal ** 

La escalabilidad horizontal consiste en potenciar el rendimiento del sistema desde un aspecto de mejora global, a diferencia de aumentar la potencia de una única parte del mismo. Este tipo de escalabilidad se basa en la modularidad de su funcionalidad. Por ello suele estar conformado por una agrupación de equipos que dan soporte a la funcionalidad completa. Normalmente, en una escalabilidad horizontal se añaden equipos para dar mas potencia a la red de trabajo.

Con un entorno de este tipo, es lógico pensar que la potencia de procesamiento es directamente proporcional al número de equipos de la red. El total de la potencia de procesamiento es la suma de la velocidad física de cada equipo transferida por la partición de aplicaciones y datos extendida a través de los nodos.

Si se aplica un modelo de escalabilidad basado en la horizontalidad, no existen limitaciones de crecimiento a priori. Como principal e importante defecto, este modelo de escalabilidad supone una gran modificación en el diseño, lo que conlleva a una gran trabajo de diseño y reimplantación. Si la lógica se ha concebido para un único servidor, es probable que se tenga que estructurar el modelo arquitectónico para soportar este modelo de escalabilidad.

#### 5) Que es un servidor Web y que es un servidor de aplicaciones
** Servidor Web:** 

Un servidor web o servidor HTTP es un programa informático que procesa una aplicación del lado del servidor realizando conexiones bidireccionales y/o unidireccionales y síncronas o asíncronas con el cliente generando o cediendo una respuesta en cualquier lenguaje o Aplicación del lado del cliente.

** Servidor de aplicaciones:**

En informática, se denomina servidor de aplicaciones a un servidor en una red de computadores que ejecuta ciertas aplicaciones.

#### 6) Con un gráfico explique cómo funciona el protocolo HTTP


#### 7) Explique los elementos importantes de REQUEST en HTTP

La request line está formada por 3 partes: el método, la ruta y el protocolo.

** METODO **

>El método indica el tipo de petición que se realiza, y que típicamente puede ser GET, POST ó HEAD. La carga de una web normalmente se hace por GET. Sin embargo, cuando por ejemplo enviamos un formulario es habitual que la petición se haga por post, de modo que la línea de petición podría ser de la forma POST /resultados.php HTTP 1.1. También el envío de un formulario puede hacerse por GET, en este caso bajo un formato similar a GET /form.php?nombre=Juan&apellidos=Perez&action=Submit HTTP/1.1

** RUTA **

>La ruta, es normalmente la ruta relativa o parte de la dirección web que viene detrás del dominio. 

** PROTOCOLO **

> El protocolo consta de HTTP y el número de versión de protocolo que se emplea, típicamente 1.1.

#### 8) Explique los elementos importantes de RESPONSE en HTTP

El objeto Response tiene 8 propiedades, 1 colección y 8 métodos: 

** PROPIEDADES **

> Response.Buffer = False | True
Response.CacheControl = "Public" | "Private"
Response.Charset("String")
Response.ContentType("String")
Response.Expires
Response.ExpiresAbsolute
Response.IsClientConnected = True | False
Response.Status = "Status"

** COLECCIONES **

>Response.Cookies(Nombre)[(Clave)|.Atributo]=Valor

** METODOS **

> Response.AddHeader "Nombre", "Valor"
Response.AppendToLog("String")
Response.BinaryWrite(Data)
Response.Clear
Response.End
Response.Flush
Response.Redirect(URL)

#### 9) Describa con un gráfico la arquitectura Java EE
![Texto alternativo](C:\Users\DELL\Downloads\java.jpeg)


#### 10) Explique cuáles son los contenedores, componentes y servicios de Java EE
** contenedores **
> ** Java EE Server:** La porción de tiempo de ejecución de un producto Java EE. provee los contenedores web y de ejb.

> ** Contenedor EJB:**  Maneja la ejecución de los enterprise beans.

>** Contenedor Web: ** Maneja la ejecución de las paginas web, servlets y algunos componentes ejb para las aplicaciones Java EE.

>** Contenedor de aplicación cliente:**  Maneja la ejecución de la aplicación cliente no necesita un servidor de aplicaciones.

>** Contenedor Applet: ** Maneja la ejecución de applets, no necesita servidor de aplicaciones, consiste en un browser y el plugin web de java.

** componentes **

** servicios de Java EE **

#### 11) Investigue los métodos más utilizados de las clases HttpServlet, HttpServletRequest y HttpServletResponse, y para cada uno de los métodos muestre un ejemplo.
### Httpservet
Los servelts pueden ser incluidos en servidores que soporten la API de Servlet (ver servidores). La API no realiza suposiciones sobre el entorno que se utiliza, como tipo de servidor o plataforma, ni del protocolo a utilizar, aunque existe una API especial para HTTP.

Los Servlets son un reemplazo efectivo para los CGI en los servidores que los soporten ya que proporcionan una forma de generar documentos dinámicos utilizando las ventajas de la programación en Java como conexión a alguna base de datos, manejo de peticiones concurrentes, programación distribuida, etc. Por ejemplo, un servlet podría ser responsable de procesar los datos desde un formulario en HTML como registrar la transacción, actualizar una base de datos, contactar algún sistema remoto y retornar un documento dinámico o redirigir a otro servlet u alguna otra cosa.
## ejemplo
public class SimpleServlet extends HttpServlet {

    public void doGet (HttpServletRequest request, HttpServletResponse response)
              throws ServletException, IOException {
    PrintWriter out;
    String title = "Simple Servlet Output";

    // primero selecciona el tipo de contenidos y otros campos de cabecera de la respuesta
    response.setContentType("text/html");
    // Luego escribe los datos de la respuesta
    out = response.getWriter();
    out.println("<HTML><HEAD><TITLE>");
    out.println(title);
    out.println("</TITLE></HEAD><BODY>");
    out.println("<H1>" + title + "</H1>");
    out.println("<P>This is output from SimpleServlet.");
    out.println("</BODY></HTML>");
    out.close();
    }
}
### HttpServletRequest 
El seguimiento de sesión es un mecanismo que los servlets utilizan para mantener el estado sobre la serie de peticiones desde un mismo usuario (esto es, peticiones originadas desde el mismo navegador) durante un periodo de tiempo.

Las sesiones son compartidas por los servlets a los que accede el cliente. Esto es conveniente para aplicaciones compuestas por varios servlets. Por ejemplo, Duke's Bookstore utiliza seguimiento de sesión para seguir la pista de los libros pedidos por el usuario. Todos los servlets del ejemplo tienen acceso a la sesión del usuario.

Para utilizar el seguimiento de sesión debemos.

Obtener una sesión (un objeto HttpSession) para un usuario.
Almacenar u obtener datos desde el objeto HttpSession.
Invalidar la sesión (opcional).
## Ejemplo
import java.io.IOException;
import javax.servlet.ServletException;
import javax.servlet.annotation.WebServlet;
import javax.servlet.http.HttpServlet;
import javax.servlet.http.HttpServletRequest;
import javax.servlet.http.HttpServletResponse;

    public HolaMundo() {
        super();
        
    }
	protected void doGet(HttpServletRequest request, HttpServletResponse response) throws ServletException, IOException {
	}

	protected void doPost(HttpServletRequest request, HttpServletResponse response) throws ServletException, IOException {
		
	}

}
### HttpServletResponse
Muchas veces cuando uno comienza a programar en el entorno web de Java suelen quedarle muy claros los conceptos de HttpServletRequest (petición) y HttpServletResponse (respuesta) junto con el propio concepto de Servlet.

Sin embargo suelen aparece muchas mas dudas a la hora de gestionar otro de los conceptos fundamentales 
## Ejemplo
protected void doGet( HttpServletRequest req, HttpServletResponse resp )
		throws ServletException, IOException {		
	Token token=new Token();
	
	
	boolean secured=RalasafeController.isSecured();
	
	if( secured ) {
		User currentUser=WebRalasafe.getCurrentUser( req );
		token.setCanAssignRoleToUser( Ralasafe.hasPrivilege( Privilege.ASSIGN_ROLE_TO_USER_ID, currentUser ) );
		token.setCanAdminRole( Ralasafe.hasPrivilege( Privilege.ROLE_ADMIN_ID, currentUser ) );
		token.setCanAdminPolicy( Ralasafe.hasPrivilege( Privilege.POLICY_ADMIN_ID, currentUser ) );
	}
	req.setAttribute( "token", token );
	WebUtil.forward( req, resp, "/ralasafe/main.jsp" );
}