<!-- Banner / Header -->
<p align="center">
  <img src="https://raw.githubusercontent.com/ideveloper-xd/authsecure-cdn/refs/heads/main/v2/assets/media/logos/logo-1-dark-preview.png" 
       width="220" alt="AuthSecure Logo">
</p>

<h1 align="center">🚀 Welcome to AuthSecure</h1>

<p align="center">
  <strong>Modern • Secure • Developer-Friendly Authentication</strong><br>
  Powering applications, websites, games, tools & more with ease.
</p>

---

## 🌟 About AuthSecure

AuthSecure is a next-generation authentication solution built for developers  
who want **speed**, **security**, and **clean integrations** without complexity.

✔ Easy to implement  
✔ Multi-language Support  
✔ Secure Authentication Flows  
✔ Lightweight & Fast  
✔ Actively Updated  

---

## 🔑 Supported Client SDKs

AuthSecure provides official SDKs for multiple programming languages:

| Language     | Repository |
|--------------|------------|
| **C#**       | [AuthSecure-CSHARP-Example](https://github.com/Authsecure-shop/AuthSecure-CSHARP-Example) |
| **C++**      | [AuthSecure-CPP-Example](https://github.com/Authsecure-shop/AuthSecure-CPP-Example) |
| **Python**   | [AuthSecure-Python-Example](https://github.com/Authsecure-shop/AuthSecure-Python-Example) |
| **Java**     | [AuthSecure-JAVA-Example](https://github.com/Authsecure-shop/AuthSecure-JAVA-Example) |
| **JavaScript** | [AuthSecure-JS-Example](https://github.com/Authsecure-shop/AuthSecure-javascript-Example) |
| **TypeScript** | [AuthSecure-TS-Example](https://github.com/Authsecure-shop/AuthSecure-typescript-Example) |
| **VB.NET**   | [AuthSecure-VB-Example](https://github.com/Authsecure-shop/AuthSecure-VB-Example) |
| **PHP**      | [AuthSecure-PHP-Example](https://github.com/Authsecure-shop/AuthSecure-PHP-Example) |
| **Rust**     | [AuthSecure-Rust-Example](https://github.com/Authsecure-shop/AuthSecure-Rust-Example) |
| **Go**       | [AuthSecure-Go-Example](https://github.com/Authsecure-shop/AuthSecure-Go-Example) |
| **Lua**      | [AuthSecure-Lua-Examples](https://github.com/Authsecure-shop/AuthSecure-Lua-Examples) |
| **Ruby**     | [AuthSecure-Ruby-Example](https://github.com/Authsecure-shop/AuthSecure-Ruby-Example) |
| **Perl**     | [AuthSecure-Perl-Example](https://github.com/Authsecure-shop/AuthSecure-Perl-Example) |

---

## 🌐 Quick Links

<p align="center">
  <a href="https://authsecure.shop/"><b>🌍 Website</b></a> • 
  <a href="https://t.me/authsecureshop"><b>💬 Telegram</b></a> • 
  <a href="https://authsecure.shop/"><b>🎟 Support</b></a> • 
  <a href="https://www.youtube.com/@Authsecure"><b>🎥 YouTube</b></a>
</p>

---

## 📦 Installation (Basic Example – JavaScript)

```js
import AuthSecure from "authsecure";

const auth = new AuthSecure("APP_KEY", "APP_SECRET");

auth.login("username", "password")
  .then(user => console.log("Logged in:", user))
  .catch(err => console.error("Login Failed:", err));
