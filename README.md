<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:1E3A8A,100:2563EB&height=220&section=header&text=Sijan%20Maharjan&fontSize=52&fontColor=FFFFFF&fontAlignY=38&desc=Full-Stack%20Web%20Developer%20%7C%20Backend%20%26%20API%20Development&descAlignY=58&descSize=18" />

<br>

<a href="https://github.com/sijan2060">
<img src="https://img.shields.io/github/followers/sijan2060?label=Followers&style=for-the-badge&logo=github">
</a>
<a href="https://github.com/sijan2060?tab=repositories">
<img src="https://img.shields.io/github/stars/sijan2060?label=Stars&style=for-the-badge&logo=github">
</a>
<a href="https://www.linkedin.com/in/sijan-maharjan-4a3408282/">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
</a>

<br><br>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=22&pause=900&color=58A6FF&center=true&vCenter=true&width=750&lines=Full-Stack+Web+Development;Backend+%26+REST+API+Development;React+%7C+Node.js+%7C+TypeScript;Authentication+%7C+Databases+%7C+Architecture;Building+Pasalmandu+%F0%9F%9B%92;Always+Learning+%F0%9F%9A%80" />

</div>

---

## 🖥️ `$ whoami`

```text
Name        : Sijan Maharjan
Location    : Kathmandu, Nepal 🇳🇵
Role        : Full-Stack Web Developer
Focus       : Backend • APIs • Databases • System Architecture
Building    : Pasalmandu 🛒
Learning    : TypeScript • Advanced React • Backend Architecture
```

> I enjoy turning ideas into working software and understanding what happens behind the interface, from the React component all the way to the database.

---

# 🧠 Engineering Focus

<table>
<tr>
<td width="50%">

### 🎨 Frontend Engineering

* React
* Vite
* TypeScript
* Tailwind CSS
* React Query
* Axios
* Responsive UI
* Role-based routing

</td>

<td width="50%">

### ⚙️ Backend Engineering

* Node.js
* Express.js
* REST APIs
* JWT Authentication
* Authorization
* API architecture
* Error handling
* Database integration

</td>
</tr>

<tr>
<td>

### 🗄️ Data

* MongoDB
* Microsoft SQL Server
* Mongoose
* Database design
* CRUD operations
* Data relationships

</td>

<td>

### 🚀 Application Architecture

* Feature-based architecture
* Multi-role applications
* API integration
* Authentication flows
* Server-state management
* Real-time application concepts

</td>
</tr>
</table>

---

# 🧰 Technology Matrix

### Frontend

<p>
<img src="https://skillicons.dev/icons?i=html,css,js,ts,react,vite,tailwind" />
</p>

### Backend

<p>
<img src="https://skillicons.dev/icons?i=nodejs,express" />
</p>

### Databases

<p>
<img src="https://skillicons.dev/icons?i=mongodb" />
<img src="https://img.shields.io/badge/Microsoft_SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
</p>

### Tools

<p>
<img src="https://skillicons.dev/icons?i=git,github,vscode,figma" />
</p>

---

# 🏗️ Current Project

<div align="center">

## 🛒 PASALMANDU

### AI-Powered Hyperlocal Grocery Delivery Platform for Nepal 🇳🇵

</div>

```text
                         PASALMANDU
                              │
              ┌───────────────┼───────────────┐
              │               │               │
          CUSTOMER         VENDOR           RIDER
              │               │               │
              └───────────────┼───────────────┘
                              │
                           ADMIN
                              │
                              ▼
                       REST API / Backend
                              │
                 ┌────────────┴────────────┐
                 │                         │
            Authentication              Database
                 │                         │
                JWT              MongoDB / SQL Server
                 │
                 ▼
          Real-Time Services
                 │
                 ▼
        Live Order / Rider Tracking
```

### Core Features

