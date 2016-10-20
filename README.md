# media-downloader

A media downloader and server Docker Compose application with Plex, Transmission, Nzbget, Sonarr, Headphones, and CouchPotato.

## Usage

1. Create the Docker Compose application:

  ```
  $ docker-compose up
  ```

2. Configure the services to your liking.

**Hint:** You can configure services to talk to each other by using the name of the container as a hostname. For example, Nzbget will be accessible on `nzbget:6789` to all other containers in the application.

## Services

| Service      | Port  |
| ------------ | ----- |
| CouchPotato  | 5050  |
| Headphones   | 8181  |
| Nzbget       | 6789  |
| Plex         | 32400 |
| Sonarr       | 8989  |
| Transmission | 9091  |
