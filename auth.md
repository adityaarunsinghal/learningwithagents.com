# Public workshop access

No login, API key, token or payment is required to read this site's HTML, Markdown or JSON. GET https://learningwithagents.com/api/v1/workshops.json returns the published course information. The API is read-only and does not accept registration or messages.

Check HTTP status and Content-Type before parsing JSON. Unknown paths return a genuine HTML 404. Retry temporary failures only with a small bounded budget and respect Retry-After when supplied. External links may have their own access requirements.
