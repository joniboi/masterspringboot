FROM drizztdourden21/frp:4.2.1
ENV LD_LIBRARY_PATH=/usr/lfissdk/libs
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-Djava.awt.headless=true","-jar","app.jar"]
