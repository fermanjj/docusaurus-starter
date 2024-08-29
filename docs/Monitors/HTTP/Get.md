Fetches a single HTTP monitor by its ID.

### Method: GET

> ```
>/http/job/{{job_id}}
>```

### Response: 200

```json
{
    "data": {
        "id": "d8efea55-2694-4f79-92e4-1a3e3b9607e2",
        "account_id": "22b48b6c-b8af-4e4a-90df-5935ad5f4ab3",
        "state": "active",
        "current_status": "success",
        "friendly_name": "Test Job",
        "follow_redirects": true,
        "method": "GET",
        "keyword_search": null,
        "timeout_ms": 30000,
        "uri": "https://mock.codes/200",
        "success_http_codes": [],
        "failure_http_codes": [],
        "last_run_at": "2024-04-23T00:12:00.149663Z",
        "last_status_change_at": "2024-04-22T19:31:00.163149Z",
        "run_interval_seconds": 60,
        "group_notifications": [],
        "tls_job_id": "3723870f-55cf-438b-bc69-4c90d8f1099b",
        "monitor_tls": true,
        "dns_job_id": "07c0a590-2e47-4e1c-9d8a-eb490b151104",
        "monitor_dns": true,
        "created_at": "2024-04-19T12:33:09.357194Z"
    }
}
```

### Response: 404

```json
{
    "message": "Not Found"
}
```
