# n3fs-discord-welcome

This repo contains the messages posted in the `#welcome` channel of the N3FS Discord. 

These JSON files are meant to be `POST`ed to a Discord webhook. You can do that with CURL like this: 

```
curl -X POST -d @filename.json $WEBHOOK_URL
```

(Of course I'm not including our webhook URL in here)