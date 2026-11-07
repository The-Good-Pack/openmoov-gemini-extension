# OpenMoov for Gemini CLI

Search UK homes for sale and to rent, book viewings, request valuations, and get sold prices, stamp duty,
conveyancing quotes and local estate agents from [OpenMoov](https://openmoov.co.uk), right inside Gemini CLI.
No account or API key needed.

## Install

```bash
gemini extensions install https://github.com/The-Good-Pack/openmoov-gemini-extension
```

Then try:

- "Find 3-bed homes for sale in Folkestone under £400k"
- "What have houses sold for in CT19 5QW?"
- "How much stamp duty would a first-time buyer pay on £350,000?"

## What it connects to

One remote MCP server, `https://mcp.openmoov.co.uk/` (Streamable HTTP, no authentication). The full tool list and
docs: <https://openmoov.co.uk/developers/mcp>.

Bookings and valuation requests create real enquiries handled by real estate agents. Anything that takes a payment
finishes on openmoov.co.uk.

- Privacy: <https://openmoov.co.uk/privacy-policy>
- Terms: <https://openmoov.co.uk/terms>
- Support: <https://openmoov.co.uk/contact>

© Openmoov Ltd
