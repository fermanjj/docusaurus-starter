Fetch Cron Job monitor

### Method: GET

> ```
>/cron/job/{{cron_job_id}}
>```

### Response: 200

```json
{
    "data": {
        "id": "5f86c090-0da8-4187-9ab9-02317dade0ff",
        "account_id": "22b48b6c-b8af-4e4a-90df-5935ad5f4ab3",
        "created_at": "2024-08-21T02:03:39.590146Z",
        "current_status": "failed",
        "friendly_name": "Cron Job",
        "last_received_at": "2024-08-22T18:11:07.527502Z",
        "last_status_change_at": null,
        "last_checked_at": "2024-08-29T00:15:27.499551Z",
        "check_interval_seconds": 60,
        "group_notification_ids": [
            "288c2927-e13d-48e2-b731-7bb0746c2905"
        ],
        "group_notifications": [
            {
                "id": "288c2927-e13d-48e2-b731-7bb0746c2905",
                "account_id": "22b48b6c-b8af-4e4a-90df-5935ad5f4ab3",
                "friendly_name": "Test",
                "delay_send_after_minutes": 1,
                "resend_every_minutes": 60,
                "created_at": "2024-04-23T00:20:49.806692Z",
                "notifications": [
                    {
                        "id": "aec54828-d71c-469a-b1d1-0239f8567acd",
                        "account_id": "22b48b6c-b8af-4e4a-90df-5935ad5f4ab3",
                        "type": "email",
                        "details": {
                            "email_address": "test@siteqwality.com"
                        },
                        "created_at": "2024-04-23T00:21:07.289012Z"
                    }
                ]
            }
        ],
        "state": "active"
    }
}
```
