# Express Password Check Server

A simple backend project built while learning **Node.js and Express**.  
The server receives a password through a form, checks it on the server, and conditionally returns a protected page.

This project focuses on **backend fundamentals**, not frontend design.

---

## Concepts Practiced

- Node.js server setup  
- Express routing (`GET`, `POST`)  
- HTTP request / response cycle  
- Middleware usage (`body-parser`)  
- Parsing form data with `req.body`  
- Redirecting requests  
- Serving static files  
- Testing endpoints with **Postman**  
- Using **nodemon** during development

---

## How It Works

1. User visits `/`
2. Server sends a form (`index.html`)
3. Form sends a **POST request** to `/check`
4. Server reads the password from `req.body`
5. If correct → sends `secret.html`
6. If incorrect → redirects back to `/`

---

## Run the Project

Install dependencies

```bash
npm install
```

Run the server

```bash
node solution.js
```

(Optional during development)

```bash
nodemon solution.js
```

Open in browser

```
http://localhost:3000
```

---

## Tech Used

- Node.js  
- Express.js  
- body-parser middleware  
- HTTP  
- Postman (API testing)

---

This project was built while learning **backend development with Node.js and Express**.
