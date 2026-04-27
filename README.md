# 💧 WaterStudy

WaterStudy is a focused study website to help prepare for water treatment operator exams.  

---

## 🚀 Features

* 📚 **Question Bank**

  * Multiple choice (A–D)
  * True / False
  * Scenario-based questions
  * Commonly tested concepts

---

## 🧪 Question Format

Question datasets originate as a Google Sheet (Excel) file organized in a specific way. It's exported as a CSV file, then converted to the JS dataset seen in this Github repo.
When the structure and my plans are more rigid, I'd welcome adding other question bank datasets, they don't necessarily even need to be for water treatment operator..
Example structure used in `dataset.js`:

```js
{
  question: "What is the primary purpose of coagulation?",
  choices: [
    "Remove dissolved gases",
    "Destabilize suspended particles",
    "Kill pathogens",
    "Adjust pH"
  ],
  answer: 1
}
```

---

## 🎯 Goals

* Help operators study conveniently from their phone or computer
* Provide a reusable and expandable study system

---

## 🛠️ Future Ideas.. Maybe?

* Difficulty levels (Class I → IV) or categories
* Questions are shuffled each session or answer choices are shuffled per question?

---

## ⚠️ Disclaimer

This project is intended as a **study aid only**. Always refer to official provincial/ state guidelines for regulation requirements.
There maybe mistakes, typos. Please report anything that looks ambiguous.

---

## 🤝 Contributing

If you want to expand the question bank:
* TODO - Discuss *.CSV format that get's exported to a *.JS question bank dataset.

---

## 📌 Notes

* Regulations are largely focused on Canadian limits
* This is a work-in-progress (WIP) project as I am studing for my certifications

## 💬 Contact

If you have any questions or discuss an error with the questions, please make a Github issue.

---
