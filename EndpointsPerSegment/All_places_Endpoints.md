| Endpoint | v1.0 | V1.0-Url | v1.0-Methods | beta | Beta-Url | Beta-Methods | Path | Root | Children | Segment |
| ----------| ----------| ----------| ----------| ----------| ----------| ----------| ----------| ----------| ----------| ----------|
| places| True| https://graph.microsoft.com/v1.0/places| Get Post| True| https://graph.microsoft.com/beta/places| Get Post| places| places| 3| places|
| places/$count| True| https://graph.microsoft.com/v1.0/places/$count| Get| True| https://graph.microsoft.com/beta/places/$count| Get| places $count| places| 0| $count|
| places/{place-id}| True| https://graph.microsoft.com/v1.0/places/{place-id}| Get Patch Delete| True| https://graph.microsoft.com/beta/places/{place-id}| Get Patch Delete| places {place-id}| places| 1| {place-id}|
| places/{place-id}/microsoft.graph.room| True| https://graph.microsoft.com/v1.0/places/{place-id}/microsoft.graph.room| Get| True| https://graph.microsoft.com/beta/places/{place-id}/microsoft.graph.room| Get| places {place-id} microsoft.graph.room| places| 0| microsoft.graph.room|
| places/microsoft.graph.room| True| https://graph.microsoft.com/v1.0/places/microsoft.graph.room| Get| True| https://graph.microsoft.com/beta/places/microsoft.graph.room| Get| places microsoft.graph.room| places| 1| microsoft.graph.room|
| places/microsoft.graph.room/$count| True| https://graph.microsoft.com/v1.0/places/microsoft.graph.room/$count| Get| True| https://graph.microsoft.com/beta/places/microsoft.graph.room/$count| Get| places microsoft.graph.room $count| places| 0| $count|
