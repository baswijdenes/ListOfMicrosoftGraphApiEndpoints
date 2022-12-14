| Endpoint | v1.0 | V1.0-Url | v1.0-Methods | beta | Beta-Url | Beta-Methods | Path | Root | Children | Segment |
| ----------| ----------| ----------| ----------| ----------| ----------| ----------| ----------| ----------| ----------| ----------|
| groupLifecyclePolicies| True| https://graph.microsoft.com/v1.0/groupLifecyclePolicies| Get Post| True| https://graph.microsoft.com/beta/groupLifecyclePolicies| Get Post| groupLifecyclePolicies| groupLifecyclePolicies| 3| groupLifecyclePolicies|
| groupLifecyclePolicies/$count| True| https://graph.microsoft.com/v1.0/groupLifecyclePolicies/$count| Get| True| https://graph.microsoft.com/beta/groupLifecyclePolicies/$count| Get| groupLifecyclePolicies $count| groupLifecyclePolicies| 0| $count|
| groupLifecyclePolicies/{groupLifecyclePolicy-id}| True| https://graph.microsoft.com/v1.0/groupLifecyclePolicies/{groupLifecyclePolicy-id}| Get Patch Delete| True| https://graph.microsoft.com/beta/groupLifecyclePolicies/{groupLifecyclePolicy-id}| Get Patch Delete| groupLifecyclePolicies {groupLifecyclePolicy-id}| groupLifecyclePolicies| 2| {groupLifecyclePolicy-id}|
| groupLifecyclePolicies/{groupLifecyclePolicy-id}/microsoft.graph.addGroup| True| https://graph.microsoft.com/v1.0/groupLifecyclePolicies/{groupLifecyclePolicy-id}/microsoft.graph.addGroup| Post| True| https://graph.microsoft.com/beta/groupLifecyclePolicies/{groupLifecyclePolicy-id}/microsoft.graph.addGroup| Post| groupLifecyclePolicies {groupLifecyclePolicy-id} microsoft.graph.addGroup| groupLifecyclePolicies| 0| microsoft.graph.addGroup|
| groupLifecyclePolicies/{groupLifecyclePolicy-id}/microsoft.graph.removeGroup| True| https://graph.microsoft.com/v1.0/groupLifecyclePolicies/{groupLifecyclePolicy-id}/microsoft.graph.removeGroup| Post| True| https://graph.microsoft.com/beta/groupLifecyclePolicies/{groupLifecyclePolicy-id}/microsoft.graph.removeGroup| Post| groupLifecyclePolicies {groupLifecyclePolicy-id} microsoft.graph.removeGroup| groupLifecyclePolicies| 0| microsoft.graph.removeGroup|
| groupLifecyclePolicies/microsoft.graph.renewGroup| False| | | True| https://graph.microsoft.com/beta/groupLifecyclePolicies/microsoft.graph.renewGroup| Post| groupLifecyclePolicies microsoft.graph.renewGroup| groupLifecyclePolicies| 0| microsoft.graph.renewGroup|