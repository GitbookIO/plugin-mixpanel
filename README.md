Mixpanel tracking for GitBook
==============

This is a default GitBook plugin, You can disable it using:

```
{
    plugins: ["-mixpanel"]
}
```


Or you can set your own mixpanel token using the plugins configuration in book.json:

```
{
    plugins: ["mixpanel"],
    pluginsConfig: {
        "mixpanel": {
            "token": "my mixpanel token"
        }
    }
}
```

