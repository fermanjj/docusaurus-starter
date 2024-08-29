List HTTP monitor performance

### Method: GET

> ```
>/http/job/{{job_id}}/performance?time_frame=day
>```

### Query Params

| Param      | value |
|------------|-------|
| time_frame | day   |
| threshold  | 1000  |

### Response: 200

```json
{
    "data": [
        {
            "time_period": "2024-04-21T00:30:00Z",
            "avg_response_time_ms": 702.65,
            "success_rate": 100
        },
        {
            "time_period": "2024-04-21T01:00:00Z",
            "avg_response_time_ms": 605.33,
            "success_rate": 100
        },
        ...
    ]
}
```
