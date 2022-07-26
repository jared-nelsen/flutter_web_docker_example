# flutter_web_docker_example

An example project to show how a Flutter web app can be served from a Docker Container.

See my blog article [here](https://www.jarednelsen.dev/blog/serve-a-flutter-web-app-from-docker/) for a tutorial!

## Commands

Build: `docker build . -t flutter_web_docker_example`

Run: `docker run -i -p 808:4040 -td flutter_web_docker_example`

