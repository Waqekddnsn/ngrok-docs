<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2024-02-09T19:21:06Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2c8wMgHtcZEoxpgkrOEUDahlAIA",
					"uri": "https://api.ngrok.com/event_destinations/ed_2c8wMgHtcZEoxpgkrOEUDahlAIA"
				}
			],
			"id": "esb_2c8wMfx0dViSY0nP17quF8n5FX0",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2c8wMfx0dViSY0nP17quF8n5FX0/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2c8wMfx0dViSY0nP17quF8n5FX0"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```
