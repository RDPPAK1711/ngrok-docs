<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-02-01T10:08:51Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2sR3P1I6Plzi46p5OL4BVD6or9Z",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2sR3P1I6Plzi46p5OL4BVD6or9Z"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2sR3Nd9pXRBJIQVaYF7kpoA8MPU",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2sR3Nd9pXRBJIQVaYF7kpoA8MPU"
				},
				"enabled": true
			},
			"created_at": "2025-02-01T10:08:40Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2sR3NdNSIFPQw6x0grfVXeDm3kT",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2sR3NdNSIFPQw6x0grfVXeDm3kT"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
