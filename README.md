# RESTful APIs

## Notes from "Effective Design of RESTful APIs"
- Three approaches to adding an API
    - Bolt-On Strategy
    - Greenfield Strategy
    - Facade Strategy
    
- Relationship Types
    - Independent
    - Dependent
    - Associative
    
- HTTP Response Codes
    - 1xx : Informational
    - 2xx : Success
        - 200 : okay
        - 201 : Created
        - 202 : Accepted
        - 204 : No content
    - 3xx : Redirect
        - 301 : Moved Permanently
        - 302 : Moved Temporarily
    - 4xx : Client Error
        - 400 : Bad Request
        - 401 : Authentication is required
        - 403 : Forbidden
        - 404 : Not Found
    - 5xx : Server Error

- HTTP Response Header Content Types (Content-Type)
    - application/json;charset=utf-8
    - text/html; charset=iso-8859-1
    - text/plain; charset=utf-8

- REST APIs The six constraints
    - Client - Server
    - Stateless
    - Cacheable
    - Layered System
    - Code on Demand (optional)
    - Uniform Interface
        - Identification of Resources
        - Manipulation of Resources through these Representations
        - Self-descriptive Messages
        - Hypermedia as the engine of application state (HATEOAS)

- Books
    - www.amundsen.com
    - https://groups.google.com/forum/#!forum/api-craft
    - RESTful Web APIs by O'Reilly
    - A Practical Approach to API Design
    - www.theapidesignbook.com
    - http://www.restfest.org/
    