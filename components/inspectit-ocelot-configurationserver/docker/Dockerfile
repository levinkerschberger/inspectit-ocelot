FROM --platform=$BUILDPLATFORM eclipse-temurin:17

WORKDIR /app

COPY docker/entrypoint.sh /app/entrypoint.sh
COPY build/docker-jar/*.jar /app/inspectit-ocelot-configurationserver.jar

ENTRYPOINT ["sh", "/app/entrypoint.sh"]
