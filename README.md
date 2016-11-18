#Inquiry: Node & Express

## Goals of Inquiry

### What is Node and what is the difference between Node and JS?

JS is a language. Node is NOT a language, it's just a JS engine. Node is another way to execute code on your computer - as previously said, simply a JS engine bundled wth some libraries. It also includes a package management system, NPM.

The distinction between Node and the JS interpreter in Google is mainly the libraries. In the browser, the end goal is to modify the webpage while Node.js is to run general code that does anything from running a web server to manipulating files.

### How can we use Node to use an HTTP server and client?

See [Node.js docs on HTTP]
(https://nodejs.org/api/http.html), and `my_web_server.js`.

### What is npm?

npm stands for Node Package Manager, and is a way to download modules available on the internet to solve typical problems faced by developers, or provide tools. Node.js applications often use many "modules", called "dependencies" in this context.

If you have a lot of dependencies, it is not practical to install them one-by-one, so we can make use of a package.json.

A [package.json](https://docs.npmjs.com/files/package.json) is like the Gemfile of your Node application. Example of contents of package.json:

```javascript
{
  "name" : "MyStaticServer",
  "version" : "0.0.1",
  "dependencies" : {
    "express" : "3.3.x"
  }
}
```

To install all the dependencies at once, you run `$ npm install` (analogous to `bundle install`).

### What is Express? How do I download it?

Express is a framework for Node that makes creating normal websites simple. See [Express Docs](https://expressjs.com/en/3x/api.html).

More on Express, and routing in Express: [here](https://www.joezimjs.com/javascript/getting-started-with-node-js-and-express-3/)
