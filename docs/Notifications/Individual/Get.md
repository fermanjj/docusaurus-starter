### Method: GET

> ```
>/notification/{{notification_id}}
>```

### Response: 200

```json
{
    "data": {
        "id": "93d550c3-de40-4123-9f41-c55da33191ad",
        "account_id": "22b48b6c-b8af-4e4a-90df-5935ad5f4ab3",
        "type": "email",
        "details": {
            "email_address": "test@siteqwality.com"
        },
        "created_at": "2023-10-12T05:08:59.418671Z"
    }
}
```

### Response: 404

```json
{
    "message": "Not Found"
}
```
