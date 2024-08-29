Creates a new HTTP monitor.

### Method: POST

> ```
>/http/job
> ```

### Body

```json
{
  "friendly_name": "Test Job",
  "method": "GET",
  "uri": "https://mock.codes/200",
  "timeout_ms": 15000,
  "run_interval_seconds": 600,
  "group_notification_ids": [],
  "monitor_tls": false,
  "monitor_dns": false
}
```

### Response: 201

```json
{
  "data": {
    "id": "6807232b-8267-4120-abdd-e13fdefc7830",
    "account_id": "22b48b6c-b8af-4e4a-90df-5935ad5f4ab3",
    "state": "active",
    "current_status": "success",
    "friendly_name": "Test Job",
    "follow_redirects": true,
    "method": "GET",
    "keyword_search": null,
    "timeout_ms": 15000,
    "uri": "https://mock.codes/200",
    "success_http_codes": [],
    "failure_http_codes": [],
    "last_run_at": null,
    "last_status_change_at": null,
    "run_interval_seconds": 600,
    "group_notifications": [],
    "tls_job_id": null,
    "monitor_tls": false,
    "dns_job_id": null,
    "monitor_dns": false,
    "created_at": "2024-04-23T00:13:25.717517Z"
  }
}
```
