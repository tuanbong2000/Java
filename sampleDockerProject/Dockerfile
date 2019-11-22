FROM openjdk
COPY src sampleDockerProject
WORKDIR sampleDockerProject
RUN mkdir -p bin
RUN javac -d bin ./com/tuan/myapp/HelloWorld.java
WORKDIR bin
CMD ["java", "com.tuan.myapp.HelloWorld"]