# E2E B2C Money Transfer

## Security Description
1. Between Client App and B2C Serivce the security and multi-user usage is established using Token-based authentication.
2. B2C Service makes all Client App request calls to other services on behalf of Client App using OAuth 2.0. So it first requests for an access_token from AuthService that has an expiration date that is renewing after each its usage.

## Artifacts
SwaggerUI and PlantUML are generated dynamically based on source files

### API Specification
https://viacheslav-lasukov.github.io/UMoney_TT

### Sequence Diagram
![Sequence Diagram](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/viacheslav-lasukov/UMoney_TT/main/sequenceDiagram.puml)
