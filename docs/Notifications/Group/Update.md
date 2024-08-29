### Method: PUT

> ```
>/notification_group/{{notification_group_id}}
>```

### Body

```json
{
    "friendly_name": "TESTING",
    "delay_send_after_minutes": 10,
    "resend_every_minutes": 10
}
```

### Response: 200

```json
{
    "data": {
        "id": "554cc143-a055-4983-a764-6cd851fad902",
        "account_id": "22b48b6c-b8af-4e4a-90df-5935ad5f4ab3",
        "friendly_name": "TESTING",
        "delay_send_after_minutes": 10,
        "resend_every_minutes": 10,
        "created_at": "2023-10-12T05:07:47.176142Z"
    }
}
```

### Response: 400

```json
{
    "message": "friendly_name cannot be empty"
}
```

### Response: 404

```json
{
    "message": "Not Found"
}
```
