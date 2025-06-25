<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-06-25T10:07:05Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2yzmxFgX1soaS7AEePPCqYnmI8B",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2yzmxFgX1soaS7AEePPCqYnmI8B"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2yzmxx0HljyaiZJ0FiofLS19qI6",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-06-25T10:07:05Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2yzmxx0HljyaiZJ0FiofLS19qI6",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-06-25T10:07:03Z",
      "hostport": "ca8fbd44e311.ngrok.paid:443",
      "id": "ep_2yzmxg0rEXs2Kb74Tr3xJHPU53H",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2yzmvD4EAp9g89dIgnq7kAfg5yz",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://ca8fbd44e311.ngrok.paid",
      "tunnel": {
        "id": "tn_2yzmxg0rEXs2Kb74Tr3xJHPU53H",
        "uri": "https://api.ngrok.com/tunnels/tn_2yzmxg0rEXs2Kb74Tr3xJHPU53H"
      },
      "tunnel_session": {
        "id": "ts_2yzmxbvdw5SHBVCQJM2taGqKBCf",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2yzmxbvdw5SHBVCQJM2taGqKBCf"
      },
      "type": "ephemeral",
      "updated_at": "2025-06-25T10:07:03Z",
      "upstream_url": "http://localhost:80",
      "url": "https://ca8fbd44e311.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-06-25T10:07:00Z",
      "domain": {
        "id": "rd_2yzmxFgX1soaS7AEePPCqYnmI8B",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2yzmxFgX1soaS7AEePPCqYnmI8B"
      },
      "edge": {
        "id": "edgtls_2yzmxKtZXQlowkliTiQST3iLusX",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2yzmxKtZXQlowkliTiQST3iLusX"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2yzmxIDjnyIb656vE3FcsJz5Bwr",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-06-25T10:07:00Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
