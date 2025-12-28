```java
// BussyBakks.java
import org.apache.logging.log4j.LogManager; // i will never use it again 
import org.apache.logging.log4j.Logger; // i will never use it again

import org.slf4j.Logger;
import org.slf4j.LoggerFactory;

// about me
public class BussyBakks {
  public static void main(String[] args) {
    private static final Logger logger = LoggerFactory.getLogger("BussyBakks");

    private static final String RealName           = "Nguyen Van Ngu";
    private static final String YearOfBirth        = "2010";
    private static final String GithubUsername     = "BussyBakks";
    private static final String LangIWorked        = "Batch, Python, Java, C# (.NET framework)";
    private static final String Gender             = "nope .-.";
    private static final String Pronouns           = "\"they/them\"";
    private static final String[] Website          = {"https://thenoppy12.is-a.dev", "https://thenoppy12.hopto.org"}
    private static final String Country            = "Vietnam";
    private static final String MinecraftUsername  = "thenoppy12";
    private static final String Discord            = "fkrystal.noppy";
    private static final String ContributorAt      = "rejetto/hfs";

    logger.info("welcum to my profile:D")
  }
}
```
```gradle
// build.gradle
plugins {
    id 'java'
}

repositories {
    mavenCentral()
}

dependencies {
    implementation 'org.slf4j:slf4j-api:{the_latest}'
    implementation 'ch.qos.logback:logback-classic:{the_latest}'
}
```
