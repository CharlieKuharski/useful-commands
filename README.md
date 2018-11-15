# useful-commands

- To curl a url in a loop
-- while true; do curl https://www.google.com/; sleep .7; done

- Gradle
--- ./gradlew bootrun  -Dspring.profiles.active=smash  ==> you will get base

- ./gradlew build --scan

--
./gradlew clean build && java -jar build/libs/sourceservice-1.0-SNAPSHOT.jar --spring.profiles.active=dev
