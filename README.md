# React.js software engineer practical test

In this practical test, we build a simple CRUD application called 🍔 **The Fridge**. We use this application to see what we have in our fridge at a glance and when do they expire.

_Please read the instructions properly before you proceed._

### ⚙️ Tech Stack to be used

- React.js (Latest)
- SASS Stylesheets (scss) / TailwindCSS / CSS
- Axios http client

---

# ⚔️ Objectives

Each objective will be evaluated individually. Please use the given API endpoints below.

### 1️⃣ Objective One

Develop the UI following the given 🎨 [Figma design](https://www.figma.com/file/IPXZBpnc20QUbGcuiv1K9Z/TheFridge-React-Practical-Test?node-id=0%3A1), using react `functional components` and `scss/css stylesheets` for styles. (Please **DO NOT** use any third party component libraries or css libraries. write custom code. You can use TailwindCSS for utility classes)

https://www.figma.com/file/IPXZBpnc20QUbGcuiv1K9Z/TheFridge-React-Practical-Test

### 2️⃣ Objective Two

1. List the items with details as pointed in the Figma design, once data completely fetched from API.
2. Show a pre-loading message/spinner while fetching the List items from API.
3. Show Total items count by counting the list items.
4. Show `Expiring soon` label if _Expiry date_ is due in one month.
5. Show `Expired` label if _Expiry date_ is passed.
6. Show `Healthy` label if _Expiry date_ is **NOT** due in less than one month.

### 3️⃣ Objective Three

1. Add form functionality to add a New item to the fridge.
2. Each added item should show on the items list without a page refresh.
3. Add a date picker to the `Expiry date` input field. (You can use ANY datepicker)

### 4️⃣ Objective Four (Optional)

1. Add List item delete functionality.
2. Show an alert confirmation window before deleting an item. (You can use your imagination for the confirmation window design)
3. The deleted item should immediately remove from the shown list without a page refresh.

---

# 🚥 API Endpoints

### ▶︎ Get all items

_Request_
```
GET https://thefridge-api.karapincha.io/fridge
```

### ▶︎ Create a new item

_Request_
```
POST https://thefridge-api.karapincha.io/fridge
```
_Body_
```
{
    "title": "Lemon",
    "expiry": "20/11/2040"
}
```

### ▶︎ Delete an Item (optional)

_Request_
```
DELETE https://thefridge-api.karapincha.io/fridge/:itemId
```

--- 

# 🔑 Evaluating criterias

- Follow instructions
- Attention to design details
- Code splitting
- Use of React best practices
- Use of SCSS best practices
- Code cleanliness and readability

# 👌 Added advantages 

- Write SCSS using [BEM](http://getbem.com/introduction/) methodology
- Better folder structure
- Redux toolkit usage

# 💾 Submission

Once you are completed;

1. Please commit the codebase to a Github repository.
2. Host the application on [Vercel.com](https://vercel.com/)

And email us the both links.

# Good luck! 🥂
