# Catechism of Pope St. Pius X JSON

## Introduction

The Catechism of the Council of Trent was directed to all priests. The recently released Catechism of the Catholic Church was directed to all bishops. The Catechism of Pope St. Pius X is that pope's partial realization of a simple, plain, brief popular Catechism for uniform use throughout the whole world. In other words, it is directed to the layman. It was used in the ecclesiastical province of Rome and for some years in other parts of Italy. It was not, however, prescribed for use throughout the universal church.

## JSON Structure Outline

The JSON file (`catechism-st-pius-x.json`) is structured as follows:

```json
{
  "title": string,
  "introduction": string,
  "sections": [
    {
      "title": string,
      "subsections": [
        {
          "title": string,
          "questions": [
            {
              "question": string,
              "answer": string
            },
            ...
          ]
        },
        ...
      ]
    },
    ...
  ]
}
```

- `title`: The title of the catechism.
- `introduction`: A brief introduction to the catechism.
- `sections`: An array of major sections, each with:
  - `title`: The section title.
  - `subsections`: An array of subsections, each with:
    - `title`: The subsection title.
    - `questions`: An array of question objects, each with:
      - `question`: The question text.
      - `answer`: The answer text.
```
