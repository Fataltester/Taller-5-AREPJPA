# Taller JPA y CLI
Seguir los tutoriales con CLI y JPA postulados para esta semana
[JPA](https://spring.io/guides/gs/accessing-data-jpa)

## PreRequisitos
Para el proyecto debemos configurar un entorno maven para armar el proyecto, para esto hay diferentes opciones como visual studio, intellij, etc. Si se quiere trabajar sobre estos se debe configurar e instalar maven para su funcionamiento, pero, para este laboratorio y facilitarme este proceso utilicé Netbeans el cual me ahorra ese proceso, puede instalar el ambiente de desarrollo en su página oficial [aquí](https://netbeans.apache.org/front/main/index.html). También debemos tener java 17 instalado y git para poder clonar el repositorio actual.
Además de tener instalado maven, debe tener docker instalado en su computador para lograr ejecutar el laboratorio y los contenedores
## CLI
No pude crear las instancias ya que no me generaba las llaves por falta de permiso en aws, no se por qué pasó eso, ya que había podido hacerlo anteriormente
## Accessing Data with JPA

instalación con
```bash
git clone https://github.com/Fataltester/Taller-5-AREPJPA.git

```

```bash
mvn clean install
mvn clean package
mvn spring-boot:run
```

Resultado

<img width="1098" height="494" alt="image" src="https://github.com/user-attachments/assets/f8269c15-0826-4d93-b60e-55229585055c" />

El proyecto fue realizado con (inicializr)[https://start.spring.io] para montar el proyecto maven con unas dependencias mínimas, y ya se crearon las clases dadas en el tutorial de jpa.

### Contruido con

[Maven](https://maven.apache.org) Maven

[Netbeans](https://netbeans.apache.org/front/main/index.html) Netbeans 

[Git](https://git-scm.com) Git

[docker](https://www.docker.com) Docker

[AWS](https://aws.amazon.com/es/free/?trk=d467a1e4-ef7e-4b01-9632-5fc46ff30fb0&sc_channel=ps&ef_id=CjwKCAjwlaTGBhANEiwAoRgXBSZykrEBt9z7thDt-V49nT_IO1KIvJXazolkoGAiyE1Bzko3wk7V8RoCdX4QAvD_BwE:G:s&s_kwcid=AL!4422!3!647999789205!e!!g!!aws!19685287144!146461596896&gad_campaignid=19685287144&gclid=CjwKCAjwlaTGBhANEiwAoRgXBSZykrEBt9z7thDt-V49nT_IO1KIvJXazolkoGAiyE1Bzko3wk7V8RoCdX4QAvD_BwE) AWS

### Autor
Juan David Martínez Mendez - [Fataltester](https://github.com/Fataltester)


