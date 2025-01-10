# Setup Backend

## Prerequisites

1. Docker installed on your system.
2. Docker Compose installed on your system.

## Installation Steps

1. Clone the backend repository:
   ```sh
   git clone https://github.com/boersen-party/boersenparty-backend.git
   cd boersenparty-backend
   ```

2. Copy the `.env.tmp` file to `.env` and update the environment variables as needed:
   ```sh
   cp .env.tmp .env
   ```

3. Start the backend application using Docker Compose:
   ```sh
   docker-compose up -d
   ```

4. Access the backend application at `http://localhost:8080`.

# Backend einrichten

## Voraussetzungen

1. Docker auf Ihrem System installiert.
2. Docker Compose auf Ihrem System installiert.

## Installationsschritte

1. Klonen Sie das Backend-Repository:
   ```sh
   git clone https://github.com/boersen-party/boersenparty-backend.git
   cd boersenparty-backend
   ```

2. Kopieren Sie die Datei `.env.tmp` nach `.env` und aktualisieren Sie die Umgebungsvariablen nach Bedarf:
   ```sh
   cp .env.tmp .env
   ```

3. Starten Sie die Backend-Anwendung mit Docker Compose:
   ```sh
   docker-compose up -d
   ```

4. Greifen Sie auf die Backend-Anwendung unter `http://localhost:8080` zu.