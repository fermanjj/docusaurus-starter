Fetches the most recent job results for a single HTTP monitor by its ID.

### Method: GET

> ```
>}/http/job/{{job_id}}/events
>```

### Query Params

| Param  | value |
|--------|-------|
| limit  | 100   |
| offset | 1     |

### Response: 200

```json
{
    "data": [
        {
            "id": "4468f56e-1b94-4e03-8b01-b64255fc43c6",
            "account_id": "6df6b992-429f-40b5-b5f6-36268cea0613",
            "http_job_id": "22fbfe0f-23c1-41d1-aedd-cb1a9ad7c262",
            "created_at": "2023-09-18T00:12:00.15135Z",
            "status": "failed",
            "started_at": "2023-09-18T00:12:00.15135Z",
            "started_by_http_job_result_id": "57a7b91a-ec77-4085-8fad-aaf8d41de47c",
            "ended_at": "2023-09-18T00:37:00.227611Z",
            "ended_by_http_job_result_id": "93e34b9f-ac59-47cf-92e7-9310f13e4dc5",
            "failure_reason": null,
            "response_http_code": null
        }
    ]
}
```

### Response: 200

```json
{
    "data": []
}
```
