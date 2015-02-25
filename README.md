# campones-primefaces-theme
Tema Camponês para o primefaces, contendo também os ícones do bootstrap

<h3>Utilização</h3>

1) Instalar o campones-theme-{version}.jar no repositório local do maven:

    mvn install:install-file -Dfile=C:\Users\samsung\workspace\Styles Projects\campones-theme\pf_theme\campones-theme-{version}.jar -DgroupId=campones -DartifactId=campones-theme -Dversion=1.0 -Dpackaging=jar


2) Incluir a dependência no pom.xml (maven):

    <dependency>                                        
     <groupId>campones</groupId>                                         
     <artifactId>campones-theme</artifactId>                                         
     <version>1.0-SNAPSHOT</version>                                         
    </dependency> 

3) Incluir o tema no web.xml:

    <context-param>
        <param-name>primefaces.THEME</param-name>
        <param-value>campones</param-value>
    </context-param>
