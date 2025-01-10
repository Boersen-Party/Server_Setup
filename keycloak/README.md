# Setup Keycloak

## Prerequisites

1. Docker installed on your system.
2. Docker Compose installed on your system.

## Installation Steps

1. Clone the Keycloak repository:
   ```sh
   git clone https://github.com/keycloak/keycloak-containers.git
   cd keycloak-containers/server
   ```

2. Copy the `.env.tmp` file to `.env` and update the environment variables as needed:
   ```sh
   cp .env.tmp .env
   ```

3. Create a Docker Compose file `docker-compose.yml` with the necessary content.

4. Start the Keycloak server using Docker Compose:
   ```sh
   docker-compose up -d
   ```

5. Access Keycloak in your browser at `http://localhost:8080` and log in with the username `admin` and password `password`.

6. Create a new realm and create a new client with the following settings:
   #### Access Settings
    - Root URL: `https://{yourDomain}`
    - Home URL: `https://{yourDomain}`
    - Valid Redirect URIs: `https://{yourDomain}/*`
    - Valid Post Logout Redirect URIs: `https://{yourDomain}/*`
    - Web Origins: `*`
    - Admin URL: `https://{yourDomain}`
   #### Capability config
    - Authentication flow (Standard Flow and Direct Access Grants)



# Keycloak einrichten

## Voraussetzungen

1. Docker auf Ihrem System installiert.
2. Docker Compose auf Ihrem System installiert.

## Installationsschritte

1. Klonen Sie das Keycloak-Repository:
   ```sh
   git clone https://github.com/keycloak/keycloak-containers.git
   cd keycloak-containers/server
   ```

2. Kopieren Sie die Datei `.env.tmp` nach `.env` und aktualisieren Sie die Umgebungsvariablen nach Bedarf:
   ```sh
   cp .env.tmp .env
   ```

3. Erstellen Sie eine Docker Compose-Datei `docker-compose.yml` mit dem notwendigen Inhalt.

4. Starten Sie den Keycloak-Server mit Docker Compose:
   ```sh
   docker-compose up -d
   ```

5. Greifen Sie in Ihrem Browser auf Keycloak unter `http://localhost:8080` zu und melden Sie sich mit dem Benutzernamen `admin` und dem Passwort `password` an.

6. Erstellen Sie ein neues Realm und einen neuen Client mit den folgenden Einstellungen:
   #### Zugriffseinstellungen
    - Root-URL: `https://{yourDomain}`
    - Home-URL: `https://{yourDomain}`
    - Gültige Umleitungs-URIs: `https://{yourDomain}/*`
    - Gültige Post-Logout-Umleitungs-URIs: `https://{yourDomain}/*`
    - Web-Ursprünge: `*`
    - Admin-URL: `https://{yourDomain}`
   #### Fähigkeitskonfiguration
    - Authentifizierungsfluss (Standardfluss und Direkter Zugriff)