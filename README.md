# 💧 WaterStudy

WaterStudy is a small project I am building while studying for my water treatment operator exams.

I wanted to make flashcards, but existing websites for that are cluttered with ads.

This is just a clean website, with no ads. It's still very much a work-in-progress that I may never finish...

* ⚠️ Regulation questions are largely focused on Guidelines for Canadian Drinking Water Quality, however most of the theory/ questions are from US water treatment theory programs, Sacremento/ AWWA.
* ⚠️ There maybe mistakes, typos. Please report anything that looks ambiguous.

---

## 🚀 Features

**Question Bank**

  * True / False
  * Best Answer (A–D) - Only one correct answer
  * Select All (A–D) - One or all answers maybe correct
  * Flashcards
  * Factsheets

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

## 🤝 Contributing

If you want to expand the question bank:
* TODO - Discuss *.CSV format that get's exported to a *.JS question bank dataset.

---

## 💬 Contact

If you have any questions or want to discuss any errors with the website, please make a Github issue here.
