# Bauhaus-Classless.css 📐

A modernist, print-inspired CSS framework hosted via **GitHub Pages**. Transform raw semantic HTML into a high-end Swiss design manifesto with a single `<link>`.

## 🌐 CDN Usage (GitHub Pages)

You don't even need to download the file. Just paste this into the `<head>` of your `index.html`:

```html
<link rel="stylesheet" href="https://ashik-maybe.github.io/bauhaus-classless-css/bauhaus-classless.css">

```

---

## 📖 How to Design (No Classes Required)

This framework relies on the **order and nesting** of your HTML tags to create the layout.

### 1. The Typographic Hero

The top of your page should use a `<header>` tag. Inside it, the `<h1>` becomes a massive architectural anchor with a thick vertical "ink" bar.

```html
<header>
    <h1>form follows function.</h1>
    <p>This paragraph automatically acts as your manifesto/subtitle.</p>
</header>

```

### 2. The Figure & Caption (Visual Assets)

To get the signature Bauhaus grayscale-to-color effect, you must use the `<figure>` tag. The `<figcaption>` will automatically render in **Bauhaus Red**.

```html
<figure>
    <img src="your-image.jpg" alt="Description">
    <figcaption>this text turns red and uppercase</figcaption>
</figure>

```

### 3. The Blueprint Form

Standard forms are stripped of their digital "input boxes" and turned into simple architectural lines. Use `<fieldset>` to group them for a framed effect.

```html
<fieldset>
    <legend>Identification</legend>
    <label>Full Name</label>
    <input type="text" placeholder="W. Gropius">
</header>

```

### 4. Data Grids

Tables are treated as high-contrast structural grids.

* **Heavy Rule:** The `<thead>` automatically creates a thick horizontal ink stroke.
* **Inversion:** Hovering over any `<tr>` will invert the colors (Black background, Paper text).

---

## 🛠 Tag Reference Cheat Sheet

| Effect | HTML Tag |
| --- | --- |
| **Main Anchor Header** | `<h1>` (inside `<header>`) |
| **Architectural Divider** | `<hr>` |
| **Indented Manifesto Quote** | `blockquote` |
| **Primary Action (Solid)** | `<button>` |
| **Grayscale Image Asset** | `<figure> > <img>` |
| **System Loading Bar** | `<progress>` |

---

## 🎨 Modifying the Theme

If you have forked this repo and want to change the "Paper" or "Ink" colors, simply update the CSS variables in `bauhaus-classless.css`:

```css
:root {
  --paper: #f4f1ea; /* The background 'page' color */
  --ink: #1a1a1a;   /* The 'text and line' color */
  --accent: #d32f2f; /* The 'Bauhaus Red' used in captions/links */
}

```

---
