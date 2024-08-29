# Monitor

A monitor can be broken down into two types, an **HTTP Monitor** and a **Cron Monitor**.

## HTTP Monitor

An HTTP monitor is a monitor that makes an HTTP request to a specified URL at a specified interval. The monitor will
check the response status code and response time of the request and alert you if the response status code is not `200`
or the response time exceeds a specified threshold.

## Cron Monitor

A cron monitor is a monitor that provides a URL for your server cron jobs to ping at a specified interval. The monitor
will look for a missing ping and alert you if the ping is not received within the specified interval.

This is sometimes referred to as a _"heartbeat"_ or _"dead man's switch"_ monitor.
