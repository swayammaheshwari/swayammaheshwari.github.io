---
published: true
name: "Get User Data"
title: "Get User Endpoint"
tags: ["user", "api"]
description: "Fetches user data from the API."
type: "endpoint"
---

# Get User

Fetches user data based on their ID.

```bash
curl --location 'https://api.example.com/v1/users/123' \
  --header 'Accept: application/json' \
  --header 'Authorization: Bearer my-secret-token'
```

### Response

Expect a 200 OK.
