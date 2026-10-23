# Student Registration Form (Alternative Semantic Layout)

A student registration page built with pure semantic HTML (no CSS), using a clean tabular structure that is distinctly different in visual appearance and markup architecture from the original fieldset-based design.

## Fields Collected

Only the required registration fields are collected:

| Field | Input Control | Type / Values |
|---|---|---|
| Matric Number | Single-line text input | `<input type="text">` |
| Full Name | Single-line text input | `<input type="text">` |
| Gender | Drop-down list | `<select>` (Male / Female) |
| Department | Drop-down list | `<select>` (5 department options) |
| Program | Radio group (inline) | `<input type="radio">` (Full-time / Weekday / Weekend) |
| Email Address | Email input | `<input type="email">` |
| Phone Number | Telephone input | `<input type="tel">` |

### Department Options

1. Cybersecurity and Data Sciences
2. Information Technology
3. Information Communication Technology
4. Computer Science
5. Software Engineering and Information System

## Key Differences from the Previous Version

| Aspect | Previous Version (`student-registration/`) | This Version (`student-enrollment/`) |
|---|---|---|
| **Form Layout** | Stacked `<fieldset>` boxes with `<legend>` headers and `<br>` breaks | Aligned semantic `<table>` layout (`<tr>`, `<td>`) |
| **Field Order** | Personal &rarr; Contact &rarr; Academic | Academic credentials (Matric) &rarr; Name &rarr; Details |
| **Gender Input** | Radio buttons in a nested `<fieldset>` | Clean `<select>` drop-down list |
| **Program Input** | Radio buttons wrapped in a nested `<fieldset>` | Inline `<label>` radio buttons inside a table cell |
| **Buttons** | `<button type="submit">` and `<button type="reset">` | Centered `<input type="submit">` and `<input type="reset">` |
| **Visual Appearance** | Boxed outline sections with text cutouts | Structured, horizontally aligned tabular grid |

## How to Run

Open `index.html` in any web browser:
```bash
open index.html
```

## Files

- `index.html` – Pure HTML registration form
- `README.md` – Documentation and field description
