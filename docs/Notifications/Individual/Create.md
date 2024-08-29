### Method: POST

> ```
>/notification
>```

### Body

```json
{
    "notification_group_id": "{{notification_group_id}}",
    "type": "email",
    "details": {
        "email_address": "test@siteqwality.com"
    }
}
```

### Response: 201

```json
{
    "data": {
        "id": "4dea9b48-4131-47db-866c-0f450b335c27",
        "account_id": "22b48b6c-b8af-4e4a-90df-5935ad5f4ab3",
        "type": "email",
        "details": {
            "email_address": "test@siteqwality.com"
        },
        "created_at": "2023-10-12T04:27:58.902387Z"
    }
}
```
