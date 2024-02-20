# OpenAPI description for the Paddle API

This repo contains an OpenAPI description for the Paddle API. 

We use OpenAPI 3.1.

## What is the Paddle API?

[Paddle Billing](https://www.paddle.com/billing?utm_source=dx&utm_medium=paddle-openapi) is a complete subscription and recurring revenue management platform, designed for modern SaaS businesses. It helps you increase your revenue, retain customers, and scale your operations.

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
| `x-tags`              | array   | Used to categorize schemas. May be removed in the future.                                                                                                            |
| `x-stoplight`         | object  | Contains stable IDs for working with [Stoplight Studio](https://docs.stoplight.io/docs/platform/x8m99p1dhhvl8-extensions#x-stoplight). May be removed in the future. |


## Run in Postman

[Postman](https://www.postman.com/) is platform for working with and testing APIs.

You can [fork our Postman collection](https://www.postman.com/paddlehq) to see all operations available in the Paddle API and quickly make requests. It's a great way to explore the API if you're new to Paddle or want to test newly released functionality.


## Contributing

The OpenAPI spec is automatically generated and added to this repo when we release changes to the Paddle API. It's integrated with internal developer tooling at Paddle. For this reason, we don't accept contributions.

If you've spotted a problem with the OpenAPI spec, open an issue.


## Learn more

* [Paddle API reference](https://developer.paddle.com/api-reference/overview?utm_source=dx&utm_medium=paddle-openapi)
* [Sign up for Paddle Billing](https://login.paddle.com/signup?utm_source=dx&utm_medium=paddle-openapi)
