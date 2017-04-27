# Intro

## Netlify CEO Matt Biilmann
The netlify platform gets 60M request on `wp-admin` each month.
This shows how much a simple WordPress install is at risk.

### A New Stack
Decoupled Architecture (Web Browser + Microservices + ) 
JavaScript is used as main runtime.

For E-commerce, check out *GoCommerce JS*

For user authentication check out *Stormpath*

#### Best Practices
- Entire project on a CDN
- Everything lives in Git
- Modern build tools
- Automated builds
- Atomic Deploys
- Instant Cache Invalidation


## Preethi Kasireddy: Why Use Static Types In JavaScript?

Two types of types in JavaScript.
- Static
- Dynamic

*Static Example*
```
boolean result = true; OK
boolean result = '123'; Not OK
```

*Dynamic Type*
Type checking happens at runtime.

Tools allowing to use type in JavaScript
#### Flow (Facebook)
Flow is much more like a checker. It cheks the type and then you need to use something like babel.

#### Typescript (Microsoft open source)
Typescript is compiling the file.



