# Chicken Vegetable Dumplings — Recipe Website

A simple, visually warm recipe website for making Chicken Vegetable Dumplings from scratch, including the dumpling wrapper dough, filling, cooking instructions, and a homemade chilli oil dipping sauce.

---

## Project Structure

```
project/
├── index.html          # Main recipe page
├── styles.css          # Stylesheet
└── images/
    ├── Dumpling.jpg               # Background image + header image
    ├── Dumplings-wrapper-dough.jpg
    ├── Dumpling-filling.jpg
    └── chilli-oil.jpg
```

---

## Sections Covered

1. **Dumpling Wrapper Dough** — How to make dough from scratch (or skip if using pre-made wrappers)
2. **Dumpling Filling** — Chicken, potato and stir-fried vegetable filling
3. **How to Cook Dumplings** — Steaming and pan-frying instructions
4. **Dumpling Sauce (Chilli Oil)** — A simple homemade chilli oil for dipping

---

## Features

- Smooth scroll anchor navigation via a `<nav>` menu
- Background image set on the `<body>` for a rich visual feel
- Centered recipe card (`recipe-board`) with a bisque background and brown border
- All images centered and responsive
- Horizontal rules styled in brown to visually separate each section
- Responsive layout — card width adapts on larger screens (max 900px on desktop)

---

## How to Run

No build tools or dependencies required. Just open the file in a browser:

```bash
# Option 1 — Open directly
open index.html

# Option 2 — Use a local server (recommended to load images correctly)
npx serve .
# or
python -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

---

## Responsive Behaviour

| Screen Size | Layout |
|---|---|
| Mobile (< 768px) | Recipe card takes 80% width, no max-width |
| Tablet / Desktop (≥ 768px) | Recipe card capped at 900px, centered with `margin: auto` |

---

## CSS Highlights

- `background-image` on `body` uses the dumpling photo as a full-page background
- `.recipe-board` acts as a centered card with `border-radius`, padding, and a dark red border
- `img` uses `margin-left: auto; margin-right: auto; display: block` to center all images
- `p, h1, h2, h3` are all center-aligned for a clean recipe card look
- `a` links are styled brown with no underline to match the warm color theme
- `hr` dividers are styled brown to match the overall palette


## Technologies Used

- HTML5
- CSS3 (Media Queries, Box Model, Background Image)

## Future Improvements

- Add forms for recipe comments
- Add multiple recipe pages
- Add cooking timer
- Add nutrition information


Created as an HTML practice project.
