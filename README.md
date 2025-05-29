# firecrawl-mcp
A simple API for extracting content from webpages.
# Firecrawl MCP

🧠 **Firecrawl MCP** is a free and fast REST API that extracts meaningful content from any public webpage.

> Built for developers, open to everyone. No login required.

---

## 🚀 API Endpoint

**POST** `https://firecrawl-mcp-lk7q.onrender.com/extract`

### Headers
```http
Content-Type: application/json
x-api-key: firecrawl-mcp
```

### Body
```json
{
  "url": "https://en.wikipedia.org/wiki/OpenAI"
}
```

### Response
```json
{
  "title": "OpenAI - Wikipedia",
  "content": "OpenAI is an AI research lab...",
  "images": ["https://upload.wikimedia.org/openai-logo.png"],
  "published_at": "2025-05-29T12:00:00Z"
}
```

---

## 🧪 Example Usage (Curl)
```bash
curl -X POST https://firecrawl-mcp-lk7q.onrender.com/extract \
  -H "Content-Type: application/json" \
  -H "x-api-key: firecrawl-mcp" \
  -d '{
    "url": "https://en.wikipedia.org/wiki/OpenAI"
  }'
```

---

## 🔑 Public API Keys

- `firecrawl-mcp`
- `testkey-001`
- `firecrawl-trial-access`

You can also [request your own key](https://firecrawl-mcp-lk7q.onrender.com/request-key) to monitor usage or create integrations.

---

## 📊 Stats

See usage: [https://firecrawl-mcp-lk7q.onrender.com/stats](https://firecrawl-mcp-lk7q.onrender.com/stats)

---

## 📎 Docs & Website

Documentation and usage examples available at:
[https://firecrawl-mcp-lk7q.onrender.com](https://firecrawl-mcp-lk7q.onrender.com)

---

## 🛠 Built With

- Node.js + Express
- Hosted on Render
- Simple JSON API

---

## ❤️ Contribute

Pull requests and ideas are welcome. Star ⭐️ if you find it useful!

---

## 📩 Contact

Open an issue or visit [request-key](https://firecrawl-mcp-lk7q.onrender.com/request-key) to get in touch.
