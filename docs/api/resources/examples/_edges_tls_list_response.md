<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-09-17T10:12:09Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_32p3x6pyEmpAiz4MoZYj6AYrD1f",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_32p3x6pyEmpAiz4MoZYj6AYrD1f"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_32p3vgCWSnEg6gErcXy24zENi8t",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_32p3vgCWSnEg6gErcXy24zENi8t"
        },
        "enabled": true
      },
      "created_at": "2025-09-17T10:11:58Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_32p3vjS9Ptrj9oxJTMPc0Zt15hG",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_32p3vjS9Ptrj9oxJTMPc0Zt15hG"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
