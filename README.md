# gin-in-a-can

[The existing openapi generator for Gin](https://openapi-generator.tech/docs/generators/go-gin-server)  is decent, but it lacks certain features that I need.
Ideally, I would contribute to it directly, but I need this sooner than I am able to learn how their build system, etc work.

The features I need are:
* To be able to register an existing gin Engine with predefined middleware.
* To be able to use the generated code without modifying it.

See openapi.yaml for a sample API.
Also see api/server.go for an example of generated code based on the sample API.

## TODO
* Add request and response schema attributes to their respective structs
* Add parameter validation based on the `required` flag, regex patterns and other OpenAPI format specifications