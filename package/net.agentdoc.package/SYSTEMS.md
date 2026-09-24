# The systems this agent needs

Named by what the work needs rather than by product. The access level
is the most this work needs; a deployment that grants more is granting
more than the job requires.

| System | Kind | Access | What the access is for |
|---|---|---|---|
| apify-token | service | read | It is an API key used to authenticate with Apify for fetching LinkedIn post and comment data; credential `apify-token`, spends per calls, the caller's material is sent to it |
| publora-api-key | service | read | It is an API key used to authenticate with Publora for publishing or scheduling posts and comments directly to LinkedIn; credential `publora-api-key`, the caller's material is sent to it |

Whoever deploys this agent binds these systems to their own,
and places any named credential. Nothing here names a product.
