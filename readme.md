# Jenkins Pipeline for Spring-PetClinic Project (Deploy to DockerHub)

![
    
](image.png)


## Résultat global après lancement 

## log de tests

+ mvn clean install
[INFO] Scanning for projects...
[INFO]                                                                         
[INFO] ------------------------------------------------------------------------
[INFO] Building petclinic 2.2.0.BUILD-SNAPSHOT
[INFO] ------------------------------------------------------------------------
Downloading: https://repo.spring.io/snapshot/org/apache/maven/plugins/maven-clean-plugin/3.1.0/maven-clean-plugin-3.1.0.pom

Downloading: https://repo.spring.io/milestone/org/apache/maven/plugins/maven-clean-plugin/3.1.0/maven-clean-plugin-3.1.0.pom

Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-clean-plugin/3.1.0/maven-clean-plugin-3.1.0.pom
2/6 KB   
3/6 KB   
5/6 KB   
6/6 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-clean-plugin/3.1.0/maven-clean-plugin-3.1.0.pom (6 KB at 49.0 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/plugins/maven-clean-plugin/3.1.0/maven-clean-plugin-3.1.0.jar
         
Downloading: https://repo.spring.io/milestone/org/apache/maven/plugins/maven-clean-plugin/3.1.0/maven-clean-plugin-3.1.0.jar
         
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-clean-plugin/3.1.0/maven-clean-plugin-3.1.0.jar
2/30 KB   
3/30 KB   
5/30 KB   
6/30 KB   
7/30 KB   
9/30 KB   
10/30 KB   
11/30 KB   
13/30 KB   
14/30 KB   
15/30 KB   
16/30 KB   
17/30 KB   
19/30 KB   
20/30 KB   
21/30 KB   
23/30 KB   
24/30 KB   
25/30 KB   
27/30 KB   
28/30 KB   
29/30 KB   
30/30 KB   
           
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-clean-plugin/3.1.0/maven-clean-plugin-3.1.0.jar (30 KB at 725.9 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/plugins/maven-surefire-plugin/2.22.2/maven-surefire-plugin-2.22.2.pom
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/plugins/maven-surefire-plugin/2.22.2/maven-surefire-plugin-2.22.2.pom
           
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-surefire-plugin/2.22.2/maven-surefire-plugin-2.22.2.pom
2/5 KB     
3/5 KB   
5/5 KB   
5/5 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-surefire-plugin/2.22.2/maven-surefire-plugin-2.22.2.pom (5 KB at 180.6 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/surefire/surefire/2.22.2/surefire-2.22.2.pom
         
Downloading: https://repo.spring.io/milestone/org/apache/maven/surefire/surefire/2.22.2/surefire-2.22.2.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire/2.22.2/surefire-2.22.2.pom
4/26 KB   
8/26 KB   
12/26 KB   
16/26 KB   
20/26 KB   
24/26 KB   
26/26 KB   
           
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire/2.22.2/surefire-2.22.2.pom (26 KB at 839.9 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/plugins/maven-surefire-plugin/2.22.2/maven-surefire-plugin-2.22.2.jar
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/plugins/maven-surefire-plugin/2.22.2/maven-surefire-plugin-2.22.2.jar
           
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-surefire-plugin/2.22.2/maven-surefire-plugin-2.22.2.jar
4/40 KB    
8/40 KB   
12/40 KB   
16/40 KB   
20/40 KB   
24/40 KB   
28/40 KB   
32/40 KB   
36/40 KB   
40/40 KB   
40/40 KB   
           
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-surefire-plugin/2.22.2/maven-surefire-plugin-2.22.2.jar (40 KB at 1069.3 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/plugins/maven-jar-plugin/3.1.2/maven-jar-plugin-3.1.2.pom
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/plugins/maven-jar-plugin/3.1.2/maven-jar-plugin-3.1.2.pom
           
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-jar-plugin/3.1.2/maven-jar-plugin-3.1.2.pom
4/8 KB     
8/8 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-jar-plugin/3.1.2/maven-jar-plugin-3.1.2.pom (8 KB at 254.8 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/plugins/maven-jar-plugin/3.1.2/maven-jar-plugin-3.1.2.jar
         
Downloading: https://repo.spring.io/milestone/org/apache/maven/plugins/maven-jar-plugin/3.1.2/maven-jar-plugin-3.1.2.jar
         
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-jar-plugin/3.1.2/maven-jar-plugin-3.1.2.jar
4/28 KB   
8/28 KB   
12/28 KB   
16/28 KB   
20/28 KB   
24/28 KB   
28/28 KB   
           
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-jar-plugin/3.1.2/maven-jar-plugin-3.1.2.jar (28 KB at 737.6 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/plugins/maven-install-plugin/2.5.2/maven-install-plugin-2.5.2.pom
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/plugins/maven-install-plugin/2.5.2/maven-install-plugin-2.5.2.pom
           
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-install-plugin/2.5.2/maven-install-plugin-2.5.2.pom
4/7 KB     
7/7 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-install-plugin/2.5.2/maven-install-plugin-2.5.2.pom (7 KB at 272.5 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/plugins/maven-plugins/25/maven-plugins-25.pom
         
Downloading: https://repo.spring.io/milestone/org/apache/maven/plugins/maven-plugins/25/maven-plugins-25.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-plugins/25/maven-plugins-25.pom
4/10 KB   
8/10 KB   
10/10 KB   
           
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-plugins/25/maven-plugins-25.pom (10 KB at 373.1 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/maven-parent/24/maven-parent-24.pom
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/maven-parent/24/maven-parent-24.pom
           
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/24/maven-parent-24.pom
4/37 KB    
8/37 KB   
12/37 KB   
16/37 KB   
20/37 KB   
24/37 KB   
28/37 KB   
32/37 KB   
36/37 KB   
37/37 KB   
           
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/24/maven-parent-24.pom (37 KB at 1029.5 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/apache/14/apache-14.pom
           
Downloading: https://repo.spring.io/milestone/org/apache/apache/14/apache-14.pom
           
Downloading: https://repo.maven.apache.org/maven2/org/apache/apache/14/apache-14.pom
4/15 KB    
8/15 KB   
12/15 KB   
15/15 KB   
           
Downloaded: https://repo.maven.apache.org/maven2/org/apache/apache/14/apache-14.pom (15 KB at 325.9 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/plugins/maven-install-plugin/2.5.2/maven-install-plugin-2.5.2.jar
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/plugins/maven-install-plugin/2.5.2/maven-install-plugin-2.5.2.jar
           
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-install-plugin/2.5.2/maven-install-plugin-2.5.2.jar
4/33 KB    
8/33 KB   
12/33 KB   
16/33 KB   
20/33 KB   
24/33 KB   
28/33 KB   
32/33 KB   
33/33 KB   
           
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-install-plugin/2.5.2/maven-install-plugin-2.5.2.jar (33 KB at 808.5 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/springframework/boot/spring-boot-starter-test/2.2.2.RELEASE/spring-boot-starter-test-2.2.2.RELEASE.jar
Downloading: https://repo.spring.io/snapshot/org/springframework/boot/spring-boot-test/2.2.2.RELEASE/spring-boot-test-2.2.2.RELEASE.jar
Downloading: https://repo.spring.io/snapshot/org/springframework/boot/spring-boot-test-autoconfigure/2.2.2.RELEASE/spring-boot-test-autoconfigure-2.2.2.RELEASE.jar
Downloading: https://repo.spring.io/snapshot/com/jayway/jsonpath/json-path/2.4.0/json-path-2.4.0.jar
Downloading: https://repo.spring.io/snapshot/net/minidev/json-smart/2.3/json-smart-2.3.jar
           
Downloading: https://repo.spring.io/snapshot/net/minidev/accessors-smart/1.2/accessors-smart-1.2.jar
           
Downloading: https://repo.spring.io/snapshot/org/ow2/asm/asm/5.0.4/asm-5.0.4.jar
           
Downloading: https://repo.spring.io/snapshot/org/junit/jupiter/junit-jupiter/5.5.2/junit-jupiter-5.5.2.jar
           
Downloading: https://repo.spring.io/snapshot/org/junit/jupiter/junit-jupiter-params/5.5.2/junit-jupiter-params-5.5.2.jar
           
Downloading: https://repo.spring.io/snapshot/org/assertj/assertj-core/3.13.2/assertj-core-3.13.2.jar
           
Downloading: https://repo.spring.io/snapshot/org/hamcrest/hamcrest/2.1/hamcrest-2.1.jar
           
Downloading: https://repo.spring.io/snapshot/net/bytebuddy/byte-buddy-agent/1.10.4/byte-buddy-agent-1.10.4.jar
           
Downloading: https://repo.spring.io/snapshot/org/skyscreamer/jsonassert/1.5.0/jsonassert-1.5.0.jar
           
Downloading: https://repo.spring.io/snapshot/com/vaadin/external/google/android-json/0.0.20131108.vaadin1/android-json-0.0.20131108.vaadin1.jar
           
Downloading: https://repo.spring.io/snapshot/org/springframework/spring-test/5.2.2.RELEASE/spring-test-5.2.2.RELEASE.jar
           
Downloading: https://repo.spring.io/snapshot/org/xmlunit/xmlunit-core/2.6.3/xmlunit-core-2.6.3.jar
           
Downloading: https://repo.spring.io/snapshot/org/junit/jupiter/junit-jupiter-engine/5.5.2/junit-jupiter-engine-5.5.2.jar
           
Downloading: https://repo.spring.io/snapshot/org/apiguardian/apiguardian-api/1.1.0/apiguardian-api-1.1.0.jar
           
Downloading: https://repo.spring.io/snapshot/org/junit/platform/junit-platform-engine/1.5.2/junit-platform-engine-1.5.2.jar
           
Downloading: https://repo.spring.io/snapshot/org/opentest4j/opentest4j/1.2.0/opentest4j-1.2.0.jar
           
Downloading: https://repo.spring.io/snapshot/org/junit/platform/junit-platform-commons/1.5.2/junit-platform-commons-1.5.2.jar
           
Downloading: https://repo.spring.io/snapshot/org/junit/jupiter/junit-jupiter-api/5.5.2/junit-jupiter-api-5.5.2.jar
           
Downloading: https://repo.spring.io/snapshot/org/mockito/mockito-junit-jupiter/3.1.0/mockito-junit-jupiter-3.1.0.jar
           
           
           
           
           
Downloading: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-test/2.2.2.RELEASE/spring-boot-test-2.2.2.RELEASE.jar
Downloading: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-test-autoconfigure/2.2.2.RELEASE/spring-boot-test-autoconfigure-2.2.2.RELEASE.jar
Downloading: https://repo.spring.io/milestone/net/minidev/json-smart/2.3/json-smart-2.3.jar
Downloading: https://repo.spring.io/milestone/com/jayway/jsonpath/json-path/2.4.0/json-path-2.4.0.jar
Downloading: https://repo.spring.io/milestone/org/springframework/boot/spring-boot-starter-test/2.2.2.RELEASE/spring-boot-starter-test-2.2.2.RELEASE.jar
           
Downloading: https://repo.spring.io/milestone/net/minidev/accessors-smart/1.2/accessors-smart-1.2.jar
           
Downloading: https://repo.spring.io/milestone/org/ow2/asm/asm/5.0.4/asm-5.0.4.jar
           
Downloading: https://repo.spring.io/milestone/org/junit/jupiter/junit-jupiter/5.5.2/junit-jupiter-5.5.2.jar
           
Downloading: https://repo.spring.io/milestone/org/junit/jupiter/junit-jupiter-params/5.5.2/junit-jupiter-params-5.5.2.jar
           
Downloading: https://repo.spring.io/milestone/org/assertj/assertj-core/3.13.2/assertj-core-3.13.2.jar
           
Downloading: https://repo.spring.io/milestone/org/hamcrest/hamcrest/2.1/hamcrest-2.1.jar
           
Downloading: https://repo.spring.io/milestone/net/bytebuddy/byte-buddy-agent/1.10.4/byte-buddy-agent-1.10.4.jar
           
Downloading: https://repo.spring.io/milestone/org/skyscreamer/jsonassert/1.5.0/jsonassert-1.5.0.jar
           
Downloading: https://repo.spring.io/milestone/com/vaadin/external/google/android-json/0.0.20131108.vaadin1/android-json-0.0.20131108.vaadin1.jar
           
Downloading: https://repo.spring.io/milestone/org/springframework/spring-test/5.2.2.RELEASE/spring-test-5.2.2.RELEASE.jar
           
Downloading: https://repo.spring.io/milestone/org/xmlunit/xmlunit-core/2.6.3/xmlunit-core-2.6.3.jar
           
Downloading: https://repo.spring.io/milestone/org/junit/jupiter/junit-jupiter-engine/5.5.2/junit-jupiter-engine-5.5.2.jar
           
Downloading: https://repo.spring.io/milestone/org/apiguardian/apiguardian-api/1.1.0/apiguardian-api-1.1.0.jar
           
Downloading: https://repo.spring.io/milestone/org/junit/platform/junit-platform-engine/1.5.2/junit-platform-engine-1.5.2.jar
           
Downloading: https://repo.spring.io/milestone/org/opentest4j/opentest4j/1.2.0/opentest4j-1.2.0.jar
           
Downloading: https://repo.spring.io/milestone/org/junit/platform/junit-platform-commons/1.5.2/junit-platform-commons-1.5.2.jar
           
Downloading: https://repo.spring.io/milestone/org/junit/jupiter/junit-jupiter-api/5.5.2/junit-jupiter-api-5.5.2.jar
           
Downloading: https://repo.spring.io/milestone/org/mockito/mockito-junit-jupiter/3.1.0/mockito-junit-jupiter-3.1.0.jar
           
           
           
           
           
Downloading: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-starter-test/2.2.2.RELEASE/spring-boot-starter-test-2.2.2.RELEASE.jar
Downloading: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-test/2.2.2.RELEASE/spring-boot-test-2.2.2.RELEASE.jar
Downloading: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-test-autoconfigure/2.2.2.RELEASE/spring-boot-test-autoconfigure-2.2.2.RELEASE.jar
Downloading: https://repo.maven.apache.org/maven2/com/jayway/jsonpath/json-path/2.4.0/json-path-2.4.0.jar
Downloading: https://repo.maven.apache.org/maven2/net/minidev/json-smart/2.3/json-smart-2.3.jar
401/401 B   
            
Downloaded: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-starter-test/2.2.2.RELEASE/spring-boot-starter-test-2.2.2.RELEASE.jar (401 B at 11.9 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/net/minidev/accessors-smart/1.2/accessors-smart-1.2.jar
4/218 KB    
8/218 KB   
12/218 KB   
16/218 KB   
2/205 KB   16/218 KB   
3/205 KB   16/218 KB   
4/118 KB   3/205 KB   16/218 KB   
4/118 KB   5/205 KB   16/218 KB   
8/118 KB   5/205 KB   16/218 KB   
12/118 KB   5/205 KB   16/218 KB   
16/118 KB   5/205 KB   16/218 KB   
16/118 KB   6/205 KB   16/218 KB   
16/118 KB   7/205 KB   16/218 KB   
16/118 KB   9/205 KB   16/218 KB   
16/118 KB   10/205 KB   16/218 KB   
16/118 KB   11/205 KB   16/218 KB   
16/118 KB   13/205 KB   16/218 KB   
16/118 KB   14/205 KB   16/218 KB   
16/118 KB   15/205 KB   16/218 KB   
16/118 KB   16/205 KB   16/218 KB   
16/118 KB   4/154 KB   16/205 KB   16/218 KB   
16/118 KB   8/154 KB   16/205 KB   16/218 KB   
16/118 KB   12/154 KB   16/205 KB   16/218 KB   
16/118 KB   16/154 KB   16/205 KB   16/218 KB   
16/118 KB   16/154 KB   16/205 KB   20/218 KB   
16/118 KB   16/154 KB   16/205 KB   24/218 KB   
16/118 KB   16/154 KB   16/205 KB   28/218 KB   
16/118 KB   16/154 KB   16/205 KB   32/218 KB   
20/118 KB   16/154 KB   16/205 KB   32/218 KB   
24/118 KB   16/154 KB   16/205 KB   32/218 KB   
28/118 KB   16/154 KB   16/205 KB   32/218 KB   
32/118 KB   16/154 KB   16/205 KB   32/218 KB   
32/118 KB   16/154 KB   20/205 KB   32/218 KB   
32/118 KB   16/154 KB   24/205 KB   32/218 KB   
32/118 KB   16/154 KB   28/205 KB   32/218 KB   
32/118 KB   16/154 KB   32/205 KB   32/218 KB   
32/118 KB   4/30 KB   16/154 KB   32/205 KB   32/218 KB   
32/118 KB   8/30 KB   16/154 KB   32/205 KB   32/218 KB   
32/118 KB   12/30 KB   16/154 KB   32/205 KB   32/218 KB   
32/118 KB   16/30 KB   16/154 KB   32/205 KB   32/218 KB   
32/118 KB   16/30 KB   16/154 KB   32/205 KB   36/218 KB   
32/118 KB   16/30 KB   16/154 KB   32/205 KB   40/218 KB   
32/118 KB   16/30 KB   16/154 KB   32/205 KB   44/218 KB   
32/118 KB   16/30 KB   16/154 KB   32/205 KB   48/218 KB   
32/118 KB   20/30 KB   16/154 KB   32/205 KB   48/218 KB   
32/118 KB   24/30 KB   16/154 KB   32/205 KB   48/218 KB   
32/118 KB   28/30 KB   16/154 KB   32/205 KB   48/218 KB   
32/118 KB   30/30 KB   16/154 KB   32/205 KB   48/218 KB   
32/118 KB   30/30 KB   20/154 KB   32/205 KB   48/218 KB   
32/118 KB   30/30 KB   20/154 KB   36/205 KB   48/218 KB   
32/118 KB   30/30 KB   24/154 KB   36/205 KB   48/218 KB   
32/118 KB   30/30 KB   28/154 KB   36/205 KB   48/218 KB   
32/118 KB   30/30 KB   28/154 KB   40/205 KB   48/218 KB   
32/118 KB   30/30 KB   28/154 KB   44/205 KB   48/218 KB   
32/118 KB   30/30 KB   28/154 KB   48/205 KB   48/218 KB   
36/118 KB   30/30 KB   28/154 KB   48/205 KB   48/218 KB   
40/118 KB   30/30 KB   28/154 KB   48/205 KB   48/218 KB   
44/118 KB   30/30 KB   28/154 KB   48/205 KB   48/218 KB   
48/118 KB   30/30 KB   28/154 KB   48/205 KB   48/218 KB   
48/118 KB   30/30 KB   32/154 KB   48/205 KB   48/218 KB   
48/118 KB   30/30 KB   36/154 KB   48/205 KB   48/218 KB   
48/118 KB   30/30 KB   36/154 KB   48/205 KB   52/218 KB   
48/118 KB   30/30 KB   40/154 KB   48/205 KB   56/218 KB   
48/118 KB   30/30 KB   44/154 KB   48/205 KB   56/218 KB   
48/118 KB   30/30 KB   48/154 KB   48/205 KB   56/218 KB   
48/118 KB   30/30 KB   48/154 KB   52/205 KB   56/218 KB   
48/118 KB   30/30 KB   48/154 KB   56/205 KB   56/218 KB   
48/118 KB   30/30 KB   48/154 KB   60/205 KB   56/218 KB   
48/118 KB   30/30 KB   48/154 KB   64/205 KB   56/218 KB   
52/118 KB   30/30 KB   48/154 KB   64/205 KB   56/218 KB   
56/118 KB   30/30 KB   48/154 KB   64/205 KB   56/218 KB   
60/118 KB   30/30 KB   48/154 KB   64/205 KB   56/218 KB   
64/118 KB   30/30 KB   48/154 KB   64/205 KB   56/218 KB   
64/118 KB   30/30 KB   52/154 KB   64/205 KB   56/218 KB   
64/118 KB   30/30 KB   56/154 KB   64/205 KB   56/218 KB   
64/118 KB   30/30 KB   60/154 KB   64/205 KB   56/218 KB   
64/118 KB   30/30 KB   64/154 KB   64/205 KB   56/218 KB   
64/118 KB   30/30 KB   64/154 KB   68/205 KB   56/218 KB   
64/118 KB   30/30 KB   64/154 KB   72/205 KB   56/218 KB   
64/118 KB   30/30 KB   64/154 KB   76/205 KB   56/218 KB   
64/118 KB   30/30 KB   64/154 KB   80/205 KB   56/218 KB   
48/118 KB   30/30 KB   40/154 KB   48/205 KB   56/218 KB   
64/118 KB   30/30 KB   64/154 KB   80/205 KB   60/218 KB   
64/118 KB   30/30 KB   64/154 KB   80/205 KB   64/218 KB   
68/118 KB   30/30 KB   64/154 KB   80/205 KB   64/218 KB   
72/118 KB   30/30 KB   64/154 KB   80/205 KB   64/218 KB   
76/118 KB   30/30 KB   64/154 KB   80/205 KB   64/218 KB   
80/118 KB   30/30 KB   64/154 KB   80/205 KB   64/218 KB   
80/118 KB   30/30 KB   68/154 KB   80/205 KB   64/218 KB   
80/118 KB   30/30 KB   72/154 KB   80/205 KB   64/218 KB   
80/118 KB   30/30 KB   76/154 KB   80/205 KB   64/218 KB   
80/118 KB   30/30 KB   80/154 KB   80/205 KB   64/218 KB   
80/118 KB   30/30 KB   80/154 KB   80/205 KB   68/218 KB   
80/118 KB   30/30 KB   80/154 KB   80/205 KB   72/218 KB   
80/118 KB   30/30 KB   80/154 KB   80/205 KB   76/218 KB   
80/118 KB   30/30 KB   80/154 KB   80/205 KB   80/218 KB   
84/118 KB   30/30 KB   80/154 KB   80/205 KB   80/218 KB   
88/118 KB   30/30 KB   80/154 KB   80/205 KB   80/218 KB   
92/118 KB   30/30 KB   80/154 KB   80/205 KB   80/218 KB   
96/118 KB   30/30 KB   80/154 KB   80/205 KB   80/218 KB   
96/118 KB   30/30 KB   84/154 KB   80/205 KB   80/218 KB   
96/118 KB   30/30 KB   88/154 KB   80/205 KB   80/218 KB   
96/118 KB   30/30 KB   92/154 KB   80/205 KB   80/218 KB   
96/118 KB   30/30 KB   96/154 KB   80/205 KB   80/218 KB   
                                                           
Downloaded: https://repo.maven.apache.org/maven2/net/minidev/accessors-smart/1.2/accessors-smart-1.2.jar (30 KB at 312.0 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/5.0.4/asm-5.0.4.jar
96/118 KB   96/154 KB   80/205 KB   84/218 KB              
96/118 KB   96/154 KB   80/205 KB   88/218 KB   
96/118 KB   96/154 KB   80/205 KB   92/218 KB   
96/118 KB   96/154 KB   80/205 KB   96/218 KB   
96/118 KB   100/154 KB   80/205 KB   96/218 KB   
96/118 KB   104/154 KB   80/205 KB   96/218 KB   
96/118 KB   108/154 KB   80/205 KB   96/218 KB   
96/118 KB   112/154 KB   80/205 KB   96/218 KB   
96/118 KB   112/154 KB   80/205 KB   100/218 KB   
96/118 KB   112/154 KB   80/205 KB   104/218 KB   
96/118 KB   112/154 KB   80/205 KB   108/218 KB   
96/118 KB   112/154 KB   84/205 KB   108/218 KB   
96/118 KB   112/154 KB   88/205 KB   108/218 KB   
96/118 KB   112/154 KB   92/205 KB   108/218 KB   
96/118 KB   112/154 KB   96/205 KB   108/218 KB   
96/118 KB   112/154 KB   96/205 KB   112/218 KB   
96/118 KB   116/154 KB   96/205 KB   112/218 KB   
96/118 KB   120/154 KB   96/205 KB   112/218 KB   
96/118 KB   124/154 KB   96/205 KB   112/218 KB   
96/118 KB   128/154 KB   96/205 KB   112/218 KB   
100/118 KB   128/154 KB   96/205 KB   112/218 KB   
104/118 KB   128/154 KB   96/205 KB   112/218 KB   
108/118 KB   128/154 KB   96/205 KB   112/218 KB   
112/118 KB   128/154 KB   96/205 KB   112/218 KB   
112/118 KB   128/154 KB   100/205 KB   112/218 KB   
112/118 KB   128/154 KB   104/205 KB   112/218 KB   
112/118 KB   128/154 KB   108/205 KB   112/218 KB   
112/118 KB   128/154 KB   112/205 KB   112/218 KB   
116/118 KB   128/154 KB   112/205 KB   112/218 KB   
118/118 KB   128/154 KB   112/205 KB   112/218 KB   
118/118 KB   128/154 KB   112/205 KB   116/218 KB   
118/118 KB   132/154 KB   112/205 KB   116/218 KB   
118/118 KB   136/154 KB   112/205 KB   116/218 KB   
118/118 KB   140/154 KB   112/205 KB   116/218 KB   
118/118 KB   144/154 KB   112/205 KB   116/218 KB   
118/118 KB   144/154 KB   112/205 KB   120/218 KB   
118/118 KB   144/154 KB   112/205 KB   124/218 KB   
118/118 KB   144/154 KB   112/205 KB   128/218 KB   
118/118 KB   144/154 KB   112/205 KB   132/218 KB   
118/118 KB   144/154 KB   112/205 KB   136/218 KB   
118/118 KB   144/154 KB   112/205 KB   140/218 KB   
118/118 KB   144/154 KB   112/205 KB   144/218 KB   
118/118 KB   144/154 KB   112/205 KB   144/218 KB   4/53 KB   
118/118 KB   144/154 KB   112/205 KB   144/218 KB   8/53 KB   
118/118 KB   144/154 KB   112/205 KB   144/218 KB   12/53 KB   
118/118 KB   144/154 KB   112/205 KB   144/218 KB   16/53 KB   
118/118 KB   148/154 KB   112/205 KB   144/218 KB   16/53 KB   
118/118 KB   152/154 KB   112/205 KB   144/218 KB   16/53 KB   
118/118 KB   154/154 KB   112/205 KB   144/218 KB   16/53 KB   
118/118 KB   154/154 KB   112/205 KB   148/218 KB   16/53 KB   
118/118 KB   154/154 KB   112/205 KB   152/218 KB   16/53 KB   
118/118 KB   154/154 KB   112/205 KB   156/218 KB   16/53 KB   
118/118 KB   154/154 KB   112/205 KB   160/218 KB   16/53 KB   
118/118 KB   154/154 KB   116/205 KB   160/218 KB   16/53 KB   
118/118 KB   154/154 KB   120/205 KB   160/218 KB   16/53 KB   
118/118 KB   154/154 KB   124/205 KB   160/218 KB   16/53 KB   
118/118 KB   154/154 KB   124/205 KB   160/218 KB   20/53 KB   
118/118 KB   154/154 KB   128/205 KB   160/218 KB   20/53 KB   
118/118 KB   154/154 KB   128/205 KB   160/218 KB   24/53 KB   
118/118 KB   154/154 KB   128/205 KB   160/218 KB   28/53 KB   
118/118 KB   154/154 KB   128/205 KB   160/218 KB   32/53 KB   
118/118 KB   154/154 KB   128/205 KB   164/218 KB   32/53 KB   
118/118 KB   154/154 KB   128/205 KB   168/218 KB   32/53 KB   
118/118 KB   154/154 KB   128/205 KB   172/218 KB   32/53 KB   
118/118 KB   154/154 KB   128/205 KB   176/218 KB   32/53 KB   
118/118 KB   154/154 KB   132/205 KB   176/218 KB   32/53 KB   
118/118 KB   154/154 KB   136/205 KB   176/218 KB   32/53 KB   
118/118 KB   154/154 KB   140/205 KB   176/218 KB   32/53 KB   
118/118 KB   154/154 KB   144/205 KB   176/218 KB   32/53 KB   
118/118 KB   154/154 KB   144/205 KB   176/218 KB   36/53 KB   
118/118 KB   154/154 KB   144/205 KB   176/218 KB   40/53 KB   
118/118 KB   154/154 KB   144/205 KB   176/218 KB   44/53 KB   
118/118 KB   154/154 KB   144/205 KB   176/218 KB   48/53 KB   
118/118 KB   154/154 KB   144/205 KB   176/218 KB   52/53 KB   
118/118 KB   154/154 KB   144/205 KB   176/218 KB   53/53 KB   
118/118 KB   154/154 KB   144/205 KB   180/218 KB   53/53 KB   
118/118 KB   154/154 KB   144/205 KB   184/218 KB   53/53 KB   
118/118 KB   154/154 KB   144/205 KB   188/218 KB   53/53 KB   
118/118 KB   154/154 KB   144/205 KB   192/218 KB   53/53 KB   
118/118 KB   154/154 KB   148/205 KB   192/218 KB   53/53 KB   
118/118 KB   154/154 KB   152/205 KB   192/218 KB   53/53 KB   
118/118 KB   154/154 KB   156/205 KB   192/218 KB   53/53 KB   
118/118 KB   154/154 KB   160/205 KB   192/218 KB   53/53 KB   
                                                               
Downloaded: https://repo.maven.apache.org/maven2/net/minidev/json-smart/2.3/json-smart-2.3.jar (118 KB at 810.3 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/junit/jupiter/junit-jupiter/5.5.2/junit-jupiter-5.5.2.jar
154/154 KB   160/205 KB   196/218 KB   53/53 KB                
154/154 KB   160/205 KB   200/218 KB   53/53 KB   
                                                  
160/205 KB   204/218 KB   53/53 KB                
Downloaded: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-test-autoconfigure/2.2.2.RELEASE/spring-boot-test-autoconfigure-2.2.2.RELEASE.jar (154 KB at 1026.6 KB/sec)
160/205 KB   208/218 KB   53/53 KB   
Downloading: https://repo.maven.apache.org/maven2/org/junit/jupiter/junit-jupiter-params/5.5.2/junit-jupiter-params-5.5.2.jar
164/205 KB   208/218 KB   53/53 KB   
168/205 KB   208/218 KB   53/53 KB   
172/205 KB   208/218 KB   53/53 KB   
176/205 KB   208/218 KB   53/53 KB   
176/205 KB   212/218 KB   53/53 KB   
176/205 KB   216/218 KB   53/53 KB   
176/205 KB   218/218 KB   53/53 KB   
                                     
Downloaded: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/5.0.4/asm-5.0.4.jar (53 KB at 344.7 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/assertj/assertj-core/3.13.2/assertj-core-3.13.2.jar
180/205 KB   218/218 KB              
184/205 KB   218/218 KB   
188/205 KB   218/218 KB   
192/205 KB   218/218 KB   
196/205 KB   218/218 KB   
200/205 KB   218/218 KB   
204/205 KB   218/218 KB   
205/205 KB   218/218 KB   
205/205 KB   4/7 KB   218/218 KB   
205/205 KB   7/7 KB   218/218 KB   
                                   
Downloaded: https://repo.maven.apache.org/maven2/com/jayway/jsonpath/json-path/2.4.0/json-path-2.4.0.jar (218 KB at 1345.4 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/hamcrest/hamcrest/2.1/hamcrest-2.1.jar
4/537 KB   205/205 KB   7/7 KB     
8/537 KB   205/205 KB   7/7 KB   
12/537 KB   205/205 KB   7/7 KB   
16/537 KB   205/205 KB   7/7 KB   
20/537 KB   205/205 KB   7/7 KB   
24/537 KB   205/205 KB   7/7 KB   
28/537 KB   205/205 KB   7/7 KB   
32/537 KB   205/205 KB   7/7 KB   
                                  
Downloaded: https://repo.maven.apache.org/maven2/org/junit/jupiter/junit-jupiter/5.5.2/junit-jupiter-5.5.2.jar (7 KB at 33.8 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/net/bytebuddy/byte-buddy-agent/1.10.4/byte-buddy-agent-1.10.4.jar
36/537 KB   205/205 KB            
40/537 KB   205/205 KB   
44/537 KB   205/205 KB   
48/537 KB   205/205 KB   
                         
Downloaded: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-test/2.2.2.RELEASE/spring-boot-test-2.2.2.RELEASE.jar (205 KB at 1125.7 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/skyscreamer/jsonassert/1.5.0/jsonassert-1.5.0.jar
4/4374 KB   48/537 KB    
8/4374 KB   48/537 KB   
12/4374 KB   48/537 KB   
16/4374 KB   48/537 KB   
16/4374 KB   52/537 KB   
16/4374 KB   56/537 KB   
16/4374 KB   60/537 KB   
16/4374 KB   64/537 KB   
20/4374 KB   64/537 KB   
24/4374 KB   64/537 KB   
28/4374 KB   64/537 KB   
32/4374 KB   64/537 KB   
32/4374 KB   68/537 KB   
32/4374 KB   72/537 KB   
32/4374 KB   76/537 KB   
32/4374 KB   80/537 KB   
36/4374 KB   80/537 KB   
40/4374 KB   80/537 KB   
44/4374 KB   80/537 KB   
48/4374 KB   80/537 KB   
48/4374 KB   4/121 KB   80/537 KB   
48/4374 KB   8/121 KB   80/537 KB   
48/4374 KB   12/121 KB   80/537 KB   
48/4374 KB   16/121 KB   80/537 KB   
48/4374 KB   16/121 KB   84/537 KB   
48/4374 KB   16/121 KB   88/537 KB   
48/4374 KB   16/121 KB   92/537 KB   
48/4374 KB   16/121 KB   96/537 KB   
52/4374 KB   16/121 KB   96/537 KB   
56/4374 KB   16/121 KB   96/537 KB   
60/4374 KB   16/121 KB   96/537 KB   
64/4374 KB   16/121 KB   96/537 KB   
64/4374 KB   20/121 KB   96/537 KB   
64/4374 KB   24/121 KB   96/537 KB   
64/4374 KB   28/121 KB   96/537 KB   
64/4374 KB   32/121 KB   96/537 KB   
64/4374 KB   32/121 KB   100/537 KB   
64/4374 KB   32/121 KB   104/537 KB   
64/4374 KB   32/121 KB   108/537 KB   
64/4374 KB   32/121 KB   112/537 KB   
68/4374 KB   32/121 KB   112/537 KB   
72/4374 KB   32/121 KB   112/537 KB   
76/4374 KB   32/121 KB   112/537 KB   
80/4374 KB   32/121 KB   112/537 KB   
80/4374 KB   36/121 KB   112/537 KB   
80/4374 KB   40/121 KB   112/537 KB   
80/4374 KB   44/121 KB   112/537 KB   
80/4374 KB   48/121 KB   112/537 KB   
80/4374 KB   48/121 KB   116/537 KB   
80/4374 KB   48/121 KB   120/537 KB   
80/4374 KB   48/121 KB   124/537 KB   
80/4374 KB   48/121 KB   128/537 KB   
84/4374 KB   48/121 KB   128/537 KB   
88/4374 KB   48/121 KB   128/537 KB   
92/4374 KB   48/121 KB   128/537 KB   
96/4374 KB   48/121 KB   128/537 KB   
96/4374 KB   48/121 KB   132/537 KB   
96/4374 KB   48/121 KB   136/537 KB   
96/4374 KB   48/121 KB   140/537 KB   
96/4374 KB   48/121 KB   144/537 KB   
96/4374 KB   52/121 KB   144/537 KB   
96/4374 KB   56/121 KB   144/537 KB   
96/4374 KB   60/121 KB   144/537 KB   
96/4374 KB   64/121 KB   144/537 KB   
96/4374 KB   64/121 KB   148/537 KB   
96/4374 KB   64/121 KB   152/537 KB   
96/4374 KB   64/121 KB   156/537 KB   
96/4374 KB   64/121 KB   160/537 KB   
96/4374 KB   4/253 KB   64/121 KB   160/537 KB   
96/4374 KB   8/253 KB   64/121 KB   160/537 KB   
96/4374 KB   12/253 KB   64/121 KB   160/537 KB   
96/4374 KB   16/253 KB   64/121 KB   160/537 KB   
96/4374 KB   16/253 KB   64/121 KB   160/537 KB   4/30 KB   
96/4374 KB   16/253 KB   64/121 KB   160/537 KB   8/30 KB   
96/4374 KB   16/253 KB   64/121 KB   160/537 KB   12/30 KB   
96/4374 KB   16/253 KB   64/121 KB   160/537 KB   16/30 KB   
100/4374 KB   16/253 KB   64/121 KB   160/537 KB   16/30 KB   
104/4374 KB   16/253 KB   64/121 KB   160/537 KB   16/30 KB   
108/4374 KB   16/253 KB   64/121 KB   160/537 KB   16/30 KB   
112/4374 KB   16/253 KB   64/121 KB   160/537 KB   16/30 KB   
112/4374 KB   16/253 KB   68/121 KB   160/537 KB   16/30 KB   
116/4374 KB   16/253 KB   68/121 KB   164/537 KB   16/30 KB   
116/4374 KB   16/253 KB   68/121 KB   164/537 KB   16/30 KB   
120/4374 KB   16/253 KB   68/121 KB   164/537 KB   16/30 KB   
120/4374 KB   16/253 KB   72/121 KB   168/537 KB   16/30 KB   
124/4374 KB   16/253 KB   72/121 KB   168/537 KB   16/30 KB   
124/4374 KB   16/253 KB   76/121 KB   168/537 KB   16/30 KB   
128/4374 KB   16/253 KB   76/121 KB   168/537 KB   16/30 KB   
128/4374 KB   16/253 KB   80/121 KB   168/537 KB   16/30 KB   
128/4374 KB   16/253 KB   80/121 KB   168/537 KB   20/30 KB   
128/4374 KB   16/253 KB   80/121 KB   168/537 KB   24/30 KB   
128/4374 KB   16/253 KB   80/121 KB   168/537 KB   28/30 KB   
128/4374 KB   16/253 KB   80/121 KB   168/537 KB   30/30 KB   
128/4374 KB   20/253 KB   80/121 KB   168/537 KB   30/30 KB   
128/4374 KB   24/253 KB   80/121 KB   168/537 KB   30/30 KB   
128/4374 KB   28/253 KB   80/121 KB   168/537 KB   30/30 KB   
128/4374 KB   32/253 KB   80/121 KB   168/537 KB   30/30 KB   
132/4374 KB   32/253 KB   80/121 KB   168/537 KB   30/30 KB   
136/4374 KB   32/253 KB   80/121 KB   168/537 KB   30/30 KB   
140/4374 KB   32/253 KB   80/121 KB   168/537 KB   30/30 KB   
144/4374 KB   32/253 KB   80/121 KB   168/537 KB   30/30 KB   
120/4374 KB   16/253 KB   68/121 KB   168/537 KB   16/30 KB   
144/4374 KB   32/253 KB   80/121 KB   172/537 KB   30/30 KB   
144/4374 KB   32/253 KB   80/121 KB   176/537 KB   30/30 KB   
148/4374 KB   32/253 KB   80/121 KB   176/537 KB   30/30 KB   
152/4374 KB   32/253 KB   80/121 KB   176/537 KB   30/30 KB   
156/4374 KB   32/253 KB   80/121 KB   176/537 KB   30/30 KB   
160/4374 KB   32/253 KB   80/121 KB   176/537 KB   30/30 KB   
160/4374 KB   36/253 KB   80/121 KB   176/537 KB   30/30 KB   
160/4374 KB   40/253 KB   80/121 KB   176/537 KB   30/30 KB   
160/4374 KB   44/253 KB   80/121 KB   176/537 KB   30/30 KB   
160/4374 KB   48/253 KB   80/121 KB   176/537 KB   30/30 KB   
164/4374 KB   48/253 KB   80/121 KB   176/537 KB   30/30 KB   
168/4374 KB   48/253 KB   80/121 KB   176/537 KB   30/30 KB   
172/4374 KB   48/253 KB   80/121 KB   176/537 KB   30/30 KB   
176/4374 KB   48/253 KB   80/121 KB   176/537 KB   30/30 KB   
176/4374 KB   52/253 KB   80/121 KB   176/537 KB   30/30 KB   
176/4374 KB   56/253 KB   80/121 KB   176/537 KB   30/30 KB   
176/4374 KB   60/253 KB   80/121 KB   176/537 KB   30/30 KB   
176/4374 KB   64/253 KB   80/121 KB   176/537 KB   30/30 KB   
180/4374 KB   64/253 KB   80/121 KB   176/537 KB   30/30 KB   
184/4374 KB   64/253 KB   80/121 KB   176/537 KB   30/30 KB   
188/4374 KB   64/253 KB   80/121 KB   176/537 KB   30/30 KB   
192/4374 KB   64/253 KB   80/121 KB   176/537 KB   30/30 KB   
192/4374 KB   64/253 KB   84/121 KB   176/537 KB   30/30 KB   
192/4374 KB   64/253 KB   88/121 KB   176/537 KB   30/30 KB   
192/4374 KB   64/253 KB   92/121 KB   176/537 KB   30/30 KB   
192/4374 KB   64/253 KB   96/121 KB   176/537 KB   30/30 KB   
196/4374 KB   64/253 KB   96/121 KB   176/537 KB   30/30 KB   
200/4374 KB   64/253 KB   96/121 KB   176/537 KB   30/30 KB   
204/4374 KB   64/253 KB   96/121 KB   176/537 KB   30/30 KB   
208/4374 KB   64/253 KB   96/121 KB   176/537 KB   30/30 KB   
208/4374 KB   64/253 KB   96/121 KB   180/537 KB   30/30 KB   
208/4374 KB   64/253 KB   96/121 KB   184/537 KB   30/30 KB   
208/4374 KB   64/253 KB   96/121 KB   188/537 KB   30/30 KB   
208/4374 KB   64/253 KB   96/121 KB   192/537 KB   30/30 KB   
212/4374 KB   64/253 KB   96/121 KB   192/537 KB   30/30 KB   
216/4374 KB   64/253 KB   96/121 KB   192/537 KB   30/30 KB   
220/4374 KB   64/253 KB   96/121 KB   192/537 KB   30/30 KB   
224/4374 KB   64/253 KB   96/121 KB   192/537 KB   30/30 KB   
224/4374 KB   64/253 KB   100/121 KB   192/537 KB   30/30 KB   
224/4374 KB   64/253 KB   104/121 KB   192/537 KB   30/30 KB   
224/4374 KB   64/253 KB   108/121 KB   192/537 KB   30/30 KB   
224/4374 KB   64/253 KB   112/121 KB   192/537 KB   30/30 KB   
224/4374 KB   68/253 KB   112/121 KB   192/537 KB   30/30 KB   
224/4374 KB   72/253 KB   112/121 KB   192/537 KB   30/30 KB   
224/4374 KB   76/253 KB   112/121 KB   192/537 KB   30/30 KB   
224/4374 KB   80/253 KB   112/121 KB   192/537 KB   30/30 KB   
                                                               
Downloaded: https://repo.maven.apache.org/maven2/org/skyscreamer/jsonassert/1.5.0/jsonassert-1.5.0.jar (30 KB at 107.6 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/com/vaadin/external/google/android-json/0.0.20131108.vaadin1/android-json-0.0.20131108.vaadin1.jar
224/4374 KB   80/253 KB   112/121 KB   196/537 KB              
224/4374 KB   80/253 KB   112/121 KB   200/537 KB   
224/4374 KB   80/253 KB   112/121 KB   204/537 KB   
224/4374 KB   80/253 KB   112/121 KB   208/537 KB   
228/4374 KB   80/253 KB   112/121 KB   208/537 KB   
232/4374 KB   80/253 KB   112/121 KB   208/537 KB   
236/4374 KB   80/253 KB   112/121 KB   208/537 KB   
240/4374 KB   80/253 KB   112/121 KB   208/537 KB   
240/4374 KB   80/253 KB   116/121 KB   208/537 KB   
240/4374 KB   80/253 KB   120/121 KB   208/537 KB   
240/4374 KB   80/253 KB   121/121 KB   208/537 KB   
244/4374 KB   80/253 KB   121/121 KB   208/537 KB   
244/4374 KB   80/253 KB   121/121 KB   212/537 KB   
248/4374 KB   80/253 KB   121/121 KB   212/537 KB   
248/4374 KB   80/253 KB   121/121 KB   216/537 KB   
252/4374 KB   80/253 KB   121/121 KB   216/537 KB   
252/4374 KB   80/253 KB   121/121 KB   220/537 KB   
256/4374 KB   80/253 KB   121/121 KB   220/537 KB   
256/4374 KB   80/253 KB   121/121 KB   224/537 KB   
256/4374 KB   84/253 KB   121/121 KB   224/537 KB   
256/4374 KB   88/253 KB   121/121 KB   224/537 KB   
256/4374 KB   92/253 KB   121/121 KB   224/537 KB   
256/4374 KB   96/253 KB   121/121 KB   224/537 KB   
256/4374 KB   100/253 KB   121/121 KB   224/537 KB   
256/4374 KB   104/253 KB   121/121 KB   224/537 KB   
260/4374 KB   104/253 KB   121/121 KB   228/537 KB   
260/4374 KB   104/253 KB   121/121 KB   224/537 KB   
260/4374 KB   108/253 KB   121/121 KB   232/537 KB   
264/4374 KB   108/253 KB   121/121 KB   232/537 KB   
264/4374 KB   108/253 KB   121/121 KB   236/537 KB   
268/4374 KB   108/253 KB   121/121 KB   236/537 KB   
268/4374 KB   108/253 KB   121/121 KB   240/537 KB   
272/4374 KB   108/253 KB   121/121 KB   240/537 KB   
260/4374 KB   108/253 KB   121/121 KB   228/537 KB   
272/4374 KB   112/253 KB   121/121 KB   240/537 KB   
272/4374 KB   112/253 KB   121/121 KB   244/537 KB   
272/4374 KB   112/253 KB   121/121 KB   248/537 KB   
272/4374 KB   112/253 KB   121/121 KB   252/537 KB   
272/4374 KB   112/253 KB   121/121 KB   256/537 KB   
276/4374 KB   112/253 KB   121/121 KB   256/537 KB   
280/4374 KB   112/253 KB   121/121 KB   256/537 KB   
284/4374 KB   112/253 KB   121/121 KB   256/537 KB   
288/4374 KB   112/253 KB   121/121 KB   256/537 KB   
288/4374 KB   112/253 KB   121/121 KB   260/537 KB   
288/4374 KB   112/253 KB   121/121 KB   264/537 KB   
288/4374 KB   112/253 KB   121/121 KB   268/537 KB   
288/4374 KB   112/253 KB   121/121 KB   272/537 KB   
288/4374 KB   116/253 KB   121/121 KB   272/537 KB   
288/4374 KB   120/253 KB   121/121 KB   272/537 KB   
288/4374 KB   124/253 KB   121/121 KB   272/537 KB   
288/4374 KB   128/253 KB   121/121 KB   272/537 KB   
288/4374 KB   128/253 KB   121/121 KB   276/537 KB   
288/4374 KB   128/253 KB   121/121 KB   280/537 KB   
288/4374 KB   128/253 KB   121/121 KB   284/537 KB   
288/4374 KB   128/253 KB   121/121 KB   288/537 KB   
288/4374 KB   128/253 KB   121/121 KB   288/537 KB   4/18 KB   
288/4374 KB   128/253 KB   121/121 KB   288/537 KB   8/18 KB   
288/4374 KB   128/253 KB   121/121 KB   288/537 KB   12/18 KB   
288/4374 KB   128/253 KB   121/121 KB   288/537 KB   16/18 KB   
288/4374 KB   132/253 KB   121/121 KB   288/537 KB   16/18 KB   
288/4374 KB   136/253 KB   121/121 KB   288/537 KB   16/18 KB   
288/4374 KB   140/253 KB   121/121 KB   288/537 KB   16/18 KB   
288/4374 KB   144/253 KB   121/121 KB   288/537 KB   16/18 KB   
292/4374 KB   144/253 KB   121/121 KB   288/537 KB   16/18 KB   
                                                                
296/4374 KB   144/253 KB   288/537 KB   16/18 KB                
296/4374 KB   144/253 KB   288/537 KB   18/18 KB   
300/4374 KB   144/253 KB   288/537 KB   18/18 KB   
Downloaded: https://repo.maven.apache.org/maven2/org/hamcrest/hamcrest/2.1/hamcrest-2.1.jar (121 KB at 387.8 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/springframework/spring-test/5.2.2.RELEASE/spring-test-5.2.2.RELEASE.jar
304/4374 KB   144/253 KB   288/537 KB   18/18 KB   
304/4374 KB   144/253 KB   292/537 KB   18/18 KB   
304/4374 KB   144/253 KB   296/537 KB   18/18 KB   
304/4374 KB   144/253 KB   300/537 KB   18/18 KB   
304/4374 KB   144/253 KB   304/537 KB   18/18 KB   
308/4374 KB   148/253 KB   304/537 KB   18/18 KB   
308/4374 KB   148/253 KB   304/537 KB   18/18 KB   
312/4374 KB   148/253 KB   304/537 KB   18/18 KB   
312/4374 KB   152/253 KB   304/537 KB   18/18 KB   
316/4374 KB   152/253 KB   304/537 KB   18/18 KB   
316/4374 KB   156/253 KB   304/537 KB   18/18 KB   
320/4374 KB   156/253 KB   304/537 KB   18/18 KB   
320/4374 KB   160/253 KB   304/537 KB   18/18 KB   
320/4374 KB   160/253 KB   308/537 KB   18/18 KB   
320/4374 KB   160/253 KB   312/537 KB   18/18 KB   
320/4374 KB   160/253 KB   316/537 KB   18/18 KB   
320/4374 KB   160/253 KB   320/537 KB   18/18 KB   
324/4374 KB   160/253 KB   320/537 KB   18/18 KB   
328/4374 KB   160/253 KB   320/537 KB   18/18 KB   
332/4374 KB   160/253 KB   320/537 KB   18/18 KB   
336/4374 KB   160/253 KB   320/537 KB   18/18 KB   
336/4374 KB   160/253 KB   324/537 KB   18/18 KB   
336/4374 KB   160/253 KB   328/537 KB   18/18 KB   
336/4374 KB   160/253 KB   332/537 KB   18/18 KB   
336/4374 KB   160/253 KB   336/537 KB   18/18 KB   
336/4374 KB   164/253 KB   336/537 KB   18/18 KB   
336/4374 KB   168/253 KB   336/537 KB   18/18 KB   
336/4374 KB   172/253 KB   336/537 KB   18/18 KB   
336/4374 KB   176/253 KB   336/537 KB   18/18 KB   
340/4374 KB   176/253 KB   336/537 KB   18/18 KB   
344/4374 KB   176/253 KB   336/537 KB   18/18 KB   
348/4374 KB   176/253 KB   336/537 KB   18/18 KB   
352/4374 KB   176/253 KB   336/537 KB   18/18 KB   
352/4374 KB   176/253 KB   340/537 KB   18/18 KB   
352/4374 KB   176/253 KB   344/537 KB   18/18 KB   
352/4374 KB   176/253 KB   348/537 KB   18/18 KB   
352/4374 KB   176/253 KB   352/537 KB   18/18 KB   
356/4374 KB   176/253 KB   352/537 KB   18/18 KB   
360/4374 KB   176/253 KB   352/537 KB   18/18 KB   
364/4374 KB   176/253 KB   352/537 KB   18/18 KB   
368/4374 KB   176/253 KB   352/537 KB   18/18 KB   
368/4374 KB   176/253 KB   356/537 KB   18/18 KB   
368/4374 KB   176/253 KB   360/537 KB   18/18 KB   
368/4374 KB   176/253 KB   364/537 KB   18/18 KB   
368/4374 KB   176/253 KB   368/537 KB   18/18 KB   
372/4374 KB   176/253 KB   368/537 KB   18/18 KB   
376/4374 KB   176/253 KB   368/537 KB   18/18 KB   
380/4374 KB   176/253 KB   368/537 KB   18/18 KB   
384/4374 KB   176/253 KB   368/537 KB   18/18 KB   
                                                   
Downloaded: https://repo.maven.apache.org/maven2/com/vaadin/external/google/android-json/0.0.20131108.vaadin1/android-json-0.0.20131108.vaadin1.jar (18 KB at 51.3 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/xmlunit/xmlunit-core/2.6.3/xmlunit-core-2.6.3.jar
384/4374 KB   176/253 KB   368/537 KB   4/663 KB   
384/4374 KB   176/253 KB   368/537 KB   8/663 KB   
384/4374 KB   176/253 KB   368/537 KB   12/663 KB   
384/4374 KB   176/253 KB   368/537 KB   16/663 KB   
388/4374 KB   176/253 KB   368/537 KB   16/663 KB   
392/4374 KB   176/253 KB   368/537 KB   16/663 KB   
396/4374 KB   176/253 KB   368/537 KB   16/663 KB   
400/4374 KB   176/253 KB   368/537 KB   16/663 KB   
400/4374 KB   180/253 KB   368/537 KB   16/663 KB   
400/4374 KB   184/253 KB   368/537 KB   16/663 KB   
400/4374 KB   188/253 KB   368/537 KB   16/663 KB   
400/4374 KB   192/253 KB   368/537 KB   16/663 KB   
400/4374 KB   192/253 KB   368/537 KB   20/663 KB   
400/4374 KB   192/253 KB   368/537 KB   24/663 KB   
400/4374 KB   192/253 KB   368/537 KB   28/663 KB   
400/4374 KB   192/253 KB   368/537 KB   32/663 KB   
404/4374 KB   192/253 KB   368/537 KB   32/663 KB   
408/4374 KB   192/253 KB   368/537 KB   32/663 KB   
412/4374 KB   192/253 KB   368/537 KB   32/663 KB   
416/4374 KB   192/253 KB   368/537 KB   32/663 KB   
416/4374 KB   196/253 KB   368/537 KB   32/663 KB   
416/4374 KB   200/253 KB   368/537 KB   32/663 KB   
416/4374 KB   204/253 KB   368/537 KB   32/663 KB   
416/4374 KB   208/253 KB   368/537 KB   32/663 KB   
416/4374 KB   208/253 KB   372/537 KB   32/663 KB   
416/4374 KB   208/253 KB   376/537 KB   32/663 KB   
416/4374 KB   208/253 KB   380/537 KB   32/663 KB   
416/4374 KB   208/253 KB   384/537 KB   32/663 KB   
420/4374 KB   208/253 KB   384/537 KB   32/663 KB   
424/4374 KB   208/253 KB   384/537 KB   32/663 KB   
428/4374 KB   208/253 KB   384/537 KB   32/663 KB   
432/4374 KB   208/253 KB   384/537 KB   32/663 KB   
432/4374 KB   212/253 KB   384/537 KB   32/663 KB   
432/4374 KB   216/253 KB   384/537 KB   32/663 KB   
432/4374 KB   220/253 KB   384/537 KB   32/663 KB   
432/4374 KB   224/253 KB   384/537 KB   32/663 KB   
432/4374 KB   224/253 KB   388/537 KB   32/663 KB   
432/4374 KB   224/253 KB   392/537 KB   32/663 KB   
432/4374 KB   224/253 KB   393/537 KB   32/663 KB   
432/4374 KB   224/253 KB   393/537 KB   36/663 KB   
432/4374 KB   224/253 KB   393/537 KB   40/663 KB   
432/4374 KB   224/253 KB   393/537 KB   44/663 KB   
432/4374 KB   224/253 KB   393/537 KB   48/663 KB   
432/4374 KB   224/253 KB   397/537 KB   48/663 KB   
432/4374 KB   224/253 KB   401/537 KB   48/663 KB   
432/4374 KB   224/253 KB   405/537 KB   48/663 KB   
432/4374 KB   224/253 KB   409/537 KB   48/663 KB   
432/4374 KB   224/253 KB   409/537 KB   52/663 KB   
432/4374 KB   224/253 KB   409/537 KB   56/663 KB   
432/4374 KB   224/253 KB   409/537 KB   60/663 KB   
432/4374 KB   224/253 KB   409/537 KB   64/663 KB   
432/4374 KB   224/253 KB   413/537 KB   64/663 KB   
432/4374 KB   224/253 KB   417/537 KB   64/663 KB   
432/4374 KB   224/253 KB   421/537 KB   64/663 KB   
432/4374 KB   224/253 KB   425/537 KB   64/663 KB   
432/4374 KB   224/253 KB   4/165 KB   425/537 KB   64/663 KB   
432/4374 KB   224/253 KB   8/165 KB   425/537 KB   64/663 KB   
432/4374 KB   224/253 KB   12/165 KB   425/537 KB   64/663 KB   
432/4374 KB   224/253 KB   16/165 KB   425/537 KB   64/663 KB   
432/4374 KB   224/253 KB   16/165 KB   425/537 KB   68/663 KB   
432/4374 KB   224/253 KB   16/165 KB   425/537 KB   72/663 KB   
432/4374 KB   224/253 KB   16/165 KB   425/537 KB   76/663 KB   
432/4374 KB   224/253 KB   16/165 KB   425/537 KB   80/663 KB   
432/4374 KB   224/253 KB   16/165 KB   429/537 KB   80/663 KB   
432/4374 KB   224/253 KB   16/165 KB   433/537 KB   80/663 KB   
432/4374 KB   224/253 KB   16/165 KB   437/537 KB   80/663 KB   
432/4374 KB   224/253 KB   16/165 KB   441/537 KB   80/663 KB   
432/4374 KB   228/253 KB   16/165 KB   441/537 KB   80/663 KB   
432/4374 KB   228/253 KB   16/165 KB   445/537 KB   80/663 KB   
432/4374 KB   232/253 KB   16/165 KB   445/537 KB   80/663 KB   
432/4374 KB   236/253 KB   16/165 KB   449/537 KB   80/663 KB   
432/4374 KB   240/253 KB   16/165 KB   449/537 KB   80/663 KB   
432/4374 KB   244/253 KB   16/165 KB   449/537 KB   80/663 KB   
432/4374 KB   248/253 KB   16/165 KB   449/537 KB   80/663 KB   
432/4374 KB   252/253 KB   16/165 KB   449/537 KB   80/663 KB   
432/4374 KB   253/253 KB   16/165 KB   449/537 KB   80/663 KB   
432/4374 KB   253/253 KB   16/165 KB   449/537 KB   84/663 KB   
432/4374 KB   253/253 KB   16/165 KB   449/537 KB   88/663 KB   
432/4374 KB   253/253 KB   16/165 KB   449/537 KB   92/663 KB   
432/4374 KB   253/253 KB   16/165 KB   449/537 KB   96/663 KB   
432/4374 KB   253/253 KB   20/165 KB   449/537 KB   96/663 KB   
432/4374 KB   253/253 KB   24/165 KB   449/537 KB   96/663 KB   
432/4374 KB   253/253 KB   28/165 KB   449/537 KB   96/663 KB   
432/4374 KB   253/253 KB   32/165 KB   449/537 KB   96/663 KB   
436/4374 KB   253/253 KB   32/165 KB   449/537 KB   96/663 KB   
436/4374 KB   253/253 KB   32/165 KB   449/537 KB   100/663 KB   
436/4374 KB   253/253 KB   32/165 KB   449/537 KB   104/663 KB   
436/4374 KB   253/253 KB   32/165 KB   449/537 KB   108/663 KB   
436/4374 KB   253/253 KB   32/165 KB   449/537 KB   112/663 KB   
432/4374 KB   232/253 KB   16/165 KB   449/537 KB   112/663 KB   
436/4374 KB   253/253 KB   32/165 KB   453/537 KB   112/663 KB   
436/4374 KB   253/253 KB   32/165 KB   457/537 KB   112/663 KB   
436/4374 KB   253/253 KB   32/165 KB   457/537 KB   116/663 KB   
436/4374 KB   253/253 KB   32/165 KB   457/537 KB   120/663 KB   
436/4374 KB   253/253 KB   32/165 KB   457/537 KB   124/663 KB   
436/4374 KB   253/253 KB   32/165 KB   457/537 KB   128/663 KB   
436/4374 KB   253/253 KB   36/165 KB   457/537 KB   128/663 KB   
436/4374 KB   253/253 KB   40/165 KB   457/537 KB   128/663 KB   
436/4374 KB   253/253 KB   44/165 KB   457/537 KB   128/663 KB   
436/4374 KB   253/253 KB   48/165 KB   457/537 KB   128/663 KB   
440/4374 KB   253/253 KB   48/165 KB   457/537 KB   128/663 KB   
444/4374 KB   253/253 KB   48/165 KB   457/537 KB   128/663 KB   
448/4374 KB   253/253 KB   48/165 KB   457/537 KB   128/663 KB   
448/4374 KB   253/253 KB   48/165 KB   461/537 KB   128/663 KB   
448/4374 KB   253/253 KB   48/165 KB   465/537 KB   128/663 KB   
448/4374 KB   253/253 KB   48/165 KB   469/537 KB   128/663 KB   
448/4374 KB   253/253 KB   48/165 KB   473/537 KB   128/663 KB   
448/4374 KB   253/253 KB   48/165 KB   473/537 KB   132/663 KB   
448/4374 KB   253/253 KB   48/165 KB   473/537 KB   136/663 KB   
448/4374 KB   253/253 KB   48/165 KB   473/537 KB   140/663 KB   
448/4374 KB   253/253 KB   48/165 KB   473/537 KB   144/663 KB   
448/4374 KB   253/253 KB   52/165 KB   473/537 KB   144/663 KB   
448/4374 KB   253/253 KB   52/165 KB   477/537 KB   144/663 KB   
448/4374 KB   253/253 KB   56/165 KB   477/537 KB   144/663 KB   
448/4374 KB   253/253 KB   56/165 KB   481/537 KB   144/663 KB   
448/4374 KB   253/253 KB   60/165 KB   481/537 KB   144/663 KB   
448/4374 KB   253/253 KB   60/165 KB   485/537 KB   144/663 KB   
448/4374 KB   253/253 KB   64/165 KB   485/537 KB   144/663 KB   
448/4374 KB   253/253 KB   64/165 KB   489/537 KB   144/663 KB   
448/4374 KB   253/253 KB   64/165 KB   489/537 KB   148/663 KB   
448/4374 KB   253/253 KB   64/165 KB   489/537 KB   152/663 KB   
448/4374 KB   253/253 KB   64/165 KB   489/537 KB   156/663 KB   
448/4374 KB   253/253 KB   64/165 KB   489/537 KB   160/663 KB   
452/4374 KB   253/253 KB   64/165 KB   489/537 KB   160/663 KB   
456/4374 KB   253/253 KB   64/165 KB   489/537 KB   160/663 KB   
460/4374 KB   253/253 KB   64/165 KB   489/537 KB   160/663 KB   
464/4374 KB   253/253 KB   64/165 KB   489/537 KB   160/663 KB   
464/4374 KB   253/253 KB   64/165 KB   493/537 KB   160/663 KB   
464/4374 KB   253/253 KB   64/165 KB   497/537 KB   160/663 KB   
464/4374 KB   253/253 KB   64/165 KB   501/537 KB   160/663 KB   
464/4374 KB   253/253 KB   64/165 KB   505/537 KB   160/663 KB   
464/4374 KB   253/253 KB   64/165 KB   505/537 KB   164/663 KB   
464/4374 KB   253/253 KB   64/165 KB   505/537 KB   168/663 KB   
464/4374 KB   253/253 KB   64/165 KB   505/537 KB   172/663 KB   
464/4374 KB   253/253 KB   64/165 KB   505/537 KB   176/663 KB   
464/4374 KB   253/253 KB   64/165 KB   509/537 KB   176/663 KB   
464/4374 KB   253/253 KB   64/165 KB   513/537 KB   176/663 KB   
464/4374 KB   253/253 KB   64/165 KB   517/537 KB   176/663 KB   
464/4374 KB   253/253 KB   64/165 KB   521/537 KB   176/663 KB   
464/4374 KB   253/253 KB   68/165 KB   521/537 KB   176/663 KB   
464/4374 KB   253/253 KB   72/165 KB   521/537 KB   176/663 KB   
464/4374 KB   253/253 KB   76/165 KB   521/537 KB   176/663 KB   
464/4374 KB   253/253 KB   76/165 KB   521/537 KB   180/663 KB   
464/4374 KB   253/253 KB   80/165 KB   521/537 KB   180/663 KB   
464/4374 KB   253/253 KB   80/165 KB   521/537 KB   184/663 KB   
464/4374 KB   253/253 KB   80/165 KB   521/537 KB   188/663 KB   
464/4374 KB   253/253 KB   80/165 KB   521/537 KB   192/663 KB   
464/4374 KB   253/253 KB   80/165 KB   525/537 KB   192/663 KB   
464/4374 KB   253/253 KB   80/165 KB   529/537 KB   192/663 KB   
464/4374 KB   253/253 KB   80/165 KB   533/537 KB   192/663 KB   
464/4374 KB   253/253 KB   80/165 KB   537/537 KB   192/663 KB   
464/4374 KB   253/253 KB   84/165 KB   537/537 KB   192/663 KB   
                                                                 
464/4374 KB   88/165 KB   537/537 KB   192/663 KB                
464/4374 KB   92/165 KB   537/537 KB   192/663 KB   
Downloaded: https://repo.maven.apache.org/maven2/net/bytebuddy/byte-buddy-agent/1.10.4/byte-buddy-agent-1.10.4.jar (253 KB at 595.1 KB/sec)
464/4374 KB   96/165 KB   537/537 KB   192/663 KB   
Downloading: https://repo.maven.apache.org/maven2/org/junit/jupiter/junit-jupiter-engine/5.5.2/junit-jupiter-engine-5.5.2.jar
464/4374 KB   100/165 KB   537/537 KB   192/663 KB   
464/4374 KB   104/165 KB   537/537 KB   192/663 KB   
464/4374 KB   108/165 KB   537/537 KB   192/663 KB   
464/4374 KB   112/165 KB   537/537 KB   192/663 KB   
464/4374 KB   112/165 KB   537/537 KB   196/663 KB   
464/4374 KB   112/165 KB   537/537 KB   200/663 KB   
464/4374 KB   112/165 KB   537/537 KB   204/663 KB   
464/4374 KB   112/165 KB   537/537 KB   208/663 KB   
468/4374 KB   112/165 KB   537/537 KB   208/663 KB   
472/4374 KB   112/165 KB   537/537 KB   208/663 KB   
476/4374 KB   112/165 KB   537/537 KB   208/663 KB   
480/4374 KB   112/165 KB   537/537 KB   208/663 KB   
480/4374 KB   116/165 KB   537/537 KB   208/663 KB   
480/4374 KB   120/165 KB   537/537 KB   208/663 KB   
480/4374 KB   124/165 KB   537/537 KB   208/663 KB   
480/4374 KB   128/165 KB   537/537 KB   208/663 KB   
480/4374 KB   128/165 KB   537/537 KB   212/663 KB   
480/4374 KB   128/165 KB   537/537 KB   216/663 KB   
480/4374 KB   128/165 KB   537/537 KB   220/663 KB   
480/4374 KB   128/165 KB   537/537 KB   224/663 KB   
484/4374 KB   128/165 KB   537/537 KB   224/663 KB   
488/4374 KB   128/165 KB   537/537 KB   224/663 KB   
492/4374 KB   128/165 KB   537/537 KB   224/663 KB   
496/4374 KB   128/165 KB   537/537 KB   224/663 KB   
496/4374 KB   132/165 KB   537/537 KB   224/663 KB   
496/4374 KB   136/165 KB   537/537 KB   224/663 KB   
496/4374 KB   140/165 KB   537/537 KB   224/663 KB   
496/4374 KB   144/165 KB   537/537 KB   224/663 KB   
496/4374 KB   144/165 KB   537/537 KB   228/663 KB   
496/4374 KB   144/165 KB   537/537 KB   232/663 KB   
496/4374 KB   144/165 KB   537/537 KB   236/663 KB   
496/4374 KB   144/165 KB   537/537 KB   240/663 KB   
500/4374 KB   144/165 KB   537/537 KB   240/663 KB   
504/4374 KB   144/165 KB   537/537 KB   240/663 KB   
508/4374 KB   144/165 KB   537/537 KB   240/663 KB   
512/4374 KB   144/165 KB   537/537 KB   240/663 KB   
512/4374 KB   148/165 KB   537/537 KB   240/663 KB   
512/4374 KB   152/165 KB   537/537 KB   240/663 KB   
512/4374 KB   156/165 KB   537/537 KB   240/663 KB   
512/4374 KB   160/165 KB   537/537 KB   240/663 KB   
512/4374 KB   160/165 KB   537/537 KB   244/663 KB   
512/4374 KB   160/165 KB   537/537 KB   248/663 KB   
512/4374 KB   160/165 KB   537/537 KB   252/663 KB   
512/4374 KB   160/165 KB   537/537 KB   256/663 KB   
516/4374 KB   160/165 KB   537/537 KB   256/663 KB   
516/4374 KB   164/165 KB   537/537 KB   256/663 KB   
520/4374 KB   164/165 KB   537/537 KB   256/663 KB   
520/4374 KB   165/165 KB   537/537 KB   256/663 KB   
524/4374 KB   165/165 KB   537/537 KB   256/663 KB   
528/4374 KB   165/165 KB   537/537 KB   256/663 KB   
528/4374 KB   165/165 KB   537/537 KB   260/663 KB   
528/4374 KB   165/165 KB   537/537 KB   264/663 KB   
528/4374 KB   165/165 KB   537/537 KB   268/663 KB   
528/4374 KB   165/165 KB   537/537 KB   272/663 KB   
532/4374 KB   165/165 KB   537/537 KB   272/663 KB   
536/4374 KB   165/165 KB   537/537 KB   272/663 KB   
540/4374 KB   165/165 KB   537/537 KB   272/663 KB   
544/4374 KB   165/165 KB   537/537 KB   272/663 KB   
544/4374 KB   165/165 KB   537/537 KB   276/663 KB   
544/4374 KB   165/165 KB   537/537 KB   280/663 KB   
544/4374 KB   165/165 KB   537/537 KB   284/663 KB   
544/4374 KB   165/165 KB   537/537 KB   288/663 KB   
548/4374 KB   165/165 KB   537/537 KB   288/663 KB   
552/4374 KB   165/165 KB   537/537 KB   288/663 KB   
556/4374 KB   165/165 KB   537/537 KB   288/663 KB   
560/4374 KB   165/165 KB   537/537 KB   288/663 KB   
564/4374 KB   165/165 KB   537/537 KB   288/663 KB   
568/4374 KB   165/165 KB   537/537 KB   288/663 KB   
571/4374 KB   165/165 KB   537/537 KB   288/663 KB   
571/4374 KB   165/165 KB   537/537 KB   4/215 KB   288/663 KB   
571/4374 KB   165/165 KB   537/537 KB   8/215 KB   288/663 KB   
571/4374 KB   165/165 KB   537/537 KB   12/215 KB   288/663 KB   
571/4374 KB   165/165 KB   537/537 KB   16/215 KB   288/663 KB   
571/4374 KB   165/165 KB   537/537 KB   16/215 KB   292/663 KB   
571/4374 KB   165/165 KB   537/537 KB   16/215 KB   296/663 KB   
571/4374 KB   165/165 KB   537/537 KB   16/215 KB   300/663 KB   
571/4374 KB   165/165 KB   537/537 KB   16/215 KB   304/663 KB   
575/4374 KB   165/165 KB   537/537 KB   16/215 KB   304/663 KB   
579/4374 KB   165/165 KB   537/537 KB   16/215 KB   304/663 KB   
583/4374 KB   165/165 KB   537/537 KB   16/215 KB   304/663 KB   
587/4374 KB   165/165 KB   537/537 KB   16/215 KB   304/663 KB   
587/4374 KB   165/165 KB   537/537 KB   16/215 KB   308/663 KB   
587/4374 KB   165/165 KB   537/537 KB   16/215 KB   312/663 KB   
587/4374 KB   165/165 KB   537/537 KB   16/215 KB   316/663 KB   
587/4374 KB   165/165 KB   537/537 KB   16/215 KB   320/663 KB   
                                                                 
Downloaded: https://repo.maven.apache.org/maven2/org/junit/jupiter/junit-jupiter-params/5.5.2/junit-jupiter-params-5.5.2.jar (537 KB at 1148.9 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/apiguardian/apiguardian-api/1.1.0/apiguardian-api-1.1.0.jar
587/4374 KB   165/165 KB   20/215 KB   320/663 KB                
587/4374 KB   165/165 KB   24/215 KB   320/663 KB   
587/4374 KB   165/165 KB   28/215 KB   320/663 KB   
587/4374 KB   165/165 KB   32/215 KB   320/663 KB   
591/4374 KB   165/165 KB   32/215 KB   320/663 KB   
595/4374 KB   165/165 KB   32/215 KB   320/663 KB   
599/4374 KB   165/165 KB   32/215 KB   320/663 KB   
603/4374 KB   165/165 KB   32/215 KB   320/663 KB   
603/4374 KB   165/165 KB   32/215 KB   324/663 KB   
603/4374 KB   165/165 KB   32/215 KB   328/663 KB   
603/4374 KB   165/165 KB   32/215 KB   332/663 KB   
603/4374 KB   165/165 KB   32/215 KB   336/663 KB   
603/4374 KB   165/165 KB   36/215 KB   336/663 KB   
603/4374 KB   165/165 KB   40/215 KB   336/663 KB   
603/4374 KB   165/165 KB   44/215 KB   336/663 KB   
603/4374 KB   165/165 KB   48/215 KB   336/663 KB   
607/4374 KB   165/165 KB   48/215 KB   336/663 KB   
611/4374 KB   165/165 KB   48/215 KB   336/663 KB   
615/4374 KB   165/165 KB   48/215 KB   336/663 KB   
619/4374 KB   165/165 KB   48/215 KB   336/663 KB   
619/4374 KB   165/165 KB   48/215 KB   340/663 KB   
619/4374 KB   165/165 KB   48/215 KB   344/663 KB   
619/4374 KB   165/165 KB   48/215 KB   348/663 KB   
619/4374 KB   165/165 KB   48/215 KB   352/663 KB   
623/4374 KB   165/165 KB   48/215 KB   352/663 KB   
627/4374 KB   165/165 KB   48/215 KB   352/663 KB   
631/4374 KB   165/165 KB   48/215 KB   352/663 KB   
635/4374 KB   165/165 KB   48/215 KB   352/663 KB   
635/4374 KB   165/165 KB   52/215 KB   352/663 KB   
635/4374 KB   165/165 KB   56/215 KB   352/663 KB   
                                                    
635/4374 KB   60/215 KB   352/663 KB                
635/4374 KB   64/215 KB   352/663 KB   
Downloaded: https://repo.maven.apache.org/maven2/org/xmlunit/xmlunit-core/2.6.3/xmlunit-core-2.6.3.jar (165 KB at 343.0 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-engine/1.5.2/junit-platform-engine-1.5.2.jar
635/4374 KB   64/215 KB   356/663 KB   
635/4374 KB   64/215 KB   360/663 KB   
635/4374 KB   64/215 KB   364/663 KB   
635/4374 KB   64/215 KB   368/663 KB   
639/4374 KB   64/215 KB   368/663 KB   
643/4374 KB   64/215 KB   368/663 KB   
647/4374 KB   64/215 KB   368/663 KB   
651/4374 KB   64/215 KB   368/663 KB   
651/4374 KB   64/215 KB   372/663 KB   
651/4374 KB   64/215 KB   376/663 KB   
651/4374 KB   64/215 KB   380/663 KB   
651/4374 KB   64/215 KB   384/663 KB   
655/4374 KB   64/215 KB   384/663 KB   
659/4374 KB   64/215 KB   384/663 KB   
663/4374 KB   64/215 KB   384/663 KB   
667/4374 KB   64/215 KB   384/663 KB   
667/4374 KB   68/215 KB   384/663 KB   
667/4374 KB   72/215 KB   384/663 KB   
667/4374 KB   76/215 KB   384/663 KB   
667/4374 KB   80/215 KB   384/663 KB   
667/4374 KB   80/215 KB   388/663 KB   
667/4374 KB   80/215 KB   392/663 KB   
667/4374 KB   80/215 KB   396/663 KB   
667/4374 KB   80/215 KB   400/663 KB   
671/4374 KB   80/215 KB   400/663 KB   
675/4374 KB   80/215 KB   400/663 KB   
679/4374 KB   80/215 KB   400/663 KB   
683/4374 KB   80/215 KB   400/663 KB   
683/4374 KB   84/215 KB   400/663 KB   
683/4374 KB   88/215 KB   400/663 KB   
683/4374 KB   92/215 KB   400/663 KB   
683/4374 KB   96/215 KB   400/663 KB   
687/4374 KB   96/215 KB   400/663 KB   
691/4374 KB   96/215 KB   400/663 KB   
695/4374 KB   96/215 KB   400/663 KB   
699/4374 KB   96/215 KB   400/663 KB   
699/4374 KB   100/215 KB   400/663 KB   
699/4374 KB   104/215 KB   400/663 KB   
699/4374 KB   108/215 KB   400/663 KB   
699/4374 KB   112/215 KB   400/663 KB   
703/4374 KB   112/215 KB   400/663 KB   
707/4374 KB   112/215 KB   400/663 KB   
711/4374 KB   112/215 KB   400/663 KB   
715/4374 KB   112/215 KB   400/663 KB   
715/4374 KB   112/215 KB   404/663 KB   
715/4374 KB   112/215 KB   408/663 KB   
715/4374 KB   112/215 KB   412/663 KB   
715/4374 KB   112/215 KB   416/663 KB   
715/4374 KB   116/215 KB   416/663 KB   
715/4374 KB   120/215 KB   416/663 KB   
715/4374 KB   124/215 KB   416/663 KB   
715/4374 KB   128/215 KB   416/663 KB   
719/4374 KB   128/215 KB   416/663 KB   
723/4374 KB   128/215 KB   416/663 KB   
727/4374 KB   128/215 KB   416/663 KB   
731/4374 KB   128/215 KB   416/663 KB   
731/4374 KB   3/3 KB   128/215 KB   416/663 KB   
731/4374 KB   3/3 KB   132/215 KB   416/663 KB   
735/4374 KB   3/3 KB   132/215 KB   416/663 KB   
739/4374 KB   3/3 KB   132/215 KB   416/663 KB   
743/4374 KB   3/3 KB   132/215 KB   416/663 KB   
747/4374 KB   3/3 KB   132/215 KB   416/663 KB   
747/4374 KB   3/3 KB   136/215 KB   416/663 KB   
747/4374 KB   3/3 KB   140/215 KB   416/663 KB   
747/4374 KB   3/3 KB   144/215 KB   416/663 KB   
751/4374 KB   3/3 KB   144/215 KB   416/663 KB   
755/4374 KB   3/3 KB   144/215 KB   416/663 KB   
759/4374 KB   3/3 KB   144/215 KB   416/663 KB   
763/4374 KB   3/3 KB   144/215 KB   416/663 KB   
767/4374 KB   3/3 KB   144/215 KB   416/663 KB   
771/4374 KB   3/3 KB   144/215 KB   416/663 KB   
775/4374 KB   3/3 KB   144/215 KB   416/663 KB   
779/4374 KB   3/3 KB   144/215 KB   416/663 KB   
783/4374 KB   3/3 KB   144/215 KB   416/663 KB   
787/4374 KB   3/3 KB   144/215 KB   416/663 KB   
791/4374 KB   3/3 KB   144/215 KB   416/663 KB   
795/4374 KB   3/3 KB   144/215 KB   416/663 KB   
795/4374 KB   3/3 KB   144/215 KB   4/161 KB   416/663 KB   
795/4374 KB   3/3 KB   144/215 KB   8/161 KB   416/663 KB   
795/4374 KB   3/3 KB   144/215 KB   12/161 KB   416/663 KB   
795/4374 KB   3/3 KB   144/215 KB   16/161 KB   416/663 KB   
799/4374 KB   3/3 KB   144/215 KB   16/161 KB   416/663 KB   
803/4374 KB   3/3 KB   144/215 KB   16/161 KB   416/663 KB   
807/4374 KB   3/3 KB   144/215 KB   16/161 KB   416/663 KB   
811/4374 KB   3/3 KB   144/215 KB   16/161 KB   416/663 KB   
811/4374 KB   3/3 KB   144/215 KB   20/161 KB   416/663 KB   
811/4374 KB   3/3 KB   144/215 KB   24/161 KB   416/663 KB   
811/4374 KB   3/3 KB   144/215 KB   28/161 KB   416/663 KB   
811/4374 KB   3/3 KB   144/215 KB   32/161 KB   416/663 KB   
815/4374 KB   3/3 KB   144/215 KB   32/161 KB   416/663 KB   
819/4374 KB   3/3 KB   144/215 KB   32/161 KB   416/663 KB   
823/4374 KB   3/3 KB   144/215 KB   32/161 KB   416/663 KB   
827/4374 KB   3/3 KB   144/215 KB   32/161 KB   416/663 KB   
827/4374 KB   3/3 KB   144/215 KB   36/161 KB   416/663 KB   
827/4374 KB   3/3 KB   144/215 KB   40/161 KB   416/663 KB   
827/4374 KB   3/3 KB   144/215 KB   44/161 KB   416/663 KB   
827/4374 KB   3/3 KB   144/215 KB   48/161 KB   416/663 KB   
831/4374 KB   3/3 KB   144/215 KB   48/161 KB   416/663 KB   
835/4374 KB   3/3 KB   144/215 KB   48/161 KB   416/663 KB   
839/4374 KB   3/3 KB   144/215 KB   48/161 KB   416/663 KB   
843/4374 KB   3/3 KB   144/215 KB   48/161 KB   416/663 KB   
843/4374 KB   3/3 KB   144/215 KB   52/161 KB   416/663 KB   
843/4374 KB   3/3 KB   144/215 KB   56/161 KB   416/663 KB   
843/4374 KB   3/3 KB   144/215 KB   60/161 KB   416/663 KB   
843/4374 KB   3/3 KB   144/215 KB   64/161 KB   416/663 KB   
847/4374 KB   3/3 KB   144/215 KB   64/161 KB   416/663 KB   
851/4374 KB   3/3 KB   144/215 KB   64/161 KB   416/663 KB   
855/4374 KB   3/3 KB   144/215 KB   64/161 KB   416/663 KB   
859/4374 KB   3/3 KB   144/215 KB   64/161 KB   416/663 KB   
859/4374 KB   3/3 KB   144/215 KB   68/161 KB   416/663 KB   
859/4374 KB   3/3 KB   144/215 KB   72/161 KB   416/663 KB   
859/4374 KB   3/3 KB   144/215 KB   76/161 KB   416/663 KB   
859/4374 KB   3/3 KB   144/215 KB   80/161 KB   416/663 KB   
863/4374 KB   3/3 KB   144/215 KB   80/161 KB   416/663 KB   
867/4374 KB   3/3 KB   144/215 KB   80/161 KB   416/663 KB   
871/4374 KB   3/3 KB   144/215 KB   80/161 KB   416/663 KB   
875/4374 KB   3/3 KB   144/215 KB   80/161 KB   416/663 KB   
                                                             
Downloaded: https://repo.maven.apache.org/maven2/org/apiguardian/apiguardian-api/1.1.0/apiguardian-api-1.1.0.jar (3 KB at 4.2 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/opentest4j/opentest4j/1.2.0/opentest4j-1.2.0.jar
875/4374 KB   148/215 KB   80/161 KB   416/663 KB            
879/4374 KB   148/215 KB   80/161 KB   416/663 KB   
879/4374 KB   152/215 KB   80/161 KB   416/663 KB   
883/4374 KB   152/215 KB   80/161 KB   416/663 KB   
883/4374 KB   156/215 KB   80/161 KB   416/663 KB   
887/4374 KB   156/215 KB   80/161 KB   416/663 KB   
891/4374 KB   160/215 KB   80/161 KB   416/663 KB   
891/4374 KB   160/215 KB   80/161 KB   416/663 KB   
891/4374 KB   160/215 KB   80/161 KB   420/663 KB   
891/4374 KB   160/215 KB   80/161 KB   424/663 KB   
891/4374 KB   160/215 KB   80/161 KB   428/663 KB   
891/4374 KB   160/215 KB   80/161 KB   432/663 KB   
895/4374 KB   160/215 KB   80/161 KB   432/663 KB   
899/4374 KB   160/215 KB   80/161 KB   432/663 KB   
903/4374 KB   160/215 KB   80/161 KB   432/663 KB   
907/4374 KB   160/215 KB   80/161 KB   432/663 KB   
907/4374 KB   164/215 KB   80/161 KB   432/663 KB   
907/4374 KB   168/215 KB   80/161 KB   432/663 KB   
907/4374 KB   172/215 KB   80/161 KB   432/663 KB   
907/4374 KB   176/215 KB   80/161 KB   432/663 KB   
907/4374 KB   176/215 KB   80/161 KB   436/663 KB   
907/4374 KB   176/215 KB   80/161 KB   440/663 KB   
907/4374 KB   176/215 KB   80/161 KB   444/663 KB   
907/4374 KB   176/215 KB   80/161 KB   448/663 KB   
911/4374 KB   176/215 KB   80/161 KB   448/663 KB   
915/4374 KB   176/215 KB   80/161 KB   448/663 KB   
919/4374 KB   176/215 KB   80/161 KB   448/663 KB   
923/4374 KB   176/215 KB   80/161 KB   448/663 KB   
923/4374 KB   180/215 KB   80/161 KB   448/663 KB   
923/4374 KB   184/215 KB   80/161 KB   448/663 KB   
923/4374 KB   188/215 KB   80/161 KB   448/663 KB   
923/4374 KB   192/215 KB   80/161 KB   448/663 KB   
923/4374 KB   192/215 KB   84/161 KB   448/663 KB   
923/4374 KB   192/215 KB   88/161 KB   448/663 KB   
923/4374 KB   192/215 KB   92/161 KB   448/663 KB   
923/4374 KB   192/215 KB   96/161 KB   448/663 KB   
927/4374 KB   192/215 KB   96/161 KB   448/663 KB   
931/4374 KB   192/215 KB   96/161 KB   448/663 KB   
935/4374 KB   192/215 KB   96/161 KB   448/663 KB   
939/4374 KB   192/215 KB   96/161 KB   448/663 KB   
939/4374 KB   196/215 KB   96/161 KB   448/663 KB   
939/4374 KB   200/215 KB   96/161 KB   448/663 KB   
939/4374 KB   204/215 KB   96/161 KB   448/663 KB   
939/4374 KB   208/215 KB   96/161 KB   448/663 KB   
939/4374 KB   212/215 KB   96/161 KB   448/663 KB   
939/4374 KB   215/215 KB   96/161 KB   448/663 KB   
939/4374 KB   215/215 KB   96/161 KB   452/663 KB   
939/4374 KB   215/215 KB   96/161 KB   456/663 KB   
939/4374 KB   215/215 KB   96/161 KB   460/663 KB   
939/4374 KB   215/215 KB   96/161 KB   464/663 KB   
943/4374 KB   215/215 KB   96/161 KB   464/663 KB   
947/4374 KB   215/215 KB   96/161 KB   464/663 KB   
951/4374 KB   215/215 KB   96/161 KB   464/663 KB   
955/4374 KB   215/215 KB   96/161 KB   464/663 KB   
955/4374 KB   215/215 KB   100/161 KB   464/663 KB   
955/4374 KB   215/215 KB   104/161 KB   464/663 KB   
955/4374 KB   215/215 KB   108/161 KB   464/663 KB   
955/4374 KB   215/215 KB   112/161 KB   464/663 KB   
955/4374 KB   215/215 KB   112/161 KB   468/663 KB   
955/4374 KB   215/215 KB   112/161 KB   472/663 KB   
955/4374 KB   215/215 KB   112/161 KB   476/663 KB   
955/4374 KB   215/215 KB   112/161 KB   480/663 KB   
959/4374 KB   215/215 KB   112/161 KB   480/663 KB   
963/4374 KB   215/215 KB   112/161 KB   480/663 KB   
967/4374 KB   215/215 KB   112/161 KB   480/663 KB   
971/4374 KB   215/215 KB   112/161 KB   480/663 KB   
971/4374 KB   4/8 KB   215/215 KB   112/161 KB   480/663 KB   
971/4374 KB   8/8 KB   215/215 KB   112/161 KB   480/663 KB   
971/4374 KB   8/8 KB   215/215 KB   116/161 KB   480/663 KB   
975/4374 KB   8/8 KB   215/215 KB   116/161 KB   480/663 KB   
975/4374 KB   8/8 KB   215/215 KB   120/161 KB   480/663 KB   
979/4374 KB   8/8 KB   215/215 KB   120/161 KB   480/663 KB   
979/4374 KB   8/8 KB   215/215 KB   124/161 KB   480/663 KB   
983/4374 KB   8/8 KB   215/215 KB   124/161 KB   480/663 KB   
983/4374 KB   8/8 KB   215/215 KB   128/161 KB   480/663 KB   
987/4374 KB   8/8 KB   215/215 KB   128/161 KB   480/663 KB   
987/4374 KB   8/8 KB   215/215 KB   128/161 KB   484/663 KB   
987/4374 KB   8/8 KB   215/215 KB   128/161 KB   488/663 KB   
987/4374 KB   8/8 KB   215/215 KB   128/161 KB   492/663 KB   
987/4374 KB   8/8 KB   215/215 KB   128/161 KB   496/663 KB   
991/4374 KB   8/8 KB   215/215 KB   128/161 KB   496/663 KB   
995/4374 KB   8/8 KB   215/215 KB   128/161 KB   496/663 KB   
999/4374 KB   8/8 KB   215/215 KB   128/161 KB   496/663 KB   
1003/4374 KB   8/8 KB   215/215 KB   128/161 KB   496/663 KB   
1003/4374 KB   8/8 KB   215/215 KB   132/161 KB   496/663 KB   
1003/4374 KB   8/8 KB   215/215 KB   136/161 KB   496/663 KB   
1003/4374 KB   8/8 KB   215/215 KB   140/161 KB   496/663 KB   
1003/4374 KB   8/8 KB   215/215 KB   144/161 KB   496/663 KB   
1003/4374 KB   8/8 KB   215/215 KB   144/161 KB   500/663 KB   
1003/4374 KB   8/8 KB   215/215 KB   144/161 KB   504/663 KB   
1003/4374 KB   8/8 KB   215/215 KB   144/161 KB   508/663 KB   
1003/4374 KB   8/8 KB   215/215 KB   144/161 KB   512/663 KB   
                                                               
Downloaded: https://repo.maven.apache.org/maven2/org/junit/jupiter/junit-jupiter-engine/5.5.2/junit-jupiter-engine-5.5.2.jar (215 KB at 364.1 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-commons/1.5.2/junit-platform-commons-1.5.2.jar
1007/4374 KB   8/8 KB   144/161 KB   512/663 KB                
1011/4374 KB   8/8 KB   144/161 KB   512/663 KB   
1015/4374 KB   8/8 KB   144/161 KB   512/663 KB   
1019/4374 KB   8/8 KB   144/161 KB   512/663 KB   
1019/4374 KB   8/8 KB   144/161 KB   516/663 KB   
1019/4374 KB   8/8 KB   144/161 KB   520/663 KB   
1019/4374 KB   8/8 KB   144/161 KB   524/663 KB   
1019/4374 KB   8/8 KB   144/161 KB   528/663 KB   
1019/4374 KB   8/8 KB   148/161 KB   528/663 KB   
1019/4374 KB   8/8 KB   152/161 KB   528/663 KB   
1019/4374 KB   8/8 KB   156/161 KB   528/663 KB   
1019/4374 KB   8/8 KB   160/161 KB   528/663 KB   
1019/4374 KB   8/8 KB   161/161 KB   528/663 KB   
1023/4374 KB   8/8 KB   161/161 KB   528/663 KB   
1027/4374 KB   8/8 KB   161/161 KB   528/663 KB   
1031/4374 KB   8/8 KB   161/161 KB   528/663 KB   
1035/4374 KB   8/8 KB   161/161 KB   528/663 KB   
1039/4374 KB   8/8 KB   161/161 KB   528/663 KB   
1043/4374 KB   8/8 KB   161/161 KB   528/663 KB   
1047/4374 KB   8/8 KB   161/161 KB   528/663 KB   
1051/4374 KB   8/8 KB   161/161 KB   528/663 KB   
                                                  
Downloaded: https://repo.maven.apache.org/maven2/org/opentest4j/opentest4j/1.2.0/opentest4j-1.2.0.jar (8 KB at 12.5 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/junit/jupiter/junit-jupiter-api/5.5.2/junit-jupiter-api-5.5.2.jar
1051/4374 KB   161/161 KB   532/663 KB            
1051/4374 KB   161/161 KB   536/663 KB   
1051/4374 KB   161/161 KB   540/663 KB   
1051/4374 KB   161/161 KB   544/663 KB   
1055/4374 KB   161/161 KB   544/663 KB   
1059/4374 KB   161/161 KB   544/663 KB   
1063/4374 KB   161/161 KB   544/663 KB   
1067/4374 KB   161/161 KB   544/663 KB   
1067/4374 KB   161/161 KB   548/663 KB   
1067/4374 KB   161/161 KB   552/663 KB   
1067/4374 KB   161/161 KB   556/663 KB   
1067/4374 KB   161/161 KB   560/663 KB   
1071/4374 KB   161/161 KB   560/663 KB   
1075/4374 KB   161/161 KB   560/663 KB   
1079/4374 KB   161/161 KB   560/663 KB   
1083/4374 KB   161/161 KB   560/663 KB   
1087/4374 KB   161/161 KB   560/663 KB   
1091/4374 KB   161/161 KB   560/663 KB   
1095/4374 KB   161/161 KB   560/663 KB   
1099/4374 KB   161/161 KB   560/663 KB   
1099/4374 KB   161/161 KB   564/663 KB   
1099/4374 KB   161/161 KB   568/663 KB   
1099/4374 KB   161/161 KB   572/663 KB   
1099/4374 KB   161/161 KB   576/663 KB   
                                         
1103/4374 KB   576/663 KB                
1107/4374 KB   576/663 KB   
Downloaded: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-engine/1.5.2/junit-platform-engine-1.5.2.jar (161 KB at 259.4 KB/sec)
1111/4374 KB   576/663 KB   
Downloading: https://repo.maven.apache.org/maven2/org/mockito/mockito-junit-jupiter/3.1.0/mockito-junit-jupiter-3.1.0.jar
1115/4374 KB   576/663 KB   
1115/4374 KB   4/90 KB   576/663 KB   
1115/4374 KB   8/90 KB   576/663 KB   
1115/4374 KB   12/90 KB   576/663 KB   
1115/4374 KB   16/90 KB   576/663 KB   
1115/4374 KB   16/90 KB   580/663 KB   
1115/4374 KB   16/90 KB   584/663 KB   
1115/4374 KB   16/90 KB   588/663 KB   
1115/4374 KB   16/90 KB   592/663 KB   
1119/4374 KB   16/90 KB   592/663 KB   
1123/4374 KB   16/90 KB   592/663 KB   
1127/4374 KB   16/90 KB   592/663 KB   
1131/4374 KB   16/90 KB   592/663 KB   
1131/4374 KB   16/90 KB   596/663 KB   
1131/4374 KB   16/90 KB   600/663 KB   
1131/4374 KB   16/90 KB   604/663 KB   
1131/4374 KB   16/90 KB   608/663 KB   
1135/4374 KB   16/90 KB   608/663 KB   
1139/4374 KB   16/90 KB   608/663 KB   
1142/4374 KB   16/90 KB   608/663 KB   
1142/4374 KB   20/90 KB   608/663 KB   
1142/4374 KB   24/90 KB   608/663 KB   
1142/4374 KB   28/90 KB   608/663 KB   
1142/4374 KB   32/90 KB   608/663 KB   
1142/4374 KB   32/90 KB   612/663 KB   
1142/4374 KB   32/90 KB   616/663 KB   
1142/4374 KB   32/90 KB   620/663 KB   
1142/4374 KB   32/90 KB   624/663 KB   
1146/4374 KB   32/90 KB   624/663 KB   
1150/4374 KB   32/90 KB   624/663 KB   
1154/4374 KB   32/90 KB   624/663 KB   
1158/4374 KB   32/90 KB   624/663 KB   
1158/4374 KB   4/139 KB   32/90 KB   624/663 KB   
1158/4374 KB   8/139 KB   32/90 KB   624/663 KB   
1158/4374 KB   12/139 KB   32/90 KB   624/663 KB   
1158/4374 KB   16/139 KB   32/90 KB   624/663 KB   
1158/4374 KB   16/139 KB   32/90 KB   628/663 KB   
1158/4374 KB   16/139 KB   32/90 KB   632/663 KB   
1158/4374 KB   16/139 KB   32/90 KB   636/663 KB   
1158/4374 KB   16/139 KB   32/90 KB   640/663 KB   
1162/4374 KB   16/139 KB   32/90 KB   640/663 KB   
1166/4374 KB   16/139 KB   32/90 KB   640/663 KB   
1170/4374 KB   16/139 KB   32/90 KB   640/663 KB   
1174/4374 KB   16/139 KB   32/90 KB   640/663 KB   
1174/4374 KB   16/139 KB   32/90 KB   643/663 KB   
1178/4374 KB   16/139 KB   32/90 KB   643/663 KB   
1182/4374 KB   16/139 KB   32/90 KB   643/663 KB   
1186/4374 KB   16/139 KB   32/90 KB   643/663 KB   
1190/4374 KB   16/139 KB   32/90 KB   643/663 KB   
1190/4374 KB   16/139 KB   36/90 KB   643/663 KB   
1190/4374 KB   16/139 KB   40/90 KB   643/663 KB   
1190/4374 KB   16/139 KB   44/90 KB   643/663 KB   
1190/4374 KB   16/139 KB   48/90 KB   643/663 KB   
1190/4374 KB   16/139 KB   48/90 KB   647/663 KB   
1190/4374 KB   16/139 KB   48/90 KB   651/663 KB   
1190/4374 KB   16/139 KB   48/90 KB   655/663 KB   
1190/4374 KB   16/139 KB   48/90 KB   659/663 KB   
1190/4374 KB   20/139 KB   48/90 KB   659/663 KB   
1190/4374 KB   24/139 KB   48/90 KB   659/663 KB   
1190/4374 KB   28/139 KB   48/90 KB   659/663 KB   
1190/4374 KB   32/139 KB   48/90 KB   659/663 KB   
1190/4374 KB   32/139 KB   48/90 KB   663/663 KB   
1190/4374 KB   32/139 KB   48/90 KB   663/663 KB   
1194/4374 KB   32/139 KB   48/90 KB   663/663 KB   
1198/4374 KB   32/139 KB   48/90 KB   663/663 KB   
1202/4374 KB   32/139 KB   48/90 KB   663/663 KB   
1206/4374 KB   32/139 KB   48/90 KB   663/663 KB   
1206/4374 KB   32/139 KB   52/90 KB   663/663 KB   
1206/4374 KB   32/139 KB   56/90 KB   663/663 KB   
1206/4374 KB   32/139 KB   60/90 KB   663/663 KB   
1206/4374 KB   32/139 KB   64/90 KB   663/663 KB   
1210/4374 KB   32/139 KB   64/90 KB   663/663 KB   
1214/4374 KB   32/139 KB   64/90 KB   663/663 KB   
1218/4374 KB   32/139 KB   64/90 KB   663/663 KB   
1222/4374 KB   32/139 KB   64/90 KB   663/663 KB   
1222/4374 KB   36/139 KB   64/90 KB   663/663 KB   
1222/4374 KB   40/139 KB   64/90 KB   663/663 KB   
1222/4374 KB   44/139 KB   64/90 KB   663/663 KB   
1222/4374 KB   44/139 KB   4/5 KB   64/90 KB   663/663 KB   
1222/4374 KB   48/139 KB   4/5 KB   64/90 KB   663/663 KB   
1222/4374 KB   48/139 KB   5/5 KB   64/90 KB   663/663 KB   
1226/4374 KB   48/139 KB   5/5 KB   64/90 KB   663/663 KB   
1230/4374 KB   48/139 KB   5/5 KB   64/90 KB   663/663 KB   
1234/4374 KB   48/139 KB   5/5 KB   64/90 KB   663/663 KB   
1238/4374 KB   48/139 KB   5/5 KB   64/90 KB   663/663 KB   
1238/4374 KB   48/139 KB   5/5 KB   68/90 KB   663/663 KB   
1238/4374 KB   48/139 KB   5/5 KB   72/90 KB   663/663 KB   
1238/4374 KB   48/139 KB   5/5 KB   76/90 KB   663/663 KB   
1238/4374 KB   48/139 KB   5/5 KB   80/90 KB   663/663 KB   
1238/4374 KB   52/139 KB   5/5 KB   80/90 KB   663/663 KB   
1238/4374 KB   56/139 KB   5/5 KB   80/90 KB   663/663 KB   
1238/4374 KB   60/139 KB   5/5 KB   80/90 KB   663/663 KB   
1238/4374 KB   64/139 KB   5/5 KB   80/90 KB   663/663 KB   
1238/4374 KB   64/139 KB   5/5 KB   84/90 KB   663/663 KB   
1238/4374 KB   64/139 KB   5/5 KB   88/90 KB   663/663 KB   
1238/4374 KB   64/139 KB   5/5 KB   90/90 KB   663/663 KB   
1242/4374 KB   64/139 KB   5/5 KB   90/90 KB   663/663 KB   
1246/4374 KB   64/139 KB   5/5 KB   90/90 KB   663/663 KB   
1250/4374 KB   64/139 KB   5/5 KB   90/90 KB   663/663 KB   
1254/4374 KB   64/139 KB   5/5 KB   90/90 KB   663/663 KB   
1254/4374 KB   68/139 KB   5/5 KB   90/90 KB   663/663 KB   
1254/4374 KB   72/139 KB   5/5 KB   90/90 KB   663/663 KB   
1254/4374 KB   76/139 KB   5/5 KB   90/90 KB   663/663 KB   
1254/4374 KB   80/139 KB   5/5 KB   90/90 KB   663/663 KB   
1258/4374 KB   80/139 KB   5/5 KB   90/90 KB   663/663 KB   
1262/4374 KB   80/139 KB   5/5 KB   90/90 KB   663/663 KB   
1266/4374 KB   80/139 KB   5/5 KB   90/90 KB   663/663 KB   
1270/4374 KB   80/139 KB   5/5 KB   90/90 KB   663/663 KB   
1274/4374 KB   80/139 KB   5/5 KB   90/90 KB   663/663 KB   
1278/4374 KB   80/139 KB   5/5 KB   90/90 KB   663/663 KB   
1282/4374 KB   80/139 KB   5/5 KB   90/90 KB   663/663 KB   
1286/4374 KB   80/139 KB   5/5 KB   90/90 KB   663/663 KB   
                                                            
Downloaded: https://repo.maven.apache.org/maven2/org/springframework/spring-test/5.2.2.RELEASE/spring-test-5.2.2.RELEASE.jar (663 KB at 994.6 KB/sec)
1286/4374 KB   84/139 KB   5/5 KB   90/90 KB                
1286/4374 KB   88/139 KB   5/5 KB   90/90 KB   
1286/4374 KB   92/139 KB   5/5 KB   90/90 KB   
1286/4374 KB   96/139 KB   5/5 KB   90/90 KB   
                                               
Downloaded: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-commons/1.5.2/junit-platform-commons-1.5.2.jar (90 KB at 133.7 KB/sec)
1290/4374 KB   96/139 KB   5/5 KB              
1294/4374 KB   96/139 KB   5/5 KB   
1298/4374 KB   96/139 KB   5/5 KB   
1302/4374 KB   96/139 KB   5/5 KB   
                                    
Downloaded: https://repo.maven.apache.org/maven2/org/mockito/mockito-junit-jupiter/3.1.0/mockito-junit-jupiter-3.1.0.jar (5 KB at 7.3 KB/sec)
1302/4374 KB   100/139 KB           
1302/4374 KB   104/139 KB   
1302/4374 KB   108/139 KB   
1306/4374 KB   108/139 KB   
1306/4374 KB   112/139 KB   
1310/4374 KB   112/139 KB   
1314/4374 KB   112/139 KB   
1318/4374 KB   112/139 KB   
1322/4374 KB   112/139 KB   
1326/4374 KB   112/139 KB   
1330/4374 KB   112/139 KB   
1330/4374 KB   116/139 KB   
1334/4374 KB   116/139 KB   
1334/4374 KB   120/139 KB   
1334/4374 KB   124/139 KB   
1334/4374 KB   128/139 KB   
1334/4374 KB   132/139 KB   
1334/4374 KB   136/139 KB   
1334/4374 KB   139/139 KB   
1338/4374 KB   139/139 KB   
1342/4374 KB   139/139 KB   
1346/4374 KB   139/139 KB   
1350/4374 KB   139/139 KB   
1354/4374 KB   139/139 KB   
1358/4374 KB   139/139 KB   
1362/4374 KB   139/139 KB   
1366/4374 KB   139/139 KB   
1370/4374 KB   139/139 KB   
1374/4374 KB   139/139 KB   
1378/4374 KB   139/139 KB   
1382/4374 KB   139/139 KB   
1386/4374 KB   139/139 KB   
1390/4374 KB   139/139 KB   
1392/4374 KB   139/139 KB   
1396/4374 KB   139/139 KB   
1400/4374 KB   139/139 KB   
1404/4374 KB   139/139 KB   
1408/4374 KB   139/139 KB   
1412/4374 KB   139/139 KB   
1416/4374 KB   139/139 KB   
1420/4374 KB   139/139 KB   
1424/4374 KB   139/139 KB   
1428/4374 KB   139/139 KB   
1432/4374 KB   139/139 KB   
1436/4374 KB   139/139 KB   
1440/4374 KB   139/139 KB   
                            
Downloaded: https://repo.maven.apache.org/maven2/org/junit/jupiter/junit-jupiter-api/5.5.2/junit-jupiter-api-5.5.2.jar (139 KB at 194.2 KB/sec)
1444/4374 KB                
1448/4374 KB   
1452/4374 KB   
1456/4374 KB   
1460/4374 KB   
1464/4374 KB   
1468/4374 KB   
1472/4374 KB   
1476/4374 KB   
1480/4374 KB   
1484/4374 KB   
1488/4374 KB   
1492/4374 KB   
1496/4374 KB   
1500/4374 KB   
1504/4374 KB   
1508/4374 KB   
1512/4374 KB   
1516/4374 KB   
1520/4374 KB   
1524/4374 KB   
1528/4374 KB   
1532/4374 KB   
1536/4374 KB   
1540/4374 KB   
1544/4374 KB   
1548/4374 KB   
1552/4374 KB   
1556/4374 KB   
1560/4374 KB   
1564/4374 KB   
1568/4374 KB   
1572/4374 KB   
1576/4374 KB   
1580/4374 KB   
1584/4374 KB   
1588/4374 KB   
1592/4374 KB   
1596/4374 KB   
1600/4374 KB   
1604/4374 KB   
1608/4374 KB   
1612/4374 KB   
1616/4374 KB   
1620/4374 KB   
1624/4374 KB   
1628/4374 KB   
1632/4374 KB   
1636/4374 KB   
1640/4374 KB   
1644/4374 KB   
1648/4374 KB   
1652/4374 KB   
1656/4374 KB   
1660/4374 KB   
1664/4374 KB   
1668/4374 KB   
1672/4374 KB   
1676/4374 KB   
1680/4374 KB   
1684/4374 KB   
1688/4374 KB   
1692/4374 KB   
1696/4374 KB   
1700/4374 KB   
1704/4374 KB   
1708/4374 KB   
1712/4374 KB   
1716/4374 KB   
1720/4374 KB   
1724/4374 KB   
1728/4374 KB   
1732/4374 KB   
1736/4374 KB   
1740/4374 KB   
1744/4374 KB   
1748/4374 KB   
1752/4374 KB   
1756/4374 KB   
1760/4374 KB   
1764/4374 KB   
1768/4374 KB   
1772/4374 KB   
1776/4374 KB   
1780/4374 KB   
1784/4374 KB   
1788/4374 KB   
1792/4374 KB   
1796/4374 KB   
1800/4374 KB   
1804/4374 KB   
1808/4374 KB   
1812/4374 KB   
1816/4374 KB   
1820/4374 KB   
1824/4374 KB   
1828/4374 KB   
1832/4374 KB   
1836/4374 KB   
1840/4374 KB   
1844/4374 KB   
1848/4374 KB   
1852/4374 KB   
1856/4374 KB   
1860/4374 KB   
1864/4374 KB   
1868/4374 KB   
1872/4374 KB   
1876/4374 KB   
1880/4374 KB   
1884/4374 KB   
1888/4374 KB   
1892/4374 KB   
1896/4374 KB   
1900/4374 KB   
1904/4374 KB   
1908/4374 KB   
1912/4374 KB   
1916/4374 KB   
1920/4374 KB   
1924/4374 KB   
1928/4374 KB   
1932/4374 KB   
1936/4374 KB   
1940/4374 KB   
1944/4374 KB   
1948/4374 KB   
1952/4374 KB   
1956/4374 KB   
1960/4374 KB   
1963/4374 KB   
1967/4374 KB   
1971/4374 KB   
1975/4374 KB   
1979/4374 KB   
1983/4374 KB   
1987/4374 KB   
1991/4374 KB   
1995/4374 KB   
1999/4374 KB   
2003/4374 KB   
2007/4374 KB   
2011/4374 KB   
2015/4374 KB   
2019/4374 KB   
2023/4374 KB   
2027/4374 KB   
2031/4374 KB   
2035/4374 KB   
2039/4374 KB   
2043/4374 KB   
2047/4374 KB   
2051/4374 KB   
2055/4374 KB   
2059/4374 KB   
2063/4374 KB   
2067/4374 KB   
2071/4374 KB   
2075/4374 KB   
2079/4374 KB   
2083/4374 KB   
2087/4374 KB   
2091/4374 KB   
2095/4374 KB   
2099/4374 KB   
2103/4374 KB   
2107/4374 KB   
2111/4374 KB   
2115/4374 KB   
2119/4374 KB   
2123/4374 KB   
2127/4374 KB   
2131/4374 KB   
2135/4374 KB   
2139/4374 KB   
2143/4374 KB   
2147/4374 KB   
2151/4374 KB   
2155/4374 KB   
2159/4374 KB   
2163/4374 KB   
2167/4374 KB   
2171/4374 KB   
2175/4374 KB   
2179/4374 KB   
2183/4374 KB   
2187/4374 KB   
2191/4374 KB   
2195/4374 KB   
2199/4374 KB   
2203/4374 KB   
2207/4374 KB   
2211/4374 KB   
2213/4374 KB   
2217/4374 KB   
2221/4374 KB   
2225/4374 KB   
2229/4374 KB   
2233/4374 KB   
2237/4374 KB   
2241/4374 KB   
2245/4374 KB   
2249/4374 KB   
2253/4374 KB   
2257/4374 KB   
2261/4374 KB   
2265/4374 KB   
2269/4374 KB   
2273/4374 KB   
2277/4374 KB   
2281/4374 KB   
2285/4374 KB   
2289/4374 KB   
2293/4374 KB   
2297/4374 KB   
2301/4374 KB   
2305/4374 KB   
2309/4374 KB   
2313/4374 KB   
2317/4374 KB   
2321/4374 KB   
2325/4374 KB   
2329/4374 KB   
2333/4374 KB   
2337/4374 KB   
2341/4374 KB   
2345/4374 KB   
2349/4374 KB   
2353/4374 KB   
2357/4374 KB   
2361/4374 KB   
2365/4374 KB   
2369/4374 KB   
2373/4374 KB   
2377/4374 KB   
2381/4374 KB   
2385/4374 KB   
2389/4374 KB   
2393/4374 KB   
2397/4374 KB   
2401/4374 KB   
2405/4374 KB   
2409/4374 KB   
2413/4374 KB   
2417/4374 KB   
2421/4374 KB   
2425/4374 KB   
2429/4374 KB   
2433/4374 KB   
2437/4374 KB   
2441/4374 KB   
2445/4374 KB   
2449/4374 KB   
2453/4374 KB   
2457/4374 KB   
2461/4374 KB   
2463/4374 KB   
2467/4374 KB   
2471/4374 KB   
2475/4374 KB   
2479/4374 KB   
2483/4374 KB   
2487/4374 KB   
2491/4374 KB   
2495/4374 KB   
2499/4374 KB   
2503/4374 KB   
2507/4374 KB   
2511/4374 KB   
2515/4374 KB   
2519/4374 KB   
2523/4374 KB   
2527/4374 KB   
2531/4374 KB   
2535/4374 KB   
2539/4374 KB   
2543/4374 KB   
2547/4374 KB   
2551/4374 KB   
2555/4374 KB   
2559/4374 KB   
2563/4374 KB   
2567/4374 KB   
2571/4374 KB   
2575/4374 KB   
2579/4374 KB   
2583/4374 KB   
2587/4374 KB   
2591/4374 KB   
2595/4374 KB   
2599/4374 KB   
2603/4374 KB   
2607/4374 KB   
2611/4374 KB   
2615/4374 KB   
2619/4374 KB   
2623/4374 KB   
2627/4374 KB   
2631/4374 KB   
2635/4374 KB   
2639/4374 KB   
2643/4374 KB   
2647/4374 KB   
2651/4374 KB   
2655/4374 KB   
2659/4374 KB   
2663/4374 KB   
2667/4374 KB   
2671/4374 KB   
2675/4374 KB   
2679/4374 KB   
2683/4374 KB   
2687/4374 KB   
2691/4374 KB   
2695/4374 KB   
2699/4374 KB   
2703/4374 KB   
2707/4374 KB   
2711/4374 KB   
2713/4374 KB   
2717/4374 KB   
2721/4374 KB   
2725/4374 KB   
2729/4374 KB   
2733/4374 KB   
2737/4374 KB   
2741/4374 KB   
2745/4374 KB   
2749/4374 KB   
2753/4374 KB   
2757/4374 KB   
2761/4374 KB   
2765/4374 KB   
2769/4374 KB   
2773/4374 KB   
2777/4374 KB   
2781/4374 KB   
2785/4374 KB   
2789/4374 KB   
2793/4374 KB   
2797/4374 KB   
2801/4374 KB   
2805/4374 KB   
2809/4374 KB   
2813/4374 KB   
2817/4374 KB   
2821/4374 KB   
2825/4374 KB   
2829/4374 KB   
2833/4374 KB   
2837/4374 KB   
2841/4374 KB   
2845/4374 KB   
2849/4374 KB   
2853/4374 KB   
2857/4374 KB   
2861/4374 KB   
2865/4374 KB   
2869/4374 KB   
2873/4374 KB   
2877/4374 KB   
2881/4374 KB   
2885/4374 KB   
2889/4374 KB   
2893/4374 KB   
2897/4374 KB   
2901/4374 KB   
2905/4374 KB   
2909/4374 KB   
2913/4374 KB   
2917/4374 KB   
2921/4374 KB   
2925/4374 KB   
2929/4374 KB   
2933/4374 KB   
2937/4374 KB   
2941/4374 KB   
2945/4374 KB   
2949/4374 KB   
2953/4374 KB   
2957/4374 KB   
2961/4374 KB   
2965/4374 KB   
2969/4374 KB   
2973/4374 KB   
2977/4374 KB   
2981/4374 KB   
2985/4374 KB   
2989/4374 KB   
2993/4374 KB   
2997/4374 KB   
3001/4374 KB   
3005/4374 KB   
3009/4374 KB   
3013/4374 KB   
3017/4374 KB   
3021/4374 KB   
3025/4374 KB   
3029/4374 KB   
3033/4374 KB   
3037/4374 KB   
3041/4374 KB   
3045/4374 KB   
3049/4374 KB   
3053/4374 KB   
3057/4374 KB   
3061/4374 KB   
3065/4374 KB   
3069/4374 KB   
3073/4374 KB   
3077/4374 KB   
3081/4374 KB   
3085/4374 KB   
3089/4374 KB   
3093/4374 KB   
3097/4374 KB   
3101/4374 KB   
3105/4374 KB   
3109/4374 KB   
3113/4374 KB   
3117/4374 KB   
3121/4374 KB   
3125/4374 KB   
3129/4374 KB   
3133/4374 KB   
3137/4374 KB   
3141/4374 KB   
3145/4374 KB   
3149/4374 KB   
3153/4374 KB   
3157/4374 KB   
3161/4374 KB   
3165/4374 KB   
3169/4374 KB   
3173/4374 KB   
3177/4374 KB   
3181/4374 KB   
3185/4374 KB   
3189/4374 KB   
3193/4374 KB   
3197/4374 KB   
3201/4374 KB   
3205/4374 KB   
3209/4374 KB   
3212/4374 KB   
3216/4374 KB   
3220/4374 KB   
3224/4374 KB   
3228/4374 KB   
3232/4374 KB   
3236/4374 KB   
3240/4374 KB   
3244/4374 KB   
3248/4374 KB   
3252/4374 KB   
3256/4374 KB   
3260/4374 KB   
3264/4374 KB   
3268/4374 KB   
3272/4374 KB   
3276/4374 KB   
3280/4374 KB   
3284/4374 KB   
3288/4374 KB   
3292/4374 KB   
3296/4374 KB   
3300/4374 KB   
3304/4374 KB   
3308/4374 KB   
3312/4374 KB   
3316/4374 KB   
3320/4374 KB   
3324/4374 KB   
3328/4374 KB   
3332/4374 KB   
3336/4374 KB   
3340/4374 KB   
3344/4374 KB   
3348/4374 KB   
3352/4374 KB   
3356/4374 KB   
3360/4374 KB   
3364/4374 KB   
3368/4374 KB   
3372/4374 KB   
3376/4374 KB   
3380/4374 KB   
3384/4374 KB   
3388/4374 KB   
3392/4374 KB   
3396/4374 KB   
3400/4374 KB   
3404/4374 KB   
3408/4374 KB   
3412/4374 KB   
3416/4374 KB   
3420/4374 KB   
3424/4374 KB   
3428/4374 KB   
3432/4374 KB   
3436/4374 KB   
3440/4374 KB   
3444/4374 KB   
3448/4374 KB   
3452/4374 KB   
3456/4374 KB   
3460/4374 KB   
3464/4374 KB   
3468/4374 KB   
3472/4374 KB   
3476/4374 KB   
3480/4374 KB   
3484/4374 KB   
3488/4374 KB   
3492/4374 KB   
3496/4374 KB   
3500/4374 KB   
3504/4374 KB   
3508/4374 KB   
3512/4374 KB   
3516/4374 KB   
3520/4374 KB   
3524/4374 KB   
3528/4374 KB   
3532/4374 KB   
3536/4374 KB   
3540/4374 KB   
3544/4374 KB   
3548/4374 KB   
3552/4374 KB   
3556/4374 KB   
3560/4374 KB   
3564/4374 KB   
3568/4374 KB   
3572/4374 KB   
3576/4374 KB   
3580/4374 KB   
3584/4374 KB   
3588/4374 KB   
3592/4374 KB   
3596/4374 KB   
3600/4374 KB   
3604/4374 KB   
3608/4374 KB   
3612/4374 KB   
3616/4374 KB   
3620/4374 KB   
3624/4374 KB   
3628/4374 KB   
3632/4374 KB   
3636/4374 KB   
3640/4374 KB   
3644/4374 KB   
3648/4374 KB   
3652/4374 KB   
3656/4374 KB   
3660/4374 KB   
3664/4374 KB   
3668/4374 KB   
3672/4374 KB   
3676/4374 KB   
3680/4374 KB   
3684/4374 KB   
3688/4374 KB   
3692/4374 KB   
3696/4374 KB   
3700/4374 KB   
3704/4374 KB   
3708/4374 KB   
3712/4374 KB   
3716/4374 KB   
3720/4374 KB   
3724/4374 KB   
3728/4374 KB   
3732/4374 KB   
3736/4374 KB   
3740/4374 KB   
3744/4374 KB   
3748/4374 KB   
3752/4374 KB   
3756/4374 KB   
3760/4374 KB   
3764/4374 KB   
3768/4374 KB   
3772/4374 KB   
3776/4374 KB   
3780/4374 KB   
3784/4374 KB   
3788/4374 KB   
3792/4374 KB   
3796/4374 KB   
3800/4374 KB   
3804/4374 KB   
3808/4374 KB   
3812/4374 KB   
3816/4374 KB   
3820/4374 KB   
3824/4374 KB   
3828/4374 KB   
3832/4374 KB   
3836/4374 KB   
3840/4374 KB   
3844/4374 KB   
3848/4374 KB   
3852/4374 KB   
3856/4374 KB   
3860/4374 KB   
3864/4374 KB   
3868/4374 KB   
3872/4374 KB   
3876/4374 KB   
3880/4374 KB   
3884/4374 KB   
3888/4374 KB   
3892/4374 KB   
3896/4374 KB   
3900/4374 KB   
3904/4374 KB   
3908/4374 KB   
3912/4374 KB   
3916/4374 KB   
3920/4374 KB   
3924/4374 KB   
3928/4374 KB   
3932/4374 KB   
3936/4374 KB   
3940/4374 KB   
3944/4374 KB   
3948/4374 KB   
3952/4374 KB   
3956/4374 KB   
3960/4374 KB   
3964/4374 KB   
3968/4374 KB   
3972/4374 KB   
3976/4374 KB   
3980/4374 KB   
3984/4374 KB   
3988/4374 KB   
3992/4374 KB   
3996/4374 KB   
4000/4374 KB   
4004/4374 KB   
4008/4374 KB   
4012/4374 KB   
4016/4374 KB   
4020/4374 KB   
4024/4374 KB   
4028/4374 KB   
4032/4374 KB   
4036/4374 KB   
4040/4374 KB   
4044/4374 KB   
4048/4374 KB   
4052/4374 KB   
4056/4374 KB   
4060/4374 KB   
4064/4374 KB   
4068/4374 KB   
4072/4374 KB   
4076/4374 KB   
4080/4374 KB   
4084/4374 KB   
4088/4374 KB   
4092/4374 KB   
4096/4374 KB   
4100/4374 KB   
4104/4374 KB   
4108/4374 KB   
4112/4374 KB   
4116/4374 KB   
4120/4374 KB   
4124/4374 KB   
4128/4374 KB   
4132/4374 KB   
4136/4374 KB   
4140/4374 KB   
4144/4374 KB   
4148/4374 KB   
4152/4374 KB   
4156/4374 KB   
4160/4374 KB   
4164/4374 KB   
4168/4374 KB   
4172/4374 KB   
4176/4374 KB   
4180/4374 KB   
4184/4374 KB   
4188/4374 KB   
4192/4374 KB   
4196/4374 KB   
4200/4374 KB   
4204/4374 KB   
4208/4374 KB   
4212/4374 KB   
4216/4374 KB   
4220/4374 KB   
4224/4374 KB   
4228/4374 KB   
4232/4374 KB   
4236/4374 KB   
4240/4374 KB   
4244/4374 KB   
4248/4374 KB   
4252/4374 KB   
4256/4374 KB   
4260/4374 KB   
4264/4374 KB   
4268/4374 KB   
4272/4374 KB   
4276/4374 KB   
4280/4374 KB   
4283/4374 KB   
4287/4374 KB   
4291/4374 KB   
4295/4374 KB   
4299/4374 KB   
4303/4374 KB   
4307/4374 KB   
4311/4374 KB   
4315/4374 KB   
4319/4374 KB   
4323/4374 KB   
4327/4374 KB   
4331/4374 KB   
4335/4374 KB   
4339/4374 KB   
4343/4374 KB   
4347/4374 KB   
4351/4374 KB   
4355/4374 KB   
4359/4374 KB   
4363/4374 KB   
4367/4374 KB   
4371/4374 KB   
4374/4374 KB   
               
Downloaded: https://repo.maven.apache.org/maven2/org/assertj/assertj-core/3.13.2/assertj-core-3.13.2.jar (4374 KB at 2803.4 KB/sec)
[INFO] 
[INFO] --- maven-clean-plugin:3.1.0:clean (default-clean) @ spring-petclinic ---
[INFO] Deleting /var/jenkins_home/workspace/spring-petclinic-hub/target
[INFO] 
[INFO] --- jacoco-maven-plugin:0.8.5:prepare-agent (default) @ spring-petclinic ---
[INFO] argLine set to -javaagent:/root/.m2/repository/org/jacoco/org.jacoco.agent/0.8.5/org.jacoco.agent-0.8.5-runtime.jar=destfile=/var/jenkins_home/workspace/spring-petclinic-hub/target/jacoco.exec
[INFO] 
[INFO] --- git-commit-id-plugin:3.0.1:revision (default) @ spring-petclinic ---
[INFO] dotGitDirectory /var/jenkins_home/workspace/spring-petclinic-hub/.git
[INFO] Collected git.build.user.name with value 
[INFO] Collected git.build.user.email with value 
[INFO] Using environment variable based branch name. GIT_BRANCH = origin/master
[INFO] Collected git.branch with value origin/master
[INFO] --always = true
[INFO] --dirty = -dirty
[INFO] --abbrev = 7
[INFO] Tag refs [[Ref[refs/tags/1.5.x=c36452a2c34443ae26b4ecbba4f149906af14717]]]
[INFO] Created map: [{}]
[INFO] evalCommit is [029e3b186598e6ef4bc163ada1d2dd64a4797b26]
[INFO] Collected git.commit.id.describe with value 029e3b1
[INFO] Collected git.commit.id.describe-short with value 029e3b1
[INFO] Collected git.commit.id with value 029e3b186598e6ef4bc163ada1d2dd64a4797b26
[INFO] Collected git.commit.id.abbrev with value 029e3b1
[INFO] Collected git.dirty with value false
[INFO] Collected git.commit.user.name with value Tal Yitzhak
[INFO] Collected git.commit.user.email with value talyitzhak100@gmail.com
[INFO] Collected git.commit.message.full with value Update Jenkinsfile
[INFO] Collected git.commit.message.short with value Update Jenkinsfile
[INFO] Collected git.commit.time with value 2020-03-29T09:09:29+0000
[INFO] Collected git.remote.origin.url with value https://github.com/talitz/spring-petclinic-jenkins-pipeline.git
[INFO] Collected git.tags with value 
[INFO] evalCommit is [029e3b186598e6ef4bc163ada1d2dd64a4797b26]
[INFO] Tag refs [[Ref[refs/tags/1.5.x=c36452a2c34443ae26b4ecbba4f149906af14717]]]
[INFO] Created map: [{}]
[INFO] Collected git.closest.tag.name with value 
[INFO] evalCommit is [029e3b186598e6ef4bc163ada1d2dd64a4797b26]
[INFO] Tag refs [[Ref[refs/tags/1.5.x=c36452a2c34443ae26b4ecbba4f149906af14717]]]
[INFO] Created map: [{}]
[INFO] Collected git.closest.tag.commit.count with value 
[INFO] Collected git.total.commit.count with value 44
[INFO] Collected git.local.branch.ahead with value NO_REMOTE
[INFO] Collected git.local.branch.behind with value NO_REMOTE
[INFO] Collected git.build.time with value 2023-06-16T14:04:34+0000
[INFO] Collected git.build.version with value 2.2.0.BUILD-SNAPSHOT
[INFO] Collected git.build.host with value 3467ac7d3468
[INFO] Collected git.build.number with value 19
[INFO] including property git.build.user.email in results
[INFO] including property git.build.host in results
[INFO] including property git.dirty in results
[INFO] including property git.local.branch.behind in results
[INFO] including property git.remote.origin.url in results
[INFO] including property git.closest.tag.name in results
[INFO] including property git.local.branch.ahead in results
[INFO] including property git.total.commit.count in results
[INFO] including property git.commit.id.describe-short in results
[INFO] including property git.commit.user.email in results
[INFO] including property git.commit.time in results
[INFO] including property git.commit.message.full in results
[INFO] including property git.build.version in results
[INFO] including property git.commit.message.short in results
[INFO] including property git.commit.id.abbrev in results
[INFO] including property git.branch in results
[INFO] including property git.build.user.name in results
[INFO] including property git.build.number in results
[INFO] including property git.closest.tag.commit.count in results
[INFO] including property git.commit.id.describe in results
[INFO] including property git.commit.id in results
[INFO] including property git.tags in results
[INFO] including property git.build.time in results
[INFO] including property git.commit.user.name in results
[INFO] Writing properties file to [/var/jenkins_home/workspace/spring-petclinic-hub/target/classes/git.properties] (for module petclinic)...
[INFO] 
[INFO] --- spring-boot-maven-plugin:2.2.2.RELEASE:build-info (default) @ spring-petclinic ---
[INFO] 
[INFO] --- wro4j-maven-plugin:1.8.0:run (default) @ spring-petclinic ---
[INFO] /var/jenkins_home/workspace/spring-petclinic-hub/src/main/less
[INFO] Executing the mojo: 
[INFO] Wro4j Model path: /var/jenkins_home/workspace/spring-petclinic-hub/src/main/wro/wro.xml
[INFO] targetGroups: null
[INFO] minimize: true
[INFO] ignoreMissingResources: null
[INFO] parallelProcessing: false
[INFO] buildDirectory: /var/jenkins_home/workspace/spring-petclinic-hub/target
[INFO] destinationFolder: /var/jenkins_home/workspace/spring-petclinic-hub/target
[INFO] cssDestinationFolder: /var/jenkins_home/workspace/spring-petclinic-hub/target/classes/static/resources/css
[INFO] The following groups will be processed: [petclinic]
[INFO] folder: /var/jenkins_home/workspace/spring-petclinic-hub/target/classes/static/resources/css
[INFO] processing group: petclinic.css
[WARNING] Less warnings are:
[WARNING] 10:1 Cannot link source map. Css result location is not know and could not be deduced from input less source..
[INFO] file size: petclinic.css -> 152399 bytes
[INFO] /var/jenkins_home/workspace/spring-petclinic-hub/target/classes/static/resources/css/petclinic.css (152399 bytes)
[INFO] folder: /var/jenkins_home/workspace/spring-petclinic-hub/target
[INFO] processing group: petclinic.js
[INFO] 
[INFO] --- maven-resources-plugin:3.1.0:resources (default-resources) @ spring-petclinic ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] Copying 2 resources
[INFO] Copying 35 resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.8.1:compile (default-compile) @ spring-petclinic ---
[INFO] Changes detected - recompiling the module!
[INFO] Compiling 25 source files to /var/jenkins_home/workspace/spring-petclinic-hub/target/classes
[INFO] 
[INFO] --- maven-resources-plugin:3.1.0:testResources (default-testResources) @ spring-petclinic ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] skip non existing resourceDirectory /var/jenkins_home/workspace/spring-petclinic-hub/src/test/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.8.1:testCompile (default-testCompile) @ spring-petclinic ---
[INFO] Changes detected - recompiling the module!
[INFO] Compiling 11 source files to /var/jenkins_home/workspace/spring-petclinic-hub/target/test-classes
[INFO] 
[INFO] --- maven-surefire-plugin:2.22.2:test (default-test) @ spring-petclinic ---
Downloading: https://repo.spring.io/snapshot/org/apache/maven/surefire/maven-surefire-common/2.22.2/maven-surefire-common-2.22.2.pom
               
Downloading: https://repo.spring.io/milestone/org/apache/maven/surefire/maven-surefire-common/2.22.2/maven-surefire-common-2.22.2.pom
               
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/maven-surefire-common/2.22.2/maven-surefire-common-2.22.2.pom
4/12 KB        
8/12 KB   
12/12 KB   
           
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/maven-surefire-common/2.22.2/maven-surefire-common-2.22.2.pom (12 KB at 302.3 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/plugin-tools/maven-plugin-annotations/3.5.2/maven-plugin-annotations-3.5.2.pom
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/plugin-tools/maven-plugin-annotations/3.5.2/maven-plugin-annotations-3.5.2.pom
           
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/plugin-tools/maven-plugin-annotations/3.5.2/maven-plugin-annotations-3.5.2.pom
2/2 KB     
         
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/plugin-tools/maven-plugin-annotations/3.5.2/maven-plugin-annotations-3.5.2.pom (2 KB at 49.8 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/plugin-tools/maven-plugin-tools/3.5.2/maven-plugin-tools-3.5.2.pom
         
Downloading: https://repo.spring.io/milestone/org/apache/maven/plugin-tools/maven-plugin-tools/3.5.2/maven-plugin-tools-3.5.2.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/plugin-tools/maven-plugin-tools/3.5.2/maven-plugin-tools-3.5.2.pom
4/16 KB   
8/16 KB   
12/16 KB   
16/16 KB   
           
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/plugin-tools/maven-plugin-tools/3.5.2/maven-plugin-tools-3.5.2.pom (16 KB at 405.5 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/surefire/surefire-api/2.22.2/surefire-api-2.22.2.pom
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/surefire/surefire-api/2.22.2/surefire-api-2.22.2.pom
           
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-api/2.22.2/surefire-api-2.22.2.pom
4/4 KB     
         
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-api/2.22.2/surefire-api-2.22.2.pom (4 KB at 123.5 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/surefire/surefire-logger-api/2.22.2/surefire-logger-api-2.22.2.pom
         
Downloading: https://repo.spring.io/milestone/org/apache/maven/surefire/surefire-logger-api/2.22.2/surefire-logger-api-2.22.2.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-logger-api/2.22.2/surefire-logger-api-2.22.2.pom
2/2 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-logger-api/2.22.2/surefire-logger-api-2.22.2.pom (2 KB at 76.6 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/surefire/surefire-booter/2.22.2/surefire-booter-2.22.2.pom
         
Downloading: https://repo.spring.io/milestone/org/apache/maven/surefire/surefire-booter/2.22.2/surefire-booter-2.22.2.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-booter/2.22.2/surefire-booter-2.22.2.pom
4/8 KB   
8/8 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-booter/2.22.2/surefire-booter-2.22.2.pom (8 KB at 234.8 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/hamcrest/hamcrest-core/1.3/hamcrest-core-1.3.pom
         
Downloading: https://repo.spring.io/milestone/org/hamcrest/hamcrest-core/1.3/hamcrest-core-1.3.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-core/1.3/hamcrest-core-1.3.pom
766/766 B   
            
Downloaded: https://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-core/1.3/hamcrest-core-1.3.pom (766 B at 25.8 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/hamcrest/hamcrest-parent/1.3/hamcrest-parent-1.3.pom
            
Downloading: https://repo.spring.io/milestone/org/hamcrest/hamcrest-parent/1.3/hamcrest-parent-1.3.pom
            
Downloading: https://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-parent/1.3/hamcrest-parent-1.3.pom
2/2 KB      
         
Downloaded: https://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-parent/1.3/hamcrest-parent-1.3.pom (2 KB at 66.4 KB/sec)
Downloading: https://repo.spring.io/snapshot/classworlds/classworlds/1.1/classworlds-1.1.pom
         
Downloading: https://repo.spring.io/milestone/classworlds/classworlds/1.1/classworlds-1.1.pom
         
Downloading: https://repo.maven.apache.org/maven2/classworlds/classworlds/1.1/classworlds-1.1.pom
4/4 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/classworlds/classworlds/1.1/classworlds-1.1.pom (4 KB at 111.9 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/maven-toolchain/2.2.1/maven-toolchain-2.2.1.pom
         
Downloading: https://repo.spring.io/milestone/org/apache/maven/maven-toolchain/2.2.1/maven-toolchain-2.2.1.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/maven-toolchain/2.2.1/maven-toolchain-2.2.1.pom
4/4 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/maven-toolchain/2.2.1/maven-toolchain-2.2.1.pom (4 KB at 99.0 KB/sec)
Downloading: https://repo.spring.io/snapshot/com/thoughtworks/qdox/qdox/2.0-M8/qdox-2.0-M8.pom
         
Downloading: https://repo.spring.io/milestone/com/thoughtworks/qdox/qdox/2.0-M8/qdox-2.0-M8.pom
         
Downloading: https://repo.maven.apache.org/maven2/com/thoughtworks/qdox/qdox/2.0-M8/qdox-2.0-M8.pom
4/16 KB   
8/16 KB   
12/16 KB   
16/16 KB   
           
Downloaded: https://repo.maven.apache.org/maven2/com/thoughtworks/qdox/qdox/2.0-M8/qdox-2.0-M8.pom (16 KB at 368.4 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/surefire/maven-surefire-common/2.22.2/maven-surefire-common-2.22.2.jar
Downloading: https://repo.spring.io/snapshot/org/apache/maven/maven-plugin-api/2.2.1/maven-plugin-api-2.2.1.jar
Downloading: https://repo.spring.io/snapshot/org/apache/maven/plugin-tools/maven-plugin-annotations/3.5.2/maven-plugin-annotations-3.5.2.jar
Downloading: https://repo.spring.io/snapshot/org/apache/maven/surefire/surefire-api/2.22.2/surefire-api-2.22.2.jar
Downloading: https://repo.spring.io/snapshot/org/apache/maven/surefire/surefire-logger-api/2.22.2/surefire-logger-api-2.22.2.jar
           
Downloading: https://repo.spring.io/snapshot/org/apache/maven/surefire/surefire-booter/2.22.2/surefire-booter-2.22.2.jar
           
Downloading: https://repo.spring.io/snapshot/org/apache/maven/maven-artifact/2.2.1/maven-artifact-2.2.1.jar
           
Downloading: https://repo.spring.io/snapshot/org/codehaus/plexus/plexus-utils/1.5.15/plexus-utils-1.5.15.jar
           
Downloading: https://repo.spring.io/snapshot/org/apache/maven/maven-plugin-descriptor/2.2.1/maven-plugin-descriptor-2.2.1.jar
           
Downloading: https://repo.spring.io/snapshot/org/codehaus/plexus/plexus-container-default/1.0-alpha-9-stable-1/plexus-container-default-1.0-alpha-9-stable-1.jar
           
Downloading: https://repo.spring.io/snapshot/junit/junit/4.12/junit-4.12.jar
           
Downloading: https://repo.spring.io/snapshot/org/hamcrest/hamcrest-core/1.3/hamcrest-core-1.3.jar
           
Downloading: https://repo.spring.io/snapshot/org/apache/maven/maven-project/2.2.1/maven-project-2.2.1.jar
           
Downloading: https://repo.spring.io/snapshot/org/apache/maven/maven-settings/2.2.1/maven-settings-2.2.1.jar
           
Downloading: https://repo.spring.io/snapshot/org/apache/maven/maven-profile/2.2.1/maven-profile-2.2.1.jar
           
Downloading: https://repo.spring.io/snapshot/org/apache/maven/maven-artifact-manager/2.2.1/maven-artifact-manager-2.2.1.jar
           
Downloading: https://repo.spring.io/snapshot/backport-util-concurrent/backport-util-concurrent/3.1/backport-util-concurrent-3.1.jar
           
Downloading: https://repo.spring.io/snapshot/org/apache/maven/maven-plugin-registry/2.2.1/maven-plugin-registry-2.2.1.jar
           
Downloading: https://repo.spring.io/snapshot/org/codehaus/plexus/plexus-interpolation/1.11/plexus-interpolation-1.11.jar
           
Downloading: https://repo.spring.io/snapshot/org/apache/maven/maven-model/2.2.1/maven-model-2.2.1.jar
           
Downloading: https://repo.spring.io/snapshot/org/apache/maven/maven-core/2.2.1/maven-core-2.2.1.jar
           
Downloading: https://repo.spring.io/snapshot/org/apache/maven/maven-plugin-parameter-documenter/2.2.1/maven-plugin-parameter-documenter-2.2.1.jar
           
Downloading: https://repo.spring.io/snapshot/org/slf4j/slf4j-jdk14/1.5.6/slf4j-jdk14-1.5.6.jar
           
Downloading: https://repo.spring.io/snapshot/org/slf4j/slf4j-api/1.5.6/slf4j-api-1.5.6.jar
           
Downloading: https://repo.spring.io/snapshot/org/slf4j/jcl-over-slf4j/1.5.6/jcl-over-slf4j-1.5.6.jar
           
Downloading: https://repo.spring.io/snapshot/org/apache/maven/maven-repository-metadata/2.2.1/maven-repository-metadata-2.2.1.jar
           
Downloading: https://repo.spring.io/snapshot/org/apache/maven/maven-error-diagnostics/2.2.1/maven-error-diagnostics-2.2.1.jar
           
Downloading: https://repo.spring.io/snapshot/org/apache/maven/maven-monitor/2.2.1/maven-monitor-2.2.1.jar
           
Downloading: https://repo.spring.io/snapshot/classworlds/classworlds/1.1/classworlds-1.1.jar
           
Downloading: https://repo.spring.io/snapshot/org/apache/maven/maven-toolchain/2.2.1/maven-toolchain-2.2.1.jar
           
Downloading: https://repo.spring.io/snapshot/com/thoughtworks/qdox/qdox/2.0-M8/qdox-2.0-M8.jar
           
           
           
           
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/surefire/maven-surefire-common/2.22.2/maven-surefire-common-2.22.2.jar
Downloading: https://repo.spring.io/milestone/org/apache/maven/maven-plugin-api/2.2.1/maven-plugin-api-2.2.1.jar
Downloading: https://repo.spring.io/milestone/org/apache/maven/plugin-tools/maven-plugin-annotations/3.5.2/maven-plugin-annotations-3.5.2.jar
Downloading: https://repo.spring.io/milestone/org/apache/maven/surefire/surefire-api/2.22.2/surefire-api-2.22.2.jar
Downloading: https://repo.spring.io/milestone/org/apache/maven/surefire/surefire-logger-api/2.22.2/surefire-logger-api-2.22.2.jar
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/surefire/surefire-booter/2.22.2/surefire-booter-2.22.2.jar
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/maven-artifact/2.2.1/maven-artifact-2.2.1.jar
           
Downloading: https://repo.spring.io/milestone/org/codehaus/plexus/plexus-utils/1.5.15/plexus-utils-1.5.15.jar
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/maven-plugin-descriptor/2.2.1/maven-plugin-descriptor-2.2.1.jar
           
Downloading: https://repo.spring.io/milestone/org/codehaus/plexus/plexus-container-default/1.0-alpha-9-stable-1/plexus-container-default-1.0-alpha-9-stable-1.jar
           
Downloading: https://repo.spring.io/milestone/junit/junit/4.12/junit-4.12.jar
           
Downloading: https://repo.spring.io/milestone/org/hamcrest/hamcrest-core/1.3/hamcrest-core-1.3.jar
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/maven-project/2.2.1/maven-project-2.2.1.jar
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/maven-settings/2.2.1/maven-settings-2.2.1.jar
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/maven-profile/2.2.1/maven-profile-2.2.1.jar
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/maven-artifact-manager/2.2.1/maven-artifact-manager-2.2.1.jar
           
Downloading: https://repo.spring.io/milestone/backport-util-concurrent/backport-util-concurrent/3.1/backport-util-concurrent-3.1.jar
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/maven-plugin-registry/2.2.1/maven-plugin-registry-2.2.1.jar
           
Downloading: https://repo.spring.io/milestone/org/codehaus/plexus/plexus-interpolation/1.11/plexus-interpolation-1.11.jar
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/maven-model/2.2.1/maven-model-2.2.1.jar
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/maven-core/2.2.1/maven-core-2.2.1.jar
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/maven-plugin-parameter-documenter/2.2.1/maven-plugin-parameter-documenter-2.2.1.jar
           
Downloading: https://repo.spring.io/milestone/org/slf4j/slf4j-jdk14/1.5.6/slf4j-jdk14-1.5.6.jar
           
Downloading: https://repo.spring.io/milestone/org/slf4j/slf4j-api/1.5.6/slf4j-api-1.5.6.jar
           
Downloading: https://repo.spring.io/milestone/org/slf4j/jcl-over-slf4j/1.5.6/jcl-over-slf4j-1.5.6.jar
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/maven-repository-metadata/2.2.1/maven-repository-metadata-2.2.1.jar
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/maven-error-diagnostics/2.2.1/maven-error-diagnostics-2.2.1.jar
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/maven-monitor/2.2.1/maven-monitor-2.2.1.jar
           
Downloading: https://repo.spring.io/milestone/classworlds/classworlds/1.1/classworlds-1.1.jar
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/maven-toolchain/2.2.1/maven-toolchain-2.2.1.jar
           
Downloading: https://repo.spring.io/milestone/com/thoughtworks/qdox/qdox/2.0-M8/qdox-2.0-M8.jar
           
           
           
           
           
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/maven-surefire-common/2.22.2/maven-surefire-common-2.22.2.jar
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-api/2.2.1/maven-plugin-api-2.2.1.jar
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/plugin-tools/maven-plugin-annotations/3.5.2/maven-plugin-annotations-3.5.2.jar
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-api/2.22.2/surefire-api-2.22.2.jar
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-logger-api/2.22.2/surefire-logger-api-2.22.2.jar
4/516 KB   
8/516 KB   
12/516 KB   
16/516 KB   
16/516 KB   4/13 KB   
16/516 KB   8/13 KB   
16/516 KB   12/13 KB   
16/516 KB   13/13 KB   
20/516 KB   13/13 KB   
24/516 KB   13/13 KB   
28/516 KB   13/13 KB   
32/516 KB   13/13 KB   
32/516 KB   4/14 KB   13/13 KB   
32/516 KB   8/14 KB   13/13 KB   
32/516 KB   12/14 KB   13/13 KB   
32/516 KB   14/14 KB   13/13 KB   
4/182 KB   32/516 KB   14/14 KB   13/13 KB   
8/182 KB   32/516 KB   14/14 KB   13/13 KB   
12/182 KB   32/516 KB   14/14 KB   13/13 KB   
16/182 KB   32/516 KB   14/14 KB   13/13 KB   
16/182 KB   36/516 KB   14/14 KB   13/13 KB   
16/182 KB   40/516 KB   14/14 KB   13/13 KB   
16/182 KB   44/516 KB   14/14 KB   13/13 KB   
16/182 KB   48/516 KB   14/14 KB   13/13 KB   
16/182 KB   48/516 KB   4/14 KB   14/14 KB   13/13 KB   
16/182 KB   48/516 KB   8/14 KB   14/14 KB   13/13 KB   
16/182 KB   48/516 KB   12/14 KB   14/14 KB   13/13 KB   
16/182 KB   48/516 KB   14/14 KB   14/14 KB   13/13 KB   
16/182 KB   52/516 KB   14/14 KB   14/14 KB   13/13 KB   
16/182 KB   56/516 KB   14/14 KB   14/14 KB   13/13 KB   
16/182 KB   60/516 KB   14/14 KB   14/14 KB   13/13 KB   
16/182 KB   64/516 KB   14/14 KB   14/14 KB   13/13 KB   
20/182 KB   64/516 KB   14/14 KB   14/14 KB   13/13 KB   
24/182 KB   64/516 KB   14/14 KB   14/14 KB   13/13 KB   
28/182 KB   64/516 KB   14/14 KB   14/14 KB   13/13 KB   
32/182 KB   64/516 KB   14/14 KB   14/14 KB   13/13 KB   
32/182 KB   68/516 KB   14/14 KB   14/14 KB   13/13 KB   
32/182 KB   72/516 KB   14/14 KB   14/14 KB   13/13 KB   
32/182 KB   76/516 KB   14/14 KB   14/14 KB   13/13 KB   
32/182 KB   80/516 KB   14/14 KB   14/14 KB   13/13 KB   
36/182 KB   80/516 KB   14/14 KB   14/14 KB   13/13 KB   
40/182 KB   80/516 KB   14/14 KB   14/14 KB   13/13 KB   
44/182 KB   80/516 KB   14/14 KB   14/14 KB   13/13 KB   
48/182 KB   80/516 KB   14/14 KB   14/14 KB   13/13 KB   
48/182 KB   84/516 KB   14/14 KB   14/14 KB   13/13 KB   
48/182 KB   88/516 KB   14/14 KB   14/14 KB   13/13 KB   
48/182 KB   92/516 KB   14/14 KB   14/14 KB   13/13 KB   
48/182 KB   96/516 KB   14/14 KB   14/14 KB   13/13 KB   
52/182 KB   96/516 KB   14/14 KB   14/14 KB   13/13 KB   
56/182 KB   96/516 KB   14/14 KB   14/14 KB   13/13 KB   
60/182 KB   96/516 KB   14/14 KB   14/14 KB   13/13 KB   
64/182 KB   96/516 KB   14/14 KB   14/14 KB   13/13 KB   
64/182 KB   100/516 KB   14/14 KB   14/14 KB   13/13 KB   
64/182 KB   104/516 KB   14/14 KB   14/14 KB   13/13 KB   
64/182 KB   108/516 KB   14/14 KB   14/14 KB   13/13 KB   
64/182 KB   112/516 KB   14/14 KB   14/14 KB   13/13 KB   
                                                          
                                                          
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-logger-api/2.22.2/surefire-logger-api-2.22.2.jar (14 KB at 228.7 KB/sec)
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-api/2.2.1/maven-plugin-api-2.2.1.jar (13 KB at 180.4 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-booter/2.22.2/surefire-booter-2.22.2.jar
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact/2.2.1/maven-artifact-2.2.1.jar
68/182 KB   112/516 KB   14/14 KB                         
72/182 KB   112/516 KB   14/14 KB   
76/182 KB   112/516 KB   14/14 KB   
80/182 KB   112/516 KB   14/14 KB   
80/182 KB   116/516 KB   14/14 KB   
80/182 KB   120/516 KB   14/14 KB   
80/182 KB   124/516 KB   14/14 KB   
80/182 KB   128/516 KB   14/14 KB   
84/182 KB   128/516 KB   14/14 KB   
88/182 KB   128/516 KB   14/14 KB   
92/182 KB   128/516 KB   14/14 KB   
96/182 KB   128/516 KB   14/14 KB   
96/182 KB   132/516 KB   14/14 KB   
96/182 KB   136/516 KB   14/14 KB   
96/182 KB   140/516 KB   14/14 KB   
96/182 KB   144/516 KB   14/14 KB   
96/182 KB   148/516 KB   14/14 KB   
96/182 KB   152/516 KB   14/14 KB   
96/182 KB   156/516 KB   14/14 KB   
96/182 KB   160/516 KB   14/14 KB   
100/182 KB   160/516 KB   14/14 KB   
104/182 KB   160/516 KB   14/14 KB   
108/182 KB   160/516 KB   14/14 KB   
112/182 KB   160/516 KB   14/14 KB   
                                     
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/plugin-tools/maven-plugin-annotations/3.5.2/maven-plugin-annotations-3.5.2.jar (14 KB at 165.8 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/1.5.15/plexus-utils-1.5.15.jar
112/182 KB   164/516 KB              
112/182 KB   168/516 KB   
112/182 KB   172/516 KB   
112/182 KB   176/516 KB   
116/182 KB   176/516 KB   
120/182 KB   176/516 KB   
124/182 KB   176/516 KB   
128/182 KB   176/516 KB   
128/182 KB   180/516 KB   
128/182 KB   184/516 KB   
128/182 KB   188/516 KB   
128/182 KB   192/516 KB   
132/182 KB   192/516 KB   
136/182 KB   192/516 KB   
140/182 KB   192/516 KB   
144/182 KB   192/516 KB   
144/182 KB   196/516 KB   
144/182 KB   200/516 KB   
144/182 KB   204/516 KB   
144/182 KB   208/516 KB   
148/182 KB   208/516 KB   
152/182 KB   208/516 KB   
156/182 KB   208/516 KB   
160/182 KB   208/516 KB   
160/182 KB   208/516 KB   4/79 KB   
160/182 KB   208/516 KB   8/79 KB   
160/182 KB   208/516 KB   12/79 KB   
160/182 KB   208/516 KB   16/79 KB   
160/182 KB   212/516 KB   16/79 KB   
160/182 KB   216/516 KB   16/79 KB   
160/182 KB   220/516 KB   16/79 KB   
160/182 KB   224/516 KB   16/79 KB   
164/182 KB   224/516 KB   16/79 KB   
168/182 KB   224/516 KB   16/79 KB   
172/182 KB   224/516 KB   16/79 KB   
176/182 KB   224/516 KB   16/79 KB   
180/182 KB   224/516 KB   16/79 KB   
182/182 KB   224/516 KB   16/79 KB   
182/182 KB   224/516 KB   20/79 KB   
182/182 KB   224/516 KB   24/79 KB   
182/182 KB   224/516 KB   28/79 KB   
182/182 KB   224/516 KB   32/79 KB   
182/182 KB   228/516 KB   32/79 KB   
182/182 KB   232/516 KB   32/79 KB   
182/182 KB   236/516 KB   32/79 KB   
182/182 KB   236/516 KB   4/268 KB   32/79 KB   
182/182 KB   240/516 KB   4/268 KB   32/79 KB   
182/182 KB   240/516 KB   8/268 KB   32/79 KB   
182/182 KB   240/516 KB   12/268 KB   32/79 KB   
182/182 KB   240/516 KB   16/268 KB   32/79 KB   
182/182 KB   244/516 KB   16/268 KB   32/79 KB   
182/182 KB   248/516 KB   16/268 KB   32/79 KB   
182/182 KB   252/516 KB   16/268 KB   32/79 KB   
182/182 KB   256/516 KB   16/268 KB   32/79 KB   
182/182 KB   256/516 KB   20/268 KB   32/79 KB   
182/182 KB   256/516 KB   24/268 KB   32/79 KB   
182/182 KB   256/516 KB   28/268 KB   32/79 KB   
182/182 KB   256/516 KB   32/268 KB   32/79 KB   
182/182 KB   260/516 KB   32/268 KB   32/79 KB   
                                                 
264/516 KB   32/268 KB   32/79 KB                
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-api/2.22.2/surefire-api-2.22.2.jar (182 KB at 1498.8 KB/sec)
268/516 KB   32/268 KB   32/79 KB   
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-descriptor/2.2.1/maven-plugin-descriptor-2.2.1.jar
272/516 KB   32/268 KB   32/79 KB   
272/516 KB   32/268 KB   4/223 KB   32/79 KB   
272/516 KB   32/268 KB   8/223 KB   32/79 KB   
272/516 KB   32/268 KB   12/223 KB   32/79 KB   
272/516 KB   32/268 KB   16/223 KB   32/79 KB   
272/516 KB   32/268 KB   16/223 KB   36/79 KB   
272/516 KB   32/268 KB   16/223 KB   40/79 KB   
272/516 KB   32/268 KB   16/223 KB   44/79 KB   
272/516 KB   32/268 KB   16/223 KB   48/79 KB   
272/516 KB   36/268 KB   16/223 KB   48/79 KB   
272/516 KB   40/268 KB   16/223 KB   48/79 KB   
272/516 KB   44/268 KB   16/223 KB   48/79 KB   
272/516 KB   48/268 KB   16/223 KB   48/79 KB   
272/516 KB   48/268 KB   20/223 KB   48/79 KB   
272/516 KB   48/268 KB   24/223 KB   48/79 KB   
272/516 KB   48/268 KB   28/223 KB   48/79 KB   
272/516 KB   48/268 KB   32/223 KB   48/79 KB   
272/516 KB   52/268 KB   32/223 KB   48/79 KB   
272/516 KB   56/268 KB   32/223 KB   48/79 KB   
272/516 KB   60/268 KB   32/223 KB   48/79 KB   
272/516 KB   64/268 KB   32/223 KB   48/79 KB   
272/516 KB   64/268 KB   32/223 KB   52/79 KB   
272/516 KB   64/268 KB   32/223 KB   56/79 KB   
272/516 KB   64/268 KB   32/223 KB   60/79 KB   
272/516 KB   64/268 KB   32/223 KB   64/79 KB   
276/516 KB   64/268 KB   32/223 KB   64/79 KB   
280/516 KB   64/268 KB   32/223 KB   64/79 KB   
284/516 KB   64/268 KB   32/223 KB   64/79 KB   
288/516 KB   64/268 KB   32/223 KB   64/79 KB   
288/516 KB   68/268 KB   32/223 KB   64/79 KB   
288/516 KB   72/268 KB   32/223 KB   64/79 KB   
288/516 KB   76/268 KB   32/223 KB   64/79 KB   
288/516 KB   80/268 KB   32/223 KB   64/79 KB   
288/516 KB   80/268 KB   32/223 KB   68/79 KB   
288/516 KB   80/268 KB   32/223 KB   72/79 KB   
288/516 KB   84/268 KB   32/223 KB   72/79 KB   
288/516 KB   88/268 KB   32/223 KB   72/79 KB   
288/516 KB   92/268 KB   32/223 KB   72/79 KB   
288/516 KB   96/268 KB   32/223 KB   72/79 KB   
288/516 KB   96/268 KB   36/223 KB   72/79 KB   
288/516 KB   96/268 KB   40/223 KB   72/79 KB   
288/516 KB   96/268 KB   44/223 KB   72/79 KB   
288/516 KB   96/268 KB   48/223 KB   72/79 KB   
288/516 KB   96/268 KB   48/223 KB   4/39 KB   72/79 KB   
288/516 KB   100/268 KB   48/223 KB   4/39 KB   72/79 KB   
288/516 KB   104/268 KB   48/223 KB   4/39 KB   72/79 KB   
288/516 KB   108/268 KB   48/223 KB   4/39 KB   72/79 KB   
288/516 KB   108/268 KB   48/223 KB   8/39 KB   72/79 KB   
288/516 KB   112/268 KB   48/223 KB   8/39 KB   72/79 KB   
288/516 KB   112/268 KB   48/223 KB   12/39 KB   72/79 KB   
288/516 KB   112/268 KB   48/223 KB   16/39 KB   72/79 KB   
292/516 KB   112/268 KB   48/223 KB   16/39 KB   72/79 KB   
296/516 KB   112/268 KB   48/223 KB   16/39 KB   72/79 KB   
300/516 KB   112/268 KB   48/223 KB   16/39 KB   72/79 KB   
304/516 KB   112/268 KB   48/223 KB   16/39 KB   72/79 KB   
304/516 KB   112/268 KB   48/223 KB   16/39 KB   76/79 KB   
304/516 KB   112/268 KB   48/223 KB   16/39 KB   79/79 KB   
304/516 KB   116/268 KB   48/223 KB   16/39 KB   79/79 KB   
304/516 KB   120/268 KB   48/223 KB   16/39 KB   79/79 KB   
304/516 KB   124/268 KB   48/223 KB   16/39 KB   79/79 KB   
304/516 KB   128/268 KB   48/223 KB   16/39 KB   79/79 KB   
304/516 KB   128/268 KB   48/223 KB   20/39 KB   79/79 KB   
304/516 KB   128/268 KB   48/223 KB   24/39 KB   79/79 KB   
304/516 KB   128/268 KB   48/223 KB   28/39 KB   79/79 KB   
304/516 KB   128/268 KB   48/223 KB   32/39 KB   79/79 KB   
304/516 KB   128/268 KB   48/223 KB   36/39 KB   79/79 KB   
304/516 KB   128/268 KB   48/223 KB   39/39 KB   79/79 KB   
308/516 KB   128/268 KB   48/223 KB   39/39 KB   79/79 KB   
312/516 KB   128/268 KB   48/223 KB   39/39 KB   79/79 KB   
316/516 KB   128/268 KB   48/223 KB   39/39 KB   79/79 KB   
320/516 KB   128/268 KB   48/223 KB   39/39 KB   79/79 KB   
320/516 KB   128/268 KB   52/223 KB   39/39 KB   79/79 KB   
320/516 KB   128/268 KB   56/223 KB   39/39 KB   79/79 KB   
320/516 KB   128/268 KB   60/223 KB   39/39 KB   79/79 KB   
320/516 KB   128/268 KB   64/223 KB   39/39 KB   79/79 KB   
                                                            
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact/2.2.1/maven-artifact-2.2.1.jar (79 KB at 499.6 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-container-default/1.0-alpha-9-stable-1/plexus-container-default-1.0-alpha-9-stable-1.jar
320/516 KB   132/268 KB   64/223 KB   39/39 KB              
320/516 KB   136/268 KB   64/223 KB   39/39 KB   
320/516 KB   140/268 KB   64/223 KB   39/39 KB   
320/516 KB   144/268 KB   64/223 KB   39/39 KB   
324/516 KB   144/268 KB   64/223 KB   39/39 KB   
328/516 KB   144/268 KB   64/223 KB   39/39 KB   
332/516 KB   144/268 KB   64/223 KB   39/39 KB   
336/516 KB   144/268 KB   64/223 KB   39/39 KB   
336/516 KB   144/268 KB   68/223 KB   39/39 KB   
336/516 KB   144/268 KB   72/223 KB   39/39 KB   
336/516 KB   144/268 KB   76/223 KB   39/39 KB   
336/516 KB   144/268 KB   80/223 KB   39/39 KB   
                                                 
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-descriptor/2.2.1/maven-plugin-descriptor-2.2.1.jar (39 KB at 236.8 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/junit/junit/4.12/junit-4.12.jar
336/516 KB   148/268 KB   80/223 KB              
336/516 KB   152/268 KB   80/223 KB   
336/516 KB   156/268 KB   80/223 KB   
336/516 KB   160/268 KB   80/223 KB   
340/516 KB   160/268 KB   80/223 KB   
344/516 KB   160/268 KB   80/223 KB   
348/516 KB   160/268 KB   80/223 KB   
352/516 KB   160/268 KB   80/223 KB   
352/516 KB   160/268 KB   84/223 KB   
352/516 KB   160/268 KB   88/223 KB   
352/516 KB   160/268 KB   92/223 KB   
352/516 KB   160/268 KB   96/223 KB   
352/516 KB   164/268 KB   96/223 KB   
352/516 KB   168/268 KB   96/223 KB   
352/516 KB   172/268 KB   96/223 KB   
352/516 KB   176/268 KB   96/223 KB   
352/516 KB   176/268 KB   100/223 KB   
356/516 KB   176/268 KB   104/223 KB   
356/516 KB   176/268 KB   108/223 KB   
356/516 KB   176/268 KB   100/223 KB   
360/516 KB   176/268 KB   108/223 KB   
364/516 KB   176/268 KB   108/223 KB   
368/516 KB   176/268 KB   108/223 KB   
368/516 KB   176/268 KB   112/223 KB   
368/516 KB   180/268 KB   112/223 KB   
368/516 KB   184/268 KB   112/223 KB   
368/516 KB   188/268 KB   112/223 KB   
368/516 KB   192/268 KB   112/223 KB   
368/516 KB   192/268 KB   112/223 KB   4/190 KB   
368/516 KB   192/268 KB   116/223 KB   4/190 KB   
368/516 KB   192/268 KB   116/223 KB   8/190 KB   
368/516 KB   192/268 KB   120/223 KB   8/190 KB   
368/516 KB   192/268 KB   120/223 KB   12/190 KB   
368/516 KB   192/268 KB   124/223 KB   12/190 KB   
368/516 KB   192/268 KB   124/223 KB   16/190 KB   
368/516 KB   192/268 KB   128/223 KB   16/190 KB   
372/516 KB   192/268 KB   128/223 KB   16/190 KB   
376/516 KB   192/268 KB   128/223 KB   16/190 KB   
380/516 KB   192/268 KB   128/223 KB   16/190 KB   
384/516 KB   192/268 KB   128/223 KB   16/190 KB   
384/516 KB   196/268 KB   128/223 KB   16/190 KB   
384/516 KB   200/268 KB   128/223 KB   16/190 KB   
384/516 KB   204/268 KB   128/223 KB   16/190 KB   
384/516 KB   208/268 KB   128/223 KB   16/190 KB   
384/516 KB   208/268 KB   132/223 KB   16/190 KB   
384/516 KB   208/268 KB   136/223 KB   16/190 KB   
384/516 KB   208/268 KB   140/223 KB   16/190 KB   
384/516 KB   208/268 KB   144/223 KB   16/190 KB   
384/516 KB   212/268 KB   144/223 KB   16/190 KB   
384/516 KB   216/268 KB   144/223 KB   16/190 KB   
384/516 KB   220/268 KB   144/223 KB   16/190 KB   
384/516 KB   224/268 KB   144/223 KB   16/190 KB   
384/516 KB   224/268 KB   144/223 KB   4/308 KB   16/190 KB   
384/516 KB   224/268 KB   148/223 KB   4/308 KB   16/190 KB   
384/516 KB   224/268 KB   148/223 KB   8/308 KB   16/190 KB   
384/516 KB   224/268 KB   148/223 KB   12/308 KB   16/190 KB   
384/516 KB   224/268 KB   148/223 KB   16/308 KB   16/190 KB   
384/516 KB   224/268 KB   152/223 KB   16/308 KB   16/190 KB   
384/516 KB   224/268 KB   156/223 KB   16/308 KB   16/190 KB   
384/516 KB   224/268 KB   160/223 KB   16/308 KB   16/190 KB   
384/516 KB   228/268 KB   160/223 KB   16/308 KB   16/190 KB   
384/516 KB   232/268 KB   160/223 KB   16/308 KB   16/190 KB   
384/516 KB   236/268 KB   160/223 KB   16/308 KB   16/190 KB   
384/516 KB   240/268 KB   160/223 KB   16/308 KB   16/190 KB   
384/516 KB   240/268 KB   160/223 KB   20/308 KB   16/190 KB   
384/516 KB   240/268 KB   160/223 KB   24/308 KB   16/190 KB   
384/516 KB   240/268 KB   160/223 KB   28/308 KB   16/190 KB   
384/516 KB   240/268 KB   160/223 KB   32/308 KB   16/190 KB   
384/516 KB   240/268 KB   164/223 KB   32/308 KB   16/190 KB   
384/516 KB   240/268 KB   168/223 KB   32/308 KB   16/190 KB   
384/516 KB   240/268 KB   172/223 KB   32/308 KB   16/190 KB   
384/516 KB   240/268 KB   176/223 KB   32/308 KB   16/190 KB   
384/516 KB   244/268 KB   176/223 KB   32/308 KB   16/190 KB   
384/516 KB   248/268 KB   176/223 KB   32/308 KB   16/190 KB   
384/516 KB   252/268 KB   176/223 KB   32/308 KB   16/190 KB   
384/516 KB   256/268 KB   176/223 KB   32/308 KB   16/190 KB   
388/516 KB   256/268 KB   176/223 KB   32/308 KB   16/190 KB   
392/516 KB   256/268 KB   176/223 KB   32/308 KB   16/190 KB   
393/516 KB   256/268 KB   176/223 KB   32/308 KB   16/190 KB   
393/516 KB   256/268 KB   180/223 KB   32/308 KB   16/190 KB   
393/516 KB   256/268 KB   184/223 KB   32/308 KB   16/190 KB   
393/516 KB   256/268 KB   188/223 KB   32/308 KB   16/190 KB   
393/516 KB   256/268 KB   192/223 KB   32/308 KB   16/190 KB   
393/516 KB   260/268 KB   192/223 KB   32/308 KB   16/190 KB   
393/516 KB   264/268 KB   192/223 KB   32/308 KB   16/190 KB   
393/516 KB   268/268 KB   192/223 KB   32/308 KB   16/190 KB   
393/516 KB   268/268 KB   192/223 KB   32/308 KB   20/190 KB   
393/516 KB   268/268 KB   192/223 KB   32/308 KB   24/190 KB   
393/516 KB   268/268 KB   192/223 KB   32/308 KB   28/190 KB   
393/516 KB   268/268 KB   192/223 KB   32/308 KB   32/190 KB   
393/516 KB   268/268 KB   196/223 KB   32/308 KB   32/190 KB   
393/516 KB   268/268 KB   200/223 KB   32/308 KB   32/190 KB   
393/516 KB   268/268 KB   204/223 KB   32/308 KB   32/190 KB   
393/516 KB   268/268 KB   208/223 KB   32/308 KB   32/190 KB   
393/516 KB   268/268 KB   208/223 KB   36/308 KB   32/190 KB   
393/516 KB   268/268 KB   208/223 KB   40/308 KB   32/190 KB   
393/516 KB   268/268 KB   208/223 KB   44/308 KB   32/190 KB   
393/516 KB   268/268 KB   208/223 KB   48/308 KB   32/190 KB   
393/516 KB   268/268 KB   208/223 KB   48/308 KB   36/190 KB   
393/516 KB   268/268 KB   208/223 KB   48/308 KB   40/190 KB   
393/516 KB   268/268 KB   208/223 KB   48/308 KB   44/190 KB   
393/516 KB   268/268 KB   208/223 KB   48/308 KB   48/190 KB   
397/516 KB   268/268 KB   208/223 KB   48/308 KB   48/190 KB   
401/516 KB   268/268 KB   208/223 KB   48/308 KB   48/190 KB   
405/516 KB   268/268 KB   208/223 KB   48/308 KB   48/190 KB   
409/516 KB   268/268 KB   208/223 KB   48/308 KB   48/190 KB   
409/516 KB   268/268 KB   212/223 KB   48/308 KB   48/190 KB   
409/516 KB   268/268 KB   212/223 KB   52/308 KB   48/190 KB   
409/516 KB   268/268 KB   216/223 KB   52/308 KB   48/190 KB   
409/516 KB   268/268 KB   216/223 KB   56/308 KB   48/190 KB   
409/516 KB   268/268 KB   220/223 KB   56/308 KB   48/190 KB   
409/516 KB   268/268 KB   223/223 KB   56/308 KB   48/190 KB   
409/516 KB   268/268 KB   223/223 KB   60/308 KB   48/190 KB   
409/516 KB   268/268 KB   223/223 KB   64/308 KB   48/190 KB   
409/516 KB   268/268 KB   223/223 KB   64/308 KB   52/190 KB   
409/516 KB   268/268 KB   223/223 KB   64/308 KB   56/190 KB   
409/516 KB   268/268 KB   223/223 KB   64/308 KB   60/190 KB   
409/516 KB   268/268 KB   223/223 KB   64/308 KB   64/190 KB   
                                                               
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-booter/2.22.2/surefire-booter-2.22.2.jar (268 KB at 1117.9 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-core/1.3/hamcrest-core-1.3.jar
                                                               
Downloaded: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/1.5.15/plexus-utils-1.5.15.jar (223 KB at 928.2 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/maven-project/2.2.1/maven-project-2.2.1.jar
409/516 KB   68/308 KB   64/190 KB                             
409/516 KB   72/308 KB   64/190 KB   
409/516 KB   76/308 KB   64/190 KB   
409/516 KB   80/308 KB   64/190 KB   
413/516 KB   80/308 KB   64/190 KB   
417/516 KB   80/308 KB   64/190 KB   
421/516 KB   80/308 KB   64/190 KB   
425/516 KB   80/308 KB   64/190 KB   
425/516 KB   80/308 KB   68/190 KB   
425/516 KB   80/308 KB   72/190 KB   
425/516 KB   80/308 KB   76/190 KB   
425/516 KB   80/308 KB   80/190 KB   
425/516 KB   84/308 KB   80/190 KB   
425/516 KB   88/308 KB   80/190 KB   
425/516 KB   92/308 KB   80/190 KB   
425/516 KB   96/308 KB   80/190 KB   
429/516 KB   96/308 KB   80/190 KB   
433/516 KB   96/308 KB   80/190 KB   
437/516 KB   96/308 KB   80/190 KB   
441/516 KB   96/308 KB   80/190 KB   
441/516 KB   96/308 KB   84/190 KB   
441/516 KB   96/308 KB   88/190 KB   
441/516 KB   96/308 KB   92/190 KB   
441/516 KB   96/308 KB   96/190 KB   
441/516 KB   100/308 KB   96/190 KB   
441/516 KB   104/308 KB   96/190 KB   
441/516 KB   108/308 KB   96/190 KB   
441/516 KB   112/308 KB   96/190 KB   
445/516 KB   112/308 KB   96/190 KB   
449/516 KB   112/308 KB   96/190 KB   
453/516 KB   112/308 KB   96/190 KB   
457/516 KB   112/308 KB   96/190 KB   
457/516 KB   112/308 KB   100/190 KB   
457/516 KB   112/308 KB   104/190 KB   
457/516 KB   112/308 KB   108/190 KB   
457/516 KB   112/308 KB   112/190 KB   
457/516 KB   116/308 KB   112/190 KB   
457/516 KB   120/308 KB   112/190 KB   
457/516 KB   124/308 KB   112/190 KB   
457/516 KB   128/308 KB   112/190 KB   
461/516 KB   128/308 KB   112/190 KB   
465/516 KB   128/308 KB   112/190 KB   
469/516 KB   128/308 KB   112/190 KB   
473/516 KB   128/308 KB   112/190 KB   
473/516 KB   128/308 KB   116/190 KB   
473/516 KB   128/308 KB   120/190 KB   
473/516 KB   132/308 KB   120/190 KB   
473/516 KB   136/308 KB   120/190 KB   
473/516 KB   140/308 KB   120/190 KB   
473/516 KB   144/308 KB   120/190 KB   
473/516 KB   144/308 KB   124/190 KB   
473/516 KB   144/308 KB   128/190 KB   
477/516 KB   144/308 KB   128/190 KB   
481/516 KB   144/308 KB   128/190 KB   
485/516 KB   144/308 KB   128/190 KB   
489/516 KB   144/308 KB   128/190 KB   
489/516 KB   148/308 KB   128/190 KB   
489/516 KB   152/308 KB   128/190 KB   
489/516 KB   156/308 KB   128/190 KB   
489/516 KB   160/308 KB   128/190 KB   
493/516 KB   160/308 KB   128/190 KB   
497/516 KB   160/308 KB   128/190 KB   
501/516 KB   160/308 KB   128/190 KB   
505/516 KB   160/308 KB   128/190 KB   
4/44 KB   505/516 KB   160/308 KB   128/190 KB   
8/44 KB   505/516 KB   160/308 KB   128/190 KB   
12/44 KB   505/516 KB   160/308 KB   128/190 KB   
16/44 KB   505/516 KB   160/308 KB   128/190 KB   
16/44 KB   505/516 KB   164/308 KB   128/190 KB   
16/44 KB   505/516 KB   168/308 KB   128/190 KB   
16/44 KB   505/516 KB   172/308 KB   128/190 KB   
16/44 KB   505/516 KB   176/308 KB   128/190 KB   
16/44 KB   509/516 KB   176/308 KB   128/190 KB   
16/44 KB   513/516 KB   176/308 KB   128/190 KB   
16/44 KB   516/516 KB   176/308 KB   128/190 KB   
4/153 KB   16/44 KB   516/516 KB   176/308 KB   128/190 KB   
8/153 KB   16/44 KB   516/516 KB   176/308 KB   128/190 KB   
12/153 KB   16/44 KB   516/516 KB   176/308 KB   128/190 KB   
16/153 KB   16/44 KB   516/516 KB   176/308 KB   128/190 KB   
16/153 KB   16/44 KB   516/516 KB   180/308 KB   128/190 KB   
16/153 KB   16/44 KB   516/516 KB   184/308 KB   128/190 KB   
16/153 KB   16/44 KB   516/516 KB   188/308 KB   128/190 KB   
16/153 KB   16/44 KB   516/516 KB   192/308 KB   128/190 KB   
16/153 KB   16/44 KB   516/516 KB   192/308 KB   132/190 KB   
16/153 KB   16/44 KB   516/516 KB   192/308 KB   136/190 KB   
16/153 KB   16/44 KB   516/516 KB   192/308 KB   140/190 KB   
16/153 KB   16/44 KB   516/516 KB   192/308 KB   144/190 KB   
16/153 KB   16/44 KB   516/516 KB   196/308 KB   144/190 KB   
16/153 KB   16/44 KB   516/516 KB   200/308 KB   144/190 KB   
16/153 KB   16/44 KB   516/516 KB   204/308 KB   144/190 KB   
16/153 KB   16/44 KB   516/516 KB   208/308 KB   144/190 KB   
16/153 KB   16/44 KB   516/516 KB   208/308 KB   148/190 KB   
16/153 KB   16/44 KB   516/516 KB   208/308 KB   152/190 KB   
16/153 KB   16/44 KB   516/516 KB   208/308 KB   156/190 KB   
16/153 KB   16/44 KB   516/516 KB   208/308 KB   160/190 KB   
16/153 KB   20/44 KB   516/516 KB   208/308 KB   160/190 KB   
16/153 KB   24/44 KB   516/516 KB   208/308 KB   160/190 KB   
16/153 KB   28/44 KB   516/516 KB   208/308 KB   160/190 KB   
16/153 KB   32/44 KB   516/516 KB   208/308 KB   160/190 KB   
                                                              
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/maven-surefire-common/2.22.2/maven-surefire-common-2.22.2.jar (516 KB at 1759.8 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings/2.2.1/maven-settings-2.2.1.jar
16/153 KB   32/44 KB   208/308 KB   164/190 KB                
16/153 KB   32/44 KB   208/308 KB   168/190 KB   
16/153 KB   32/44 KB   208/308 KB   172/190 KB   
20/153 KB   32/44 KB   208/308 KB   172/190 KB   
20/153 KB   32/44 KB   208/308 KB   176/190 KB   
20/153 KB   32/44 KB   212/308 KB   176/190 KB   
24/153 KB   32/44 KB   212/308 KB   176/190 KB   
24/153 KB   32/44 KB   216/308 KB   176/190 KB   
28/153 KB   32/44 KB   216/308 KB   176/190 KB   
28/153 KB   32/44 KB   220/308 KB   176/190 KB   
32/153 KB   32/44 KB   220/308 KB   176/190 KB   
32/153 KB   32/44 KB   224/308 KB   176/190 KB   
32/153 KB   36/44 KB   224/308 KB   176/190 KB   
32/153 KB   40/44 KB   224/308 KB   176/190 KB   
32/153 KB   44/44 KB   224/308 KB   176/190 KB   
32/153 KB   44/44 KB   224/308 KB   180/190 KB   
32/153 KB   44/44 KB   228/308 KB   180/190 KB   
32/153 KB   44/44 KB   228/308 KB   184/190 KB   
32/153 KB   44/44 KB   232/308 KB   184/190 KB   
32/153 KB   44/44 KB   232/308 KB   188/190 KB   
32/153 KB   44/44 KB   236/308 KB   188/190 KB   
32/153 KB   44/44 KB   236/308 KB   190/190 KB   
32/153 KB   44/44 KB   240/308 KB   190/190 KB   
36/153 KB   44/44 KB   240/308 KB   190/190 KB   
40/153 KB   44/44 KB   240/308 KB   190/190 KB   
44/153 KB   44/44 KB   240/308 KB   190/190 KB   
48/153 KB   44/44 KB   240/308 KB   190/190 KB   
48/153 KB   44/44 KB   244/308 KB   190/190 KB   
48/153 KB   44/44 KB   248/308 KB   190/190 KB   
48/153 KB   44/44 KB   252/308 KB   190/190 KB   
48/153 KB   44/44 KB   256/308 KB   190/190 KB   
52/153 KB   44/44 KB   256/308 KB   190/190 KB   
56/153 KB   44/44 KB   256/308 KB   190/190 KB   
60/153 KB   44/44 KB   256/308 KB   190/190 KB   
64/153 KB   44/44 KB   256/308 KB   190/190 KB   
68/153 KB   44/44 KB   256/308 KB   190/190 KB   
72/153 KB   44/44 KB   256/308 KB   190/190 KB   
76/153 KB   44/44 KB   256/308 KB   190/190 KB   
80/153 KB   44/44 KB   256/308 KB   190/190 KB   
                                                 
Downloaded: https://repo.maven.apache.org/maven2/org/hamcrest/hamcrest-core/1.3/hamcrest-core-1.3.jar (44 KB at 145.6 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/maven-profile/2.2.1/maven-profile-2.2.1.jar
80/153 KB   256/308 KB   190/190 KB   4/48 KB    
80/153 KB   256/308 KB   190/190 KB   8/48 KB   
80/153 KB   256/308 KB   190/190 KB   12/48 KB   
80/153 KB   256/308 KB   190/190 KB   16/48 KB   
80/153 KB   260/308 KB   190/190 KB   16/48 KB   
80/153 KB   264/308 KB   190/190 KB   16/48 KB   
80/153 KB   268/308 KB   190/190 KB   16/48 KB   
80/153 KB   272/308 KB   190/190 KB   16/48 KB   
84/153 KB   272/308 KB   190/190 KB   16/48 KB   
88/153 KB   272/308 KB   190/190 KB   16/48 KB   
92/153 KB   272/308 KB   190/190 KB   16/48 KB   
96/153 KB   272/308 KB   190/190 KB   16/48 KB   
96/153 KB   272/308 KB   190/190 KB   20/48 KB   
96/153 KB   272/308 KB   190/190 KB   24/48 KB   
96/153 KB   272/308 KB   190/190 KB   28/48 KB   
96/153 KB   272/308 KB   190/190 KB   32/48 KB   
96/153 KB   276/308 KB   190/190 KB   32/48 KB   
96/153 KB   280/308 KB   190/190 KB   32/48 KB   
96/153 KB   284/308 KB   190/190 KB   32/48 KB   
96/153 KB   288/308 KB   190/190 KB   32/48 KB   
100/153 KB   288/308 KB   190/190 KB   32/48 KB   
104/153 KB   288/308 KB   190/190 KB   32/48 KB   
108/153 KB   288/308 KB   190/190 KB   32/48 KB   
112/153 KB   288/308 KB   190/190 KB   32/48 KB   
112/153 KB   288/308 KB   190/190 KB   36/48 KB   
112/153 KB   288/308 KB   190/190 KB   40/48 KB   
112/153 KB   288/308 KB   190/190 KB   44/48 KB   
112/153 KB   288/308 KB   190/190 KB   48/48 KB   
112/153 KB   288/308 KB   190/190 KB   48/48 KB   
112/153 KB   292/308 KB   190/190 KB   48/48 KB   
                                                  
112/153 KB   296/308 KB   48/48 KB                
Downloaded: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-container-default/1.0-alpha-9-stable-1/plexus-container-default-1.0-alpha-9-stable-1.jar (190 KB at 602.0 KB/sec)
112/153 KB   300/308 KB   48/48 KB   
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact-manager/2.2.1/maven-artifact-manager-2.2.1.jar
112/153 KB   304/308 KB   48/48 KB   
112/153 KB   308/308 KB   48/48 KB   
112/153 KB   308/308 KB   48/48 KB   
116/153 KB   308/308 KB   48/48 KB   
120/153 KB   308/308 KB   48/48 KB   
124/153 KB   308/308 KB   48/48 KB   
128/153 KB   308/308 KB   48/48 KB   
128/153 KB   4/35 KB   308/308 KB   48/48 KB   
128/153 KB   8/35 KB   308/308 KB   48/48 KB   
128/153 KB   12/35 KB   308/308 KB   48/48 KB   
128/153 KB   16/35 KB   308/308 KB   48/48 KB   
132/153 KB   16/35 KB   308/308 KB   48/48 KB   
136/153 KB   16/35 KB   308/308 KB   48/48 KB   
140/153 KB   16/35 KB   308/308 KB   48/48 KB   
144/153 KB   16/35 KB   308/308 KB   48/48 KB   
                                                
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings/2.2.1/maven-settings-2.2.1.jar (48 KB at 147.8 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/backport-util-concurrent/backport-util-concurrent/3.1/backport-util-concurrent-3.1.jar
148/153 KB   16/35 KB   308/308 KB              
152/153 KB   16/35 KB   308/308 KB   
153/153 KB   16/35 KB   308/308 KB   
153/153 KB   20/35 KB   308/308 KB   
153/153 KB   24/35 KB   308/308 KB   
153/153 KB   28/35 KB   308/308 KB   
153/153 KB   32/35 KB   308/308 KB   
153/153 KB   35/35 KB   308/308 KB   
                                     
Downloaded: https://repo.maven.apache.org/maven2/junit/junit/4.12/junit-4.12.jar (308 KB at 934.8 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-registry/2.2.1/maven-plugin-registry-2.2.1.jar
                                     
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/maven-project/2.2.1/maven-project-2.2.1.jar (153 KB at 456.9 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.11/plexus-interpolation-1.11.jar
35/35 KB   4/66 KB                   
35/35 KB   8/66 KB   
35/35 KB   12/66 KB   
35/35 KB   16/66 KB   
                      
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/maven-profile/2.2.1/maven-profile-2.2.1.jar (35 KB at 102.2 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model/2.2.1/maven-model-2.2.1.jar
20/66 KB              
24/66 KB   
28/66 KB   
32/66 KB   
36/66 KB   
40/66 KB   
44/66 KB   
48/66 KB   
48/66 KB   4/324 KB   
48/66 KB   8/324 KB   
48/66 KB   12/324 KB   
48/66 KB   16/324 KB   
48/66 KB   20/324 KB   
48/66 KB   24/324 KB   
48/66 KB   28/324 KB   
48/66 KB   32/324 KB   
52/66 KB   32/324 KB   
56/66 KB   32/324 KB   
60/66 KB   32/324 KB   
64/66 KB   32/324 KB   
66/66 KB   32/324 KB   
66/66 KB   32/324 KB   4/30 KB   
66/66 KB   32/324 KB   8/30 KB   
66/66 KB   32/324 KB   12/30 KB   
66/66 KB   32/324 KB   16/30 KB   
66/66 KB   36/324 KB   16/30 KB   
66/66 KB   40/324 KB   16/30 KB   
66/66 KB   44/324 KB   16/30 KB   
66/66 KB   48/324 KB   16/30 KB   
66/66 KB   48/324 KB   20/30 KB   
66/66 KB   48/324 KB   24/30 KB   
66/66 KB   48/324 KB   28/30 KB   
66/66 KB   48/324 KB   30/30 KB   
66/66 KB   52/324 KB   30/30 KB   
66/66 KB   56/324 KB   30/30 KB   
66/66 KB   60/324 KB   30/30 KB   
66/66 KB   64/324 KB   30/30 KB   
66/66 KB   68/324 KB   30/30 KB   
66/66 KB   72/324 KB   30/30 KB   
66/66 KB   76/324 KB   30/30 KB   
66/66 KB   80/324 KB   30/30 KB   
66/66 KB   80/324 KB   30/30 KB   4/50 KB   
66/66 KB   80/324 KB   30/30 KB   8/50 KB   
66/66 KB   80/324 KB   30/30 KB   12/50 KB   
66/66 KB   80/324 KB   30/30 KB   16/50 KB   
66/66 KB   80/324 KB   30/30 KB   16/50 KB   4/86 KB   
66/66 KB   80/324 KB   30/30 KB   16/50 KB   8/86 KB   
66/66 KB   80/324 KB   30/30 KB   16/50 KB   12/86 KB   
66/66 KB   80/324 KB   30/30 KB   16/50 KB   16/86 KB   
66/66 KB   84/324 KB   30/30 KB   16/50 KB   16/86 KB   
66/66 KB   88/324 KB   30/30 KB   16/50 KB   16/86 KB   
66/66 KB   92/324 KB   30/30 KB   16/50 KB   16/86 KB   
66/66 KB   96/324 KB   30/30 KB   16/50 KB   16/86 KB   
66/66 KB   96/324 KB   30/30 KB   16/50 KB   20/86 KB   
66/66 KB   96/324 KB   30/30 KB   16/50 KB   24/86 KB   
66/66 KB   96/324 KB   30/30 KB   16/50 KB   28/86 KB   
66/66 KB   96/324 KB   30/30 KB   16/50 KB   32/86 KB   
66/66 KB   96/324 KB   30/30 KB   20/50 KB   32/86 KB   
66/66 KB   96/324 KB   30/30 KB   24/50 KB   32/86 KB   
66/66 KB   100/324 KB   30/30 KB   24/50 KB   32/86 KB   
66/66 KB   100/324 KB   30/30 KB   28/50 KB   32/86 KB   
66/66 KB   104/324 KB   30/30 KB   28/50 KB   32/86 KB   
66/66 KB   104/324 KB   30/30 KB   32/50 KB   32/86 KB   
66/66 KB   108/324 KB   30/30 KB   32/50 KB   32/86 KB   
66/66 KB   112/324 KB   30/30 KB   32/50 KB   32/86 KB   
66/66 KB   112/324 KB   30/30 KB   32/50 KB   36/86 KB   
66/66 KB   112/324 KB   30/30 KB   32/50 KB   40/86 KB   
66/66 KB   112/324 KB   30/30 KB   32/50 KB   44/86 KB   
66/66 KB   112/324 KB   30/30 KB   32/50 KB   48/86 KB   
66/66 KB   116/324 KB   30/30 KB   32/50 KB   48/86 KB   
66/66 KB   116/324 KB   30/30 KB   36/50 KB   48/86 KB   
66/66 KB   120/324 KB   30/30 KB   36/50 KB   48/86 KB   
66/66 KB   120/324 KB   30/30 KB   40/50 KB   48/86 KB   
66/66 KB   124/324 KB   30/30 KB   40/50 KB   48/86 KB   
66/66 KB   128/324 KB   30/30 KB   40/50 KB   48/86 KB   
66/66 KB   128/324 KB   30/30 KB   44/50 KB   48/86 KB   
66/66 KB   128/324 KB   30/30 KB   48/50 KB   48/86 KB   
66/66 KB   128/324 KB   30/30 KB   50/50 KB   48/86 KB   
66/66 KB   128/324 KB   30/30 KB   50/50 KB   52/86 KB   
66/66 KB   132/324 KB   30/30 KB   50/50 KB   52/86 KB   
66/66 KB   132/324 KB   30/30 KB   50/50 KB   56/86 KB   
66/66 KB   136/324 KB   30/30 KB   50/50 KB   56/86 KB   
66/66 KB   136/324 KB   30/30 KB   50/50 KB   60/86 KB   
66/66 KB   140/324 KB   30/30 KB   50/50 KB   60/86 KB   
66/66 KB   140/324 KB   30/30 KB   50/50 KB   64/86 KB   
66/66 KB   144/324 KB   30/30 KB   50/50 KB   64/86 KB   
                                                         
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-registry/2.2.1/maven-plugin-registry-2.2.1.jar (30 KB at 74.6 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/maven-core/2.2.1/maven-core-2.2.1.jar
66/66 KB   148/324 KB   50/50 KB   64/86 KB              
66/66 KB   152/324 KB   50/50 KB   64/86 KB   
66/66 KB   156/324 KB   50/50 KB   64/86 KB   
66/66 KB   160/324 KB   50/50 KB   64/86 KB   
66/66 KB   160/324 KB   50/50 KB   68/86 KB   
66/66 KB   160/324 KB   50/50 KB   72/86 KB   
66/66 KB   160/324 KB   50/50 KB   76/86 KB   
66/66 KB   160/324 KB   50/50 KB   80/86 KB   
                                              
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact-manager/2.2.1/maven-artifact-manager-2.2.1.jar (66 KB at 168.3 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-parameter-documenter/2.2.1/maven-plugin-parameter-documenter-2.2.1.jar
160/324 KB   50/50 KB   84/86 KB              
160/324 KB   50/50 KB   86/86 KB   
164/324 KB   50/50 KB   86/86 KB   
168/324 KB   50/50 KB   86/86 KB   
172/324 KB   50/50 KB   86/86 KB   
176/324 KB   50/50 KB   86/86 KB   
                                   
Downloaded: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.11/plexus-interpolation-1.11.jar (50 KB at 125.9 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-jdk14/1.5.6/slf4j-jdk14-1.5.6.jar
180/324 KB   86/86 KB              
184/324 KB   86/86 KB   
188/324 KB   86/86 KB   
192/324 KB   86/86 KB   
196/324 KB   86/86 KB   
200/324 KB   86/86 KB   
204/324 KB   86/86 KB   
208/324 KB   86/86 KB   
                        
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model/2.2.1/maven-model-2.2.1.jar (86 KB at 210.7 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.5.6/slf4j-api-1.5.6.jar
208/324 KB   4/174 KB   
208/324 KB   8/174 KB   
208/324 KB   12/174 KB   
208/324 KB   16/174 KB   
4/9 KB   208/324 KB   16/174 KB   
4/9 KB   212/324 KB   16/174 KB   
4/9 KB   216/324 KB   16/174 KB   
8/9 KB   216/324 KB   16/174 KB   
9/9 KB   216/324 KB   16/174 KB   
9/9 KB   220/324 KB   16/174 KB   
9/9 KB   224/324 KB   16/174 KB   
9/9 KB   224/324 KB   20/174 KB   
9/9 KB   224/324 KB   24/174 KB   
9/9 KB   224/324 KB   28/174 KB   
9/9 KB   224/324 KB   32/174 KB   
9/9 KB   228/324 KB   32/174 KB   
9/9 KB   232/324 KB   32/174 KB   
9/9 KB   236/324 KB   32/174 KB   
9/9 KB   240/324 KB   32/174 KB   
9/9 KB   4/22 KB   240/324 KB   32/174 KB   
9/9 KB   8/22 KB   240/324 KB   32/174 KB   
9/9 KB   12/22 KB   240/324 KB   32/174 KB   
9/9 KB   16/22 KB   240/324 KB   32/174 KB   
9/9 KB   16/22 KB   240/324 KB   36/174 KB   
9/9 KB   20/22 KB   240/324 KB   36/174 KB   
9/9 KB   22/22 KB   240/324 KB   36/174 KB   
9/9 KB   22/22 KB   240/324 KB   40/174 KB   
9/9 KB   22/22 KB   240/324 KB   44/174 KB   
9/9 KB   22/22 KB   240/324 KB   48/174 KB   
9/9 KB   22/22 KB   244/324 KB   48/174 KB   
9/9 KB   22/22 KB   248/324 KB   48/174 KB   
9/9 KB   22/22 KB   252/324 KB   48/174 KB   
9/9 KB   22/22 KB   256/324 KB   48/174 KB   
9/9 KB   22/22 KB   256/324 KB   52/174 KB   
9/9 KB   22/22 KB   256/324 KB   56/174 KB   
9/9 KB   22/22 KB   256/324 KB   60/174 KB   
9/9 KB   22/22 KB   256/324 KB   64/174 KB   
9/9 KB   22/22 KB   260/324 KB   64/174 KB   
9/9 KB   22/22 KB   264/324 KB   64/174 KB   
9/9 KB   22/22 KB   268/324 KB   64/174 KB   
9/9 KB   22/22 KB   272/324 KB   64/174 KB   
9/9 KB   22/22 KB   272/324 KB   68/174 KB   
9/9 KB   22/22 KB   272/324 KB   72/174 KB   
9/9 KB   22/22 KB   272/324 KB   76/174 KB   
9/9 KB   22/22 KB   272/324 KB   80/174 KB   
9/9 KB   22/22 KB   4/22 KB   272/324 KB   80/174 KB   
9/9 KB   22/22 KB   8/22 KB   272/324 KB   80/174 KB   
9/9 KB   22/22 KB   12/22 KB   272/324 KB   80/174 KB   
9/9 KB   22/22 KB   16/22 KB   272/324 KB   80/174 KB   
9/9 KB   22/22 KB   16/22 KB   276/324 KB   80/174 KB   
9/9 KB   22/22 KB   16/22 KB   280/324 KB   80/174 KB   
9/9 KB   22/22 KB   16/22 KB   284/324 KB   80/174 KB   
9/9 KB   22/22 KB   16/22 KB   288/324 KB   80/174 KB   
                                                        
Downloaded: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-jdk14/1.5.6/slf4j-jdk14-1.5.6.jar (9 KB at 20.0 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/slf4j/jcl-over-slf4j/1.5.6/jcl-over-slf4j-1.5.6.jar
22/22 KB   20/22 KB   288/324 KB   80/174 KB            
22/22 KB   22/22 KB   288/324 KB   80/174 KB   
22/22 KB   22/22 KB   292/324 KB   80/174 KB   
22/22 KB   22/22 KB   296/324 KB   80/174 KB   
22/22 KB   22/22 KB   300/324 KB   80/174 KB   
22/22 KB   22/22 KB   304/324 KB   80/174 KB   
                                               
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-parameter-documenter/2.2.1/maven-plugin-parameter-documenter-2.2.1.jar (22 KB at 50.1 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/maven-repository-metadata/2.2.1/maven-repository-metadata-2.2.1.jar
22/22 KB   304/324 KB   84/174 KB              
22/22 KB   304/324 KB   88/174 KB   
22/22 KB   304/324 KB   92/174 KB   
22/22 KB   304/324 KB   96/174 KB   
22/22 KB   308/324 KB   96/174 KB   
22/22 KB   312/324 KB   96/174 KB   
22/22 KB   316/324 KB   96/174 KB   
22/22 KB   320/324 KB   96/174 KB   
22/22 KB   320/324 KB   100/174 KB   
22/22 KB   320/324 KB   104/174 KB   
22/22 KB   324/324 KB   104/174 KB   
22/22 KB   324/324 KB   108/174 KB   
22/22 KB   324/324 KB   112/174 KB   
                                     
Downloaded: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.5.6/slf4j-api-1.5.6.jar (22 KB at 49.4 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/maven-error-diagnostics/2.2.1/maven-error-diagnostics-2.2.1.jar
324/324 KB   116/174 KB              
324/324 KB   120/174 KB   
324/324 KB   124/174 KB   
324/324 KB   128/174 KB   
324/324 KB   132/174 KB   
324/324 KB   136/174 KB   
324/324 KB   140/174 KB   
324/324 KB   144/174 KB   
4/17 KB   324/324 KB   144/174 KB   
4/17 KB   4/26 KB   324/324 KB   144/174 KB   
8/17 KB   4/26 KB   324/324 KB   144/174 KB   
8/17 KB   8/26 KB   324/324 KB   144/174 KB   
12/17 KB   8/26 KB   324/324 KB   144/174 KB   
12/17 KB   12/26 KB   324/324 KB   144/174 KB   
16/17 KB   16/26 KB   324/324 KB   144/174 KB   
16/17 KB   12/26 KB   324/324 KB   144/174 KB   
17/17 KB   16/26 KB   324/324 KB   144/174 KB   
17/17 KB   16/26 KB   324/324 KB   148/174 KB   
17/17 KB   16/26 KB   324/324 KB   152/174 KB   
17/17 KB   16/26 KB   324/324 KB   156/174 KB   
17/17 KB   16/26 KB   324/324 KB   160/174 KB   
17/17 KB   20/26 KB   324/324 KB   160/174 KB   
17/17 KB   24/26 KB   324/324 KB   160/174 KB   
17/17 KB   26/26 KB   324/324 KB   160/174 KB   
                                                
Downloaded: https://repo.maven.apache.org/maven2/backport-util-concurrent/backport-util-concurrent/3.1/backport-util-concurrent-3.1.jar (324 KB at 712.0 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/maven-monitor/2.2.1/maven-monitor-2.2.1.jar
17/17 KB   26/26 KB   164/174 KB                
17/17 KB   26/26 KB   168/174 KB   
17/17 KB   26/26 KB   172/174 KB   
17/17 KB   26/26 KB   174/174 KB   
17/17 KB   4/13 KB   26/26 KB   174/174 KB   
17/17 KB   8/13 KB   26/26 KB   174/174 KB   
17/17 KB   12/13 KB   26/26 KB   174/174 KB   
17/17 KB   13/13 KB   26/26 KB   174/174 KB   
                                              
Downloaded: https://repo.maven.apache.org/maven2/org/slf4j/jcl-over-slf4j/1.5.6/jcl-over-slf4j-1.5.6.jar (17 KB at 35.2 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/classworlds/classworlds/1.1/classworlds-1.1.jar
                                              
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/maven-repository-metadata/2.2.1/maven-repository-metadata-2.2.1.jar (26 KB at 53.8 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/maven-toolchain/2.2.1/maven-toolchain-2.2.1.jar
                                              
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/maven-core/2.2.1/maven-core-2.2.1.jar (174 KB at 372.0 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/com/thoughtworks/qdox/qdox/2.0-M8/qdox-2.0-M8.jar
                                              
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/maven-error-diagnostics/2.2.1/maven-error-diagnostics-2.2.1.jar (13 KB at 26.8 KB/sec)
4/11 KB                                       
8/11 KB   
11/11 KB   
4/37 KB   11/11 KB   
8/37 KB   11/11 KB   
12/37 KB   11/11 KB   
16/37 KB   11/11 KB   
20/37 KB   11/11 KB   
24/37 KB   11/11 KB   
28/37 KB   11/11 KB   
32/37 KB   11/11 KB   
36/37 KB   11/11 KB   
37/37 KB   11/11 KB   
                      
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/maven-monitor/2.2.1/maven-monitor-2.2.1.jar (11 KB at 20.8 KB/sec)
37/37 KB   4/37 KB    
37/37 KB   8/37 KB   
37/37 KB   12/37 KB   
37/37 KB   16/37 KB   
37/37 KB   4/310 KB   16/37 KB   
37/37 KB   8/310 KB   16/37 KB   
37/37 KB   12/310 KB   16/37 KB   
37/37 KB   16/310 KB   16/37 KB   
37/37 KB   16/310 KB   20/37 KB   
37/37 KB   16/310 KB   24/37 KB   
37/37 KB   16/310 KB   28/37 KB   
37/37 KB   16/310 KB   32/37 KB   
37/37 KB   20/310 KB   32/37 KB   
37/37 KB   20/310 KB   36/37 KB   
37/37 KB   20/310 KB   37/37 KB   
37/37 KB   24/310 KB   37/37 KB   
37/37 KB   28/310 KB   37/37 KB   
37/37 KB   32/310 KB   37/37 KB   
                                  
Downloaded: https://repo.maven.apache.org/maven2/classworlds/classworlds/1.1/classworlds-1.1.jar (37 KB at 72.9 KB/sec)
36/310 KB   37/37 KB              
40/310 KB   37/37 KB   
44/310 KB   37/37 KB   
48/310 KB   37/37 KB   
52/310 KB   37/37 KB   
56/310 KB   37/37 KB   
60/310 KB   37/37 KB   
64/310 KB   37/37 KB   
68/310 KB   37/37 KB   
72/310 KB   37/37 KB   
76/310 KB   37/37 KB   
80/310 KB   37/37 KB   
                       
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/maven-toolchain/2.2.1/maven-toolchain-2.2.1.jar (37 KB at 70.3 KB/sec)
84/310 KB              
88/310 KB   
92/310 KB   
96/310 KB   
100/310 KB   
104/310 KB   
108/310 KB   
112/310 KB   
116/310 KB   
120/310 KB   
124/310 KB   
128/310 KB   
132/310 KB   
136/310 KB   
140/310 KB   
144/310 KB   
148/310 KB   
152/310 KB   
156/310 KB   
160/310 KB   
164/310 KB   
168/310 KB   
172/310 KB   
176/310 KB   
180/310 KB   
184/310 KB   
188/310 KB   
192/310 KB   
196/310 KB   
200/310 KB   
204/310 KB   
208/310 KB   
212/310 KB   
216/310 KB   
220/310 KB   
224/310 KB   
228/310 KB   
232/310 KB   
236/310 KB   
240/310 KB   
244/310 KB   
248/310 KB   
252/310 KB   
256/310 KB   
260/310 KB   
264/310 KB   
268/310 KB   
272/310 KB   
276/310 KB   
280/310 KB   
284/310 KB   
288/310 KB   
292/310 KB   
296/310 KB   
300/310 KB   
304/310 KB   
308/310 KB   
310/310 KB   
             
Downloaded: https://repo.maven.apache.org/maven2/com/thoughtworks/qdox/qdox/2.0-M8/qdox-2.0-M8.jar (310 KB at 513.3 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/surefire/surefire-junit-platform/2.22.2/surefire-junit-platform-2.22.2.pom
             
Downloading: https://repo.spring.io/milestone/org/apache/maven/surefire/surefire-junit-platform/2.22.2/surefire-junit-platform-2.22.2.pom
             
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-junit-platform/2.22.2/surefire-junit-platform-2.22.2.pom
4/7 KB       
7/7 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-junit-platform/2.22.2/surefire-junit-platform-2.22.2.pom (7 KB at 283.9 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/surefire/surefire-providers/2.22.2/surefire-providers-2.22.2.pom
         
Downloading: https://repo.spring.io/milestone/org/apache/maven/surefire/surefire-providers/2.22.2/surefire-providers-2.22.2.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-providers/2.22.2/surefire-providers-2.22.2.pom
3/3 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-providers/2.22.2/surefire-providers-2.22.2.pom (3 KB at 121.5 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/junit/platform/junit-platform-launcher/1.3.1/junit-platform-launcher-1.3.1.pom
         
Downloading: https://repo.spring.io/milestone/org/junit/platform/junit-platform-launcher/1.3.1/junit-platform-launcher-1.3.1.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-launcher/1.3.1/junit-platform-launcher-1.3.1.pom
3/3 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-launcher/1.3.1/junit-platform-launcher-1.3.1.pom (3 KB at 80.2 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apiguardian/apiguardian-api/1.0.0/apiguardian-api-1.0.0.pom
         
Downloading: https://repo.spring.io/milestone/org/apiguardian/apiguardian-api/1.0.0/apiguardian-api-1.0.0.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/apiguardian/apiguardian-api/1.0.0/apiguardian-api-1.0.0.pom
2/2 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/apiguardian/apiguardian-api/1.0.0/apiguardian-api-1.0.0.pom (2 KB at 49.6 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/junit/platform/junit-platform-engine/1.3.1/junit-platform-engine-1.3.1.pom
         
Downloading: https://repo.spring.io/milestone/org/junit/platform/junit-platform-engine/1.3.1/junit-platform-engine-1.3.1.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-engine/1.3.1/junit-platform-engine-1.3.1.pom
3/3 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-engine/1.3.1/junit-platform-engine-1.3.1.pom (3 KB at 97.4 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/junit/platform/junit-platform-commons/1.3.1/junit-platform-commons-1.3.1.pom
         
Downloading: https://repo.spring.io/milestone/org/junit/platform/junit-platform-commons/1.3.1/junit-platform-commons-1.3.1.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-commons/1.3.1/junit-platform-commons-1.3.1.pom
2/2 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-commons/1.3.1/junit-platform-commons-1.3.1.pom (2 KB at 116.2 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/opentest4j/opentest4j/1.1.1/opentest4j-1.1.1.pom
         
Downloading: https://repo.spring.io/milestone/org/opentest4j/opentest4j/1.1.1/opentest4j-1.1.1.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/opentest4j/opentest4j/1.1.1/opentest4j-1.1.1.pom
2/2 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/opentest4j/opentest4j/1.1.1/opentest4j-1.1.1.pom (2 KB at 86.5 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apiguardian/apiguardian-api/1.0.0/apiguardian-api-1.0.0.jar
Downloading: https://repo.spring.io/snapshot/org/apache/maven/surefire/surefire-junit-platform/2.22.2/surefire-junit-platform-2.22.2.jar
Downloading: https://repo.spring.io/snapshot/org/junit/platform/junit-platform-commons/1.3.1/junit-platform-commons-1.3.1.jar
Downloading: https://repo.spring.io/snapshot/org/junit/platform/junit-platform-engine/1.3.1/junit-platform-engine-1.3.1.jar
Downloading: https://repo.spring.io/snapshot/org/junit/platform/junit-platform-launcher/1.3.1/junit-platform-launcher-1.3.1.jar
         
Downloading: https://repo.spring.io/milestone/org/apiguardian/apiguardian-api/1.0.0/apiguardian-api-1.0.0.jar
         
Downloading: https://repo.spring.io/milestone/org/junit/platform/junit-platform-launcher/1.3.1/junit-platform-launcher-1.3.1.jar
         
Downloading: https://repo.spring.io/milestone/org/junit/platform/junit-platform-engine/1.3.1/junit-platform-engine-1.3.1.jar
         
         
Downloading: https://repo.spring.io/milestone/org/apache/maven/surefire/surefire-junit-platform/2.22.2/surefire-junit-platform-2.22.2.jar
Downloading: https://repo.spring.io/milestone/org/junit/platform/junit-platform-commons/1.3.1/junit-platform-commons-1.3.1.jar
         
Downloading: https://repo.maven.apache.org/maven2/org/apiguardian/apiguardian-api/1.0.0/apiguardian-api-1.0.0.jar
3/3 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/apiguardian/apiguardian-api/1.0.0/apiguardian-api-1.0.0.jar (3 KB at 81.3 KB/sec)
         
Downloading: https://repo.spring.io/snapshot/org/opentest4j/opentest4j/1.1.1/opentest4j-1.1.1.jar
Downloading: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-commons/1.3.1/junit-platform-commons-1.3.1.jar
         
         
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-junit-platform/2.22.2/surefire-junit-platform-2.22.2.jar
Downloading: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-launcher/1.3.1/junit-platform-launcher-1.3.1.jar
4/77 KB   
8/77 KB   
12/77 KB   
16/77 KB   
4/93 KB   16/77 KB   
8/93 KB   16/77 KB   
12/93 KB   16/77 KB   
16/93 KB   16/77 KB   
16/93 KB   20/77 KB   
16/93 KB   24/77 KB   
16/93 KB   28/77 KB   
16/93 KB   32/77 KB   
4/65 KB   16/93 KB   32/77 KB   
8/65 KB   16/93 KB   32/77 KB   
12/65 KB   16/93 KB   32/77 KB   
16/65 KB   16/93 KB   32/77 KB   
                                 
Downloading: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-engine/1.3.1/junit-platform-engine-1.3.1.jar
20/65 KB   16/93 KB   32/77 KB   
24/65 KB   16/93 KB   32/77 KB   
28/65 KB   16/93 KB   32/77 KB   
32/65 KB   16/93 KB   32/77 KB   
32/65 KB   20/93 KB   32/77 KB   
32/65 KB   24/93 KB   32/77 KB   
32/65 KB   28/93 KB   32/77 KB   
32/65 KB   32/93 KB   32/77 KB   
32/65 KB   36/93 KB   32/77 KB   
32/65 KB   40/93 KB   32/77 KB   
32/65 KB   44/93 KB   32/77 KB   
32/65 KB   48/93 KB   32/77 KB   
32/65 KB   48/93 KB   36/77 KB   
32/65 KB   48/93 KB   40/77 KB   
32/65 KB   48/93 KB   44/77 KB   
32/65 KB   48/93 KB   48/77 KB   
36/65 KB   48/93 KB   48/77 KB   
40/65 KB   48/93 KB   48/77 KB   
44/65 KB   48/93 KB   48/77 KB   
48/65 KB   48/93 KB   48/77 KB   
48/65 KB   52/93 KB   48/77 KB   
48/65 KB   56/93 KB   48/77 KB   
48/65 KB   60/93 KB   48/77 KB   
48/65 KB   64/93 KB   48/77 KB   
52/65 KB   64/93 KB   48/77 KB   
56/65 KB   64/93 KB   48/77 KB   
60/65 KB   64/93 KB   48/77 KB   
64/65 KB   64/93 KB   48/77 KB   
65/65 KB   64/93 KB   48/77 KB   
65/65 KB   64/93 KB   52/77 KB   
65/65 KB   64/93 KB   56/77 KB   
65/65 KB   64/93 KB   60/77 KB   
65/65 KB   64/93 KB   64/77 KB   
65/65 KB   4/132 KB   64/93 KB   64/77 KB   
65/65 KB   8/132 KB   64/93 KB   64/77 KB   
65/65 KB   12/132 KB   64/93 KB   64/77 KB   
65/65 KB   16/132 KB   64/93 KB   64/77 KB   
65/65 KB   16/132 KB   68/93 KB   64/77 KB   
65/65 KB   16/132 KB   72/93 KB   64/77 KB   
65/65 KB   16/132 KB   76/93 KB   64/77 KB   
65/65 KB   16/132 KB   80/93 KB   64/77 KB   
65/65 KB   16/132 KB   80/93 KB   68/77 KB   
65/65 KB   16/132 KB   80/93 KB   72/77 KB   
65/65 KB   16/132 KB   80/93 KB   76/77 KB   
65/65 KB   16/132 KB   80/93 KB   77/77 KB   
65/65 KB   20/132 KB   80/93 KB   77/77 KB   
65/65 KB   24/132 KB   80/93 KB   77/77 KB   
65/65 KB   28/132 KB   80/93 KB   77/77 KB   
65/65 KB   32/132 KB   80/93 KB   77/77 KB   
65/65 KB   32/132 KB   84/93 KB   77/77 KB   
65/65 KB   32/132 KB   88/93 KB   77/77 KB   
65/65 KB   32/132 KB   92/93 KB   77/77 KB   
65/65 KB   32/132 KB   93/93 KB   77/77 KB   
65/65 KB   36/132 KB   93/93 KB   77/77 KB   
65/65 KB   40/132 KB   93/93 KB   77/77 KB   
65/65 KB   44/132 KB   93/93 KB   77/77 KB   
65/65 KB   48/132 KB   93/93 KB   77/77 KB   
65/65 KB   52/132 KB   93/93 KB   77/77 KB   
65/65 KB   56/132 KB   93/93 KB   77/77 KB   
65/65 KB   60/132 KB   93/93 KB   77/77 KB   
65/65 KB   64/132 KB   93/93 KB   77/77 KB   
                                             
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-junit-platform/2.22.2/surefire-junit-platform-2.22.2.jar (65 KB at 906.6 KB/sec)
                                             
Downloaded: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-commons/1.3.1/junit-platform-commons-1.3.1.jar (77 KB at 1056.0 KB/sec)
                                             
Downloaded: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-launcher/1.3.1/junit-platform-launcher-1.3.1.jar (93 KB at 1249.0 KB/sec)
68/132 KB                                    
72/132 KB   
76/132 KB   
80/132 KB   
84/132 KB   
88/132 KB   
92/132 KB   
96/132 KB   
100/132 KB   
104/132 KB   
108/132 KB   
112/132 KB   
116/132 KB   
120/132 KB   
124/132 KB   
128/132 KB   
132/132 KB   
             
Downloaded: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-engine/1.3.1/junit-platform-engine-1.3.1.jar (132 KB at 1883.5 KB/sec)
             
Downloading: https://repo.spring.io/milestone/org/opentest4j/opentest4j/1.1.1/opentest4j-1.1.1.jar
             
Downloading: https://repo.maven.apache.org/maven2/org/opentest4j/opentest4j/1.1.1/opentest4j-1.1.1.jar
4/7 KB       
7/7 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/opentest4j/opentest4j/1.1.1/opentest4j-1.1.1.jar (7 KB at 267.5 KB/sec)
[INFO] 
[INFO] -------------------------------------------------------
[INFO]  T E S T S
[INFO] -------------------------------------------------------
[INFO] Running org.springframework.samples.petclinic.vet.VetTests
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.169 s - in org.springframework.samples.petclinic.vet.VetTests
[INFO] Running org.springframework.samples.petclinic.vet.VetControllerTests
14:05:03.255 [main] DEBUG org.springframework.test.context.BootstrapUtils - Instantiating CacheAwareContextLoaderDelegate from class [org.springframework.test.context.cache.DefaultCacheAwareContextLoaderDelegate]
14:05:03.344 [main] DEBUG org.springframework.test.context.BootstrapUtils - Instantiating BootstrapContext using constructor [public org.springframework.test.context.support.DefaultBootstrapContext(java.lang.Class,org.springframework.test.context.CacheAwareContextLoaderDelegate)]
14:05:03.427 [main] DEBUG org.springframework.test.context.BootstrapUtils - Instantiating TestContextBootstrapper for test class [org.springframework.samples.petclinic.vet.VetControllerTests] from class [org.springframework.boot.test.autoconfigure.web.servlet.WebMvcTestContextBootstrapper]
14:05:03.474 [main] INFO org.springframework.boot.test.autoconfigure.web.servlet.WebMvcTestContextBootstrapper - Neither @ContextConfiguration nor @ContextHierarchy found for test class [org.springframework.samples.petclinic.vet.VetControllerTests], using SpringBootContextLoader
14:05:03.481 [main] DEBUG org.springframework.test.context.support.AbstractContextLoader - Did not detect default resource location for test class [org.springframework.samples.petclinic.vet.VetControllerTests]: class path resource [org/springframework/samples/petclinic/vet/VetControllerTests-context.xml] does not exist
14:05:03.482 [main] DEBUG org.springframework.test.context.support.AbstractContextLoader - Did not detect default resource location for test class [org.springframework.samples.petclinic.vet.VetControllerTests]: class path resource [org/springframework/samples/petclinic/vet/VetControllerTestsContext.groovy] does not exist
14:05:03.482 [main] INFO org.springframework.test.context.support.AbstractContextLoader - Could not detect default resource locations for test class [org.springframework.samples.petclinic.vet.VetControllerTests]: no resource found for suffixes {-context.xml, Context.groovy}.
14:05:03.483 [main] INFO org.springframework.test.context.support.AnnotationConfigContextLoaderUtils - Could not detect default configuration classes for test class [org.springframework.samples.petclinic.vet.VetControllerTests]: VetControllerTests does not declare any static, non-private, non-final, nested classes annotated with @Configuration.
14:05:03.642 [main] DEBUG org.springframework.test.context.support.ActiveProfilesUtils - Could not find an 'annotation declaring class' for annotation type [org.springframework.test.context.ActiveProfiles] and class [org.springframework.samples.petclinic.vet.VetControllerTests]
14:05:03.807 [main] DEBUG org.springframework.context.annotation.ClassPathScanningCandidateComponentProvider - Identified candidate component class: file [/var/jenkins_home/workspace/spring-petclinic-hub/target/classes/org/springframework/samples/petclinic/PetClinicApplication.class]
14:05:03.807 [main] INFO org.springframework.boot.test.context.SpringBootTestContextBootstrapper - Found @SpringBootConfiguration org.springframework.samples.petclinic.PetClinicApplication for test class org.springframework.samples.petclinic.vet.VetControllerTests
14:05:03.810 [main] DEBUG org.springframework.boot.test.autoconfigure.web.servlet.WebMvcTestContextBootstrapper - @TestExecutionListeners is not present for class [org.springframework.samples.petclinic.vet.VetControllerTests]: using defaults.
14:05:03.810 [main] INFO org.springframework.boot.test.autoconfigure.web.servlet.WebMvcTestContextBootstrapper - Loaded default TestExecutionListener class names from location [META-INF/spring.factories]: [org.springframework.boot.test.mock.mockito.MockitoTestExecutionListener, org.springframework.boot.test.mock.mockito.ResetMocksTestExecutionListener, org.springframework.boot.test.autoconfigure.restdocs.RestDocsTestExecutionListener, org.springframework.boot.test.autoconfigure.web.client.MockRestServiceServerResetTestExecutionListener, org.springframework.boot.test.autoconfigure.web.servlet.MockMvcPrintOnlyOnFailureTestExecutionListener, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverTestExecutionListener, org.springframework.test.context.web.ServletTestExecutionListener, org.springframework.test.context.support.DirtiesContextBeforeModesTestExecutionListener, org.springframework.test.context.support.DependencyInjectionTestExecutionListener, org.springframework.test.context.support.DirtiesContextTestExecutionListener, org.springframework.test.context.transaction.TransactionalTestExecutionListener, org.springframework.test.context.jdbc.SqlScriptsTestExecutionListener, org.springframework.test.context.event.EventPublishingTestExecutionListener]
14:05:03.866 [main] INFO org.springframework.boot.test.autoconfigure.web.servlet.WebMvcTestContextBootstrapper - Using TestExecutionListeners: [org.springframework.test.context.web.ServletTestExecutionListener@4ae49387, org.springframework.test.context.support.DirtiesContextBeforeModesTestExecutionListener@6abb7b7d, org.springframework.boot.test.mock.mockito.MockitoTestExecutionListener@34cf0e80, org.springframework.boot.test.autoconfigure.SpringBootDependencyInjectionTestExecutionListener@38ef1a0a, org.springframework.test.context.support.DirtiesContextTestExecutionListener@56f9de3b, org.springframework.test.context.transaction.TransactionalTestExecutionListener@6728370a, org.springframework.test.context.jdbc.SqlScriptsTestExecutionListener@2b5f8e61, org.springframework.test.context.event.EventPublishingTestExecutionListener@6ba0ee4a, org.springframework.boot.test.mock.mockito.ResetMocksTestExecutionListener@73b0ed03, org.springframework.boot.test.autoconfigure.restdocs.RestDocsTestExecutionListener@55061418, org.springframework.boot.test.autoconfigure.web.client.MockRestServiceServerResetTestExecutionListener@27db45f, org.springframework.boot.test.autoconfigure.web.servlet.MockMvcPrintOnlyOnFailureTestExecutionListener@6ec3d8e4, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverTestExecutionListener@1aeff8ca]
14:05:03.875 [main] DEBUG org.springframework.test.context.support.AbstractDirtiesContextTestExecutionListener - Before test class: context [DefaultTestContext@2211b44f testClass = VetControllerTests, testInstance = [null], testMethod = [null], testException = [null], mergedContextConfiguration = [WebMergedContextConfiguration@6c830ebd testClass = VetControllerTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.web.servlet.WebMvcTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@15f519f7 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.context.MessageSourceAutoConfiguration, org.springframework.boot.autoconfigure.data.web.SpringDataWebAutoConfiguration, org.springframework.boot.autoconfigure.freemarker.FreeMarkerAutoConfiguration, org.springframework.boot.autoconfigure.groovy.template.GroovyTemplateAutoConfiguration, org.springframework.boot.autoconfigure.gson.GsonAutoConfiguration, org.springframework.boot.autoconfigure.hateoas.HypermediaAutoConfiguration, org.springframework.boot.autoconfigure.http.HttpMessageConvertersAutoConfiguration, org.springframework.boot.autoconfigure.jackson.JacksonAutoConfiguration, org.springframework.boot.autoconfigure.jsonb.JsonbAutoConfiguration, org.springframework.boot.autoconfigure.mustache.MustacheAutoConfiguration, org.springframework.boot.autoconfigure.task.TaskExecutionAutoConfiguration, org.springframework.boot.autoconfigure.thymeleaf.ThymeleafAutoConfiguration, org.springframework.boot.autoconfigure.validation.ValidationAutoConfiguration, org.springframework.boot.autoconfigure.web.servlet.error.ErrorMvcAutoConfiguration, org.springframework.boot.autoconfigure.web.servlet.WebMvcAutoConfiguration, org.springframework.boot.test.autoconfigure.web.servlet.MockMvcAutoConfiguration, org.springframework.boot.test.autoconfigure.web.servlet.MockMvcWebClientAutoConfiguration, org.springframework.boot.test.autoconfigure.web.servlet.MockMvcWebDriverAutoConfiguration, org.springframework.boot.autoconfigure.security.servlet.SecurityAutoConfiguration, org.springframework.boot.autoconfigure.security.servlet.UserDetailsServiceAutoConfiguration, org.springframework.boot.test.autoconfigure.web.servlet.MockMvcSecurityConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@219447cb, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@96d93bd0, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@49fe1c0f, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], resourceBasePath = 'src/main/webapp', contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]], class annotated with @DirtiesContext [false] with mode [null].
14:05:04.348 [main] DEBUG org.springframework.test.context.support.TestPropertySourceUtils - Adding inlined properties to environment: {spring.jmx.enabled=false, org.springframework.boot.test.autoconfigure.web.servlet.WebMvcTestContextBootstrapper=true, server.port=-1}


              |\      _,,,--,,_
             /,`.-'`'   ._  \-;;,_
  _______ __|,4-  ) )_   .;.(__`'-'__     ___ __    _ ___ _______
 |       | '---''(_/._)-'(_\_)   |   |   |   |  |  | |   |       |
 |    _  |    ___|_     _|       |   |   |   |   |_| |   |       | __ _ _
 |   |_| |   |___  |   | |       |   |   |   |       |   |       | \ \ \ \
 |    ___|    ___| |   | |      _|   |___|   |  _    |   |      _|  \ \ \ \
 |   |   |   |___  |   | |     |_|       |   | | |   |   |     |_    ) ) ) )
 |___|   |_______| |___| |_______|_______|___|_|  |__|___|_______|  / / / /
 ==================================================================/_/_/_/

:: Built with Spring Boot :: 2.2.2.RELEASE


2023-06-16 14:05:05.519  INFO 1158 --- [           main] o.s.s.petclinic.vet.VetControllerTests   : Starting VetControllerTests on 3467ac7d3468 with PID 1158 (started by root in /var/jenkins_home/workspace/spring-petclinic-hub)
2023-06-16 14:05:05.524  INFO 1158 --- [           main] o.s.s.petclinic.vet.VetControllerTests   : No active profile set, falling back to default profiles: default
2023-06-16 14:05:08.782  INFO 1158 --- [           main] o.s.s.concurrent.ThreadPoolTaskExecutor  : Initializing ExecutorService 'applicationTaskExecutor'
2023-06-16 14:05:11.008  INFO 1158 --- [           main] o.s.b.t.m.w.SpringBootMockServletContext : Initializing Spring TestDispatcherServlet ''
2023-06-16 14:05:11.008  INFO 1158 --- [           main] o.s.t.web.servlet.TestDispatcherServlet  : Initializing Servlet ''
2023-06-16 14:05:11.043  INFO 1158 --- [           main] o.s.t.web.servlet.TestDispatcherServlet  : Completed initialization in 35 ms
2023-06-16 14:05:11.121  INFO 1158 --- [           main] o.s.s.petclinic.vet.VetControllerTests   : Started VetControllerTests in 6.742 seconds (JVM running for 10.011)
[INFO] Tests run: 2, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 9.212 s - in org.springframework.samples.petclinic.vet.VetControllerTests
[INFO] Running org.springframework.samples.petclinic.model.ValidatorTests
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.31 s - in org.springframework.samples.petclinic.model.ValidatorTests
[INFO] Running org.springframework.samples.petclinic.system.CrashControllerTests
[WARNING] Tests run: 1, Failures: 0, Errors: 0, Skipped: 1, Time elapsed: 0.001 s - in org.springframework.samples.petclinic.system.CrashControllerTests
[INFO] Running org.springframework.samples.petclinic.PetclinicIntegrationTests
2023-06-16 14:05:12.649  INFO 1158 --- [           main] .b.t.c.SpringBootTestContextBootstrapper : Neither @ContextConfiguration nor @ContextHierarchy found for test class [org.springframework.samples.petclinic.PetclinicIntegrationTests], using SpringBootContextLoader
2023-06-16 14:05:12.650  INFO 1158 --- [           main] o.s.t.c.support.AbstractContextLoader    : Could not detect default resource locations for test class [org.springframework.samples.petclinic.PetclinicIntegrationTests]: no resource found for suffixes {-context.xml, Context.groovy}.
2023-06-16 14:05:12.650  INFO 1158 --- [           main] t.c.s.AnnotationConfigContextLoaderUtils : Could not detect default configuration classes for test class [org.springframework.samples.petclinic.PetclinicIntegrationTests]: PetclinicIntegrationTests does not declare any static, non-private, non-final, nested classes annotated with @Configuration.
2023-06-16 14:05:12.667  INFO 1158 --- [           main] .b.t.c.SpringBootTestContextBootstrapper : Found @SpringBootConfiguration org.springframework.samples.petclinic.PetClinicApplication for test class org.springframework.samples.petclinic.PetclinicIntegrationTests
2023-06-16 14:05:12.669  INFO 1158 --- [           main] .b.t.c.SpringBootTestContextBootstrapper : Loaded default TestExecutionListener class names from location [META-INF/spring.factories]: [org.springframework.boot.test.mock.mockito.MockitoTestExecutionListener, org.springframework.boot.test.mock.mockito.ResetMocksTestExecutionListener, org.springframework.boot.test.autoconfigure.restdocs.RestDocsTestExecutionListener, org.springframework.boot.test.autoconfigure.web.client.MockRestServiceServerResetTestExecutionListener, org.springframework.boot.test.autoconfigure.web.servlet.MockMvcPrintOnlyOnFailureTestExecutionListener, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverTestExecutionListener, org.springframework.test.context.web.ServletTestExecutionListener, org.springframework.test.context.support.DirtiesContextBeforeModesTestExecutionListener, org.springframework.test.context.support.DependencyInjectionTestExecutionListener, org.springframework.test.context.support.DirtiesContextTestExecutionListener, org.springframework.test.context.transaction.TransactionalTestExecutionListener, org.springframework.test.context.jdbc.SqlScriptsTestExecutionListener, org.springframework.test.context.event.EventPublishingTestExecutionListener]
2023-06-16 14:05:12.671  INFO 1158 --- [           main] .b.t.c.SpringBootTestContextBootstrapper : Using TestExecutionListeners: [org.springframework.test.context.web.ServletTestExecutionListener@1b6edd3f, org.springframework.test.context.support.DirtiesContextBeforeModesTestExecutionListener@6a795ef6, org.springframework.boot.test.mock.mockito.MockitoTestExecutionListener@33518754, org.springframework.boot.test.autoconfigure.SpringBootDependencyInjectionTestExecutionListener@4d74c01d, org.springframework.test.context.support.DirtiesContextTestExecutionListener@201e7ba9, org.springframework.test.context.transaction.TransactionalTestExecutionListener@301fb2, org.springframework.test.context.jdbc.SqlScriptsTestExecutionListener@3f6443c7, org.springframework.test.context.event.EventPublishingTestExecutionListener@547b081e, org.springframework.boot.test.mock.mockito.ResetMocksTestExecutionListener@76be20b, org.springframework.boot.test.autoconfigure.restdocs.RestDocsTestExecutionListener@7a6a0db, org.springframework.boot.test.autoconfigure.web.client.MockRestServiceServerResetTestExecutionListener@1a41a193, org.springframework.boot.test.autoconfigure.web.servlet.MockMvcPrintOnlyOnFailureTestExecutionListener@1676713d, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverTestExecutionListener@4e55a242]


              |\      _,,,--,,_
             /,`.-'`'   ._  \-;;,_
  _______ __|,4-  ) )_   .;.(__`'-'__     ___ __    _ ___ _______
 |       | '---''(_/._)-'(_\_)   |   |   |   |  |  | |   |       |
 |    _  |    ___|_     _|       |   |   |   |   |_| |   |       | __ _ _
 |   |_| |   |___  |   | |       |   |   |   |       |   |       | \ \ \ \
 |    ___|    ___| |   | |      _|   |___|   |  _    |   |      _|  \ \ \ \
 |   |   |   |___  |   | |     |_|       |   | | |   |   |     |_    ) ) ) )
 |___|   |_______| |___| |_______|_______|___|_|  |__|___|_______|  / / / /
 ==================================================================/_/_/_/

:: Built with Spring Boot :: 2.2.2.RELEASE


2023-06-16 14:05:12.752  INFO 1158 --- [           main] o.s.s.p.PetclinicIntegrationTests        : Starting PetclinicIntegrationTests on 3467ac7d3468 with PID 1158 (started by root in /var/jenkins_home/workspace/spring-petclinic-hub)
2023-06-16 14:05:12.754  INFO 1158 --- [           main] o.s.s.p.PetclinicIntegrationTests        : No active profile set, falling back to default profiles: default
2023-06-16 14:05:14.166  INFO 1158 --- [           main] .s.d.r.c.RepositoryConfigurationDelegate : Bootstrapping Spring Data JPA repositories in DEFAULT mode.
2023-06-16 14:05:14.309  INFO 1158 --- [           main] .s.d.r.c.RepositoryConfigurationDelegate : Finished Spring Data repository scanning in 115ms. Found 4 JPA repository interfaces.
2023-06-16 14:05:14.771  INFO 1158 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.transaction.annotation.ProxyTransactionManagementConfiguration' of type [org.springframework.transaction.annotation.ProxyTransactionManagementConfiguration] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2023-06-16 14:05:15.437  INFO 1158 --- [           main] org.ehcache.core.EhcacheManager          : Cache 'vets' created in EhcacheManager.
2023-06-16 14:05:15.457  INFO 1158 --- [           main] org.ehcache.jsr107.Eh107CacheManager     : Registering Ehcache MBean javax.cache:type=CacheStatistics,CacheManager=urn.X-ehcache.jsr107-default-config,Cache=vets
2023-06-16 14:05:15.484  INFO 1158 --- [           main] org.ehcache.jsr107.Eh107CacheManager     : Registering Ehcache MBean javax.cache:type=CacheStatistics,CacheManager=urn.X-ehcache.jsr107-default-config,Cache=vets
2023-06-16 14:05:15.587  INFO 1158 --- [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Starting...
2023-06-16 14:05:15.593  WARN 1158 --- [           main] com.zaxxer.hikari.util.DriverDataSource  : Registered driver with driverClassName=org.hsqldb.jdbcDriver was not found, trying direct instantiation.
2023-06-16 14:05:16.282  INFO 1158 --- [           main] com.zaxxer.hikari.pool.PoolBase          : HikariPool-1 - Driver does not support get/set network timeout for connections. (feature not supported)
2023-06-16 14:05:16.291  INFO 1158 --- [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Start completed.
2023-06-16 14:05:16.753  INFO 1158 --- [           main] o.hibernate.jpa.internal.util.LogHelper  : HHH000204: Processing PersistenceUnitInfo [name: default]
2023-06-16 14:05:16.941  INFO 1158 --- [           main] org.hibernate.Version                    : HHH000412: Hibernate Core {5.4.9.Final}
2023-06-16 14:05:17.043  INFO 1158 --- [           main] o.hibernate.annotations.common.Version   : HCANN000001: Hibernate Commons Annotations {5.1.0.Final}
2023-06-16 14:05:17.325  INFO 1158 --- [           main] org.hibernate.dialect.Dialect            : HHH000400: Using dialect: org.hibernate.dialect.HSQLDialect
2023-06-16 14:05:18.664  INFO 1158 --- [           main] o.h.e.t.j.p.i.JtaPlatformInitiator       : HHH000490: Using JtaPlatform implementation: [org.hibernate.engine.transaction.jta.platform.internal.NoJtaPlatform]
2023-06-16 14:05:18.676  INFO 1158 --- [           main] j.LocalContainerEntityManagerFactoryBean : Initialized JPA EntityManagerFactory for persistence unit 'default'
2023-06-16 14:05:20.113  WARN 1158 --- [           main] JpaBaseConfiguration$JpaWebConfiguration : spring.jpa.open-in-view is enabled by default. Therefore, database queries may be performed during view rendering. Explicitly configure spring.jpa.open-in-view to disable this warning
2023-06-16 14:05:20.451  INFO 1158 --- [           main] o.s.s.concurrent.ThreadPoolTaskExecutor  : Initializing ExecutorService 'applicationTaskExecutor'
2023-06-16 14:05:22.323  INFO 1158 --- [           main] o.s.b.a.e.web.EndpointLinksResolver      : Exposing 13 endpoint(s) beneath base path '/manage'
2023-06-16 14:05:22.411  INFO 1158 --- [           main] o.s.s.p.PetclinicIntegrationTests        : Started PetclinicIntegrationTests in 9.735 seconds (JVM running for 21.302)
[INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 10.086 s - in org.springframework.samples.petclinic.PetclinicIntegrationTests
[INFO] Running org.springframework.samples.petclinic.owner.VisitControllerTests
2023-06-16 14:05:22.771  INFO 1158 --- [           main] .b.t.a.w.s.WebMvcTestContextBootstrapper : Neither @ContextConfiguration nor @ContextHierarchy found for test class [org.springframework.samples.petclinic.owner.VisitControllerTests], using SpringBootContextLoader
2023-06-16 14:05:22.776  INFO 1158 --- [           main] o.s.t.c.support.AbstractContextLoader    : Could not detect default resource locations for test class [org.springframework.samples.petclinic.owner.VisitControllerTests]: no resource found for suffixes {-context.xml, Context.groovy}.
2023-06-16 14:05:22.780  INFO 1158 --- [           main] t.c.s.AnnotationConfigContextLoaderUtils : Could not detect default configuration classes for test class [org.springframework.samples.petclinic.owner.VisitControllerTests]: VisitControllerTests does not declare any static, non-private, non-final, nested classes annotated with @Configuration.
2023-06-16 14:05:22.804  INFO 1158 --- [           main] .b.t.c.SpringBootTestContextBootstrapper : Found @SpringBootConfiguration org.springframework.samples.petclinic.PetClinicApplication for test class org.springframework.samples.petclinic.owner.VisitControllerTests
2023-06-16 14:05:22.805  INFO 1158 --- [           main] .b.t.a.w.s.WebMvcTestContextBootstrapper : Loaded default TestExecutionListener class names from location [META-INF/spring.factories]: [org.springframework.boot.test.mock.mockito.MockitoTestExecutionListener, org.springframework.boot.test.mock.mockito.ResetMocksTestExecutionListener, org.springframework.boot.test.autoconfigure.restdocs.RestDocsTestExecutionListener, org.springframework.boot.test.autoconfigure.web.client.MockRestServiceServerResetTestExecutionListener, org.springframework.boot.test.autoconfigure.web.servlet.MockMvcPrintOnlyOnFailureTestExecutionListener, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverTestExecutionListener, org.springframework.test.context.web.ServletTestExecutionListener, org.springframework.test.context.support.DirtiesContextBeforeModesTestExecutionListener, org.springframework.test.context.support.DependencyInjectionTestExecutionListener, org.springframework.test.context.support.DirtiesContextTestExecutionListener, org.springframework.test.context.transaction.TransactionalTestExecutionListener, org.springframework.test.context.jdbc.SqlScriptsTestExecutionListener, org.springframework.test.context.event.EventPublishingTestExecutionListener]
2023-06-16 14:05:22.806  INFO 1158 --- [           main] .b.t.a.w.s.WebMvcTestContextBootstrapper : Using TestExecutionListeners: [org.springframework.test.context.web.ServletTestExecutionListener@54e29dd1, org.springframework.test.context.support.DirtiesContextBeforeModesTestExecutionListener@552bd37b, org.springframework.boot.test.mock.mockito.MockitoTestExecutionListener@61a861da, org.springframework.boot.test.autoconfigure.SpringBootDependencyInjectionTestExecutionListener@5f582a47, org.springframework.test.context.support.DirtiesContextTestExecutionListener@1f143868, org.springframework.test.context.transaction.TransactionalTestExecutionListener@142f80fa, org.springframework.test.context.jdbc.SqlScriptsTestExecutionListener@36ab8514, org.springframework.test.context.event.EventPublishingTestExecutionListener@283f8b94, org.springframework.boot.test.mock.mockito.ResetMocksTestExecutionListener@16562183, org.springframework.boot.test.autoconfigure.restdocs.RestDocsTestExecutionListener@7e964be3, org.springframework.boot.test.autoconfigure.web.client.MockRestServiceServerResetTestExecutionListener@14ffe200, org.springframework.boot.test.autoconfigure.web.servlet.MockMvcPrintOnlyOnFailureTestExecutionListener@4048b820, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverTestExecutionListener@6735d393]


              |\      _,,,--,,_
             /,`.-'`'   ._  \-;;,_
  _______ __|,4-  ) )_   .;.(__`'-'__     ___ __    _ ___ _______
 |       | '---''(_/._)-'(_\_)   |   |   |   |  |  | |   |       |
 |    _  |    ___|_     _|       |   |   |   |   |_| |   |       | __ _ _
 |   |_| |   |___  |   | |       |   |   |   |       |   |       | \ \ \ \
 |    ___|    ___| |   | |      _|   |___|   |  _    |   |      _|  \ \ \ \
 |   |   |   |___  |   | |     |_|       |   | | |   |   |     |_    ) ) ) )
 |___|   |_______| |___| |_______|_______|___|_|  |__|___|_______|  / / / /
 ==================================================================/_/_/_/

:: Built with Spring Boot :: 2.2.2.RELEASE


2023-06-16 14:05:22.854  INFO 1158 --- [           main] o.s.s.p.owner.VisitControllerTests       : Starting VisitControllerTests on 3467ac7d3468 with PID 1158 (started by root in /var/jenkins_home/workspace/spring-petclinic-hub)
2023-06-16 14:05:22.856  INFO 1158 --- [           main] o.s.s.p.owner.VisitControllerTests       : No active profile set, falling back to default profiles: default
2023-06-16 14:05:23.412  INFO 1158 --- [           main] o.s.s.concurrent.ThreadPoolTaskExecutor  : Initializing ExecutorService 'applicationTaskExecutor'
2023-06-16 14:05:24.692  INFO 1158 --- [           main] o.s.b.t.m.w.SpringBootMockServletContext : Initializing Spring TestDispatcherServlet ''
2023-06-16 14:05:24.692  INFO 1158 --- [           main] o.s.t.web.servlet.TestDispatcherServlet  : Initializing Servlet ''
2023-06-16 14:05:24.702  INFO 1158 --- [           main] o.s.t.web.servlet.TestDispatcherServlet  : Completed initialization in 10 ms
2023-06-16 14:05:24.718  INFO 1158 --- [           main] o.s.s.p.owner.VisitControllerTests       : Started VisitControllerTests in 1.905 seconds (JVM running for 23.608)
[INFO] Tests run: 3, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 2.183 s - in org.springframework.samples.petclinic.owner.VisitControllerTests
[INFO] Running org.springframework.samples.petclinic.owner.PetTypeFormatterTests
[INFO] Tests run: 3, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.046 s - in org.springframework.samples.petclinic.owner.PetTypeFormatterTests
[INFO] Running org.springframework.samples.petclinic.owner.PetControllerTests
2023-06-16 14:05:25.021  INFO 1158 --- [           main] .b.t.a.w.s.WebMvcTestContextBootstrapper : Neither @ContextConfiguration nor @ContextHierarchy found for test class [org.springframework.samples.petclinic.owner.PetControllerTests], using SpringBootContextLoader
2023-06-16 14:05:25.021  INFO 1158 --- [           main] o.s.t.c.support.AbstractContextLoader    : Could not detect default resource locations for test class [org.springframework.samples.petclinic.owner.PetControllerTests]: no resource found for suffixes {-context.xml, Context.groovy}.
2023-06-16 14:05:25.022  INFO 1158 --- [           main] t.c.s.AnnotationConfigContextLoaderUtils : Could not detect default configuration classes for test class [org.springframework.samples.petclinic.owner.PetControllerTests]: PetControllerTests does not declare any static, non-private, non-final, nested classes annotated with @Configuration.
2023-06-16 14:05:25.028  INFO 1158 --- [           main] .b.t.c.SpringBootTestContextBootstrapper : Found @SpringBootConfiguration org.springframework.samples.petclinic.PetClinicApplication for test class org.springframework.samples.petclinic.owner.PetControllerTests
2023-06-16 14:05:25.032  INFO 1158 --- [           main] .b.t.a.w.s.WebMvcTestContextBootstrapper : Loaded default TestExecutionListener class names from location [META-INF/spring.factories]: [org.springframework.boot.test.mock.mockito.MockitoTestExecutionListener, org.springframework.boot.test.mock.mockito.ResetMocksTestExecutionListener, org.springframework.boot.test.autoconfigure.restdocs.RestDocsTestExecutionListener, org.springframework.boot.test.autoconfigure.web.client.MockRestServiceServerResetTestExecutionListener, org.springframework.boot.test.autoconfigure.web.servlet.MockMvcPrintOnlyOnFailureTestExecutionListener, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverTestExecutionListener, org.springframework.test.context.web.ServletTestExecutionListener, org.springframework.test.context.support.DirtiesContextBeforeModesTestExecutionListener, org.springframework.test.context.support.DependencyInjectionTestExecutionListener, org.springframework.test.context.support.DirtiesContextTestExecutionListener, org.springframework.test.context.transaction.TransactionalTestExecutionListener, org.springframework.test.context.jdbc.SqlScriptsTestExecutionListener, org.springframework.test.context.event.EventPublishingTestExecutionListener]
2023-06-16 14:05:25.032  INFO 1158 --- [           main] .b.t.a.w.s.WebMvcTestContextBootstrapper : Using TestExecutionListeners: [org.springframework.test.context.web.ServletTestExecutionListener@58eb2e65, org.springframework.test.context.support.DirtiesContextBeforeModesTestExecutionListener@5c771407, org.springframework.boot.test.mock.mockito.MockitoTestExecutionListener@189c4e3a, org.springframework.boot.test.autoconfigure.SpringBootDependencyInjectionTestExecutionListener@2a82be56, org.springframework.test.context.support.DirtiesContextTestExecutionListener@2b9b2565, org.springframework.test.context.transaction.TransactionalTestExecutionListener@4f28cb3d, org.springframework.test.context.jdbc.SqlScriptsTestExecutionListener@35bfa17c, org.springframework.test.context.event.EventPublishingTestExecutionListener@af0c993, org.springframework.boot.test.mock.mockito.ResetMocksTestExecutionListener@783265a5, org.springframework.boot.test.autoconfigure.restdocs.RestDocsTestExecutionListener@71ca28bd, org.springframework.boot.test.autoconfigure.web.client.MockRestServiceServerResetTestExecutionListener@3936d3b9, org.springframework.boot.test.autoconfigure.web.servlet.MockMvcPrintOnlyOnFailureTestExecutionListener@3586395d, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverTestExecutionListener@5ef26d05]


              |\      _,,,--,,_
             /,`.-'`'   ._  \-;;,_
  _______ __|,4-  ) )_   .;.(__`'-'__     ___ __    _ ___ _______
 |       | '---''(_/._)-'(_\_)   |   |   |   |  |  | |   |       |
 |    _  |    ___|_     _|       |   |   |   |   |_| |   |       | __ _ _
 |   |_| |   |___  |   | |       |   |   |   |       |   |       | \ \ \ \
 |    ___|    ___| |   | |      _|   |___|   |  _    |   |      _|  \ \ \ \
 |   |   |   |___  |   | |     |_|       |   | | |   |   |     |_    ) ) ) )
 |___|   |_______| |___| |_______|_______|___|_|  |__|___|_______|  / / / /
 ==================================================================/_/_/_/

:: Built with Spring Boot :: 2.2.2.RELEASE


2023-06-16 14:05:25.067  INFO 1158 --- [           main] o.s.s.p.owner.PetControllerTests         : Starting PetControllerTests on 3467ac7d3468 with PID 1158 (started by root in /var/jenkins_home/workspace/spring-petclinic-hub)
2023-06-16 14:05:25.068  INFO 1158 --- [           main] o.s.s.p.owner.PetControllerTests         : No active profile set, falling back to default profiles: default
2023-06-16 14:05:25.423  INFO 1158 --- [           main] o.s.s.concurrent.ThreadPoolTaskExecutor  : Initializing ExecutorService 'applicationTaskExecutor'
2023-06-16 14:05:26.092  INFO 1158 --- [           main] o.s.b.t.m.w.SpringBootMockServletContext : Initializing Spring TestDispatcherServlet ''
2023-06-16 14:05:26.092  INFO 1158 --- [           main] o.s.t.web.servlet.TestDispatcherServlet  : Initializing Servlet ''
2023-06-16 14:05:26.101  INFO 1158 --- [           main] o.s.t.web.servlet.TestDispatcherServlet  : Completed initialization in 9 ms
2023-06-16 14:05:26.115  INFO 1158 --- [           main] o.s.s.p.owner.PetControllerTests         : Started PetControllerTests in 1.078 seconds (JVM running for 25.006)
[INFO] Tests run: 6, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 1.314 s - in org.springframework.samples.petclinic.owner.PetControllerTests
[INFO] Running org.springframework.samples.petclinic.owner.OwnerControllerTests
2023-06-16 14:05:26.335  INFO 1158 --- [           main] .b.t.a.w.s.WebMvcTestContextBootstrapper : Neither @ContextConfiguration nor @ContextHierarchy found for test class [org.springframework.samples.petclinic.owner.OwnerControllerTests], using SpringBootContextLoader
2023-06-16 14:05:26.335  INFO 1158 --- [           main] o.s.t.c.support.AbstractContextLoader    : Could not detect default resource locations for test class [org.springframework.samples.petclinic.owner.OwnerControllerTests]: no resource found for suffixes {-context.xml, Context.groovy}.
2023-06-16 14:05:26.336  INFO 1158 --- [           main] t.c.s.AnnotationConfigContextLoaderUtils : Could not detect default configuration classes for test class [org.springframework.samples.petclinic.owner.OwnerControllerTests]: OwnerControllerTests does not declare any static, non-private, non-final, nested classes annotated with @Configuration.
2023-06-16 14:05:26.338  INFO 1158 --- [           main] .b.t.c.SpringBootTestContextBootstrapper : Found @SpringBootConfiguration org.springframework.samples.petclinic.PetClinicApplication for test class org.springframework.samples.petclinic.owner.OwnerControllerTests
2023-06-16 14:05:26.339  INFO 1158 --- [           main] .b.t.a.w.s.WebMvcTestContextBootstrapper : Loaded default TestExecutionListener class names from location [META-INF/spring.factories]: [org.springframework.boot.test.mock.mockito.MockitoTestExecutionListener, org.springframework.boot.test.mock.mockito.ResetMocksTestExecutionListener, org.springframework.boot.test.autoconfigure.restdocs.RestDocsTestExecutionListener, org.springframework.boot.test.autoconfigure.web.client.MockRestServiceServerResetTestExecutionListener, org.springframework.boot.test.autoconfigure.web.servlet.MockMvcPrintOnlyOnFailureTestExecutionListener, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverTestExecutionListener, org.springframework.test.context.web.ServletTestExecutionListener, org.springframework.test.context.support.DirtiesContextBeforeModesTestExecutionListener, org.springframework.test.context.support.DependencyInjectionTestExecutionListener, org.springframework.test.context.support.DirtiesContextTestExecutionListener, org.springframework.test.context.transaction.TransactionalTestExecutionListener, org.springframework.test.context.jdbc.SqlScriptsTestExecutionListener, org.springframework.test.context.event.EventPublishingTestExecutionListener]
2023-06-16 14:05:26.340  INFO 1158 --- [           main] .b.t.a.w.s.WebMvcTestContextBootstrapper : Using TestExecutionListeners: [org.springframework.test.context.web.ServletTestExecutionListener@1897a01, org.springframework.test.context.support.DirtiesContextBeforeModesTestExecutionListener@3c5298b0, org.springframework.boot.test.mock.mockito.MockitoTestExecutionListener@1a6f5e8b, org.springframework.boot.test.autoconfigure.SpringBootDependencyInjectionTestExecutionListener@6fcbeb8e, org.springframework.test.context.support.DirtiesContextTestExecutionListener@25d8dd04, org.springframework.test.context.transaction.TransactionalTestExecutionListener@d674617, org.springframework.test.context.jdbc.SqlScriptsTestExecutionListener@6d9cca36, org.springframework.test.context.event.EventPublishingTestExecutionListener@5dbbdb90, org.springframework.boot.test.mock.mockito.ResetMocksTestExecutionListener@3ee81dde, org.springframework.boot.test.autoconfigure.restdocs.RestDocsTestExecutionListener@908b3ea, org.springframework.boot.test.autoconfigure.web.client.MockRestServiceServerResetTestExecutionListener@2ce1587, org.springframework.boot.test.autoconfigure.web.servlet.MockMvcPrintOnlyOnFailureTestExecutionListener@12a3915, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverTestExecutionListener@7f52d203]


              |\      _,,,--,,_
             /,`.-'`'   ._  \-;;,_
  _______ __|,4-  ) )_   .;.(__`'-'__     ___ __    _ ___ _______
 |       | '---''(_/._)-'(_\_)   |   |   |   |  |  | |   |       |
 |    _  |    ___|_     _|       |   |   |   |   |_| |   |       | __ _ _
 |   |_| |   |___  |   | |       |   |   |   |       |   |       | \ \ \ \
 |    ___|    ___| |   | |      _|   |___|   |  _    |   |      _|  \ \ \ \
 |   |   |   |___  |   | |     |_|       |   | | |   |   |     |_    ) ) ) )
 |___|   |_______| |___| |_______|_______|___|_|  |__|___|_______|  / / / /
 ==================================================================/_/_/_/

:: Built with Spring Boot :: 2.2.2.RELEASE


2023-06-16 14:05:26.362  INFO 1158 --- [           main] o.s.s.p.owner.OwnerControllerTests       : Starting OwnerControllerTests on 3467ac7d3468 with PID 1158 (started by root in /var/jenkins_home/workspace/spring-petclinic-hub)
2023-06-16 14:05:26.363  INFO 1158 --- [           main] o.s.s.p.owner.OwnerControllerTests       : No active profile set, falling back to default profiles: default
2023-06-16 14:05:26.741  INFO 1158 --- [           main] o.s.s.concurrent.ThreadPoolTaskExecutor  : Initializing ExecutorService 'applicationTaskExecutor'
2023-06-16 14:05:27.257  INFO 1158 --- [           main] o.s.b.t.m.w.SpringBootMockServletContext : Initializing Spring TestDispatcherServlet ''
2023-06-16 14:05:27.258  INFO 1158 --- [           main] o.s.t.web.servlet.TestDispatcherServlet  : Initializing Servlet ''
2023-06-16 14:05:27.267  INFO 1158 --- [           main] o.s.t.web.servlet.TestDispatcherServlet  : Completed initialization in 9 ms
2023-06-16 14:05:27.281  INFO 1158 --- [           main] o.s.s.p.owner.OwnerControllerTests       : Started OwnerControllerTests in 0.938 seconds (JVM running for 26.171)
[INFO] Tests run: 11, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 1.285 s - in org.springframework.samples.petclinic.owner.OwnerControllerTests
[INFO] Running org.springframework.samples.petclinic.service.ClinicServiceTests
2023-06-16 14:05:27.624  INFO 1158 --- [           main] b.t.a.o.j.DataJpaTestContextBootstrapper : Neither @ContextConfiguration nor @ContextHierarchy found for test class [org.springframework.samples.petclinic.service.ClinicServiceTests], using SpringBootContextLoader
2023-06-16 14:05:27.625  INFO 1158 --- [           main] o.s.t.c.support.AbstractContextLoader    : Could not detect default resource locations for test class [org.springframework.samples.petclinic.service.ClinicServiceTests]: no resource found for suffixes {-context.xml, Context.groovy}.
2023-06-16 14:05:27.625  INFO 1158 --- [           main] t.c.s.AnnotationConfigContextLoaderUtils : Could not detect default configuration classes for test class [org.springframework.samples.petclinic.service.ClinicServiceTests]: ClinicServiceTests does not declare any static, non-private, non-final, nested classes annotated with @Configuration.
2023-06-16 14:05:27.630  INFO 1158 --- [           main] .b.t.c.SpringBootTestContextBootstrapper : Found @SpringBootConfiguration org.springframework.samples.petclinic.PetClinicApplication for test class org.springframework.samples.petclinic.service.ClinicServiceTests
2023-06-16 14:05:27.630  INFO 1158 --- [           main] b.t.a.o.j.DataJpaTestContextBootstrapper : Loaded default TestExecutionListener class names from location [META-INF/spring.factories]: [org.springframework.boot.test.mock.mockito.MockitoTestExecutionListener, org.springframework.boot.test.mock.mockito.ResetMocksTestExecutionListener, org.springframework.boot.test.autoconfigure.restdocs.RestDocsTestExecutionListener, org.springframework.boot.test.autoconfigure.web.client.MockRestServiceServerResetTestExecutionListener, org.springframework.boot.test.autoconfigure.web.servlet.MockMvcPrintOnlyOnFailureTestExecutionListener, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverTestExecutionListener, org.springframework.test.context.web.ServletTestExecutionListener, org.springframework.test.context.support.DirtiesContextBeforeModesTestExecutionListener, org.springframework.test.context.support.DependencyInjectionTestExecutionListener, org.springframework.test.context.support.DirtiesContextTestExecutionListener, org.springframework.test.context.transaction.TransactionalTestExecutionListener, org.springframework.test.context.jdbc.SqlScriptsTestExecutionListener, org.springframework.test.context.event.EventPublishingTestExecutionListener]
2023-06-16 14:05:27.631  INFO 1158 --- [           main] b.t.a.o.j.DataJpaTestContextBootstrapper : Using TestExecutionListeners: [org.springframework.test.context.web.ServletTestExecutionListener@1ccc75c1, org.springframework.test.context.support.DirtiesContextBeforeModesTestExecutionListener@2e031e3d, org.springframework.boot.test.mock.mockito.MockitoTestExecutionListener@5ef2fe3b, org.springframework.boot.test.autoconfigure.SpringBootDependencyInjectionTestExecutionListener@7346a425, org.springframework.test.context.support.DirtiesContextTestExecutionListener@c5ba5f1, org.springframework.test.context.transaction.TransactionalTestExecutionListener@3a1fb0b1, org.springframework.test.context.jdbc.SqlScriptsTestExecutionListener@73d592ef, org.springframework.test.context.event.EventPublishingTestExecutionListener@3574673c, org.springframework.boot.test.mock.mockito.ResetMocksTestExecutionListener@6451384e, org.springframework.boot.test.autoconfigure.restdocs.RestDocsTestExecutionListener@230c964d, org.springframework.boot.test.autoconfigure.web.client.MockRestServiceServerResetTestExecutionListener@7c112a29, org.springframework.boot.test.autoconfigure.web.servlet.MockMvcPrintOnlyOnFailureTestExecutionListener@6acaff10, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverTestExecutionListener@7b4294f]


              |\      _,,,--,,_
             /,`.-'`'   ._  \-;;,_
  _______ __|,4-  ) )_   .;.(__`'-'__     ___ __    _ ___ _______
 |       | '---''(_/._)-'(_\_)   |   |   |   |  |  | |   |       |
 |    _  |    ___|_     _|       |   |   |   |   |_| |   |       | __ _ _
 |   |_| |   |___  |   | |       |   |   |   |       |   |       | \ \ \ \
 |    ___|    ___| |   | |      _|   |___|   |  _    |   |      _|  \ \ \ \
 |   |   |   |___  |   | |     |_|       |   | | |   |   |     |_    ) ) ) )
 |___|   |_______| |___| |_______|_______|___|_|  |__|___|_______|  / / / /
 ==================================================================/_/_/_/

:: Built with Spring Boot :: 2.2.2.RELEASE


2023-06-16 14:05:27.660  INFO 1158 --- [           main] o.s.s.p.service.ClinicServiceTests       : Starting ClinicServiceTests on 3467ac7d3468 with PID 1158 (started by root in /var/jenkins_home/workspace/spring-petclinic-hub)
2023-06-16 14:05:27.660  INFO 1158 --- [           main] o.s.s.p.service.ClinicServiceTests       : No active profile set, falling back to default profiles: default
2023-06-16 14:05:27.740  INFO 1158 --- [           main] .s.d.r.c.RepositoryConfigurationDelegate : Bootstrapping Spring Data JPA repositories in DEFAULT mode.
2023-06-16 14:05:27.756  INFO 1158 --- [           main] .s.d.r.c.RepositoryConfigurationDelegate : Finished Spring Data repository scanning in 15ms. Found 4 JPA repository interfaces.
2023-06-16 14:05:27.770  INFO 1158 --- [           main] beddedDataSourceBeanFactoryPostProcessor : Replacing 'dataSource' DataSource bean with embedded version
2023-06-16 14:05:27.809  INFO 1158 --- [           main] o.s.j.d.e.EmbeddedDatabaseFactory        : Starting embedded database: url='jdbc:hsqldb:mem:2ffd2d79-2f42-4804-ab5b-b3a19f7dc4b5', username='sa'
2023-06-16 14:05:27.934  INFO 1158 --- [           main] o.hibernate.jpa.internal.util.LogHelper  : HHH000204: Processing PersistenceUnitInfo [name: default]
2023-06-16 14:05:27.941  INFO 1158 --- [           main] org.hibernate.dialect.Dialect            : HHH000400: Using dialect: org.hibernate.dialect.HSQLDialect
2023-06-16 14:05:28.050  INFO 1158 --- [           main] o.h.e.t.j.p.i.JtaPlatformInitiator       : HHH000490: Using JtaPlatform implementation: [org.hibernate.engine.transaction.jta.platform.internal.NoJtaPlatform]
2023-06-16 14:05:28.050  INFO 1158 --- [           main] j.LocalContainerEntityManagerFactoryBean : Initialized JPA EntityManagerFactory for persistence unit 'default'
2023-06-16 14:05:28.212  INFO 1158 --- [           main] o.s.s.p.service.ClinicServiceTests       : Started ClinicServiceTests in 0.578 seconds (JVM running for 27.103)
2023-06-16 14:05:28.223  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Began transaction (1) for test context [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@280c19a4, testMethod = shouldFindVets@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]; transaction manager [org.springframework.orm.jpa.JpaTransactionManager@2ce2587b]; rollback [true]
Hibernate: select vet0_.id as id1_5_, vet0_.first_name as first_na2_5_, vet0_.last_name as last_nam3_5_ from vets vet0_
Hibernate: select specialtie0_.vet_id as vet_id1_4_0_, specialtie0_.specialty_id as specialt2_4_0_, specialty1_.id as id1_2_1_, specialty1_.name as name2_2_1_ from vet_specialties specialtie0_ inner join specialties specialty1_ on specialtie0_.specialty_id=specialty1_.id where specialtie0_.vet_id=?
Hibernate: select specialtie0_.vet_id as vet_id1_4_0_, specialtie0_.specialty_id as specialt2_4_0_, specialty1_.id as id1_2_1_, specialty1_.name as name2_2_1_ from vet_specialties specialtie0_ inner join specialties specialty1_ on specialtie0_.specialty_id=specialty1_.id where specialtie0_.vet_id=?
Hibernate: select specialtie0_.vet_id as vet_id1_4_0_, specialtie0_.specialty_id as specialt2_4_0_, specialty1_.id as id1_2_1_, specialty1_.name as name2_2_1_ from vet_specialties specialtie0_ inner join specialties specialty1_ on specialtie0_.specialty_id=specialty1_.id where specialtie0_.vet_id=?
Hibernate: select specialtie0_.vet_id as vet_id1_4_0_, specialtie0_.specialty_id as specialt2_4_0_, specialty1_.id as id1_2_1_, specialty1_.name as name2_2_1_ from vet_specialties specialtie0_ inner join specialties specialty1_ on specialtie0_.specialty_id=specialty1_.id where specialtie0_.vet_id=?
Hibernate: select specialtie0_.vet_id as vet_id1_4_0_, specialtie0_.specialty_id as specialt2_4_0_, specialty1_.id as id1_2_1_, specialty1_.name as name2_2_1_ from vet_specialties specialtie0_ inner join specialties specialty1_ on specialtie0_.specialty_id=specialty1_.id where specialtie0_.vet_id=?
Hibernate: select specialtie0_.vet_id as vet_id1_4_0_, specialtie0_.specialty_id as specialt2_4_0_, specialty1_.id as id1_2_1_, specialty1_.name as name2_2_1_ from vet_specialties specialtie0_ inner join specialties specialty1_ on specialtie0_.specialty_id=specialty1_.id where specialtie0_.vet_id=?
2023-06-16 14:05:28.242  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Rolled back transaction for test: [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@280c19a4, testMethod = shouldFindVets@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]
2023-06-16 14:05:28.246  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Began transaction (1) for test context [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@6edd8741, testMethod = shouldFindOwnersByLastName@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]; transaction manager [org.springframework.orm.jpa.JpaTransactionManager@2ce2587b]; rollback [true]
Hibernate: select distinct owner0_.id as id1_0_0_, pets1_.id as id1_1_1_, owner0_.first_name as first_na2_0_0_, owner0_.last_name as last_nam3_0_0_, owner0_.address as address4_0_0_, owner0_.city as city5_0_0_, owner0_.telephone as telephon6_0_0_, pets1_.name as name2_1_1_, pets1_.birth_date as birth_da3_1_1_, pets1_.owner_id as owner_id4_1_1_, pets1_.type_id as type_id5_1_1_, pets1_.owner_id as owner_id4_1_0__, pets1_.id as id1_1_0__ from owners owner0_ left outer join pets pets1_ on owner0_.id=pets1_.owner_id where owner0_.last_name like ?
Hibernate: select pettype0_.id as id1_3_0_, pettype0_.name as name2_3_0_ from types pettype0_ where pettype0_.id=?
Hibernate: select pettype0_.id as id1_3_0_, pettype0_.name as name2_3_0_ from types pettype0_ where pettype0_.id=?
Hibernate: select distinct owner0_.id as id1_0_0_, pets1_.id as id1_1_1_, owner0_.first_name as first_na2_0_0_, owner0_.last_name as last_nam3_0_0_, owner0_.address as address4_0_0_, owner0_.city as city5_0_0_, owner0_.telephone as telephon6_0_0_, pets1_.name as name2_1_1_, pets1_.birth_date as birth_da3_1_1_, pets1_.owner_id as owner_id4_1_1_, pets1_.type_id as type_id5_1_1_, pets1_.owner_id as owner_id4_1_0__, pets1_.id as id1_1_0__ from owners owner0_ left outer join pets pets1_ on owner0_.id=pets1_.owner_id where owner0_.last_name like ?
2023-06-16 14:05:28.314  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Rolled back transaction for test: [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@6edd8741, testMethod = shouldFindOwnersByLastName@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]
2023-06-16 14:05:28.317  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Began transaction (1) for test context [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@dd5f5e3, testMethod = shouldAddNewVisitForPet@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]; transaction manager [org.springframework.orm.jpa.JpaTransactionManager@2ce2587b]; rollback [true]
Hibernate: select pet0_.id as id1_1_0_, pet0_.name as name2_1_0_, pet0_.birth_date as birth_da3_1_0_, pet0_.owner_id as owner_id4_1_0_, pet0_.type_id as type_id5_1_0_, owner1_.id as id1_0_1_, owner1_.first_name as first_na2_0_1_, owner1_.last_name as last_nam3_0_1_, owner1_.address as address4_0_1_, owner1_.city as city5_0_1_, owner1_.telephone as telephon6_0_1_, pettype2_.id as id1_3_2_, pettype2_.name as name2_3_2_ from pets pet0_ left outer join owners owner1_ on pet0_.owner_id=owner1_.id left outer join types pettype2_ on pet0_.type_id=pettype2_.id where pet0_.id=?
Hibernate: insert into visits (id, visit_date, description, pet_id) values (default, ?, ?, ?)
2023-06-16 14:05:28.427  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Rolled back transaction for test: [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@dd5f5e3, testMethod = shouldAddNewVisitForPet@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]
2023-06-16 14:05:28.430  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Began transaction (1) for test context [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@1f5b76ed, testMethod = shouldUpdateOwner@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]; transaction manager [org.springframework.orm.jpa.JpaTransactionManager@2ce2587b]; rollback [true]
Hibernate: select owner0_.id as id1_0_0_, pets1_.id as id1_1_1_, owner0_.first_name as first_na2_0_0_, owner0_.last_name as last_nam3_0_0_, owner0_.address as address4_0_0_, owner0_.city as city5_0_0_, owner0_.telephone as telephon6_0_0_, pets1_.name as name2_1_1_, pets1_.birth_date as birth_da3_1_1_, pets1_.owner_id as owner_id4_1_1_, pets1_.type_id as type_id5_1_1_, pets1_.owner_id as owner_id4_1_0__, pets1_.id as id1_1_0__ from owners owner0_ left outer join pets pets1_ on owner0_.id=pets1_.owner_id where owner0_.id=?
Hibernate: select pettype0_.id as id1_3_0_, pettype0_.name as name2_3_0_ from types pettype0_ where pettype0_.id=?
Hibernate: update owners set first_name=?, last_name=?, address=?, city=?, telephone=? where id=?
Hibernate: select owner0_.id as id1_0_0_, pets1_.id as id1_1_1_, owner0_.first_name as first_na2_0_0_, owner0_.last_name as last_nam3_0_0_, owner0_.address as address4_0_0_, owner0_.city as city5_0_0_, owner0_.telephone as telephon6_0_0_, pets1_.name as name2_1_1_, pets1_.birth_date as birth_da3_1_1_, pets1_.owner_id as owner_id4_1_1_, pets1_.type_id as type_id5_1_1_, pets1_.owner_id as owner_id4_1_0__, pets1_.id as id1_1_0__ from owners owner0_ left outer join pets pets1_ on owner0_.id=pets1_.owner_id where owner0_.id=?
2023-06-16 14:05:28.459  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Rolled back transaction for test: [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@1f5b76ed, testMethod = shouldUpdateOwner@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]
2023-06-16 14:05:28.462  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Began transaction (1) for test context [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@2705ce70, testMethod = shouldFindVisitsByPetId@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]; transaction manager [org.springframework.orm.jpa.JpaTransactionManager@2ce2587b]; rollback [true]
Hibernate: select visit0_.id as id1_6_, visit0_.visit_date as visit_da2_6_, visit0_.description as descript3_6_, visit0_.pet_id as pet_id4_6_ from visits visit0_ where visit0_.pet_id=?
2023-06-16 14:05:28.473  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Rolled back transaction for test: [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@2705ce70, testMethod = shouldFindVisitsByPetId@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]
2023-06-16 14:05:28.476  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Began transaction (1) for test context [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@725f556c, testMethod = shouldInsertPetIntoDatabaseAndGenerateId@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]; transaction manager [org.springframework.orm.jpa.JpaTransactionManager@2ce2587b]; rollback [true]
Hibernate: select owner0_.id as id1_0_0_, pets1_.id as id1_1_1_, owner0_.first_name as first_na2_0_0_, owner0_.last_name as last_nam3_0_0_, owner0_.address as address4_0_0_, owner0_.city as city5_0_0_, owner0_.telephone as telephon6_0_0_, pets1_.name as name2_1_1_, pets1_.birth_date as birth_da3_1_1_, pets1_.owner_id as owner_id4_1_1_, pets1_.type_id as type_id5_1_1_, pets1_.owner_id as owner_id4_1_0__, pets1_.id as id1_1_0__ from owners owner0_ left outer join pets pets1_ on owner0_.id=pets1_.owner_id where owner0_.id=?
Hibernate: select pettype0_.id as id1_3_0_, pettype0_.name as name2_3_0_ from types pettype0_ where pettype0_.id=?
Hibernate: select pettype0_.id as id1_3_, pettype0_.name as name2_3_ from types pettype0_ order by pettype0_.name
Hibernate: insert into pets (id, name, birth_date, owner_id, type_id) values (default, ?, ?, ?, ?)
Hibernate: select owner0_.id as id1_0_0_, pets1_.id as id1_1_1_, owner0_.first_name as first_na2_0_0_, owner0_.last_name as last_nam3_0_0_, owner0_.address as address4_0_0_, owner0_.city as city5_0_0_, owner0_.telephone as telephon6_0_0_, pets1_.name as name2_1_1_, pets1_.birth_date as birth_da3_1_1_, pets1_.owner_id as owner_id4_1_1_, pets1_.type_id as type_id5_1_1_, pets1_.owner_id as owner_id4_1_0__, pets1_.id as id1_1_0__ from owners owner0_ left outer join pets pets1_ on owner0_.id=pets1_.owner_id where owner0_.id=?
2023-06-16 14:05:28.501  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Rolled back transaction for test: [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@725f556c, testMethod = shouldInsertPetIntoDatabaseAndGenerateId@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]
2023-06-16 14:05:28.504  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Began transaction (1) for test context [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@1ee2c501, testMethod = shouldInsertOwner@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]; transaction manager [org.springframework.orm.jpa.JpaTransactionManager@2ce2587b]; rollback [true]
Hibernate: select distinct owner0_.id as id1_0_0_, pets1_.id as id1_1_1_, owner0_.first_name as first_na2_0_0_, owner0_.last_name as last_nam3_0_0_, owner0_.address as address4_0_0_, owner0_.city as city5_0_0_, owner0_.telephone as telephon6_0_0_, pets1_.name as name2_1_1_, pets1_.birth_date as birth_da3_1_1_, pets1_.owner_id as owner_id4_1_1_, pets1_.type_id as type_id5_1_1_, pets1_.owner_id as owner_id4_1_0__, pets1_.id as id1_1_0__ from owners owner0_ left outer join pets pets1_ on owner0_.id=pets1_.owner_id where owner0_.last_name like ?
Hibernate: insert into owners (id, first_name, last_name, address, city, telephone) values (default, ?, ?, ?, ?, ?)
Hibernate: select distinct owner0_.id as id1_0_0_, pets1_.id as id1_1_1_, owner0_.first_name as first_na2_0_0_, owner0_.last_name as last_nam3_0_0_, owner0_.address as address4_0_0_, owner0_.city as city5_0_0_, owner0_.telephone as telephon6_0_0_, pets1_.name as name2_1_1_, pets1_.birth_date as birth_da3_1_1_, pets1_.owner_id as owner_id4_1_1_, pets1_.type_id as type_id5_1_1_, pets1_.owner_id as owner_id4_1_0__, pets1_.id as id1_1_0__ from owners owner0_ left outer join pets pets1_ on owner0_.id=pets1_.owner_id where owner0_.last_name like ?
2023-06-16 14:05:28.513  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Rolled back transaction for test: [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@1ee2c501, testMethod = shouldInsertOwner@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]
2023-06-16 14:05:28.516  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Began transaction (1) for test context [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@ddeb2b6, testMethod = shouldFindSingleOwnerWithPet@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]; transaction manager [org.springframework.orm.jpa.JpaTransactionManager@2ce2587b]; rollback [true]
Hibernate: select owner0_.id as id1_0_0_, pets1_.id as id1_1_1_, owner0_.first_name as first_na2_0_0_, owner0_.last_name as last_nam3_0_0_, owner0_.address as address4_0_0_, owner0_.city as city5_0_0_, owner0_.telephone as telephon6_0_0_, pets1_.name as name2_1_1_, pets1_.birth_date as birth_da3_1_1_, pets1_.owner_id as owner_id4_1_1_, pets1_.type_id as type_id5_1_1_, pets1_.owner_id as owner_id4_1_0__, pets1_.id as id1_1_0__ from owners owner0_ left outer join pets pets1_ on owner0_.id=pets1_.owner_id where owner0_.id=?
Hibernate: select pettype0_.id as id1_3_0_, pettype0_.name as name2_3_0_ from types pettype0_ where pettype0_.id=?
2023-06-16 14:05:28.530  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Rolled back transaction for test: [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@ddeb2b6, testMethod = shouldFindSingleOwnerWithPet@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]
2023-06-16 14:05:28.534  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Began transaction (1) for test context [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@425d9e33, testMethod = shouldUpdatePetName@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]; transaction manager [org.springframework.orm.jpa.JpaTransactionManager@2ce2587b]; rollback [true]
Hibernate: select pet0_.id as id1_1_0_, pet0_.name as name2_1_0_, pet0_.birth_date as birth_da3_1_0_, pet0_.owner_id as owner_id4_1_0_, pet0_.type_id as type_id5_1_0_, owner1_.id as id1_0_1_, owner1_.first_name as first_na2_0_1_, owner1_.last_name as last_nam3_0_1_, owner1_.address as address4_0_1_, owner1_.city as city5_0_1_, owner1_.telephone as telephon6_0_1_, pettype2_.id as id1_3_2_, pettype2_.name as name2_3_2_ from pets pet0_ left outer join owners owner1_ on pet0_.owner_id=owner1_.id left outer join types pettype2_ on pet0_.type_id=pettype2_.id where pet0_.id=?
2023-06-16 14:05:28.539  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Rolled back transaction for test: [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@425d9e33, testMethod = shouldUpdatePetName@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]
2023-06-16 14:05:28.542  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Began transaction (1) for test context [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@f08a09b, testMethod = shouldFindAllPetTypes@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]; transaction manager [org.springframework.orm.jpa.JpaTransactionManager@2ce2587b]; rollback [true]
Hibernate: select pettype0_.id as id1_3_, pettype0_.name as name2_3_ from types pettype0_ order by pettype0_.name
2023-06-16 14:05:28.547  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Rolled back transaction for test: [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@f08a09b, testMethod = shouldFindAllPetTypes@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]
2023-06-16 14:05:28.553  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Began transaction (1) for test context [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@30d5231e, testMethod = shouldFindPetWithCorrectId@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]; transaction manager [org.springframework.orm.jpa.JpaTransactionManager@2ce2587b]; rollback [true]
Hibernate: select pet0_.id as id1_1_0_, pet0_.name as name2_1_0_, pet0_.birth_date as birth_da3_1_0_, pet0_.owner_id as owner_id4_1_0_, pet0_.type_id as type_id5_1_0_, owner1_.id as id1_0_1_, owner1_.first_name as first_na2_0_1_, owner1_.last_name as last_nam3_0_1_, owner1_.address as address4_0_1_, owner1_.city as city5_0_1_, owner1_.telephone as telephon6_0_1_, pettype2_.id as id1_3_2_, pettype2_.name as name2_3_2_ from pets pet0_ left outer join owners owner1_ on pet0_.owner_id=owner1_.id left outer join types pettype2_ on pet0_.type_id=pettype2_.id where pet0_.id=?
2023-06-16 14:05:28.560  INFO 1158 --- [           main] o.s.t.c.transaction.TransactionContext   : Rolled back transaction for test: [DefaultTestContext@efb46f7 testClass = ClinicServiceTests, testInstance = org.springframework.samples.petclinic.service.ClinicServiceTests@30d5231e, testMethod = shouldFindPetWithCorrectId@ClinicServiceTests, testException = [null], mergedContextConfiguration = [MergedContextConfiguration@72eb2223 testClass = ClinicServiceTests, locations = '{}', classes = '{class org.springframework.samples.petclinic.PetClinicApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.autoconfigure.orm.jpa.DataJpaTestContextBootstrapper=true}', contextCustomizers = set[[ImportsContextCustomizer@4e220d74 key = [org.springframework.boot.autoconfigure.cache.CacheAutoConfiguration, org.springframework.boot.autoconfigure.data.jpa.JpaRepositoriesAutoConfiguration, org.springframework.boot.autoconfigure.flyway.FlywayAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.DataSourceTransactionManagerAutoConfiguration, org.springframework.boot.autoconfigure.jdbc.JdbcTemplateAutoConfiguration, org.springframework.boot.autoconfigure.liquibase.LiquibaseAutoConfiguration, org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaAutoConfiguration, org.springframework.boot.autoconfigure.transaction.TransactionAutoConfiguration, org.springframework.boot.test.autoconfigure.jdbc.TestDatabaseAutoConfiguration, org.springframework.boot.test.autoconfigure.orm.jpa.TestEntityManagerAutoConfiguration]], org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@6e8fdd19, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@5dbbb292, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.autoconfigure.OverrideAutoConfigurationContextCustomizerFactory$DisableAutoConfigurationContextCustomizer@5b29ab61, org.springframework.boot.test.autoconfigure.filter.TypeExcludeFiltersContextCustomizer@b2c14d1c, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@65ede59c, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@2bab618], contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map[[empty]]]
[INFO] Tests run: 11, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.94 s - in org.springframework.samples.petclinic.service.ClinicServiceTests
2023-06-16 14:05:28.597  INFO 1158 --- [extShutdownHook] o.s.s.concurrent.ThreadPoolTaskExecutor  : Shutting down ExecutorService 'applicationTaskExecutor'
2023-06-16 14:05:28.602  INFO 1158 --- [extShutdownHook] o.s.s.concurrent.ThreadPoolTaskExecutor  : Shutting down ExecutorService 'applicationTaskExecutor'
2023-06-16 14:05:28.605  INFO 1158 --- [extShutdownHook] j.LocalContainerEntityManagerFactoryBean : Closing JPA EntityManagerFactory for persistence unit 'default'
2023-06-16 14:05:28.609  INFO 1158 --- [extShutdownHook] o.s.s.concurrent.ThreadPoolTaskExecutor  : Shutting down ExecutorService 'applicationTaskExecutor'
2023-06-16 14:05:28.614  INFO 1158 --- [extShutdownHook] j.LocalContainerEntityManagerFactoryBean : Closing JPA EntityManagerFactory for persistence unit 'default'
2023-06-16 14:05:28.615  INFO 1158 --- [extShutdownHook] o.s.s.concurrent.ThreadPoolTaskExecutor  : Shutting down ExecutorService 'applicationTaskExecutor'
2023-06-16 14:05:28.615  INFO 1158 --- [extShutdownHook] o.s.s.concurrent.ThreadPoolTaskExecutor  : Shutting down ExecutorService 'applicationTaskExecutor'
2023-06-16 14:05:28.617  INFO 1158 --- [extShutdownHook] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Shutdown initiated...
2023-06-16 14:05:28.630  INFO 1158 --- [extShutdownHook] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Shutdown completed.
2023-06-16 14:05:28.765  INFO 1158 --- [extShutdownHook] org.ehcache.core.EhcacheManager          : Cache 'vets' removed from EhcacheManager.
[INFO] 
[INFO] Results:
[INFO] 
[WARNING] Tests run: 40, Failures: 0, Errors: 0, Skipped: 1
[INFO] 
[INFO] 
[INFO] --- jacoco-maven-plugin:0.8.5:report (report) @ spring-petclinic ---
[INFO] Loading execution data file /var/jenkins_home/workspace/spring-petclinic-hub/target/jacoco.exec
[INFO] Analyzed bundle 'petclinic' with 20 classes
[INFO] 
[INFO] --- maven-jar-plugin:3.1.2:jar (default-jar) @ spring-petclinic ---
Downloading: https://repo.spring.io/snapshot/org/apache/maven/shared/file-management/3.0.0/file-management-3.0.0.pom
         
Downloading: https://repo.spring.io/milestone/org/apache/maven/shared/file-management/3.0.0/file-management-3.0.0.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/shared/file-management/3.0.0/file-management-3.0.0.pom
4/5 KB   
5/5 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/shared/file-management/3.0.0/file-management-3.0.0.pom (5 KB at 169.6 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/shared/maven-shared-components/22/maven-shared-components-22.pom
         
Downloading: https://repo.spring.io/milestone/org/apache/maven/shared/maven-shared-components/22/maven-shared-components-22.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/22/maven-shared-components-22.pom
4/5 KB   
5/5 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/22/maven-shared-components-22.pom (5 KB at 208.1 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/shared/maven-shared-io/3.0.0/maven-shared-io-3.0.0.pom
         
Downloading: https://repo.spring.io/milestone/org/apache/maven/shared/maven-shared-io/3.0.0/maven-shared-io-3.0.0.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-io/3.0.0/maven-shared-io-3.0.0.pom
4/5 KB   
5/5 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-io/3.0.0/maven-shared-io-3.0.0.pom (5 KB at 176.5 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/maven-compat/3.0/maven-compat-3.0.pom
         
Downloading: https://repo.spring.io/milestone/org/apache/maven/maven-compat/3.0/maven-compat-3.0.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/maven-compat/3.0/maven-compat-3.0.pom
4/4 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/maven-compat/3.0/maven-compat-3.0.pom (4 KB at 206.7 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/wagon/wagon-provider-api/1.0-beta-6/wagon-provider-api-1.0-beta-6.pom
         
Downloading: https://repo.spring.io/milestone/org/apache/maven/wagon/wagon-provider-api/1.0-beta-6/wagon-provider-api-1.0-beta-6.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/wagon/wagon-provider-api/1.0-beta-6/wagon-provider-api-1.0-beta-6.pom
2/2 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/wagon/wagon-provider-api/1.0-beta-6/wagon-provider-api-1.0-beta-6.pom (2 KB at 78.1 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/wagon/wagon/1.0-beta-6/wagon-1.0-beta-6.pom
         
Downloading: https://repo.spring.io/milestone/org/apache/maven/wagon/wagon/1.0-beta-6/wagon-1.0-beta-6.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/wagon/wagon/1.0-beta-6/wagon-1.0-beta-6.pom
4/13 KB   
8/13 KB   
12/13 KB   
13/13 KB   
           
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/wagon/wagon/1.0-beta-6/wagon-1.0-beta-6.pom (13 KB at 403.2 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/codehaus/plexus/plexus-utils/1.4.2/plexus-utils-1.4.2.pom
           
Downloading: https://repo.spring.io/milestone/org/codehaus/plexus/plexus-utils/1.4.2/plexus-utils-1.4.2.pom
           
Downloading: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/1.4.2/plexus-utils-1.4.2.pom
2/2 KB     
         
Downloaded: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/1.4.2/plexus-utils-1.4.2.pom (2 KB at 83.2 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/wagon/wagon-provider-api/2.10/wagon-provider-api-2.10.pom
         
Downloading: https://repo.spring.io/milestone/org/apache/maven/wagon/wagon-provider-api/2.10/wagon-provider-api-2.10.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/wagon/wagon-provider-api/2.10/wagon-provider-api-2.10.pom
2/2 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/wagon/wagon-provider-api/2.10/wagon-provider-api-2.10.pom (2 KB at 70.4 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/wagon/wagon/2.10/wagon-2.10.pom
         
Downloading: https://repo.spring.io/milestone/org/apache/maven/wagon/wagon/2.10/wagon-2.10.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/wagon/wagon/2.10/wagon-2.10.pom
4/21 KB   
8/21 KB   
12/21 KB   
16/21 KB   
20/21 KB   
21/21 KB   
           
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/wagon/wagon/2.10/wagon-2.10.pom (21 KB at 667.8 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/maven-parent/26/maven-parent-26.pom
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/maven-parent/26/maven-parent-26.pom
           
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/26/maven-parent-26.pom
4/39 KB    
8/39 KB   
12/39 KB   
16/39 KB   
20/39 KB   
24/39 KB   
28/39 KB   
32/39 KB   
36/39 KB   
39/39 KB   
           
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/26/maven-parent-26.pom (39 KB at 1079.2 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/codehaus/plexus/plexus-utils/3.0.15/plexus-utils-3.0.15.pom
           
Downloading: https://repo.spring.io/milestone/org/codehaus/plexus/plexus-utils/3.0.15/plexus-utils-3.0.15.pom
           
Downloading: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.0.15/plexus-utils-3.0.15.pom
4/4 KB     
         
Downloaded: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.0.15/plexus-utils-3.0.15.pom (4 KB at 113.8 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/codehaus/plexus/plexus-utils/3.2.0/plexus-utils-3.2.0.pom
         
Downloading: https://repo.spring.io/milestone/org/codehaus/plexus/plexus-utils/3.2.0/plexus-utils-3.2.0.pom
         
Downloading: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.2.0/plexus-utils-3.2.0.pom
4/5 KB   
5/5 KB   
         
Downloaded: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.2.0/plexus-utils-3.2.0.pom (5 KB at 196.2 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/shared/file-management/3.0.0/file-management-3.0.0.jar
Downloading: https://repo.spring.io/snapshot/org/apache/maven/shared/maven-shared-io/3.0.0/maven-shared-io-3.0.0.jar
Downloading: https://repo.spring.io/snapshot/org/apache/maven/maven-compat/3.0/maven-compat-3.0.jar
Downloading: https://repo.spring.io/snapshot/org/apache/maven/wagon/wagon-provider-api/2.10/wagon-provider-api-2.10.jar
Downloading: https://repo.spring.io/snapshot/org/codehaus/plexus/plexus-archiver/4.1.0/plexus-archiver-4.1.0.jar
         
Downloading: https://repo.spring.io/snapshot/org/codehaus/plexus/plexus-io/3.1.1/plexus-io-3.1.1.jar
         
Downloading: https://repo.spring.io/snapshot/org/apache/commons/commons-compress/1.18/commons-compress-1.18.jar
         
Downloading: https://repo.spring.io/snapshot/org/codehaus/plexus/plexus-utils/3.2.0/plexus-utils-3.2.0.jar
         
         
         
         
         
Downloading: https://repo.spring.io/milestone/org/apache/maven/shared/file-management/3.0.0/file-management-3.0.0.jar
Downloading: https://repo.spring.io/milestone/org/apache/maven/shared/maven-shared-io/3.0.0/maven-shared-io-3.0.0.jar
Downloading: https://repo.spring.io/milestone/org/apache/maven/wagon/wagon-provider-api/2.10/wagon-provider-api-2.10.jar
Downloading: https://repo.spring.io/milestone/org/codehaus/plexus/plexus-archiver/4.1.0/plexus-archiver-4.1.0.jar
Downloading: https://repo.spring.io/milestone/org/apache/maven/maven-compat/3.0/maven-compat-3.0.jar
         
Downloading: https://repo.spring.io/milestone/org/codehaus/plexus/plexus-io/3.1.1/plexus-io-3.1.1.jar
         
Downloading: https://repo.spring.io/milestone/org/apache/commons/commons-compress/1.18/commons-compress-1.18.jar
         
Downloading: https://repo.spring.io/milestone/org/codehaus/plexus/plexus-utils/3.2.0/plexus-utils-3.2.0.jar
         
         
         
         
         
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/shared/file-management/3.0.0/file-management-3.0.0.jar
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-io/3.0.0/maven-shared-io-3.0.0.jar
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/wagon/wagon-provider-api/2.10/wagon-provider-api-2.10.jar
Downloading: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-archiver/4.1.0/plexus-archiver-4.1.0.jar
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/maven-compat/3.0/maven-compat-3.0.jar
4/35 KB   
8/35 KB   
12/35 KB   
16/35 KB   
16/35 KB   4/41 KB   
16/35 KB   8/41 KB   
16/35 KB   12/41 KB   
16/35 KB   16/41 KB   
16/35 KB   16/41 KB   4/53 KB   
16/35 KB   16/41 KB   8/53 KB   
16/35 KB   16/41 KB   12/53 KB   
16/35 KB   16/41 KB   16/53 KB   
16/35 KB   16/41 KB   4/188 KB   16/53 KB   
16/35 KB   16/41 KB   4/188 KB   4/279 KB   16/53 KB   
16/35 KB   16/41 KB   4/188 KB   8/279 KB   16/53 KB   
16/35 KB   16/41 KB   4/188 KB   12/279 KB   16/53 KB   
16/35 KB   16/41 KB   4/188 KB   16/279 KB   16/53 KB   
16/35 KB   16/41 KB   8/188 KB   16/279 KB   16/53 KB   
16/35 KB   16/41 KB   12/188 KB   16/279 KB   16/53 KB   
16/35 KB   16/41 KB   16/188 KB   16/279 KB   16/53 KB   
16/35 KB   20/41 KB   16/188 KB   16/279 KB   16/53 KB   
16/35 KB   24/41 KB   16/188 KB   16/279 KB   16/53 KB   
16/35 KB   28/41 KB   16/188 KB   16/279 KB   16/53 KB   
16/35 KB   32/41 KB   16/188 KB   16/279 KB   16/53 KB   
16/35 KB   32/41 KB   16/188 KB   20/279 KB   16/53 KB   
16/35 KB   32/41 KB   16/188 KB   24/279 KB   16/53 KB   
16/35 KB   32/41 KB   16/188 KB   28/279 KB   16/53 KB   
16/35 KB   32/41 KB   16/188 KB   32/279 KB   16/53 KB   
16/35 KB   36/41 KB   16/188 KB   32/279 KB   16/53 KB   
16/35 KB   40/41 KB   16/188 KB   32/279 KB   16/53 KB   
16/35 KB   41/41 KB   16/188 KB   32/279 KB   16/53 KB   
16/35 KB   41/41 KB   16/188 KB   32/279 KB   20/53 KB   
16/35 KB   41/41 KB   16/188 KB   32/279 KB   24/53 KB   
16/35 KB   41/41 KB   16/188 KB   32/279 KB   28/53 KB   
16/35 KB   41/41 KB   16/188 KB   32/279 KB   32/53 KB   
16/35 KB   41/41 KB   20/188 KB   32/279 KB   32/53 KB   
16/35 KB   41/41 KB   24/188 KB   32/279 KB   32/53 KB   
16/35 KB   41/41 KB   28/188 KB   32/279 KB   32/53 KB   
16/35 KB   41/41 KB   32/188 KB   32/279 KB   32/53 KB   
20/35 KB   41/41 KB   32/188 KB   32/279 KB   32/53 KB   
24/35 KB   41/41 KB   32/188 KB   32/279 KB   32/53 KB   
28/35 KB   41/41 KB   32/188 KB   32/279 KB   32/53 KB   
32/35 KB   41/41 KB   32/188 KB   32/279 KB   32/53 KB   
35/35 KB   41/41 KB   32/188 KB   32/279 KB   32/53 KB   
35/35 KB   41/41 KB   32/188 KB   36/279 KB   32/53 KB   
35/35 KB   41/41 KB   32/188 KB   40/279 KB   32/53 KB   
35/35 KB   41/41 KB   32/188 KB   44/279 KB   32/53 KB   
35/35 KB   41/41 KB   32/188 KB   48/279 KB   32/53 KB   
35/35 KB   41/41 KB   36/188 KB   48/279 KB   32/53 KB   
35/35 KB   41/41 KB   40/188 KB   48/279 KB   32/53 KB   
35/35 KB   41/41 KB   44/188 KB   48/279 KB   32/53 KB   
35/35 KB   41/41 KB   48/188 KB   48/279 KB   32/53 KB   
35/35 KB   41/41 KB   48/188 KB   52/279 KB   32/53 KB   
35/35 KB   41/41 KB   48/188 KB   56/279 KB   32/53 KB   
35/35 KB   41/41 KB   48/188 KB   60/279 KB   32/53 KB   
35/35 KB   41/41 KB   48/188 KB   61/279 KB   32/53 KB   
35/35 KB   41/41 KB   52/188 KB   61/279 KB   32/53 KB   
35/35 KB   41/41 KB   56/188 KB   61/279 KB   32/53 KB   
35/35 KB   41/41 KB   60/188 KB   61/279 KB   32/53 KB   
35/35 KB   41/41 KB   64/188 KB   61/279 KB   32/53 KB   
35/35 KB   41/41 KB   64/188 KB   61/279 KB   36/53 KB   
35/35 KB   41/41 KB   64/188 KB   61/279 KB   40/53 KB   
35/35 KB   41/41 KB   64/188 KB   61/279 KB   44/53 KB   
35/35 KB   41/41 KB   64/188 KB   61/279 KB   48/53 KB   
35/35 KB   41/41 KB   64/188 KB   61/279 KB   52/53 KB   
35/35 KB   41/41 KB   64/188 KB   61/279 KB   53/53 KB   
35/35 KB   41/41 KB   64/188 KB   65/279 KB   53/53 KB   
35/35 KB   41/41 KB   64/188 KB   69/279 KB   53/53 KB   
35/35 KB   41/41 KB   64/188 KB   73/279 KB   53/53 KB   
35/35 KB   41/41 KB   64/188 KB   77/279 KB   53/53 KB   
35/35 KB   41/41 KB   68/188 KB   77/279 KB   53/53 KB   
35/35 KB   41/41 KB   72/188 KB   77/279 KB   53/53 KB   
35/35 KB   41/41 KB   76/188 KB   77/279 KB   53/53 KB   
35/35 KB   41/41 KB   80/188 KB   77/279 KB   53/53 KB   
35/35 KB   41/41 KB   80/188 KB   81/279 KB   53/53 KB   
35/35 KB   41/41 KB   80/188 KB   85/279 KB   53/53 KB   
35/35 KB   41/41 KB   80/188 KB   89/279 KB   53/53 KB   
35/35 KB   41/41 KB   80/188 KB   93/279 KB   53/53 KB   
                                                         
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-io/3.0.0/maven-shared-io-3.0.0.jar (41 KB at 578.4 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-io/3.1.1/plexus-io-3.1.1.jar
35/35 KB   84/188 KB   93/279 KB   53/53 KB              
35/35 KB   88/188 KB   93/279 KB   53/53 KB   
35/35 KB   92/188 KB   93/279 KB   53/53 KB   
35/35 KB   96/188 KB   93/279 KB   53/53 KB   
                                              
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/shared/file-management/3.0.0/file-management-3.0.0.jar (35 KB at 466.1 KB/sec)
Downloading: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.18/commons-compress-1.18.jar
100/188 KB   93/279 KB   53/53 KB             
                                    
104/188 KB   93/279 KB              
108/188 KB   93/279 KB   
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/wagon/wagon-provider-api/2.10/wagon-provider-api-2.10.jar (53 KB at 736.3 KB/sec)
112/188 KB   93/279 KB   
Downloading: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.2.0/plexus-utils-3.2.0.jar
116/188 KB   93/279 KB   
120/188 KB   93/279 KB   
124/188 KB   93/279 KB   
128/188 KB   93/279 KB   
132/188 KB   93/279 KB   
136/188 KB   93/279 KB   
140/188 KB   93/279 KB   
144/188 KB   93/279 KB   
4/74 KB   144/188 KB   93/279 KB   
8/74 KB   144/188 KB   93/279 KB   
12/74 KB   144/188 KB   93/279 KB   
16/74 KB   144/188 KB   93/279 KB   
16/74 KB   4/578 KB   144/188 KB   93/279 KB   
16/74 KB   8/578 KB   144/188 KB   93/279 KB   
16/74 KB   12/578 KB   144/188 KB   93/279 KB   
16/74 KB   16/578 KB   144/188 KB   93/279 KB   
16/74 KB   16/578 KB   148/188 KB   93/279 KB   
16/74 KB   16/578 KB   152/188 KB   93/279 KB   
16/74 KB   16/578 KB   156/188 KB   93/279 KB   
16/74 KB   16/578 KB   160/188 KB   93/279 KB   
16/74 KB   16/578 KB   164/188 KB   93/279 KB   
16/74 KB   16/578 KB   168/188 KB   93/279 KB   
16/74 KB   16/578 KB   172/188 KB   93/279 KB   
16/74 KB   16/578 KB   176/188 KB   93/279 KB   
20/74 KB   16/578 KB   176/188 KB   93/279 KB   
24/74 KB   16/578 KB   176/188 KB   93/279 KB   
28/74 KB   16/578 KB   176/188 KB   93/279 KB   
32/74 KB   16/578 KB   176/188 KB   93/279 KB   
32/74 KB   16/578 KB   180/188 KB   93/279 KB   
32/74 KB   16/578 KB   184/188 KB   93/279 KB   
32/74 KB   16/578 KB   188/188 KB   93/279 KB   
32/74 KB   16/578 KB   188/188 KB   97/279 KB   
32/74 KB   16/578 KB   188/188 KB   101/279 KB   
32/74 KB   16/578 KB   188/188 KB   105/279 KB   
32/74 KB   16/578 KB   188/188 KB   109/279 KB   
32/74 KB   16/578 KB   4/257 KB   188/188 KB   109/279 KB   
32/74 KB   16/578 KB   8/257 KB   188/188 KB   109/279 KB   
32/74 KB   16/578 KB   12/257 KB   188/188 KB   109/279 KB   
32/74 KB   16/578 KB   16/257 KB   188/188 KB   109/279 KB   
32/74 KB   16/578 KB   16/257 KB   188/188 KB   113/279 KB   
32/74 KB   16/578 KB   16/257 KB   188/188 KB   117/279 KB   
32/74 KB   16/578 KB   16/257 KB   188/188 KB   121/279 KB   
32/74 KB   20/578 KB   16/257 KB   188/188 KB   125/279 KB   
36/74 KB   20/578 KB   16/257 KB   188/188 KB   125/279 KB   
40/74 KB   20/578 KB   16/257 KB   188/188 KB   125/279 KB   
44/74 KB   20/578 KB   16/257 KB   188/188 KB   125/279 KB   
48/74 KB   20/578 KB   16/257 KB   188/188 KB   125/279 KB   
48/74 KB   20/578 KB   20/257 KB   188/188 KB   125/279 KB   
48/74 KB   20/578 KB   24/257 KB   188/188 KB   125/279 KB   
48/74 KB   20/578 KB   28/257 KB   188/188 KB   125/279 KB   
48/74 KB   20/578 KB   32/257 KB   188/188 KB   125/279 KB   
52/74 KB   20/578 KB   32/257 KB   188/188 KB   125/279 KB   
56/74 KB   20/578 KB   32/257 KB   188/188 KB   125/279 KB   
60/74 KB   20/578 KB   32/257 KB   188/188 KB   125/279 KB   
64/74 KB   20/578 KB   32/257 KB   188/188 KB   125/279 KB   
64/74 KB   20/578 KB   32/257 KB   188/188 KB   129/279 KB   
64/74 KB   20/578 KB   32/257 KB   188/188 KB   133/279 KB   
64/74 KB   20/578 KB   32/257 KB   188/188 KB   137/279 KB   
64/74 KB   20/578 KB   32/257 KB   188/188 KB   141/279 KB   
64/74 KB   20/578 KB   36/257 KB   188/188 KB   141/279 KB   
64/74 KB   20/578 KB   40/257 KB   188/188 KB   141/279 KB   
64/74 KB   20/578 KB   44/257 KB   188/188 KB   141/279 KB   
64/74 KB   20/578 KB   48/257 KB   188/188 KB   141/279 KB   
32/74 KB   20/578 KB   16/257 KB   188/188 KB   121/279 KB   
64/74 KB   24/578 KB   48/257 KB   188/188 KB   141/279 KB   
64/74 KB   28/578 KB   48/257 KB   188/188 KB   141/279 KB   
64/74 KB   32/578 KB   48/257 KB   188/188 KB   141/279 KB   
64/74 KB   32/578 KB   48/257 KB   188/188 KB   145/279 KB   
64/74 KB   32/578 KB   48/257 KB   188/188 KB   149/279 KB   
64/74 KB   32/578 KB   48/257 KB   188/188 KB   153/279 KB   
64/74 KB   32/578 KB   48/257 KB   188/188 KB   157/279 KB   
64/74 KB   36/578 KB   48/257 KB   188/188 KB   157/279 KB   
64/74 KB   40/578 KB   48/257 KB   188/188 KB   157/279 KB   
64/74 KB   44/578 KB   48/257 KB   188/188 KB   157/279 KB   
68/74 KB   44/578 KB   48/257 KB   188/188 KB   157/279 KB   
68/74 KB   48/578 KB   48/257 KB   188/188 KB   157/279 KB   
72/74 KB   48/578 KB   48/257 KB   188/188 KB   157/279 KB   
74/74 KB   48/578 KB   48/257 KB   188/188 KB   157/279 KB   
74/74 KB   48/578 KB   48/257 KB   188/188 KB   161/279 KB   
74/74 KB   48/578 KB   48/257 KB   188/188 KB   165/279 KB   
74/74 KB   48/578 KB   48/257 KB   188/188 KB   169/279 KB   
74/74 KB   48/578 KB   48/257 KB   188/188 KB   173/279 KB   
                                                             
Downloaded: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-archiver/4.1.0/plexus-archiver-4.1.0.jar (188 KB at 1523.7 KB/sec)
74/74 KB   48/578 KB   52/257 KB   173/279 KB                
74/74 KB   48/578 KB   56/257 KB   173/279 KB   
74/74 KB   48/578 KB   60/257 KB   173/279 KB   
74/74 KB   48/578 KB   64/257 KB   173/279 KB   
74/74 KB   52/578 KB   64/257 KB   173/279 KB   
74/74 KB   56/578 KB   64/257 KB   173/279 KB   
74/74 KB   60/578 KB   64/257 KB   173/279 KB   
74/74 KB   64/578 KB   64/257 KB   173/279 KB   
74/74 KB   64/578 KB   64/257 KB   177/279 KB   
74/74 KB   64/578 KB   64/257 KB   181/279 KB   
74/74 KB   64/578 KB   64/257 KB   185/279 KB   
74/74 KB   64/578 KB   64/257 KB   189/279 KB   
74/74 KB   68/578 KB   64/257 KB   189/279 KB   
74/74 KB   72/578 KB   64/257 KB   189/279 KB   
74/74 KB   76/578 KB   64/257 KB   189/279 KB   
74/74 KB   80/578 KB   64/257 KB   189/279 KB   
                                                
Downloaded: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-io/3.1.1/plexus-io-3.1.1.jar (74 KB at 558.1 KB/sec)
80/578 KB   64/257 KB   193/279 KB              
80/578 KB   64/257 KB   197/279 KB   
80/578 KB   64/257 KB   201/279 KB   
80/578 KB   64/257 KB   205/279 KB   
84/578 KB   64/257 KB   205/279 KB   
88/578 KB   64/257 KB   205/279 KB   
92/578 KB   64/257 KB   205/279 KB   
96/578 KB   64/257 KB   205/279 KB   
96/578 KB   68/257 KB   205/279 KB   
96/578 KB   72/257 KB   205/279 KB   
96/578 KB   76/257 KB   205/279 KB   
96/578 KB   80/257 KB   205/279 KB   
96/578 KB   80/257 KB   209/279 KB   
96/578 KB   80/257 KB   213/279 KB   
96/578 KB   80/257 KB   217/279 KB   
96/578 KB   80/257 KB   221/279 KB   
100/578 KB   80/257 KB   221/279 KB   
104/578 KB   80/257 KB   221/279 KB   
108/578 KB   80/257 KB   221/279 KB   
112/578 KB   80/257 KB   221/279 KB   
112/578 KB   84/257 KB   221/279 KB   
112/578 KB   88/257 KB   221/279 KB   
112/578 KB   92/257 KB   221/279 KB   
112/578 KB   96/257 KB   221/279 KB   
112/578 KB   96/257 KB   225/279 KB   
112/578 KB   96/257 KB   229/279 KB   
112/578 KB   96/257 KB   233/279 KB   
112/578 KB   96/257 KB   237/279 KB   
116/578 KB   96/257 KB   237/279 KB   
120/578 KB   96/257 KB   237/279 KB   
124/578 KB   96/257 KB   237/279 KB   
128/578 KB   96/257 KB   237/279 KB   
128/578 KB   100/257 KB   237/279 KB   
128/578 KB   104/257 KB   237/279 KB   
128/578 KB   108/257 KB   237/279 KB   
128/578 KB   112/257 KB   237/279 KB   
132/578 KB   112/257 KB   237/279 KB   
136/578 KB   112/257 KB   237/279 KB   
140/578 KB   112/257 KB   237/279 KB   
144/578 KB   112/257 KB   237/279 KB   
144/578 KB   112/257 KB   241/279 KB   
144/578 KB   112/257 KB   245/279 KB   
144/578 KB   112/257 KB   249/279 KB   
144/578 KB   112/257 KB   253/279 KB   
144/578 KB   116/257 KB   253/279 KB   
144/578 KB   120/257 KB   253/279 KB   
144/578 KB   124/257 KB   253/279 KB   
144/578 KB   128/257 KB   253/279 KB   
148/578 KB   128/257 KB   253/279 KB   
152/578 KB   128/257 KB   253/279 KB   
156/578 KB   128/257 KB   253/279 KB   
160/578 KB   128/257 KB   253/279 KB   
160/578 KB   128/257 KB   257/279 KB   
160/578 KB   128/257 KB   261/279 KB   
160/578 KB   128/257 KB   265/279 KB   
160/578 KB   128/257 KB   269/279 KB   
160/578 KB   132/257 KB   269/279 KB   
160/578 KB   136/257 KB   269/279 KB   
160/578 KB   140/257 KB   269/279 KB   
160/578 KB   144/257 KB   269/279 KB   
160/578 KB   144/257 KB   273/279 KB   
160/578 KB   144/257 KB   277/279 KB   
160/578 KB   144/257 KB   279/279 KB   
164/578 KB   144/257 KB   279/279 KB   
168/578 KB   144/257 KB   279/279 KB   
172/578 KB   144/257 KB   279/279 KB   
176/578 KB   144/257 KB   279/279 KB   
176/578 KB   148/257 KB   279/279 KB   
176/578 KB   152/257 KB   279/279 KB   
176/578 KB   156/257 KB   279/279 KB   
176/578 KB   160/257 KB   279/279 KB   
180/578 KB   160/257 KB   279/279 KB   
184/578 KB   160/257 KB   279/279 KB   
188/578 KB   160/257 KB   279/279 KB   
192/578 KB   160/257 KB   279/279 KB   
192/578 KB   164/257 KB   279/279 KB   
192/578 KB   168/257 KB   279/279 KB   
192/578 KB   172/257 KB   279/279 KB   
192/578 KB   176/257 KB   279/279 KB   
196/578 KB   176/257 KB   279/279 KB   
200/578 KB   176/257 KB   279/279 KB   
204/578 KB   176/257 KB   279/279 KB   
208/578 KB   176/257 KB   279/279 KB   
                                       
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/maven-compat/3.0/maven-compat-3.0.jar (279 KB at 1554.3 KB/sec)
208/578 KB   180/257 KB                
208/578 KB   184/257 KB   
208/578 KB   188/257 KB   
208/578 KB   192/257 KB   
212/578 KB   192/257 KB   
216/578 KB   192/257 KB   
220/578 KB   192/257 KB   
224/578 KB   192/257 KB   
224/578 KB   196/257 KB   
224/578 KB   200/257 KB   
224/578 KB   204/257 KB   
224/578 KB   208/257 KB   
228/578 KB   208/257 KB   
232/578 KB   208/257 KB   
236/578 KB   208/257 KB   
240/578 KB   208/257 KB   
240/578 KB   212/257 KB   
240/578 KB   216/257 KB   
240/578 KB   220/257 KB   
240/578 KB   224/257 KB   
244/578 KB   224/257 KB   
248/578 KB   224/257 KB   
252/578 KB   224/257 KB   
256/578 KB   224/257 KB   
256/578 KB   228/257 KB   
256/578 KB   232/257 KB   
256/578 KB   236/257 KB   
256/578 KB   240/257 KB   
260/578 KB   240/257 KB   
264/578 KB   240/257 KB   
268/578 KB   240/257 KB   
272/578 KB   240/257 KB   
272/578 KB   244/257 KB   
272/578 KB   248/257 KB   
272/578 KB   252/257 KB   
272/578 KB   256/257 KB   
272/578 KB   257/257 KB   
276/578 KB   257/257 KB   
280/578 KB   257/257 KB   
284/578 KB   257/257 KB   
288/578 KB   257/257 KB   
292/578 KB   257/257 KB   
296/578 KB   257/257 KB   
300/578 KB   257/257 KB   
304/578 KB   257/257 KB   
308/578 KB   257/257 KB   
312/578 KB   257/257 KB   
316/578 KB   257/257 KB   
320/578 KB   257/257 KB   
                          
Downloaded: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.2.0/plexus-utils-3.2.0.jar (257 KB at 1264.1 KB/sec)
324/578 KB                
328/578 KB   
332/578 KB   
336/578 KB   
340/578 KB   
344/578 KB   
348/578 KB   
352/578 KB   
356/578 KB   
360/578 KB   
364/578 KB   
368/578 KB   
372/578 KB   
376/578 KB   
380/578 KB   
384/578 KB   
388/578 KB   
392/578 KB   
393/578 KB   
397/578 KB   
401/578 KB   
405/578 KB   
409/578 KB   
413/578 KB   
417/578 KB   
421/578 KB   
425/578 KB   
429/578 KB   
433/578 KB   
437/578 KB   
441/578 KB   
445/578 KB   
449/578 KB   
453/578 KB   
457/578 KB   
461/578 KB   
465/578 KB   
469/578 KB   
473/578 KB   
477/578 KB   
481/578 KB   
485/578 KB   
489/578 KB   
493/578 KB   
497/578 KB   
501/578 KB   
505/578 KB   
509/578 KB   
513/578 KB   
517/578 KB   
521/578 KB   
525/578 KB   
529/578 KB   
533/578 KB   
537/578 KB   
541/578 KB   
545/578 KB   
549/578 KB   
553/578 KB   
557/578 KB   
561/578 KB   
565/578 KB   
569/578 KB   
573/578 KB   
577/578 KB   
578/578 KB   
             
Downloaded: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.18/commons-compress-1.18.jar (578 KB at 1972.3 KB/sec)
[INFO] Building jar: /var/jenkins_home/workspace/spring-petclinic-hub/target/spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar
[INFO] 
[INFO] --- spring-boot-maven-plugin:2.2.2.RELEASE:repackage (repackage) @ spring-petclinic ---
[INFO] Replacing main artifact with repackaged archive
[INFO] 
[INFO] --- maven-install-plugin:2.5.2:install (default-install) @ spring-petclinic ---
Downloading: https://repo.spring.io/snapshot/junit/junit/3.8.1/junit-3.8.1.pom
             
Downloading: https://repo.spring.io/milestone/junit/junit/3.8.1/junit-3.8.1.pom
             
Downloading: https://repo.maven.apache.org/maven2/junit/junit/3.8.1/junit-3.8.1.pom
998/998 B    
            
Downloaded: https://repo.maven.apache.org/maven2/junit/junit/3.8.1/junit-3.8.1.pom (998 B at 46.4 KB/sec)
Downloading: https://repo.spring.io/snapshot/commons-codec/commons-codec/1.6/commons-codec-1.6.pom
            
Downloading: https://repo.spring.io/milestone/commons-codec/commons-codec/1.6/commons-codec-1.6.pom
            
Downloading: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.6/commons-codec-1.6.pom
4/11 KB     
8/11 KB   
11/11 KB   
           
Downloaded: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.6/commons-codec-1.6.pom (11 KB at 389.1 KB/sec)
Downloading: https://repo.spring.io/snapshot/org/apache/maven/shared/maven-shared-utils/0.4/maven-shared-utils-0.4.pom
           
Downloading: https://repo.spring.io/milestone/org/apache/maven/shared/maven-shared-utils/0.4/maven-shared-utils-0.4.pom
           
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/0.4/maven-shared-utils-0.4.pom
4/4 KB     
         
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/0.4/maven-shared-utils-0.4.pom (4 KB at 152.0 KB/sec)
Downloading: https://repo.spring.io/snapshot/junit/junit/3.8.1/junit-3.8.1.jar
Downloading: https://repo.spring.io/snapshot/org/apache/maven/shared/maven-shared-utils/0.4/maven-shared-utils-0.4.jar
Downloading: https://repo.spring.io/snapshot/commons-codec/commons-codec/1.6/commons-codec-1.6.jar
Downloading: https://repo.spring.io/snapshot/org/codehaus/plexus/plexus-utils/3.0.15/plexus-utils-3.0.15.jar
         
         
         
         
Downloading: https://repo.spring.io/milestone/junit/junit/3.8.1/junit-3.8.1.jar
Downloading: https://repo.spring.io/milestone/commons-codec/commons-codec/1.6/commons-codec-1.6.jar
Downloading: https://repo.spring.io/milestone/org/apache/maven/shared/maven-shared-utils/0.4/maven-shared-utils-0.4.jar
Downloading: https://repo.spring.io/milestone/org/codehaus/plexus/plexus-utils/3.0.15/plexus-utils-3.0.15.jar
         
         
         
         
Downloading: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.6/commons-codec-1.6.jar
Downloading: https://repo.maven.apache.org/maven2/junit/junit/3.8.1/junit-3.8.1.jar
Downloading: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/0.4/maven-shared-utils-0.4.jar
Downloading: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.0.15/plexus-utils-3.0.15.jar
4/228 KB   
8/228 KB   
12/228 KB   
16/228 KB   
16/228 KB   4/119 KB   
16/228 KB   8/119 KB   
16/228 KB   12/119 KB   
16/228 KB   16/119 KB   
20/228 KB   16/119 KB   
24/228 KB   16/119 KB   
28/228 KB   16/119 KB   
32/228 KB   16/119 KB   
32/228 KB   16/119 KB   4/234 KB   
32/228 KB   16/119 KB   8/234 KB   
32/228 KB   16/119 KB   12/234 KB   
32/228 KB   16/119 KB   16/234 KB   
32/228 KB   20/119 KB   16/234 KB   
32/228 KB   24/119 KB   16/234 KB   
32/228 KB   28/119 KB   16/234 KB   
32/228 KB   32/119 KB   16/234 KB   
36/228 KB   32/119 KB   16/234 KB   
40/228 KB   32/119 KB   16/234 KB   
44/228 KB   32/119 KB   16/234 KB   
48/228 KB   32/119 KB   16/234 KB   
52/228 KB   32/119 KB   16/234 KB   
56/228 KB   32/119 KB   16/234 KB   
60/228 KB   32/119 KB   16/234 KB   
64/228 KB   32/119 KB   16/234 KB   
64/228 KB   32/119 KB   4/152 KB   16/234 KB   
64/228 KB   32/119 KB   8/152 KB   16/234 KB   
64/228 KB   32/119 KB   12/152 KB   16/234 KB   
64/228 KB   32/119 KB   16/152 KB   16/234 KB   
64/228 KB   32/119 KB   16/152 KB   20/234 KB   
64/228 KB   32/119 KB   16/152 KB   24/234 KB   
64/228 KB   32/119 KB   16/152 KB   28/234 KB   
64/228 KB   32/119 KB   16/152 KB   32/234 KB   
64/228 KB   36/119 KB   16/152 KB   32/234 KB   
64/228 KB   40/119 KB   16/152 KB   32/234 KB   
64/228 KB   44/119 KB   16/152 KB   32/234 KB   
64/228 KB   48/119 KB   16/152 KB   32/234 KB   
68/228 KB   48/119 KB   16/152 KB   32/234 KB   
72/228 KB   48/119 KB   16/152 KB   32/234 KB   
76/228 KB   48/119 KB   16/152 KB   32/234 KB   
80/228 KB   48/119 KB   16/152 KB   32/234 KB   
80/228 KB   52/119 KB   16/152 KB   32/234 KB   
80/228 KB   56/119 KB   16/152 KB   32/234 KB   
80/228 KB   60/119 KB   16/152 KB   32/234 KB   
80/228 KB   64/119 KB   16/152 KB   32/234 KB   
80/228 KB   64/119 KB   20/152 KB   32/234 KB   
80/228 KB   64/119 KB   24/152 KB   32/234 KB   
80/228 KB   64/119 KB   28/152 KB   32/234 KB   
80/228 KB   64/119 KB   32/152 KB   32/234 KB   
80/228 KB   68/119 KB   32/152 KB   32/234 KB   
80/228 KB   72/119 KB   32/152 KB   32/234 KB   
80/228 KB   76/119 KB   32/152 KB   32/234 KB   
80/228 KB   80/119 KB   32/152 KB   32/234 KB   
80/228 KB   80/119 KB   32/152 KB   36/234 KB   
80/228 KB   80/119 KB   32/152 KB   40/234 KB   
80/228 KB   80/119 KB   32/152 KB   44/234 KB   
80/228 KB   80/119 KB   32/152 KB   48/234 KB   
80/228 KB   80/119 KB   36/152 KB   48/234 KB   
80/228 KB   80/119 KB   40/152 KB   48/234 KB   
80/228 KB   80/119 KB   44/152 KB   48/234 KB   
80/228 KB   80/119 KB   48/152 KB   48/234 KB   
80/228 KB   84/119 KB   48/152 KB   48/234 KB   
80/228 KB   88/119 KB   48/152 KB   48/234 KB   
80/228 KB   92/119 KB   48/152 KB   48/234 KB   
80/228 KB   96/119 KB   48/152 KB   48/234 KB   
80/228 KB   96/119 KB   48/152 KB   52/234 KB   
80/228 KB   96/119 KB   48/152 KB   56/234 KB   
80/228 KB   96/119 KB   48/152 KB   60/234 KB   
80/228 KB   96/119 KB   48/152 KB   64/234 KB   
84/228 KB   96/119 KB   48/152 KB   64/234 KB   
88/228 KB   96/119 KB   48/152 KB   64/234 KB   
92/228 KB   96/119 KB   48/152 KB   64/234 KB   
96/228 KB   96/119 KB   48/152 KB   64/234 KB   
96/228 KB   100/119 KB   48/152 KB   64/234 KB   
96/228 KB   104/119 KB   48/152 KB   64/234 KB   
96/228 KB   108/119 KB   48/152 KB   64/234 KB   
96/228 KB   112/119 KB   48/152 KB   64/234 KB   
96/228 KB   112/119 KB   52/152 KB   64/234 KB   
96/228 KB   112/119 KB   56/152 KB   64/234 KB   
96/228 KB   112/119 KB   60/152 KB   64/234 KB   
96/228 KB   112/119 KB   64/152 KB   64/234 KB   
96/228 KB   116/119 KB   64/152 KB   64/234 KB   
96/228 KB   119/119 KB   64/152 KB   64/234 KB   
96/228 KB   119/119 KB   64/152 KB   68/234 KB   
96/228 KB   119/119 KB   64/152 KB   72/234 KB   
96/228 KB   119/119 KB   64/152 KB   76/234 KB   
96/228 KB   119/119 KB   64/152 KB   80/234 KB   
96/228 KB   119/119 KB   68/152 KB   80/234 KB   
96/228 KB   119/119 KB   72/152 KB   80/234 KB   
96/228 KB   119/119 KB   76/152 KB   80/234 KB   
96/228 KB   119/119 KB   80/152 KB   80/234 KB   
100/228 KB   119/119 KB   80/152 KB   80/234 KB   
104/228 KB   119/119 KB   80/152 KB   80/234 KB   
108/228 KB   119/119 KB   80/152 KB   80/234 KB   
112/228 KB   119/119 KB   80/152 KB   80/234 KB   
112/228 KB   119/119 KB   80/152 KB   84/234 KB   
112/228 KB   119/119 KB   80/152 KB   88/234 KB   
112/228 KB   119/119 KB   80/152 KB   92/234 KB   
112/228 KB   119/119 KB   80/152 KB   96/234 KB   
116/228 KB   119/119 KB   80/152 KB   96/234 KB   
120/228 KB   119/119 KB   80/152 KB   96/234 KB   
124/228 KB   119/119 KB   80/152 KB   96/234 KB   
124/228 KB   119/119 KB   84/152 KB   96/234 KB   
128/228 KB   119/119 KB   84/152 KB   96/234 KB   
128/228 KB   119/119 KB   88/152 KB   96/234 KB   
128/228 KB   119/119 KB   92/152 KB   96/234 KB   
128/228 KB   119/119 KB   96/152 KB   96/234 KB   
128/228 KB   119/119 KB   96/152 KB   100/234 KB   
128/228 KB   119/119 KB   96/152 KB   104/234 KB   
128/228 KB   119/119 KB   96/152 KB   108/234 KB   
128/228 KB   119/119 KB   96/152 KB   112/234 KB   
132/228 KB   119/119 KB   96/152 KB   112/234 KB   
136/228 KB   119/119 KB   96/152 KB   112/234 KB   
140/228 KB   119/119 KB   96/152 KB   112/234 KB   
144/228 KB   119/119 KB   96/152 KB   112/234 KB   
144/228 KB   119/119 KB   100/152 KB   112/234 KB   
144/228 KB   119/119 KB   104/152 KB   112/234 KB   
144/228 KB   119/119 KB   108/152 KB   112/234 KB   
144/228 KB   119/119 KB   112/152 KB   112/234 KB   
148/228 KB   119/119 KB   112/152 KB   112/234 KB   
152/228 KB   119/119 KB   112/152 KB   112/234 KB   
156/228 KB   119/119 KB   112/152 KB   112/234 KB   
160/228 KB   119/119 KB   112/152 KB   112/234 KB   
160/228 KB   119/119 KB   116/152 KB   112/234 KB   
160/228 KB   119/119 KB   120/152 KB   112/234 KB   
160/228 KB   119/119 KB   124/152 KB   112/234 KB   
160/228 KB   119/119 KB   128/152 KB   112/234 KB   
160/228 KB   119/119 KB   128/152 KB   116/234 KB   
160/228 KB   119/119 KB   128/152 KB   120/234 KB   
160/228 KB   119/119 KB   128/152 KB   124/234 KB   
160/228 KB   119/119 KB   128/152 KB   128/234 KB   
164/228 KB   119/119 KB   128/152 KB   128/234 KB   
168/228 KB   119/119 KB   128/152 KB   128/234 KB   
172/228 KB   119/119 KB   128/152 KB   128/234 KB   
176/228 KB   119/119 KB   128/152 KB   128/234 KB   
176/228 KB   119/119 KB   132/152 KB   128/234 KB   
176/228 KB   119/119 KB   136/152 KB   128/234 KB   
176/228 KB   119/119 KB   140/152 KB   128/234 KB   
176/228 KB   119/119 KB   144/152 KB   128/234 KB   
176/228 KB   119/119 KB   144/152 KB   132/234 KB   
176/228 KB   119/119 KB   144/152 KB   136/234 KB   
176/228 KB   119/119 KB   144/152 KB   140/234 KB   
176/228 KB   119/119 KB   144/152 KB   144/234 KB   
180/228 KB   119/119 KB   144/152 KB   144/234 KB   
184/228 KB   119/119 KB   144/152 KB   144/234 KB   
188/228 KB   119/119 KB   144/152 KB   144/234 KB   
192/228 KB   119/119 KB   144/152 KB   144/234 KB   
192/228 KB   119/119 KB   148/152 KB   144/234 KB   
192/228 KB   119/119 KB   152/152 KB   144/234 KB   
                                                    
Downloaded: https://repo.maven.apache.org/maven2/junit/junit/3.8.1/junit-3.8.1.jar (119 KB at 1257.8 KB/sec)
192/228 KB   152/152 KB   148/234 KB                
192/228 KB   152/152 KB   152/234 KB   
192/228 KB   152/152 KB   156/234 KB   
192/228 KB   152/152 KB   160/234 KB   
196/228 KB   152/152 KB   160/234 KB   
200/228 KB   152/152 KB   160/234 KB   
204/228 KB   152/152 KB   160/234 KB   
208/228 KB   152/152 KB   160/234 KB   
212/228 KB   152/152 KB   160/234 KB   
212/228 KB   152/152 KB   164/234 KB   
216/228 KB   152/152 KB   164/234 KB   
216/228 KB   152/152 KB   168/234 KB   
220/228 KB   152/152 KB   168/234 KB   
220/228 KB   152/152 KB   172/234 KB   
224/228 KB   152/152 KB   172/234 KB   
224/228 KB   152/152 KB   176/234 KB   
228/228 KB   152/152 KB   176/234 KB   
                                       
Downloaded: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/0.4/maven-shared-utils-0.4.jar (152 KB at 1459.7 KB/sec)
228/228 KB   180/234 KB                
228/228 KB   184/234 KB   
228/228 KB   188/234 KB   
228/228 KB   192/234 KB   
228/228 KB   196/234 KB   
228/228 KB   200/234 KB   
228/228 KB   204/234 KB   
228/228 KB   208/234 KB   
                          
Downloaded: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.6/commons-codec-1.6.jar (228 KB at 2011.6 KB/sec)
212/234 KB                
216/234 KB   
220/234 KB   
224/234 KB   
228/234 KB   
232/234 KB   
234/234 KB   
             
Downloaded: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.0.15/plexus-utils-3.0.15.jar (234 KB at 1852.0 KB/sec)
[INFO] Installing /var/jenkins_home/workspace/spring-petclinic-hub/target/spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar to /root/.m2/repository/org/springframework/samples/spring-petclinic/2.2.0.BUILD-SNAPSHOT/spring-petclinic-2.2.0.BUILD-SNAPSHOT.jar
[INFO] Installing /var/jenkins_home/workspace/spring-petclinic-hub/pom.xml to /root/.m2/repository/org/springframework/samples/spring-petclinic/2.2.0.BUILD-SNAPSHOT/spring-petclinic-2.2.0.BUILD-SNAPSHOT.pom
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 01:30 min
[INFO] Finished at: 2023-06-16T14:05:45+00:00
[INFO] Final Memory: 100M/345M
[INFO] ------------------------------------------------------------------------
+ ls
Dockerfile
Jenkinsfile
docker-compose.yml
jenkins-docker
mvnw
mvnw.cmd
pom.xml
push-to-pws
readme.md
src
start.sh
target
terminate.sh
+ pwd
/var/jenkins_home/workspace/spring-petclinic-hub