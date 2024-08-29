Updates an HTTP monitor.

### Method: PUT

> ```
>/http/job/{{job_id}}
>```

### Body

```json
{
    "friendly_name": "Test Job 2",
    "run_interval_seconds": 300,
    "uri": "https://mock.codes/200",
    "timeout_ms": 1000,
    "monitor_tls": true,
    "monitor_dns": false
}
```

### Response: 200

```json
{
    "data": {
        "id": "6807232b-8267-4120-abdd-e13fdefc7830",
        "account_id": "22b48b6c-b8af-4e4a-90df-5935ad5f4ab3",
        "state": "active",
        "current_status": "success",
        "friendly_name": "Test Job 2",
        "follow_redirects": true,
        "method": "GET",
        "keyword_search": null,
        "timeout_ms": 1000,
        "uri": "https://mock.codes/200",
        "success_http_codes": [],
        "failure_http_codes": [],
        "last_run_at": null,
        "last_status_change_at": null,
        "run_interval_seconds": 300,
        "group_notifications": [],
        "tls_job_id": "2ceeff49-edc8-4202-a788-9ff9676318d2",
        "monitor_tls": true,
        "dns_job_id": null,
        "monitor_dns": false,
        "created_at": "2024-04-23T00:13:25.717517Z"
    }
}
```

### Response: 404

```json
{
    "message": "Not Found"
}
```
