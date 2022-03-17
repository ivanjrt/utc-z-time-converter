# utc-z-time-converter
``` Javascript
$timestamp = '2022-03-17T13:40:40.692Z'
$datetime  = ([DateTime]$timestamp).ToUniversalTime()
[TimeZoneInfo]::ConvertTimeBySystemTimeZoneId($datetime, 'Central Standard Time')
```
