# AsyncMock
This is a project for mocking async web protocols (Web socket and SSE)

Run the service with docker:

`docker build -t async-mock . && docker run -it --rm --network host async-mock`

Or locally (you need to have sbt and bash (together with `curl`, `unzip` and `sed`) installed):

`bash ./scripts/download-swagger-ui.sh ./src/main/resources/swagger/ && sbt run`