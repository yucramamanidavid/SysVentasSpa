
# SysVentasSpa
<hl>SysVentasSpa</hl>
```console

```

# Comandos para subir a Github desde Repositorio local de PC o Plataformas Online

```console
    1  git status
    2  git add -A .
    3  git status
    4  git commit -a -m "Ejercicios condicionales"
    5  git status
    6  git pull
    7  git push
    8  history
```

# Comandos Para actualizar cambios nuevos de Repositorio Remoto hacia Repositorio Local

```console
    1  git pull
```

# Comandos para compilar varias clases

```console
    javac -d ./ ./*.java
    javac -d . *.java
    
    java subprogramas.ClaseGeneral
```

# Proyectos de Tipo Maven
```console
    mvn archetype:generate -DarchetypeArtifactId=maven-archetype-quickstart
```
# Pom.xml
```xml
	<properties>
        <maven.compiler.source>11</maven.compiler.source>
        <maven.compiler.target>11</maven.compiler.target>
	</properties>
    
<build>
  <plugins>
    <plugin>
    <!-- Build an executable JAR -->
    <groupId>org.apache.maven.plugins</groupId>
    <artifactId>maven-jar-plugin</artifactId>
    <version>2.4</version>
    <configuration>
    <archive>
    <manifest>
    <mainClass>pe.edu.upeu.app.App</mainClass>
    </manifest>
    </archive>
    </configuration>
    </plugin>
  </plugins>
</build>    
    
```
