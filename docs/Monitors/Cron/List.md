### Method: GET

> ```
>/cron/jobs
>```

### Response: 200

```json
{
    "data": {
        "cron_jobs": [
            {
                "id": "7297e538-1e8d-4999-9017-e846f53fc997",
                "account_id": "22b48b6c-b8af-4e4a-90df-5935ad5f4ab3",
                "created_at": "2024-08-10T01:21:39.960019Z",
                "current_status": "success",
                "friendly_name": "Cron Job",
                "last_received_at": "2024-08-09T21:21:25.59Z",
                "last_status_change_at": "2024-08-09T21:21:30.081Z",
                "check_interval_seconds": 1,
                "group_notification_ids": [],
                "group_notifications": [],
                "state": "active"
            }
        ]
    }
}
```
