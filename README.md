# Hello devs 👋



## Mais sobre mim

<img align="right" width="300" src="https://i2.wp.com/allhtaccess.info/wp-content/uploads/2018/03/programming.gif?fit=1281%2C716&ssl=1" />

```java
import java.time.Duration;
import java.time.LocalDate;
import java.time.format.DateTimeFormatter;
import java.util.List;

public class Kauan {
    private static final String NAME = "Kauan Gabriel Paiva Meira";
    private static final String EMAIL = "kauan.paiva.meira@gmail.com";
    private static final String JOB_TITLE = "Desenvolvedor Java Backend";
    private static final String COMPANY = "Attus Procuradoria Digital - Grupo Eloware";
    private static final LocalDate BIRTHDAY = LocalDate.of(2002, 4, 19);
    private static final LocalDate START_DATE = LocalDate.of(2025, 2, 10);

    private static final List<String> ACKNOWLEDGEMENTS = List.of(
            "Desenvolvimento de microsserviços com Spring Boot",
            "Mensageria com Kafka e RabbitMQ",
            "Docker e containerização",
            "Desenvolvimento com foco em TDD (Test Driven Development)",
            "Práticas de BDD (Behavior Driven Development)",
            "Análise de qualidade de código com SonarQube",
            "Desenvolvimento backend em Java com Spring Boot"
    );

    private static final String PRIMARY_SKILLSET = "Principais Habilidades";
    private static final List<String> LANGUAGES = List.of("Java", "C#", "Flutter", "React", "SQL");

    public static void main(String[] args) {
        System.out.println("Nome: " + NAME);
        System.out.println("Idade: " + getAge() + " anos");
        System.out.println("E-mail: " + EMAIL);
        System.out.println("Cargo: " + JOB_TITLE);
        System.out.println("Empresa: " + COMPANY);
        System.out.println("Tempo de empresa: " + getExperienceTime() + " dias");

        System.out.println("\nConhecimentos:");
        ACKNOWLEDGEMENTS.forEach(item -> System.out.println("- " + item));

        System.out.println("\n" + PRIMARY_SKILLSET + ": " + LANGUAGES);
    }

    private static int getAge() {
        return (int) (Duration.between(BIRTHDAY.atStartOfDay(), LocalDate.now().atStartOfDay()).toDays() / 365);
    }

    private static long getExperienceTime() {
        return Duration.between(START_DATE.atStartOfDay(), LocalDate.now().atStartOfDay()).toDays();
    }
}
```

## Linguagens e ferramentas
<code><img height="30" src="https://cdn.iconscout.com/icon/free/png-512/free-java-logo-icon-download-in-svg-png-gif-file-formats--programming-language-coding-logos-icons-1720088.png"></code>
<code><img height="30" src="https://devkico.itexto.com.br/wp-content/uploads/2014/08/spring-boot-project-logo.png"></code>
<code><img height="30" src= "https://static-00.iconduck.com/assets.00/flutter-icon-1651x2048-ojswpayr.png"></code>
<code><img height="30" src="https://e7.pngegg.com/pngimages/534/663/png-clipart-net-framework-software-framework-c-microsoft-asp-net-microsoft-blue-angle-thumbnail.png"></code>
<code><img height="30" src= "https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/2300px-React-icon.svg.png"></code>
<code><img height="30" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9c/IntelliJ_IDEA_Icon.svg/800px-IntelliJ_IDEA_Icon.svg.png"></code>
<code><img height="30" src= "https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/2048px-Visual_Studio_Code_1.35_icon.svg.png"></code>


## Status

<a href="https://github.com/kauanmeira">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kauanmeira&theme=dracula&hide_langs_below=1" />
</a>

<a href="https://github.com/kauanmeira">
 <img align="center" src="https://github-readme-stats.vercel.app/api?username=kauanmeira&show_icons=true&theme=dracula&line_height=27" alt="**KAUAN MEIRA** github stats"/>
</a>

<br> 
<br> 
<br> 

  <a href="https://www.linkedin.com/in/kauan-m-46925a134/" alt="LinkedIn">
    <img src="https://img.shields.io/badge/-Linkedin-0e76a8?style=flat-square&logo=Linkedin&logoColor=white" />
  </a>

  <a href="https://api.whatsapp.com/send?phone=5517988214036" alt="WhatsApp">
    <img src="https://img.shields.io/badge/-WhatsApp-25d366?style=flat-square&labelColor=25d366&logo=whatsapp&logoColor=white" />
  </a>
</p>
