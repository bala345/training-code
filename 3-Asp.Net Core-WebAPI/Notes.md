## Security
### CORS
- Cross Origin Requests
- Mordern browsers only allow same origin requests for security purpose
- Same Origin 
    - http://www.abc.com/index.html
    - http://www.abc.com/aboutus.html
- Different Origins
  - https://www.abc.net
  - https://www.abc.com
  - tcp://abc.com
  - http:www.abc.com
  - https://www.abc.com:8085

#### Enable CORS
- There are three ways to enable CORS:
1. In middleware using a named policy or default policy.
2. Using endpoint routing.
3. With the [EnableCors] attribute.


### Authentication using JWT
- Authentication: user's identity is recognized
- Authorization: user is granted with access rights
- JWT: JSON Web Tokens
  - JWT has 2 parts separated by .
  - header.payload.signature
