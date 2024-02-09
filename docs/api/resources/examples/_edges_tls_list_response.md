<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-02-09T19:21:12Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2c8wNQC8OuTe5rld2LTzJ8j1P8Z",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2c8wNQC8OuTe5rld2LTzJ8j1P8Z"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2c8wLpgsfJ4IFfN04vGf3Gng78c",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2c8wLpgsfJ4IFfN04vGf3Gng78c"
				},
				"enabled": true
			},
			"created_at": "2024-02-09T19:21:00Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2c8wLs4DMaMDARwEwkWk0ad7zCk",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2c8wLs4DMaMDARwEwkWk0ad7zCk"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
