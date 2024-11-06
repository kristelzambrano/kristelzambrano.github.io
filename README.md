<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="author" content="Milka Kristel Zambrano Bombon" />
    <meta name="description" content="Portafolio Personal - Tarea#2" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio Personal</title>
    <link rel="icon" href="icon/iconoinicio.png" type="image/png">
</head>

<body>
    <header>
        <h1> ¡Bienvenidos! a Mi Portafolio Personal </h1>
        <hr />

        <nav>
            <ul>
                <li><a href="#inicio"> Inicio </a></li>
                <li><a href="#Sobre_mi"> Sobre mi </a></li>
                <li><a href="#Habilidades"> Habilidades </a></li>
                <li><a href="#Galeria_de_proyectos"> Galeria de proyectos </a></li>
                <li><a href="#Pagina_de_Contacto"> Contacto </a></li>
                <li><a href="#Consulta"> Consulta </a></li>
                </li>
            </ul>
            <hr>
        </nav>
    </header>
    <main id="inicio">
        <section>
            <h3>Inicio</h3>
            <p> Hola mi nombre es Milka Zambrano, soy estudiante de la carrera Sistemas de información de la Universidad
                Tecnica de Babahoyo.</p>
            <p> Actualmente curso el tercer semestre. A continuacióm encontrarás información sobre mí, mis habilidades y
                algunos de mis proyectos.</p>
        </section>
        <hr />
        <section id="Sobre_mi">
            <h3>Sobre mí</h3>
            <dl>
                <dt><b>Nombres completos:</b>
                <dd>Milka Kristel Zambrano Bombón </dd>
                </dt>
                <dt><b>Edad:</b>
                <dd>19 años </dd>
                </dt>
                <dt><b>Fecha de nacimiento:</b>
                <dd>06 de Octubre del 2005 </dd>
                </dt>
                <dt><b>Nacionalidad:</b>
                <dd> Ecuatoriana</dd>
                </dt>
                <dt><b>Lugar de nacimiento:</b>
                <dd> Olmedo, Manabí</dd>
                </dt>
                <dt><b>Intereses y pasatiempos:</b>
                <dd>Me gusta mucho nadar, cuando tengo tiempo libre lo hago. </dd>
                </dt>
                <dt><b>Objetivo Profesional:</b>
                <dd>Culminar con exito mi carrera, adquiriendo todos los aprendizajes necesarios para desenvolverme bien
                    luego en el area de trabajo. </dd>
                </dt>
            </dl>
        </section>
        <hr />
        <section id="Habilidades">
            <h3>Habilidades</h3>
            <ul>
                <li>Empatía y sensibilidad</li>
                <li>Adaptabilidad.</li>
                <li>Trabajo en equipo
                </li>
                <li>Resolución de Problemas
                </li>
            </ul>
        </section>
        <hr />
        <section id="Galeria_de_proyectos">
            <h3>Galería de Proyectos</h3>
            <article>
                <h4>Proyecto de Innovación y Desarrollo</h4>
                <p>Crear una aplicación movil y web que satisfaga necesidades del publico general.</p>
                <img src="img/yummy.jpeg" alt="Logo de yummi">
            </article>
            <article>
                <h4>Proyecto de Investigación</h4>
                <p>Determinar por qué los niños nacen con el espectro Autista, es decir cual es la tendencia de este
                    trastorno.</p>
                <img src="img/autismo.jpeg" alt="Referencia a autismo">
            </article>
            <article>
                <h4>Proyecto Educativo</h4>
                <p>Desarrollar un programa de capacitación para la comunidad acerca de el uso de las plataformas
                    ofimáticas.</p>
                <img src="img/capacitacionani.png" alt="Capacitacion para la comunidad">
            </article>
        </section>
        <hr />
    <aside id="Pagina_de_Contacto">
        <h2>Información de contacto adicional</h2>
        <table border="1">
            <tr>
                <th> Redes Sociales
                </th>
                <th>
                    Enlace
                </th>
            </tr>
            <tr>
            <td>Facebook</td>
            <td> <a href="https://www.facebook.com/xkrstlx06/" target="_blank">Facebook</a> </td>
            </tr>
            <tr>
                <td>Instagram</td>
                <td> <a href="https://www.instagram.com/bombonkristel/" target="_blank">Instagram </a> </td>
                </tr>
                <tr>
                    <td>Pagina de la universidad</td>
                    <td> <a href="https://utb.edu.ec/" target="_blank">Pagina de la UTB </a> </td>
                    </tr>
        </table>
    </aside>
</main>
</hr>    
<footer id="Consulta">
        <h2>Dudas o Consulta</h2>
        <p> Para cualquier consulta, le enviamos un correo, llene lo siguiente:</p>
<form>
   <caption>Consulta</caption> 
   <fieldset>
<legend>Consulta</legend>
<label for="nombrestxt"> Nombres y apellidos: <input type="text" id="nombrestxt"></label><br/>
<label for="email"> Correo electronico: <input type="email" id="email"></label><br/>
<label for="doc"> Escriba aquí su duda: <input type="text" id="doc"></label><br/>
<button type="submit">Enviar</button>
   </fieldset>
</form>
    </footer>
</body>
</html>
