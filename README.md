# 🔐 Password Protected Secrets Page (Express Middleware)

This project demonstrates how **Express middleware** can be used to protect routes using a password-based authentication system. When the server is run locally, an HTML page is served where users must enter the correct password to access a protected secrets page.

---

## 🚀 Features

- Express.js middleware for password validation  
- Simple HTML form for password input  
- Conditional redirection based on password correctness  
- Secrets page accessible only after successful authentication  
- Tested using **Postman** and browser  
- Lightweight and beginner-friendly project  

---

## 🛠️ Tech Stack

- **Node.js**
- **Express.js**
- **HTML**
- **Middleware**
- **Postman (for API testing)**

---

## 📂 Project Flow

1. User opens the application at  
http://localhost:3000

2. An HTML page is displayed asking for a password.

3. On form submission:
- Middleware checks the entered password.
- If the password is **correct** → user is redirected to the **secrets page**.
- If the password is **incorrect** → user remains on the same page.

4. The secrets page is protected and cannot be accessed directly without passing the middleware check.

---

## ▶️ How to Run the Project

1. Clone the repository  
```bash
git clone <your-repo-url>
Navigate into the project folder

cd project-folder-name


Install dependencies

npm install


Start the server

node index.js


or

nodemon index.js


Open your browser and visit

http://localhost:3000
```
🧪 Testing with Postman

Send a POST request to the password route

Include the password in the request body

Observe middleware behavior for valid and invalid passwords

📚 What I Learned

How middleware works in Express

How data flows through req, res, and next()

Route protection using middleware

Handling redirects in Express

Testing backend logic using Postman

📌 Future Improvements

Password hashing (bcrypt)

Session-based authentication

Environment variables for secrets

Improved UI design

JWT authentication

👨‍💻 Author

Built as a learning project to understand Express middleware, authentication flow, and backend routing.


---

### ✅ Result
- Headings will appear **large & bold**
- Bullet points will be **proper lists**
- Code blocks will be **formatted correctly**
- Emojis will render properly on GitHub

If you want, I can also:
- Customize it with **your name**
- Shorten it for **resume projects**
- Add **screenshots section**
- Make it **more professional / corporate style**
