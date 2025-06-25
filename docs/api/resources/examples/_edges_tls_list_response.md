<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-06-25T10:07:10Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2yzmyU3o7f9DhcdgFYg0Nfnyrhh",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2yzmyU3o7f9DhcdgFYg0Nfnyrhh"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2yzmxHcQoi3iwU5gQINJZWkF3AS",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2yzmxHcQoi3iwU5gQINJZWkF3AS"
        },
        "enabled": true
      },
      "created_at": "2025-06-25T10:07:00Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2yzmxKtZXQlowkliTiQST3iLusX",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2yzmxKtZXQlowkliTiQST3iLusX"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
