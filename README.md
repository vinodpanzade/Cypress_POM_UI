# 🚀 Cypress Automation Framework | OrangeHRM  
**Real-World UI Automation • Dynamic Data • Zero Hardcoding**

---

## ✨ Why This Project Stands Out

Most automation projects test **static data**.  
This project tests **real application behavior**.

- ✔ No hard-coded users  
- ✔ No flaky row-count assertions  
- ✔ No fake dropdown handling  

**Built with real QA/SDET problems in mind.**

---

## 🧠 What I Automated (In a Smart Way)

### 🔐 Login Validation
- Secure login using Page Object Model  
- Reusable `LoginPage` abstraction  

---

### 👤 User Dropdown Validation
Dynamically validates dropdown options:
- About  
- Support  
- Change Password  
- Logout  

Ensures:
- Correct text  
- Valid `href`  
- HTTP **200 OK** for each link  

**UI + backend link validation combined**

---

### 🧭 Feature Navigation Testing
Automatically verifies navigation and page headers for:
- Admin  
- PIM  
- Leave  
- Time  
- Recruitment  
- Dashboard  
- Directory  
- Claim  
- Buzz  

**Confirms correct page loads, not just clicks.**

---

## 🧩 The Core Innovation (🔥 This Is the Key)

### 📊 Dynamic Table-Driven Testing (No Hardcoding)
- Reads all users dynamically from **Admin → System Users** table  
- Converts each row into a JavaScript object  
- Stores data using Cypress alias: `@usersData`  
- Reuses the same data across multiple test flows  

```js
{
  username,
  userRole,
  employeeName,
  status
}

🧱 Architecture (Clean & Scalable)
cypress/
 ├── Pages/
 │    ├── LoginPage.js
 │    └── AdminPage.js
 ├── e2e/
 │    └── step_definitions/
 ├── fixtures/
 └── support/
✔ Page Object Model

✔ Cucumber BDD

✔ Readable step definitions

✔ Easy to extend

🛠 Tech Stack

🧪 Cypress

🥒 Cucumber (BDD)

🧠 JavaScript

🧩 Page Object Model

🌐 OrangeHRM Demo Application

📸 Visual Proof

Screenshots included to demonstrate:

Login success

Admin filters auto-applied

Dynamic table validation

Cypress tests passing ✅

👨‍💻 Author

Vinod Panzade
QA / Test Engineer | Cypress Automation | SDET Aspirant
