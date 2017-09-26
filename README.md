# Pollygot Developers

### Using the API

```bash

# Request a list of posts
https://api.pollygot.com/v1/posts?tenant={TENANT_ID}

# Request a single post
# Note that you still have to pass the Tenant ID (different tenants can have the same slug for their posts)
https://api.pollygot.com/v1/posts/{post-slug}?tenant={TENANT_ID}
```
