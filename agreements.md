# Agreements on syntax

## Wording

- Some letter `{{a}}` is **right before** letter `{{b}}` if they form the next
  string `{{a}}{{b}}`
- Some letter `{{a}}` is **before** letter `{{b}}` if they form the next
  string `{{a}}{{one or more characters}}{{b}}`
- **Time** is a certain point in a life, like `3:00pm`
- **Span** is a duration, like `20 years`
- **Time span** is everything between two **times** or after a certain **time**, like
  `from 3:00pm till the next morning`
- **Time data** is either **time**, or **span**, or **time span**.

## Form chapter

For **Form** chapter the following syntactic agreements are applied:

- `{{...}}` is used for placeholders, like `{{subject}}`
- `... | ...` is used for predefined choices, like `{{have | has}}`
- `[...]` is used for optional words, like `[not]`
- **keyword** is used for keywords, like **statement**

## Usage chapter

For **Usage** chapter the following syntactic agreements are applied:

- agreements inherited from **Form** chapter
- **e.g.** is used for placeholders before examples
- *emphasized* is used for words related to the current rule

## Spelling chapter

For **Spelling** chapter the following syntactic agreements are applied:

- `ed` is used for word endings
- **keyword** is used for keywords, like **if**
