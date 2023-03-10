## Despliegue de apps Spring Boot en Railway

1. Configurar proyecto Maven
   1. Edit configurations/Add new configuration/Maven
   2. Agregar las siguientes etiquetas en el pom.xml:

<pre><code>
&lt;properties&gt;
  &lt;java.version&gt;11&lt;/java.version&gt;
  &lt;maven.compiler.target&gt;11&lt;/maven.compiler.target&gt;
  &lt;maven.compiler.source&gt;11&lt;/maven.compiler.source&gt;
&lt;/properties&gt;
</code></pre>

Actualmente (9/3/2023) Railway acepta Java 11

2. Crear cuenta en github y ejecutar los siguientes comandos
   1. `git config --global user.name "NOMBRE_USUARIO"`
   2. `git config --global user.email EMAIL`

3. Subir el proyecto a Github desde Intellij IDEA desde la opción: VCS > Share project on Github

4. Deploy en Railway:
   1. Crear cuenta
   2. Agregar github
   3. Seleccionar repositorio
   4. Clic en deploy
   4. Clic en domains para agregar un dominio público
