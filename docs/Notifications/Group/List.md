### Method: GET

> ```
>/notification_group?limit=50&offset=0
>```

### Query Params

| Param  | value |
|--------|-------|
| limit  | 50    |
| offset | 0     |

### Response: 200

```json
{
    "data": [
        {
            "id": "85aeea53-b889-4a49-ac73-8e1e2a2a930d",
            "account_id": "22b48b6c-b8af-4e4a-90df-5935ad5f4ab3",
            "friendly_name": "Mails",
            "delay_send_after_minutes": 26,
            "resend_every_minutes": 40,
            "created_at": "2024-03-16T12:27:47.740622Z",
            "notifications": [
                {
                    "id": "a2b16901-e3a9-4e4c-a4f6-89c84d1d45db",
                    "account_id": "22b48b6c-b8af-4e4a-90df-5935ad5f4ab3",
                    "type": "email",
                    "details": {
                        "email_address": "test@example.com"
                    },
                    "created_at": "2024-03-19T11:09:51.42816Z"
                }
            ],
            "numb_of_sites": 1
        },
        {
            "id": "d7cdc84f-23ae-420e-910e-d9507c5c49a2",
            "account_id": "22b48b6c-b8af-4e4a-90df-5935ad5f4ab3",
            "friendly_name": "Phones",
            "delay_send_after_minutes": 8,
            "resend_every_minutes": 16,
            "created_at": "2024-03-19T00:50:45.852039Z",
            "notifications": [
                {
                    "id": "1a985b81-905b-4763-a2e0-aecdbcf72b27",
                    "account_id": "22b48b6c-b8af-4e4a-90df-5935ad5f4ab3",
                    "type": "sms",
                    "details": {
                        "country_code": 1,
                        "phone_number": "234234234234"
                    },
                    "created_at": "2024-03-19T13:03:02.700691Z"
                },
                {
                    "id": "fab3a8e5-e865-47d7-973c-4f4dcd601fd9",
                    "account_id": "22b48b6c-b8af-4e4a-90df-5935ad5f4ab3",
                    "type": "sms",
                    "details": {
                        "country_code": 2,
                        "phone_number": "1234567890"
                    },
                    "created_at": "2024-03-19T12:51:09.569281Z"
                }
            ],
            "numb_of_sites": 0
        }
    ]
}
```
