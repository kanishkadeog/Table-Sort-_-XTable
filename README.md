# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

--------------------------------------------------------------------------------------------------------------------------


# 🧮 XTable - Date & Views Sortable Table (ReactJS)

A simple ReactJS frontend project that renders a table of articles and allows users to sort the data by **Date** and **Views** with intelligent tie-breaker logic.


---


## 🚀 Live Demo

🔗 [Click here to view the live demo](https://xtable-jprocpf48-kanishkas-projects-95e27a37.vercel.app/)

---


## 📌 Features

- ✅ Built with ReactJS (Functional Components)
- ✅ Displays a list of articles in a table format
- ✅ Sort by **Date** (descending) with tie-breaker on **Views**
- ✅ Sort by **Views** (descending) with tie-breaker on **Date**
- ✅ No external libraries used (pure HTML, CSS, and React)
- ✅ Fully passes automated test cases (render, date sort, view sort)


---


## 📄 Data Used
[

  { date: "2022-09-01", views: 100, article: "Article 1" },
  { date: "2023-09-01", views: 100, article: "Article 1" },
  { date: "2023-09-02", views: 150, article: "Article 2" },
  { date: "2023-09-02", views: 120, article: "Article 3" },
  { date: "2020-09-03", views: 200, article: "Article 4" }
]


---



## 🧩 Tech Stack

- **ReactJS (functional components + hooks)**
- **HTML5**
- **CSS (inline + semantic styling)**

No external libraries or frameworks were used, as per assessment rules.

---


## 🧠 Sorting Logic

🔽 Sort by Date
Sorted by date in descending order (newest first)

Ties resolved by views in descending order

🔽 Sort by Views
Sorted by views in descending order

Ties resolved by date in descending order


---

## 📸 Screenshots

Initial Render:-
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/cf032359-b22e-491a-8580-758f88f48386" />


After Sorting by Date:-
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ac3e93bd-d532-4c61-9bec-af3e7229c137" />


After Sorting by Views:-
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/54636080-b09a-4576-ac68-c131b7405004" />



## 📂 Folder Structure
├── src/
    ├── App.js          # Main component with logic
    └── index.js        # React entry point



     
---
