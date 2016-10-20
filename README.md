# media-downloader

A media downloader and server Docker Compose application with Plex, Transmission, Nzbget, Sonarr, Headphones, and CouchPotato.

## Usage

1. Create the Docker Compose application:

  ```
  $ docker-compose up
  ```

2. Configure the services to your liking.

## Services

| Service      | Port  |
| ------------ | ----- |
| CouchPotato  | 5050  |
| Headphones   | 8181  |
| Nzbget       | 6789  |
| Plex         | 32400 |
| Sonarr       | 8989  |
| Transmission | 9091  |
