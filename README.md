# OpenAPI description for the Paddle API

This repo contains an OpenAPI description for the Paddle API. 

We use OpenAPI 3.1.

## What is the Paddle API?

[Paddle Billing](https://www.paddle.com/billing?utm_source=dx&utm_medium=paddle-openapi) is the developer-first merchant of record. We take care of payments, tax, subscriptions, and metrics with one unified API that does it all.

Use [the Paddle API](https://developer.paddle.com/api-reference/overview?utm_source=dx&utm_medium=paddle-openapi) to create, read, and update information in your Paddle Billing system.

> [!IMPORTANT]
> The Paddle Classic API is not part of this repository. To work with the Paddle Classic API, see: [Paddle Classic API reference](https://developer.paddle.com/classic/api-reference/1384a288aca7a-api-reference?utm_source=dx&utm_medium=paddle-openapi)


## What is OpenAPI? 

[OpenAPI](https://github.com/OAI/OpenAPI-Specification/) is a programming language-agnostic way of describing the structure and syntax of APIs. It allows humans and computers to understand how an API works. It's often used for working programmatically with an API.


## Get started

The `v1` directory contains an OpenAPI specification file for each supported [version](https://developer.paddle.com/api-reference/about/versioning?utm_source=dx&utm_medium=paddle-openapi) of the Paddle API.

We recommend that you [fork this repo](https://docs.github.com/en/get-started/quickstart/fork-a-repo), rather than downloading OpenAPI files directly. This means you can [get the latest changes](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork) using git in the future.


## Vendor extensions

We use some vendor extensions for concepts that are harder to express with OpenAPI components.

| Extension             | Type    | Description                                                                                                                                                          |
|-----------------------|---------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `x-enum-descriptions` | object  | Provides information about enums, including a description and whether they're read-only.                                                                             |
| `x-included`          | boolean | Used to mark entities that are only included in a response when the `include` query parameter is used.                                                               |

We previously used some vendor extensions that are no longer included:

* `x-tags` to categorize schemas.
* `x-stoplight` to mark entities with stable IDs for working with Stoplight Studio.


## Run in Postman

[Postman](https://www.postman.com/) is platform for working with and testing APIs.

[<img src="https://run.pstmn.io/button.svg" alt="Run In Postman" style="width: 128px; height: 32px;">](https://god.gw.postman.com/run-collection/29428794-16aca740-3ad6-4c1a-97be-05dbc504b4c3?action=collection%2Ffork&source=rip_markdown&collection-url=entityId%3D29428794-16aca740-3ad6-4c1a-97be-05dbc504b4c3%26entityType%3Dcollection%26workspaceId%3D5ed2587a-f47e-43e0-810c-0c3e782bca12)

You can [fork our Postman collection](https://god.gw.postman.com/run-collection/29428794-16aca740-3ad6-4c1a-97be-05dbc504b4c3?action=collection%2Ffork&source=rip_markdown&collection-url=entityId%3D29428794-16aca740-3ad6-4c1a-97be-05dbc504b4c3%26entityType%3Dcollection%26workspaceId%3D5ed2587a-f47e-43e0-810c-0c3e782bca12#?env%5BSandbox%5D=W3sia2V5IjoiYmFzZVVybCIsInZhbHVlIjoiaHR0cHM6Ly9zYW5kYm94LWFwaS5wYWRkbGUuY29tIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQifSx7ImtleSI6ImJlYXJlclRva2VuIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoic2VjcmV0In1d) to see all operations available in the Paddle API and quickly make requests. It's a great way to explore the API if you're new to Paddle or want to test newly released functionality.


## Contributing

The OpenAPI spec is automatically generated and added to this repo when we release changes to the Paddle API. It's integrated with internal developer tooling at Paddle. For this reason, we don't accept contributions.

If you've spotted a problem with the OpenAPI spec, open an issue.


## Learn more

* [Paddle developer docs](https://developer.paddle.com?utm_source=dx&utm_medium=paddle-openapi)
* [Paddle API reference](https://developer.paddle.com/api-reference/overview?utm_source=dx&utm_medium=paddle-openapi)
* [Sign up for Paddle Billing](https://login.paddle.com/signup?utm_source=dx&utm_medium=paddle-openapi)
