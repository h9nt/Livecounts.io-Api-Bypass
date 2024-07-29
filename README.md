# Livecounts.io-Api-Bypass
> bypass the security for (**tiktok.livecounts.io**) 

- To get access to their api, without pay anything use this header value in a request to the api:

```python
"x-from-mobile: 1"
```
thats all, with this u should get a response from it.

- response without auth:
```json
{
  "success": false,
  "message": "Unathorized. DM @livecountsio on Twitter if you'd like to purchase access to this API."
}
```

response with auth: 
```json


```
