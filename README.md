# Quizzer

Basic Slint desktop application built to study for exams.
<img width="1113" height="208" alt="image" src="https://github.com/user-attachments/assets/ef29b67c-362a-424b-91c1-e2733eb541cc" />

# Usage

Construct a JSON question series using the format:

```json
[
  {
    "question": "The question",
    "answers": [
      "answer 1",
      "answer 2",
      "answer 3",
      "answer 4"
    ],
    "correct_answer": 2,
    "explanation": [
      "answer 1 explanation",
      "answer 2 explanation",
      "answer 3 explanation",
      "answer 4 explanation"
    ]
  }
]
```

and insert into the root directory. Run the application with the JSON filename as the only argument.
