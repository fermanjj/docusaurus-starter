Fetch Uptime Percentage

### Method: GET

> ```
>/http/job/{{job_id}}/uptime_percentage?start_date_time=2024-04-25T03:13:09.781Z&end_date_time=2024-04-26T02:13:09.781Z
>```

### Query Params

| Param           | value                    |
|-----------------|--------------------------|
| start_date_time | 2024-04-25T03:13:09.781Z |
| end_date_time   | 2024-04-26T02:13:09.781Z |

### Response: 200

```json
{
    "data": {
        "http_job_id": "22b48b6c-b8af-4e4a-90df-5935ad5f4ab3",
        "incidents": 0,
        "uptime_percentage": 100,
        "start_date": "2024-03-06T03:13:09.781Z",
        "end_date": "2024-04-05T02:13:09.781Z"
    }
}
```
