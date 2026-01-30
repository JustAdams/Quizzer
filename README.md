# Quizzer

Basic Slint desktop application built to study for exams.

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
