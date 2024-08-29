Fetches the most recent job results for a single HTTP monitor by its ID.

### Method: GET

> ```
>/http/job/{{job_id}}/recent?limit=100
>```

### Query Params

| Param | value |
|-------|-------|
| limit | 100   |

### Response: 200

```json
{
    "data": [
        {
            "job_result_id": "bb78fc74-cf75-4456-9434-772035eb07d7",
            "http_job_id": "64377a97-b1e6-45bb-96f9-f006be53bdc4",
            "status": "failed",
            "created_at": "2023-11-09T00:58:06.808611Z",
            "response_time_ms": 142
        },
        {
            "job_result_id": "c3daf31d-d55c-4738-8f04-b38c5cc32fae",
            "http_job_id": "64377a97-b1e6-45bb-96f9-f006be53bdc4",
            "status": "failed",
            "created_at": "2023-11-09T00:57:06.806306Z",
            "response_time_ms": 146
        },
        ...
    ]
}
```

### Response: 200

```json
{
    "data": []
}
```
