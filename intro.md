# JAMStack conference

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


### Interfaces
is how you declare the structure of types. (Objects)

```
interface LabelledValue {
    label: string;
}

function printLabel(labelledObj: LabelledValue) {
    console.log(labelledObj.label);
}

let myObj = {size: 10, label: "Size 10 Object"};
printLabel(myObj);
```


## Daniel Brain: Cross-Domain Components with React and XComponent, at PayPal

React is awesome but what are the limitations?
In a word: **SHARING**

We can't get data from other domains. Security concerns are huge. How do we do this in the world of React.
### Iframes
Not ideal. You have to pass everything in an URL. Not really flexible. Not responsive.

### Xcomponent
Components but cross domain.
Make iframe more reliable, with error handling, pre rendering auto resizing.
Native binding for React. No event listeners.


## Panel: A Modern Web Landscape
Moderator Jessica Parsons chats with web innovators Wilson Miner, Frances Berriman, and Matt Biilmann about best practices, current trends, and future possiblities in modern web development.


## Erin McKean: You Need An API: Now What?
[LoopBack](http://loopback.io/). A tool for rapidly generating NodeJS REST APIs. Open source maitained by IBM. Free to use and deploy anywhere you can deploy NodeJS.
If you like cool datasets. Checkout Data is plural tiny letter. PLU database

Loopback is on MongoDB
requirements, npm, node and a mongo install.


## Brian Douglas: Frontend for the Serverless stack

API Gateway
Lambda 



