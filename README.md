# nginx reverse proxy

## features

## setup guide

1. create network named `nginx-proxy`

   ```bash
   docker network create nginx-proxy
   ```

2. create project directory for nginx_proxy container

   ```bash
   sudo mkdir nginx_proxy
   ```

3. clone the repository

   ```bash
   sudo git clone <name_of_remote_repository>
   ```

4. start reverse-proxy container

   ```bash
   docker-compose up -d
   ```
