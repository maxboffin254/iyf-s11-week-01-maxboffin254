# Task 1.2: DevTools Exploration

## Website 1: https://example.com

1. What HTML tags are used on this page?

**Answer:**

The document is built from seven core HTML elements:

```
<html>   — wraps the entire page
<head>   — stores metadata including the title
<title>  — defines the browser tab label
<body>   — holds all visible content
<h1>     — the page's only top-level heading
<p>      — a block of descriptive text
<a>      — a hyperlink to another resource
```

2. What is the page title?

**Answer:** Example Domain

3. How many headings are there?

**Answer:** The page contains one heading (`<h1>`).

---

## Website 2: https://developer.mozilla.org

1. Find the navigation menu — what tag is it wrapped in?

**Answer:** MDN places its navigation inside `<nav>` elements. Two are present on the page:

```
<nav class="navigation"> — outer header navigation bar
<nav class="menu">       — inner tab menu (HTML, CSS, JavaScript, etc.)
```

2. How is the search bar structured?

**Answer:** The search control is a `<button>` with an icon inside it. Clicking the button opens a popup overlay where the user can type a search query.

```html
<button class="mdn-search-button" title="Search the site">
  <!-- search icon -->
</button>
```

3. What happens when you hover over links (check the styles)?

**Answer:** Interactive elements change background color on hover. This behaviour is defined with the CSS `:hover` pseudo-class:

```css
.mdn-search-button:hover {
  background-color: var(--color-background-secondary);
}
```

---

## Website 3: https://github.com

1. Identify 5 different HTML elements

**Answer:**

```
<header> — top banner containing the primary site navigation
<nav>    — groups main menu links such as Platform and Pricing
<form>   — wraps the email sign-up section on the homepage
<footer> — bottom area with company and legal links
<input>  — email field inside the registration form
```

2. Find a form element and list its inputs

**Answer:** GitHub's homepage includes a sign-up form with the following structure:

```html
<form>
  <input type="email" placeholder="Enter your email" />
  <button type="submit">Sign up for GitHub</button>
</form>
```

Inputs found:

- `type="email"` — field for entering an email address
- `type="submit"` (button) — submits the form to create an account

3. Take a screenshot of the Elements panel

**Answer:**

![GitHub DevTools Elements Panel Screenshot](images/screenshot.png)
