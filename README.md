# guillotina_localstorage

Local FS storage support for Guillotina.


## Example

Example config.json entry:

```json
{
    "applications": [
        ...,
        "guillotina_localstorage"
    ]
    "storage": {"upload_folder": "/tmp"}
}
```

This library uses [aiofiles](https://github.com/Tinche/aiofiles)
