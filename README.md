# LG 6.0 & 6.1 Level 3 — LG 7.0 Level 2

## Task
Recreate the mock up shown.

## What you need to do

1. Open `index.html` and add the correct HTML attributes to each element.
2. Open `style.css` and write the CSS rules to recreate the mock up.
3. Open `index.html` in the browser to check your work.
4. If it matches the mock up, you are done!

## Files in this folder

- `index.html` — add your HTML attributes here
- `style.css` — write your CSS rules here
---

## LG 6.0 Rubric — Box Model

| Level | Description |
|-------|-------------|
| **Level 1** | No attempt or no changes made. |
| **Level 2** | Uses some box model properties but does not look like the mock up. |
| **Level 3** | Uses all box model properties. Looks very close to the mock up. |
| **Level 4** | Exact copy of the mock up. All box model properties used to achieve an exact match. |

---

## LG 6.1 Rubric — CSS Selectors

| Level | Description |
|-------|-------------|
| **Level 1** | No attempt or no changes made. |
| **Level 2** | Only used 1 type of selector in the assessment. |
| **Level 3** | Used 3 types of selectors in the assessment. |
| **Level 4** | Used all selector types. |

---

## LG 7.0 Rubric — Responsive Design

| Level | Description |
|-------|-------------|
| **Level 1** | Nothing changes when the window resizes. |
| **Level 2** | Some elements are responsive but most are not. |
| **Level 3** | Elements are responsive for the most part. |
| **Level 4** | All elements are responsive. |



## Resources

- 📖 CSS Property Reference: https://www.w3schools.com/CSSref/index.php

---

## How a CSS Rule Looks

A CSS rule is made up of three parts:

```
selector { property: value; }
```

| Part | What it means | Example |
|------|--------------|---------|
| **Selector** | Targets the HTML element you want to style | `h1`, `.my-class`, `#my-id` |
| **Property** | The style you want to change | `color`, `width`, `border` |
| **Value** | The value you want to apply | `red`, `200px`, `solid` |

A full example:

```css
/* Element selector */
h1 {
  color: red;
}

/* Class selector — starts with a dot */
.my-class {
  background-color: blue;
}

/* ID selector — starts with a hash */
#my-id {
  width: 200px;
}
```

---

## Box Model

Every HTML element is a box. The box model describes the space around that box.

```
┌─────────────────────────────────┐
│            MARGIN               │  ← Margin: Space outside the border
│  ┌───────────────────────────┐  │
│  │          BORDER           │  │  ← Border: The outline of the element
│  │  ┌─────────────────────┐  │  │
│  │  │       PADDING       │  │  │  ← Padding: Space inside the border
│  │  │  ┌───────────────┐  │  │  │
│  │  │  │    CONTENT    │  │  │  │  ← Content: Your text or image
│  │  │  │               │  │  │  │
│  │  │  │  ↔ width      │  │  │  │
│  │  │  │  ↕ height     │  │  │  │
│  │  │  └───────────────┘  │  │  │
│  │  └─────────────────────┘  │  │
│  └───────────────────────────┘  │
└─────────────────────────────────┘
```

### Box Model Properties

| Property | What it does | Example |
|----------|-------------|---------|
| `margin` | Space **outside** the border — pushes other elements away | `margin: 20px;` |
| `border` | A line drawn around the padding and content | `border: 2px solid red;` |
| `padding` | Space **inside** the border — between the border and the content | `padding: 10px;` |
| `width` | The horizontal size of the content area | `width: 200px;` |
| `height` | The vertical size of the content area | `height: 100px;` |

---

## Responsive Units

Responsive units change size depending on the browser window. In this assessment you will only use these three:

| Unit | Full name | What it means | Example |
|------|-----------|--------------|---------|
| `vw` | Viewport Width | 1% of the **width** of the browser window | `width: 50vw;` = 50% of the window width |
| `vh` | Viewport Height | 1% of the **height** of the browser window | `height: 100vh;` = full window height |
| `%` | Percentage | A percentage of the **parent** element's size | `width: 50%;` = half the width of the parent |

> ⚠️ These are the **only** responsive units used in this assessment.
