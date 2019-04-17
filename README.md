# Pageable

This is a RAML fragment for API collection endpoints which are paginated.

This includes both the `limit` and `offset` query parameters, and a `Link` header.

The Link header is as follows:

```json
{
  "next": "https://mycompany.com/resource?offset=75&limit=25",
  "previous": "https://mycompany.com/resource?offset=25&limit=25",
  "first": "https://mycompany.com/resource?offset=0&limit=25"
}
```
