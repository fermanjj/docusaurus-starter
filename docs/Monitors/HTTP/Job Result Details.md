### Method: GET

> ```
>/http/job/result/4ed82d9d-bac1-4ebb-94b9-2811ce694642/details
>```

### Response: 200

```json
{
    "data": {
        "id": "4ed82d9d-bac1-4ebb-94b9-2811ce694642",
        "account_id": "22b48b6c-b8af-4e4a-90df-5935ad5f4ab3",
        "http_job_id": "688096d0-6226-4ba4-8588-2c6f69f44f8c",
        "created_at": "2024-03-17T23:31:02.277445Z",
        "response_headers": {
            "content-type": "text/plain; charset=utf-8",
            "date": "Sun, 17 Mar 2024 23:31:02 GMT",
            "fly-request-id": "01HS7C26XG50SZN8CKJH7ASCCK-iad",
            "server": "Fly/19c9f115b (2024-03-16)",
            "via": "2 fly.io"
        },
        "response_http_code": 404,
        "response_body": "{\"statusCode\":404,\"description\":\"Not Found\"}",
        "response_body_raw": null,
        "final_uri": "https://mock.codes/404",
        "http_version": "HTTP/2.0",
        "remote_address": "66.241.125.193:443",
        "request_duration_ms": 91,
        "request_headers": {
            "user-agent": "site-qwality-check/0.1"
        },
        "failure_reason": "Bad status code",
        "status": "failed"
    }
}
```