| Module           | Features                                  |
| ---------------- | ----------------------------------------- |
| 👤 Customer      | Products • Cart • Checkout • Orders       |
| 🏪 Vendor        | Products • Inventory • Orders • Dashboard |
| 🛵 Rider         | Delivery • Order Status • Live Location   |
| 🛡️ Admin        | Users • Vendors • Riders • Orders         |
| 🔐 Security      | JWT • Role-Based Authorization            |
| 🌐 Localization  | English 🇬🇧 • Nepali 🇳🇵                |
| 📍 Maps          | Leaflet • Rider Tracking                  |
| ⚡ State          | React Query • Optimistic Updates          |
| 🔌 Communication | REST APIs • Real-Time Updates             |

---

# 🔌 API Architecture

One of my current learning focuses is understanding the complete request lifecycle.

```text
┌─────────────────┐
│   React Client  │
└────────┬────────┘
         │
         │ HTTP Request
         ▼
┌─────────────────┐
│  Axios Service  │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│   Express API   │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│ Middleware/Auth │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│ Business Logic  │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│    Database     │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│ JSON Response   │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│    React UI     │
└─────────────────┘
```

---

# 🔐 Authentication Flow

```text
Register
   │
   ▼
Create User
   │
   ▼
Hash Password
   │
   ▼
Store User
   │
   ▼
Login
   │
   ▼
Verify Credentials
   │
   ▼
Generate JWT
   │
   ▼
Store Token
   │
   ▼
Protected API Request
   │
   ▼
Verify JWT
   │
   ▼
Authorize User Role
```

---

# 📂 Architecture Philosophy

For larger applications, I focus on keeping features separated and maintainable.

```text
src/
│
├── app/
│   ├── router/
│   ├── providers/
│   └── layouts/
│
├── features/
│   ├── auth/
│   ├── products/
│   ├── cart/
│   ├── orders/
│   ├── payments/
│   └── maps/
│
├── components/
├── services/
├── hooks/
├── utils/
└── assets/
```

The goal is simple:

**Organize by feature → isolate responsibilities → make the application easier to scale.**

---

# 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=sijan2060&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&include_all_commits=true" height="180"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sijan2060&layout=compact&theme=tokyonight&hide_border=true" height="180"/>

</div>

<br>

<div align="center">

<img src="https://streak-stats.demolab.com?user=sijan2060&theme=tokyonight&hide_border=true" />

</div>

---

# 🚀 Featured Project

<div align="center">

<a href="https://github.com/sijan2060/first-api">

<img src="https://github-readme-stats.vercel.app/api/pin/?username=sijan2060&repo=first-api&theme=tokyonight&hide_border=true" />

</a>

</div>

### `first-api`

A backend learning project focused on building a REST API with:

```text
Node.js
Express.js
MongoDB
Mongoose
JWT Authentication
Protected Routes
User Registration
User Login
```

---

# 📈 Development Roadmap

```text
HTML / CSS
    │
    ▼
JavaScript
    │
    ▼
React
    │
    ▼
TypeScript
    │
    ▼
REST APIs
    │
    ▼
Authentication
    │
    ▼
Databases
    │
    ▼
Full-Stack Applications
    │
    ▼
System Architecture
    │
    ▼
Cloud & Deployment
    │
    ▼
Scalable Software
```

### Current Focus

`████████████████████░░` **Full-Stack Development**

`██████████████████░░░░` **Backend & APIs**

`███████████████░░░░░░░` **Database Architecture**

`████████████░░░░░░░░░░` **Cloud & Deployment**

---

# 🌱 Learning Philosophy

<div align="center">

### **Don't just use the technology. Understand how it works.**

<br>

`Build` → `Break` → `Debug` → `Understand` → `Improve`

</div>

---

# 📫 Connect

<div align="center">

<a href="https://www.linkedin.com/in/sijan-maharjan-4a3408282/">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<a href="https://x.com/sm44X">
<img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" />
</a>

<a href="https://www.instagram.com/fdr.season/">
<img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
</a>

</div>

<br>

<div align="center">

<img src="https://komarev.com/ghpvc/?username=sijan2060&style=for-the-badge&color=2563EB&label=PROFILE+VIEWS" />

<br><br>

### ⚡ Build. Learn. Debug. Repeat.

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563EB,50:1E3A8A,100:0F172A&height=120&section=footer" />
