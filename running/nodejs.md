# Node.js Topics for MERN Stack

## [1. Node.js Basics](#)
- [What is Node.js and its event-driven architecture](#)
- [Installing Node.js and using Node REPL](#)
- [Global objects (`__dirname`, `__filename`, `process`, `console`)](#)

## [2. Core Modules](#)
- [**File System**: Reading, writing, and manipulating files (`fs`)](#)
- [**Path**: Working with file and directory paths (`path`)](#)
- [**HTTP**: Creating basic HTTP servers and handling requests (`http`)](#)
- [**Events**: EventEmitter and custom events (`events`)](#)
- [**Stream**: Reading and writing streams (`stream`)](#)
- [**OS**: Accessing system information (`os`)](#)

## 3. Package Management with npm
- Installing and managing packages with npm
- Using `package.json` and `package-lock.json`
- Understanding dependencies (`dependencies` vs. `devDependencies`)
- Semantic Versioning and updating packages
- Creating and publishing custom npm packages

## 4. Asynchronous Programming
- Callbacks, Promises, and `async/await`
- Error handling in asynchronous operations
- Using `util.promisify` for callback-based APIs
- Working with the `Promise.all` method

## 5. Working with APIs
- Sending HTTP requests using `http`, `https`, or libraries like `axios` or `node-fetch`
- Parsing and handling JSON data

## 6. Building a Web Server
- Creating a simple HTTP server
- Handling requests and responses
- Serving static files manually or with libraries (e.g., `serve-static`)

## 7. File Handling
- Reading and writing files (`fs.readFile`, `fs.writeFile`)
- Working with file streams for large files
- Handling file uploads (e.g., `multer`)
- File streaming and downloads

## 8. Streams and Buffers
- Understanding streams (`Readable`, `Writable`, `Duplex`, `Transform`)
- Reading and writing large files using streams
- Working with Buffers for binary data

## 13. Security Best Practices
- Preventing common vulnerabilities (e.g., XSS, CSRF, SQL Injection)
- Securing sensitive data using environment variables (`dotenv`)
- Protecting APIs with rate limiting and CORS
- Validating user input to prevent malicious data

## 9. Unit Testing and Debugging
- Writing tests with frameworks like `Mocha`, `Jest`, or `Chai`
- Mocking and stubbing with `Sinon.js`
- Debugging using Node.js debugger or VS Code
- API testing with tools like `Postman` or `Supertest`
- Debugging with built-in Node.js tools or `debug` middleware

## 10. Performance Optimization
- Using clustering to utilize multi-core processors
- Understanding and using the Event Loop effectively
- Optimizing database queries and caching results
- Profiling and monitoring Node.js applications

## [11. API Integration](#)
- [Handling CORS for React-Express communication](#)
- [Proxying requests from React to Node.js in development](#)
