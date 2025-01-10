# Setup Frontend

## Prerequisites

1. Docker installed on your system.
2. Docker Compose installed on your system.

## Installation Steps

1. Clone the frontend repository:
   ```sh
   git clone https://github.com/boersen-party/boersenparty-frontend.git
   cd boersenparty-frontend
   ```

2. Copy the `.env.tmp` file to `.env` and update the environment variables as needed:
   ```sh
   cp .env.tmp .env
   ```

3. Start the frontend application using Docker Compose:
   ```sh
   docker-compose up -d
   ```
   
4. Access the frontend application in your browser at `http://localhost:80`.


# Frontend einrichten

## Voraussetzungen

1. Docker auf Ihrem System installiert.
2. Docker Compose auf Ihrem System installiert.

## Installationsschritte

1. Klonen Sie das Frontend-Repository:
   ```sh
   git clone https://github.com/boersen-party/boersenparty-frontend.git
   cd boersenparty-frontend
   ```

2. Kopieren Sie die Datei `.env.tmp` nach `.env` und aktualisieren Sie die Umgebungsvariablen nach Bedarf:
   ```sh
   cp .env.tmp .env
   ```

3. Starten Sie die Frontend-Anwendung mit Docker Compose:
   ```sh
   docker-compose up -d
   ```
   
4. Greifen Sie in Ihrem Browser auf die Frontend-Anwendung unter `http://localhost:80` zu.