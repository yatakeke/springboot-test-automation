FROM mcr.microsoft.com/playwright/java:v1.40.0-jammy
LABEL authors="shinnosuke"

WORKDIR /app

COPY . .

RUN chmod u+x gradlew

ENTRYPOINT ["./gradlew", "test"]

# FIXME: install gradle every building
# FIXME: install browser dev tool for playwright
