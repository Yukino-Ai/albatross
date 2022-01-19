# `dev.md`

## Tasks

### Fullpage color gradient visulization

[🍅 albatross/issues/22](https://github.com/Yukino-Ai/albatross/issues/22)

---

Why?: Visually appealing while still functional

---

Single component with script:

```
On keypress:
    Randomly change background color;
    Save (`Date.now()`, `key`) to `signal`;
```

<details>

<summary>Next tasks</summary>

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

Store user input

- `Date.now()`
- keypress type

Generate visualization in real-time

### Backend

Save history of user input
