List HTTP monitors

### Method: GET

> ```
>/http/jobs?limit=10&offset=0&status=success&state=active&text=test
>```

### Query Params

| Param  | value   |
|--------|---------|
| limit  | 10      |
| offset | 0       |
| status | success |
| state  | active  |
| text   | test    |

### Response: 200

```json
{
    "data": {
        "totals": {
            "sites_total": 12,
            "sites_online": 7,
            "sites_down": 2,
            "sites_paused": 3
        },
        "jobs": [
            {
                "id": "e14f475d-ecf9-4ace-8218-bc889fb1a1e0",
                "account_id": "22b48b6c-b8af-4e4a-90df-5935ad5f4ab3",
                "state": "active",
                "current_status": "success",
                "friendly_name": "Test 2",
                "follow_redirects": true,
                "method": "GET",
                "keyword_search": null,
                "timeout_ms": 15000,
                "uri": "https://mock.codes/200",
                "success_http_codes": [],
                "failure_http_codes": [],
                "last_run_at": "2024-03-28T01:55:15.105425Z",
                "last_status_change_at": "2023-11-29T22:50:51.872681Z",
                "run_interval_seconds": 60,
                "group_notifications": null,
                "tls_job_id": null,
                "dns_expires_at": null,
                "created_at": "2023-09-16T15:22:18.189072Z"
            }
        ]
    }
}
```
