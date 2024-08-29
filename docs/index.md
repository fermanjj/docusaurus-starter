# Introduction

This is the official documentation for the API for [**Site Qwality**](https://siteqwality.com). The API is a
RESTful API that allows you to interact with the application in a programmatic way.

# Base URL

The base URL for the API is `https://api.siteqwality.com`.

# Authentication

The API uses API keys for authentication.

To obtain an API key, you will need to sign up for an account on the [**Site Qwality App**](https://app.siteqwality.com)
website and generate an API key in the account settings.

Once you have an API key, you can include it in the `Authorization` header of your requests.

For example

    ```http
    Authorization: Bearer <YOUR_API_KEY>
    ```

# Rate Limiting

The API has rate limiting in place to prevent abuse. If you exceed the rate limit, you will receive a
`429 Too Many Requests` response.

# Errors

The API uses standard HTTP status codes to indicate the success or failure of a request. If an error occurs, you will
receive a response with an appropriate status code and an error message in the body.

# Support

If you have any questions or need help with the API, please contact us
at [support@siteqwality.com](mailto:support@siteqwality.com).
