<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": {
        "authority": "letsencrypt",
        "private_key_type": "ecdsa"
      },
      "certificate_management_status": {
        "provisioning_job": {
          "error_code": null,
          "msg": "Managed certificate provisioning in progress.",
          "retries_at": null,
          "started_at": "2025-09-17T10:11:42Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.3ixwqsnsbts1j193x.local-ngrok-cname.com",
      "created_at": "2025-09-17T10:11:42Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_32p3tj6Sp59ee8Km2MyAEZmfj7e",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_32p3tj6Sp59ee8Km2MyAEZmfj7e"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_32p3tg3CONvXyo2Yd2XRdupFeNL",
        "uri": "https://api.ngrok.com/tls_certificates/cert_32p3tg3CONvXyo2Yd2XRdupFeNL"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.3ixwqsnsbts1j193x.local-ngrok-cname.com",
      "created_at": "2025-09-17T10:11:42Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_32p3tgiwC1SiLRUIhLhV3EXHfjG",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_32p3tgiwC1SiLRUIhLhV3EXHfjG"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-09-17T10:11:12Z",
      "description": "Your dev domain",
      "domain": "justine-overfraught-donnishly.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_32p3psiqWkebOAhbe0Qb66AtxF5",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_32p3psiqWkebOAhbe0Qb66AtxF5"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
