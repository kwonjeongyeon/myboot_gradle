# myboot_gradle

(23.04.18) Maven Repository에서 Tomcat Embed Jasper와 JSTL 코드 build.gradle에 작성 

- gradle로 spring starter project 생성시 오류 (NoMatchingConfiurationSelectionException: No matching variant of org.springfrmaework.boot:spring-boot-gradle-plugin:3.0.5 was found. The consumer was configured to find a runtime of a library com...bility with java 11) 발생하면, project 생성할 때 java spring version을 2.7.10으로 낮추고 생성하면 해결가능

- WEB-INF 폴더에 lib 폴더 생성해 jstl(1.2).jar 넣었지만 해결 실패 (spring 4 에서) // spring 3에서 버전 낮추고 생성하면 해결 가능
