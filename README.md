# campones-primefaces-theme
Tema Camponês para o primefaces
Desenvolvido sobre o Aristo theme do primefaces e contendo também os ícones do bootstrap.

Para informações de uso dos ícones do bootstrap (glyphicons), acessar: ver: https://github.com/williamazevedodepaula/primefaces-bootstrap-icons


<h3>Compilação</h3>

Para gerar o .jar, executar o comando a seguir, um diretório acima da pasta campones-theme/pf_theme:

    $ jar -cvf campones-theme-{version}.jar .

<h3>Utilização</h3>

1) Instalar o campones-theme-{version}.jar no repositório local do maven:

    mvn install:install-file -Dfile=C:\Users\samsung\workspace\Styles Projects\campones-theme\pf_theme\campones-theme-{version}.jar -DgroupId=campones -DartifactId=campones-theme -Dversion=1.0 -Dpackaging=jar


2) Incluir a dependência no pom.xml (maven):

    <dependency>                                        
     <groupId>campones</groupId>                                         
     <artifactId>campones-theme</artifactId>                                         
     <version>{version}</version>                                         
    </dependency> 

3) Incluir o tema no web.xml:

    <context-param>
        <param-name>primefaces.THEME</param-name>
        <param-value>campones</param-value>
    </context-param>
    

    
