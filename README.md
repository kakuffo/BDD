Jackson Maven Dependencies

If your project uses Maven to build (and resolve + download dependencies), you need to add Jackson as a dependency to your project's POM file. Here is how Jackson as Maven dependencies look:

<dependency>
  <groupId>com.fasterxml.jackson.core</groupId>
  <artifactId>jackson-core</artifactId>
  <version>2.9.2</version>
</dependency>

<dependency>
  <groupId>com.fasterxml.jackson.core</groupId>
  <artifactId>jackson-annotations</artifactId>
  <version>2.9.2</version>
</dependency>

<dependency>
  <groupId>com.fasterxml.jackson.core</groupId>
  <artifactId>jackson-databind</artifactId>
  <version>2.9.2</version>
</dependency>
