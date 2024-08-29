### Method: PUT

> ```
>/notification/{{notification_id}}
>```

### Body

```json
{
    "type": "email",
    "details": {
        "email_address": "test@siteqwality.com"
    }
}
```

### Response: 200

```json
{
    "data": {
        "id": "c915b96b-5f46-4c2c-a7b7-30de02f7655f",
        "account_id": "22b48b6c-b8af-4e4a-90df-5935ad5f4ab3",
        "type": "email",
        "details": {
            "email_address": "test@siteqwality.com"
        },
        "created_at": "2023-10-12T05:13:24.0448Z"
    }
}
```

### Response: 400

```json
{
    "message": "Invalid sms details"
}
```

### Response: 404

```json
{
    "message": "Not Found"
}
```

