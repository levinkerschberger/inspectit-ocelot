FROM --platform=$BUILDPLATFORM amazoncorretto:17

WORKDIR /app

COPY docker/entrypoint.sh /app/entrypoint.sh
COPY build/libs/*.jar /app/inspectit-ocelot-configurationserver.jar

ENTRYPOINT ["sh", "/app/entrypoint.sh"]
