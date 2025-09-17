<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-17T10:12:03Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_32p3veBWWx8Jul63pHlOH6HEyf7",
        "uri": "https://api.ngrok.com/reserved_domains/rd_32p3veBWWx8Jul63pHlOH6HEyf7"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_32p3wO6RBtzKmvWVSYwfoPfRLz4",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-09-17T10:12:03Z",
      "uri": "https://api.ngrok.com/endpoints/ep_32p3wO6RBtzKmvWVSYwfoPfRLz4",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-17T10:12:01Z",
      "hostport": "c91c05374296.ngrok.paid:443",
      "id": "ep_32p3w6ik9TlqrdUsRysxMdt4Tsk",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_32p3pTn2VRAVhj2pXKYKnjOuxvb",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://c91c05374296.ngrok.paid",
      "tunnel": {
        "id": "tn_32p3w6ik9TlqrdUsRysxMdt4Tsk",
        "uri": "https://api.ngrok.com/tunnels/tn_32p3w6ik9TlqrdUsRysxMdt4Tsk"
      },
      "tunnel_session": {
        "id": "ts_32p3w68CMH2w9FnPpIre22YXBpE",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_32p3w68CMH2w9FnPpIre22YXBpE"
      },
      "type": "ephemeral",
      "updated_at": "2025-09-17T10:12:01Z",
      "upstream_url": "http://localhost:80",
      "url": "https://c91c05374296.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-17T10:11:58Z",
      "domain": {
        "id": "rd_32p3veBWWx8Jul63pHlOH6HEyf7",
        "uri": "https://api.ngrok.com/reserved_domains/rd_32p3veBWWx8Jul63pHlOH6HEyf7"
      },
      "edge": {
        "id": "edgtls_32p3vjS9Ptrj9oxJTMPc0Zt15hG",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_32p3vjS9Ptrj9oxJTMPc0Zt15hG"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_32p3vhmUVXEFby1k4wbQGMlKAxO",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-09-17T10:11:58Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
