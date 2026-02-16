# 🌳 SLR(1) Parsing Table Generator

A simple **web-based Compiler Design mini project** that generates an **SLR(1) parsing table layout** for a given grammar input.

Built using **HTML, CSS, and JavaScript**.

---

## 🚀 Live Demo
👉 https://dheetchana04.github.io/slr-parsing-table-generator/SLR.html  

---

## ✨ Features

✅ User-friendly grammar input box  
✅ Generates ACTION and GOTO parsing table format  
✅ Clean, responsive, and beginner-friendly UI  

---

## 🛠️ Technologies Used

- 🌐 HTML  
- 🎨 CSS  
- ⚡ JavaScript  

---

## ▶️ How to Run

1. Clone or download this repository  
2. Open `SLR.html` in any browser  

---

## 🔮 Future Improvements

- Implement actual **FIRST** and **FOLLOW** computation  
- Automate **LR(0) item set generation**  
- Detect **shift/reduce conflicts**  
- Add full SLR parsing logic  

---

## 📌 Example Grammar Input

```txt
E -> E + T | T  
T -> T * F | F  
F -> ( E ) | id
