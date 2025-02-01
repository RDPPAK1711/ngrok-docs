<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-02-01T10:08:45Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2sR3Ne7DgbEYl3SV3zgM22pUzUJ",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2sR3Ne7DgbEYl3SV3zgM22pUzUJ"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2sR3ODbm4tNlL81OV5dp3aSmYMn",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-02-01T10:08:45Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2sR3ODbm4tNlL81OV5dp3aSmYMn",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-01T10:08:44Z",
			"hostport": "dac364841962.ngrok.paid:443",
			"id": "ep_2sR3O4mffN7DLHk2kxMY7gCJD9i",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2sR3LVgBc54FRGuqaOkVO8JGPeU",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://dac364841962.ngrok.paid",
			"tunnel": {
				"id": "tn_2sR3O4mffN7DLHk2kxMY7gCJD9i",
				"uri": "https://api.ngrok.com/tunnels/tn_2sR3O4mffN7DLHk2kxMY7gCJD9i"
			},
			"tunnel_session": {
				"id": "ts_2sR3O7Ew426C7OGR6nFdA0ax3hw",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2sR3O7Ew426C7OGR6nFdA0ax3hw"
			},
			"type": "ephemeral",
			"updated_at": "2025-02-01T10:08:44Z",
			"upstream_url": "http://localhost:80",
			"url": "https://dac364841962.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-01T10:08:41Z",
			"domain": {
				"id": "rd_2sR3Ne7DgbEYl3SV3zgM22pUzUJ",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2sR3Ne7DgbEYl3SV3zgM22pUzUJ"
			},
			"edge": {
				"id": "edgtls_2sR3NdNSIFPQw6x0grfVXeDm3kT",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2sR3NdNSIFPQw6x0grfVXeDm3kT"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2sR3NYVc0PnnP9dOh5tEdOvJktx",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-02-01T10:08:41Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
