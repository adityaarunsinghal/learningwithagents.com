# Public workshop access

No login, API key, token or payment is required to read this site's HTML, Markdown or JSON. GET https://learningwithagents.com/api/v1/workshops.json returns the published course information. The API is read-only and does not accept registration or messages.

Check HTTP status and Content-Type before parsing JSON. Unknown paths return a genuine HTML 404. Retry temporary failures only with a small bounded budget and respect Retry-After when supplied. External links may have their own access requirements.

To ask a question, use [Adi's hosted assistant](https://console.ambipath.com/widget/?deploymentId=2a1f524e-434f-4e9a-b275-e608270d07a6) or follow its [public guest HTTP connection instructions](https://adi-singhal.agents.ambipath.com/api/v1/public/agent.md). Assistant conversations are handled by Ambipath, separately from this site's static documents. See the shared [privacy information](https://adityasinghal.com/privacy/#site-assistant).
