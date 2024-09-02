# marc-et-chieko

## Development

1. Install [Docker], e.g.:

   ```console
   brew cask install docker
   ```

2. Ensure Docker is running.
3. Run:

   ```console
   docker run --rm -d \
     --name web \
     -p 8080:80 \
     -v $(pwd):/usr/share/nginx/html \
      nginx
   ```

4. Open <http://localhost:8080>

[Docker]: https://docs.docker.com/engine/install/
