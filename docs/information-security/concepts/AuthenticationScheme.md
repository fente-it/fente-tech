# Authentication in HTTP

[IETF community]() has published a specification outlining authentication in HTTP: [Hypertext Transfer Protocol (HTTP/1.1): Authentication](https://datatracker.ietf.org/doc/html/rfc7235). When working with authentication, it is crucial to understand the concept of challenge-response authentication schemes.

```
HTTP provides a general framework for access control and authentication, via an extensible set of challenge-response   authentication schemes
        
        - reference [HTTP: Authentication](https://datatracker.ietf.org/doc/html/rfc7235).
```

## Challenge-response authentication scheme
 An authentication scheme can  be used by a server to challenge a client request and by a client to provide authentication information see [Introduction section](https://datatracker.ietf.org/doc/html/rfc7235#section-1) and [Authorization](https://datatracker.ietf.org/doc/html/rfc7235#section-4.2). The authentication scheme defines how the credentials are encoded. 
 
 HTTP Headers and response status codes are used in the challenge-response between server and client to provide authentication information.  

List of provided authentication schemes can be found here [Authentication scheme registry](https://www.iana.org/assignments/http-authschemes/http-authschemes.xhtml)

## References

- [Mozilla](https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/Authentication)
- [IETF Authentication](https://datatracker.ietf.org/doc/html/rfc7235)