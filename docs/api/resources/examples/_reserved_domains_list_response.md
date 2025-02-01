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
					"started_at": "2025-02-01T10:08:24Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.2v4t5yrjwjnqudtsp.local-ngrok-cname.com",
			"created_at": "2025-02-01T10:08:24Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2sR3LYeL2QH6IskTABrTZuKe631",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2sR3LYeL2QH6IskTABrTZuKe631"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2sR3Lb8HfVBQAHNWgnOkiEWq9LN",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2sR3Lb8HfVBQAHNWgnOkiEWq9LN"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.2v4t5yrjwjnqudtsp.local-ngrok-cname.com",
			"created_at": "2025-02-01T10:08:24Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2sR3LcVtlWSLj31pZZ5Tp5VNjQL",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2sR3LcVtlWSLj31pZZ5Tp5VNjQL"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
