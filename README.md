

**Important:** Remember about Meteor settings file. The contents should look like:

```javascript
{
    "public": {
        "hostName": "localhost:3000 (or your-host-name.com in the prod)",
        "maxClientApps": 3,
        "maxChatHistoryInDays": 3,
        "ga": {
            "account": "UA-********-*" (your google analitics code - optional)
        }
    },
    "private": {
        "mainAppEmail": "your-email-address@gmail.com",
        "mailGun": "smtp://{Default SMTP Login}:{Default Password}@{SMTP Hostname}:587",
        "google": {
            "clientId": "{your google API client id here}",
            "secret": "{your google API secret key here}"
        },
        "facebook": {
            "appId": "{your facebook API app id here}",
            "secret": "{your facebook API secret key here}"
        }
    }
}
```
