# List Of Microsoft Graph Api Endpoints

List of all Microsoft Graph API endpoints currently available (that I could reverse engineer) in json format and markdown tables.  

Questions? Please contact me on Github or @ [https://baswijdenes.com/contact](https://baswijdenes.com/contact)  

---

## Table of Contents

- [Endpoints Per Segment](#endpoints-per-segment)
- [ListOfMicrosoftGraphApiEndpoints.json](#listofmicrosoftgraphapiendpointsjson)
- [Object Structure](#object-structure)

---

### Endpoints Per Segment

The EndpointsPerSegment directory contains a list of all the root segments of the Microsoft Graph API. 

Each segment contains a list of all the endpoints that are available for that segment.  

---

### ListOfMicrosoftGraphApiEndpoints.json

The ListOfMicrosoftGraphApiEndpoints.json file contains a list of all the endpoints that are available in the Microsoft Graph API.  

The file is too big to be readable in Github.  

---

### Object Structure

The object structure of the endpoints is as follows:

```json
[
   {
    "Endpoint": "deviceManagement/virtualEndpoint/bulkActions",
    "v1.0": false,
    "V1.0-Url": null,
    "v1.0-Methods": null,
    "v1.0-docs": [
      "https://learn.microsoft.com/graph/api/virtualendpoint-list-auditevents?view=graph-rest-1.0",
      null
    ],
    "beta": true,
    "Beta-Url": "https://graph.microsoft.com/beta/deviceManagement/virtualEndpoint/bulkActions",
    "Beta-Methods": [
      "Get",
      "Post"
    ],
    "Beta-Docs": [
      "https://learn.microsoft.com/graph/api/virtualendpoint-list-bulkactions?view=graph-rest-beta",
      "https://learn.microsoft.com/graph/api/virtualendpoint-post-bulkactions?view=graph-rest-beta"
    ],
    "Path": [
      "deviceManagement",
      "virtualEndpoint",
      "bulkActions"
    ],
    "Root": "deviceManagement",
    "Children": 2,
    "Segment": "bulkActions"
  },
  {
    "Endpoint": "deviceManagement/virtualEndpoint/bulkActions/{cloudPcBulkAction-id}",
    "v1.0": false,
    "V1.0-Url": null,
    "v1.0-Methods": null,
    "v1.0-docs": [
      "https://learn.microsoft.com/graph/api/virtualendpoint-list-auditevents?view=graph-rest-1.0",
      null
    ],
    "beta": true,
    "Beta-Url": "https://graph.microsoft.com/beta/deviceManagement/virtualEndpoint/bulkActions/{cloudPcBulkAction-id}",
    "Beta-Methods": [
      "Get",
      "Patch",
      "Delete"
    ],
    "Beta-Docs": [
      "https://learn.microsoft.com/graph/api/cloudpcbulkaction-get?view=graph-rest-beta",
      null,
      null
    ],
    "Path": [
      "deviceManagement",
      "virtualEndpoint",
      "bulkActions",
      "{cloudPcBulkAction-id}"
    ],
    "Root": "deviceManagement",
    "Children": 0,
    "Segment": "{cloudPcBulkAction-id}"
  }
]
```

The example shows 2 objects in the json.  

Properties:

- **Endpoint**: This is the path as string value exluding the host ('https://graph.microsoft.com') and reference to the version (beta or v1.0).
- **v1.0**: Boolean value indicating if the endpoint is available in v1.0.
- **V1.0-Url**: The full url to the endpoint in v1.0.
- **v1.0-Methods**: An array of strings containing the available methods for the endpoint in v1.0.
- **v1.0-docs**: The documentation url provided by Microsoft for v1.0 methods (can be emtpy when Microsoft does not provide one).
- **beta**: Boolean value indicating if the endpoint is available in beta.
- **Beta-Url**: The full url to the endpoint in beta.
- **Beta-Methods**: An array of strings containing the available methods for the endpoint in beta.
- **beta-docs**: The documentation url provided by Microsoft for beta methods (can be emtpy when Microsoft does not provide one).
- **Path**: An array of strings containing the path to the endpoint. The first item is the root segment, the last item is the endpoint.
- **Root**: The root segment of the endpoint.
- **Children**: The number of child endpoints for the endpoint.
- **Segment**: The segment of the endpoint.
