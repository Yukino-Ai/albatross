# `dev.md`

## Tasks

### Create full-stack (with testing) task

Create a task that incoporates:

- The front-end
  - user input collection
  - client-side rendering
  - cypress testing
- The backend
  - user input storage
  - server-side rendering
  - vitest (or peek or jest) testing
- A justification
  - User experience
  - Developer experience

---

Justification: Before designing a BDD/TDD workflow with particular tools, we need a concrete task in order to setup the boilerplate code for these tools.

<details>

<summary>Next tasks</summary>

## Setup BDD process and tooling

Justification: The BDD process (and possibly tooling) should determine the overall workflow of a project.

### Fullpage color gradient visulization

[🍅 albatross/issues/22](https://github.com/Yukino-Ai/albatross/issues/22)

---

Justification: This is a good test feature that is arguably visually appealing while still being functional.

---

Single component with script:

```
On keypress:
    Randomly change background color;
    Save (`Date.now()`, `key`) to `signal`;
```

</details>

<details>
<summary>Completed tasks</summary>

### Time tracking for user inputs

Figure out how to track time of user inputs

Answer: Track only `Date.now()` times; probably only send back time differences to backend

### Setup volta to use Angular 12

Why?:

`npx` could lead to a slow workflow in general

</details>

---

## Organization

### Front-end

Framework: Angular

---

Store user input

- `Date.now()`
- keypress type

Generate visualization in real-time

### Backend

Framework: NestJS

---

~~Save history of user input~~

### Testing

Front-end: [Cypress](https://www.cypress.io)

Backend: Maybe [Vitest](https://vitest.dev/)
