
# Installation

## Prerequisites

- Python version 3.6


# Quick Start

Here is a quick example:

`GET /your/api/{param}/call`

```python
async def test():
    import python_http_client
    global_headers = {"Authorization": "Basic XXXXXXX"}
    client = Client(host='base_url', request_headers=global_headers)
    response = await client.your.api._(param).call.get()
    print(response.status_code)
    print(response.headers)
    print(response.body)

import asyncio
loop = asyncio.get_event_loop()
loop.run_until_complete(go())
```
