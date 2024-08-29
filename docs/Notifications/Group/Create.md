### Method: POST

> ```
>/notification_group
>```

### Body

```json
{
    "friendly_name": "TEST",
    "delay_send_after_minutes": 10,
    "resend_every_minutes": 10
}
```

### Response: 201

```json
{
    "data": {
        "id": "6e0ff939-3437-4f85-b7dc-103ff0f71bb4",
        "account_id": "22b48b6c-b8af-4e4a-90df-5935ad5f4ab3",
        "friendly_name": "TEST",
        "delay_send_after_minutes": 10,
        "resend_every_minutes": 10,
        "created_at": "2023-10-12T04:27:08.179768Z"
    }
}
```
