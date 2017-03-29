# java-alpine-openjdk8-jdk
Java Base Docker Image with wait-for-it based on Fabric8 Java Base Image

See https://github.com/iturgeon/wait-for-it

Example: ``docker run -P -m=125M rafabene/java-container:fabric8 /wait-for-it.sh www.google.nl:81 --strict -- /deployments/run-java.sh``
