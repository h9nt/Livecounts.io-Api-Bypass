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
{
  "cache": 1,
  "success": true,
  "method": 1,
  "id": "tiktok",
  "userId": "107955",
  "secUserId": null,
  "verified": false,
  "username": "TikTok",
  "signature": null,
  "avatar": "https://p16-pu-sign-useast8.tiktokcdn-us.com/tos-useast5-avt-0068-tx/7310048624166535211~c5_720x720.jpeg?lk3s=a5d48078&nonce=3371&refresh_token=8a61c005963cab6b132faaacb3ccc130&x-expires=1722128400&x-signature=OXqs9sZ%2FaG6a9Ddsr%2B3L%2BSg0%2Bdc%3D&shp=a5d48078&shcp=81f88b70",
  "stats": {
    "likes": 0,
    "followers": 0,
    "following": 0,
    "videos": 0
  }
}

```

- this header works for some other sites like this (; enjoy!
- Of course, a big thank you goes to livecounts.io for this great site/api service!

# if the owner of this site,  wants a **DCMA TAKEDOWN** request, contact me
