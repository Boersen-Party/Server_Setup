# Setup Traefik

## Manual Steps

1. Copy `traefik.yml.tmp` to `traefik.yml` and change the email address in `traefik.yml`.
2. Run the following command:
   ```sh
   touch acme.json && chmod 600 acme.json
   ```
3. Copy `.env.tmp` to `.env` and change the domain.
4. Run the following command to create a Docker network:
   ```sh
   docker network create traefik
   ```
5. Start Traefik using Docker Compose:
   ```sh
   docker-compose up -d
   ```

# Traefik einrichten

## Manuelle Schritte

1. Kopiere `traefik.yml.tmp` nach `traefik.yml` und ändere die E-Mail-Adresse in `traefik.yml`.
2. Führe den folgenden Befehl aus:
   ```sh
   touch acme.json && chmod 600 acme.json
   ```
3. Kopiere `.env.tmp` nach `.env` und ändere die Domain.
4. Führe den folgenden Befehl aus, um ein Docker-Netzwerk zu erstellen:
   ```sh
   docker network create traefik
   ```
5. Starte Traefik mit Docker Compose:
   ```sh
   docker-compose up -d
   ```