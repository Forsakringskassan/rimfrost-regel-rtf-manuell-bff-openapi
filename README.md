# OpenAPI-specifikation för RTF manuell BFF

Beskriver API:t mellan `rimfrost-regel-rtf-manuell-fe` och `rimfrost-regel-rtf-manuell-bff`.

- BFF:en implementerar det genererade interfacet från `rimfrost-regel-rtf-manuell-bff-openapi-jaxrs-spec` (Maven).
- FE:n genererar TypeScript-typer med `openapi-typescript` från `openapi.yaml` på en release-tagg.
