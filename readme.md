# Note

1. Web and Api must be in a separate folder hierarchy.

2. Ensure the website has this in .vscode/settings.json

```
{    
    "liveServer.settings.proxy": {
        "enable": true,
        "baseUri": "/api",
        "proxyUri": "http://127.0.0.1:7071/api"
    }
}
```